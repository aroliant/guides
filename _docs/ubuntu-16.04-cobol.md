---
layout: guide
title:  "Installing Cobol on Ubuntu 16.04"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/ubuntu/16.04/cobol.html
category: installation
platform: ubuntu
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)

<section class="wrapper">



## Introduction

## Installation

{% highlight shell %}
sudo apt-get install open-cobol
{% endhighlight %}

## Usage
{% highlight shell %}
cobc -x -free filename.cobc -o main;./main
{% endhighlight %}


</section>
