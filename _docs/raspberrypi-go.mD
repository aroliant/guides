---
layout: guide
title:  "Installing Go on Raspberry Pi"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/raspberrypi/go.html
category: installation
platform: raspberrypi
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Golang Compiler on Raspberry Pi. 

## Installation



{% highlight shell %}
sudo apt-get install golang-go
{% endhighlight %}

## Usage

Sample program:

```

package main

import "fmt"
func main() {
   fmt.Printf("Hello, this is GO!")
}
```

To run this Program enter the following command in command line.
{% highlight shell %}
 go run filename.go
{% endhighlight %}

</section>
