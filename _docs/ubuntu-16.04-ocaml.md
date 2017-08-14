---
layout: guide
title:  "Installing Ocaml on Ubuntu 16.04"
date:   2016-09-12 21:16:29 +0530
permalink: /installation/ubuntu/16.04/ocaml.html
category: installation
platform: ubuntu
---

{::options parse_block_html="true" /}

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)

<section class="wrapper">



## Introduction

This is the guide to install the Ocaml Compiler on Ubuntu. 

## Installation


{% highlight shell %}
sudo apt-get install ocaml
{% endhighlight %}

## Usage
{% highlight shell %}
ocamlc -o code filename.ml&& ./code
{% endhighlight %}
</section>
