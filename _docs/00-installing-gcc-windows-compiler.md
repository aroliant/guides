---
layout: guide
title:  "Installing C & C++ Compiler on Windows"
date:   2016-09-12 21:16:29 +0530
permalink: installation/windows/gcc.html
category: installation
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Downloading](#installation)
* [Installing](#installation)
* [Configuring](#installation)
* [Usage](#installation)
    * [Using with Sublime Text](#installing-on-windows)
    * [Using from Command Prompt]()

<section class="wrapper">



## Introduction

This is the guide to install the C & C++ Compiler on Windows. Here we are going to use the GCC Compiler ( not  Turbo C++ which was used in the old stone age). 

The reason why we are not using the  Turbo C++ is becasue the development was discontinued. The last stable verion was on September 5, 2006. Eventhough there is an updated version available school and colleges are using the version 3 which was released in 1991. 


You may argue that the Turbo C++ compiler is simple and easy to use and that's not true. Of course it's good to start with Turbo C++ but if you are planning to choose your career in programming Turbo C++ won't help you on this. You have to go for the standard compilers used by the developer community.

This guide will helps you to install the latest C & C++ Compilers available in the industry, which is the MinGW GCC Compiler.


### MinGW GCC Compiler 

MinGW is a port of GCC to Windows. It was created to support the GCC compiler on Windows Platform. It lets us to access the headers and support libraries on Windows. It produces standalone Windows executables ( exe files ) which may be distributed in any manner. 


## Downloading

Go to [mingw.org/](http://www.mingw.org/) and click on the **Download Installer** button in the top right corner.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/01.jpg)

It will take you to sourceforge for downloading.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/02.jpg)

## Installing
After the download, run the setup as Administrator
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/03.jpg)
Click on Install
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/04.jpg)
It is going to be installed in ``C:\MinGW\`` folder, Click on continue.
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/05.jpg)
It will fetch and update it's database from the server, click on the continute button when it becomes clickable. 
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/06.jpg)

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/07.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/08.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/09.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/10.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/11.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/12.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/13.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/14.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/15.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/16.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/17.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/18.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/19.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/20.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/21.jpg)
![alt img](//static.aroliant.net/images/compile.work/gcc-windows/22.jpg)

 `C:\MinGW\bin` 

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

## Configuring

## Usage

Here is the sample c program

{% highlight c %}

#include <stdio.h>

int main(int argc, char const *argv[])
{
	printf("Hello GCC!\n");
	return 0;
}

{% endhighlight %}

### Using in Command Prompt

### Using in Sublime Text



</section>