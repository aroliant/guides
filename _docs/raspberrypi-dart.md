---
layout: guide
title:  "Installing Dart on Raspberry Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/dart.html
category: installation
platform: raspberrypi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Dart Compiler on Raspberry Pi. 

## Installation

{% highlight shell %}
sudo apt-get update
{% endhighlight %}
**Get the Dart file to download**
{% highlight shell %}
wget https://github.com/dlachausse/dartberrypi/releases/download/v1.8/dart_1.8.3-1_armhf.deb
{% endhighlight %}
**Install Dart**
{% highlight shell %}
dpkg -i dart_1.8.3-1_armhf.deb
{% endhighlight %}

{% highlight shell %}
sudo apt-get update
{% endhighlight %}

{% highlight shell %}
dart --version
{% endhighlight %}

## Usage

Sample program:

```

void main(){
   print("Hello,this is Dart!");
}
```
To run this Program enter the following command in command line.
{% highlight shell %}
dart filename.dart
{% endhighlight %}

</section>


