---
layout: guide
title:  "Installing C# on Raspberry Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/c-sharp.html
category: installation
platform: raspberrypi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)


<section class="wrapper">



## Introduction
This is the guide to install the C# Compiler on Raspberry Pi .

## Installation

{% highlight shell %}
sudo apt-get install mono-complete
{% endhighlight %}

## Usage

Sample Program:
```

using System;

class MyClass
{
    static void Main()
    {
        Console.WriteLine("Hello, this is C#!");

  }
}
```
To run this Program enter the following command in command line.
{% highlight shell %}
- mcs filename.cs
- mono filename.exe
{% endhighlight %}

</section>
