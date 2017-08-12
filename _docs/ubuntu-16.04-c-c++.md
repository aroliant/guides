---
layout: guide
title:  "Installing C&C++ on Ubuntu 16.04"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/ubuntu/16.04/c-c++.html
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
