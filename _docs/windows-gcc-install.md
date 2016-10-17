---
layout: guide
title:  "Installing C & C++ Compiler on Windows"
date:   2016-09-12 21:16:29 +0530
permalink: installation/windows/gcc.html
category: installation
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Downloading](#downloading)
* [Installation](#installation)
* [Configuring](#configuring)
* [Usage](#usage)
    * [Using in Sublime Text](#using-in-sublime-text)

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

## Installation

After the download, run the setup as Administrator

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/03.jpg)

Click on Install

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/04.jpg)

It is going to be installed in ``C:\MinGW\`` folder.
Click on continue.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/05.jpg)

Then, it will fetch and update it's database from the server, click on the continute button when it becomes clickable. 

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/06.jpg)

It will be on the Basic Setup Tab by default, there look for ``mingw-32-gcc-g++``, Right Click and Mark for Installation

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/07.jpg)

Now, Click on the Installation menu and hit Apply Changes.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/08.jpg)

It will open the confirmation dialog box, there click on Apply.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/09.jpg)

It will start downloading the required files.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/10.jpg)

Once the download gets completed it will install the packages, click on **Close** to finish the setup.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/11.jpg)

### Checking the Installattion

In order to check whether it has installed correctly or not, you have to go to ``C:\MinGW\bin`` folder . There holding the shift key, right click on the empty area. Click on **Open command window here**

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/12.jpg)

In the command prompt type the command ``gcc -v`` . It will show the version of GCC installed on your computer. If the output doesn't look similar as this one then there will be some problem in your Installation.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/13.jpg)


## Configuring

### Setting the Environment Variable

The purpose of setting the Enviroment Variable is to access the gcc command everywhere in the command prompt. Setting up the enviromnent varaible will tell the system where to look for the gcc command.

Copy the ``C:\MinGW\bin`` path  and click on This PC

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/14.jpg)

Now right click on the empty are and click on Properties.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/15.jpg)

There choose **Advanced system settings**

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/16.jpg)

It will open the System Propertes dialog box, There click on the **Enviroment Variables**

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/17.jpg)

In the **System variables** section look for **Path** and click on Edit

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/18.jpg)

Append the Path ``C:\MinGW\bin`` in the **Variable Value** and click on OK

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/19.jpg)

That's all now you have successfully configured the GCC Compiler on 
your Computer.


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

Copy and paste this program on your Favorite code editor, save it as **sample.c** . If you are still using NotePad you have to read this guide Choosing the Best Code Editor.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/20.jpg)

### Using from Command Prompt

Right Click on the Windows Icon (Start Menu Icon) and click on **Command Prompt**


![alt img](//static.aroliant.net/images/compile.work/gcc-windows/21.jpg)

Navigate the prompt to the place where you have saved the sample program ( use ``cd`` command to navigate ). Then type ``gcc sample.c`` to compile the program. Now a new executable named **a** will be generated in your folder. Type a on the command prompt to run the program.

![alt img](//static.aroliant.net/images/compile.work/gcc-windows/22.jpg)

That's all this is how you have to compile and run C & C++ Programs on Windows.


</section>