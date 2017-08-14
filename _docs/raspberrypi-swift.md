---
layout: guide
title:  "Installing Swift on Raspberry pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/swift.html
category: installation
platform: raspberrypi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Downloading](#downloading)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Swift Compiler on Raspberry pi. 

## Downloading
To Download go to the [link](https://swift.org/download/#snapshots)

## Installation

{% highlight shell %}
sudo apt-get install clang libicu-dev
{% endhighlight %}

{% highlight shell %}
sudo apt-get install libpython2.7-dev
{% endhighlight %}

**Create a folder named swift in home and download the snapshot there using**

{% highlight shell %}
wget  <url>
{% endhighlight %}

**Extract the downloaded file using the command**

{% highlight shell %}
tar xzf filename
{% endhighlight %}

**Edit the environment variable file using nano**

{% highlight shell %}
sudo nano /etc/environment
{% endhighlight %}

**Add the path in environment variable**

{% highlight shell %}
/home/swift/swift-DEVELOPMENT-SNAPSHOT-2016-10-27-a-ubuntu16.04/usr/bin
{% endhighlight %}

**Verify swift installation by using command**

{% highlight shell %}
swift --version
{% endhighlight %}
 
## Usage

{% highlight shell %}
/home/swift/swift-DEVELOPMENT-SNAPSHOT-2016-10-27-a-ubuntu16.04/usr/bin/swift filename.swift'
{% endhighlight %}

</section>
