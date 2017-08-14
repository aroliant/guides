---
layout: guide
title:  "Installing PHP 5.6 on Raspberry Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/php5.6-php7.0-apache2.html
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
sudo apt-get install php7.0 php5.6 php5.6-mysql php-gettext php5.6-mbstring php-xdebug libapache2-mod-php5.6 libapache2-mod-php7.0
{% endhighlight %}

## Switching

Now lets see how to switch between the two versions

### Switching from php5.6 to php7.0

First disable PHP5

{% highlight shell %}
sudo a2dismod php5.6
{% endhighlight %}

Then enable PHP7
{% highlight shell %}
sudo a2enmod php7.0
{% endhighlight %}

Finally restart the server
{% highlight shell %}
sudo service apache2 restart
{% endhighlight %}



### Switching from php7.0 to php5.6

First disable PHP7
{% highlight shell %}
sudo a2dismod php7.0
{% endhighlight %}

Then enable PHP5
{% highlight shell %}
sudo a2enmod php5.6
{% endhighlight %}

Finally restart the Server
{% highlight shell %}
sudo service apache2 restart
{% endhighlight %}

That's all this is how you can use both PHP5.6 and PHP7.0 in the same machine.

</section>
