---
layout: guide
title:  "Installing Ruby on Orange Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/orangepi/ruby.html
category: installation
platform: orangepi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Ruby Compiler on Orange Pi. 

## Installation

{% highlight shell %}
sudo apt-get install ruby
{% endhighlight %}

{% highlight shell %}
sudo apt-get update
{% endhighlight %}

## Usage


Sample program:


```
print "Hello, Its ruby here"
```

To run this Program enter the following command in command line.
{% highlight shell %}
ruby filename.rb
{% endhighlight %}



</section>
