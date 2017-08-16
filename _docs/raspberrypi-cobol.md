---
layout: guide 
title:  "Installing Cobol on Raspberry Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/cobol.html
category: installation
platform: raspberrypi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)
<section class="wrapper">



## Introduction
This is the guide to install the Cobol Compiler on Raspberry Pi. 

## Installation

{% highlight shell %}
sudo apt-get install open-cobol
{% endhighlight %}

## Usage

Sample program:

```

IDENTIFICATION DIVISION.
PROGRAM-ID. SAMPLE.
PROCEDURE DIVISION.
DISPLAY "Hello, this is COBOL".
STOP RUN.
```
To run this Program enter the following command in command line.
{% highlight shell %}
- cobc -x -free filename.cobc
- ./filename
{% endhighlight %}

</section>
