---
layout: guide
title:  "Installing Apache 2, PHP 5.6 on Raspberry pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/php5.6-apache2.html
category: installation
platform: raspberrypi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Switching](#switching)

<section class="wrapper">



## Introduction

Raspberry pi has switched to PHP 7.0 with a new infrastructure for PHP package. So, no, you can't install php5 on Raspberry pi


## Installation

### Installing Apache 2

{% highlight shell %}
sudo add-apt-repository ppa:ondrej/php
{% endhighlight %}

{% highlight shell %}
sudo apt-get update
{% endhighlight %}

{% highlight shell %}
sudo apt-get install php5.6 php5.6-mysql php-gettext php5.6-mbstring php-xdebug libapache2-mod-php5.6
{% endhighlight %}

## Switching


Switching from php5.6 to php7.0

sudo a2dismod php5.6 ; sudo a2enmod php7.0 ; sudo service apache2 restart

Switching from php7.0 to php5.6


sudo a2dismod php7.0 ; sudo a2enmod php5.6 ; sudo service apache2 restart



That's all this is how you have to compile and run C & C++ Programs on Raspberry pi.


</section>