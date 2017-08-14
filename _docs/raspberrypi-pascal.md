---
layout: guide
title:  "Installing Pascal on Raspberry pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/pascal.html
category: installation
platform: raspberrypi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Pascal Compiler on Raspberry Pi. 

## Installation



{% highlight shell %}
sudo apt-get install fp-compiler
{% endhighlight %}

## Usage

{% highlight shell %}
fpc -vw filename.pas;./code
{% endhighlight %}



</section>
