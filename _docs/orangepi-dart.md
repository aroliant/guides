---
layout: guide
title:  "Installing Dart on Orange pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/orangepi/dart.html
category: installation
platform: orangepi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Dart Compiler on Orange Pi. 

## Installation

{% highlight shell %}
sudo apt-get update
{% endhighlight %}

{% highlight shell %}
sudo apt-get install apt-transport-https
{% endhighlight %}

**Get the Google Linux package signing key**

{% highlight shell %}
sudo sh -c 'curl https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add -'
{% endhighlight %}

**Set up the location of the stable repository**

{% highlight shell %}
sudo sh -c 'curl https://storage.googleapis.com/download.dartlang.org/linux/debian/dart_stable.list > /etc/apt/sources.list.d/dart_stable.list'
{% endhighlight %}

{% highlight shell %}
sudo apt-get update
{% endhighlight %}

{% highlight shell %}
sudo apt-get install dart
{% endhighlight %}

## Usage
{% highlight shell %}
dart filename.dart
{% endhighlight %}

</section>
