---
layout: guide
title:  "Installing C# on Ubuntu 16.04"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/ubuntu/16.04/c-sharp.html
category: installation
platform: ubuntu
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the C# Compiler on Ubuntu. 

## Installation

{% highlight shell %}
sudo apt-get install mono-complete
{% endhighlight %}

## Usage
{% highlight shell %}
mcs filename.cs -out:program.exe ;mono program.exe
{% endhighlight %}

</section>
