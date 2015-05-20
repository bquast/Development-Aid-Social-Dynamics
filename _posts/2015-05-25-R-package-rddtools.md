---
layout: post
title: "R package rddtools"
author: bastiaan_quast
modified:
excerpt: "An R package for Regression Discontinuity Design"
---

The `rddtools` package can be installed from GitHub using the `devtools` package.

{% highlight r %}
if (!require('devtools')) install.packages('devtools')
devtools::install_github("bquast/rddtools")
{% endhighlight %}

We can now load the package and inspect the vignette.

{% highlight r %}
library(rddtools)
vignette(rddtools)
{% endhighlight %}
