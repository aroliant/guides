---
layout: guide
title:  "Installing C&C++ on Orange Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/orangepi/c-c++.html
category: installation
platform: orangepi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)



<section class="wrapper">



## Introduction
This is the guide to install the C&C++ Compiler on Orange Pi .

## Installation



{% highlight shell %}
sudo apt-get install gcc g++
{% endhighlight %}

{% highlight shell %}
sudo apt-get update
{% endhighlight %}

## Usage
**For C program**
{% highlight shell %}
gcc -Wall -Wextra -lncurses filename.c -o code &&./code
{% endhighlight %}

**For C++ program**
{% highlight shell %}
g++  -Wall -Wextra -lncurses filename.cpp -o code &&./code
{% endhighlight %}


</section>
