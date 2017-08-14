---
layout: guide
title:  "Installing Pascal on Ubuntu 16.04"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/ubuntu/16.04/pascal.html
category: installation
platform: ubuntu
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Pascal Compiler on Ubuntu. 

## Installation



{% highlight shell %}
sudo apt-get install fp-compiler
{% endhighlight %}

## Usage

{% highlight shell %}
fpc -vw filename.pas;./code
{% endhighlight %}



</section>
