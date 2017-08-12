---
layout: guide
title:  "Installing Dart on Ubuntu 16.04"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/ubuntu/16.04/dart.html
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
