---
layout: page
title: rddtools
modified: 2015-05-18T13:49:02.362000-04:00
excerpt: "R package for Regression Discontinuity Design"
image:
  feature: sample-image-3.jpg
---

The rddtools package can be installed from GitHub using the devtools package.

{% highlight r %}
if (!require('devtools')) install.packages('devtools')
devtools::install_github("bquast/rddtools")
{% endhighlight %}

We can now load the package and inspect the vignette.

{% highlight r %}
library(rddtools)
vignette(rddtools)
{% endhighlight %}
