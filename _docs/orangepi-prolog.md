---
layout: guide
title:  "Installing ProLog on Orange Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/orangepi/prolog.html
category: installation
platform: orangepi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Prolog Compiler on Orange Pi. 

## Installation
{% highlight shell %}
sudo apt-get install swi-prolog
{% endhighlight %}

## Usage

Sample program:


```

?- write('Hello world!'), nl.
Hello world!
true.

?-
```

To run this Program enter the following command in command line.
{% highlight shell %}
 swipl -s hello.pl -g go -t halt

{% endhighlight %}



</section>
