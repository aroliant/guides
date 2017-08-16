---
layout: guide
title:  "Installing ProLog on Raspberry Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/prolog.html
category: installation
platform: raspberrypi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Prolog Compiler on Raspberry pi. 

## Installation



{% highlight shell %}
sudo apt-get install sudo apt-add-repository ppa:swi-prolog/stable
{% endhighlight %}

{% highlight shell %}
sudo apt-get update
{% endhighlight %}

{% highlight shell %}
sudo apt-get install swi-prolog
{% endhighlight %}


</section>
