---
layout: guide
title:  "Installing PHP 5.6 on Ubuntu 16.04"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/ubuntu/16.04/php5.6.html
category: installation
platform: ubuntu
keywords: php5.6 on ubuntu 16.04, php5 on ubuntu 16.04
author: jacobsamro
description: Ubuntu 16.04 has switched to PHP 7.0 with a new infrastructure for PHP package. his tutorial will guide you through the process of installing PHP5 on Ubuntu 16.04
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Testing](#testing)

<section class="wrapper">

## Introduction

Ubuntu 16.04 has switched to PHP 7.0 with a new infrastructure for PHP package. So, when you try to install PHP using the `apt` command it will install PHP7.0 . This tutorial will guide you through the process of installing PHP5 on Ubuntu 16.04

## Installation

Add the source where the PHP 5.6 repository is located

{% highlight shell %}
sudo add-apt-repository ppa:ondrej/php
{% endhighlight %}

![alt img](//static.aroliant.net/images/compile.work/ubuntu-16.04-apache2-with-php5.6/01.jpg)

Hit **Enter** to add the source

![alt img](//static.aroliant.net/images/compile.work/ubuntu-16.04-apache2-with-php5.6/02.jpg)

Update the apt database

{% highlight shell %}
sudo apt-get update
{% endhighlight %}
![alt img](//static.aroliant.net/images/compile.work/ubuntu-16.04-apache2-with-php5.6/03.jpg)

Now you can simply install PHP using this command

{% highlight shell %}
sudo apt-get install php5.6
{% endhighlight %}
![alt img](//static.aroliant.net/images/compile.work/ubuntu-16.04-apache2-with-php5.6/04.jpg)

## Testing

Checking the version of PHP Installed

{% highlight shell %}
php -v
{% endhighlight %}

![alt img](//static.aroliant.net/images/compile.work/ubuntu-16.04-apache2-with-php5.6/05.jpg)

If it display the version as 5.6 then you have installed the PHP 5.6 correctly or else make sure that you have followed the tutorial step by step.

</section>