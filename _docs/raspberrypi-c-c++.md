---
layout: guide
title:  "Installing C&C++ on Raspberry Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/c-c++.html
category: installation
platform: raspberrypi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)



<section class="wrapper">



## Introduction
This is the guide to install the C&C++ Compiler on Raspberry Pi .

## Installation



{% highlight shell %}
sudo apt-get install gcc g++
{% endhighlight %}

{% highlight shell %}
sudo apt-get update
{% endhighlight %}

## Usage
**For C program**

Sample program:
```

#include<stdio.h>

int main(){

printf("Hello");

return 0;

}

```
To run this Program enter the following command in command line.
{% highlight shell %}
- gcc filename.c
- ./a.out
{% endhighlight %}

**For C++ program**

Sample program:
```

#include<iostream>

using namespace std;

int main(){

cout<<"Hello";

return 0;

}
```
To run this Program enter the following command in command line.
{% highlight shell %}
- g++ filename.cpp
- ./a.out
{% endhighlight %}

</section>
