---
layout: guide 
title:  "Installing Cobol on Orange Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/orangepi/cobol.html
category: installation
platform: orangepi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)
<section class="wrapper">



## Introduction
This is the guide to install the Cobol Compiler on Orange Pi. 

## Installation

{% highlight shell %}
sudo apt-get install open-cobol
{% endhighlight %}

## Usage
{% highlight shell %}
cobc -x -free filename.cobc -o main;./main
{% endhighlight %}


</section>
