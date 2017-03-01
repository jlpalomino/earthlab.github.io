---
layout: single
title: "Add variables to an RMD report R."
excerpt: " "
authors: ['Leah Wasser']
modified: '2017-02-28'
category: [course-materials]
class-lesson: ['how-to-hints-week7']
permalink: /course-materials/earth-analytics/week-7/add-variables-to-rmarkdown-report/
nav-title: 'Variables in rmarkdown report'
module-title: 'Refine plots & add variables to knirt reports'
module-description: 'This tutorial set covers some basic things you can do to refine your plots in Rmarkdown document. It covers plotting in grids, adding titles to plotRGB() plots
and refining the width and height of plots to optimize space.'
module-nav-title: 'Refine Rmarkdown reports'
module-type: 'homework'
week: 7
sidebar:
  nav:
author_profile: false
comments: true
order: 1
---

{% include toc title="In This Lesson" icon="file-text" %}

<div class='notice--success' markdown="1">

## <i class="fa fa-graduation-cap" aria-hidden="true"></i> Learning Objectives

After completing this tutorial, you will be able to:

* Add a variable to the markdown chunk in your rmd report.

## <i class="fa fa-check-square-o fa-2" aria-hidden="true"></i> What you need

You will need a computer with internet access to complete this lesson and the
data for week 6 of the course.

[<i class="fa fa-download" aria-hidden="true"></i> Download Week 6 Data (~500 MB)](https://ndownloader.figshare.com/files/7677208){:data-proofer-ignore='' .btn }
</div>





```r

total_area <- (800 * 7) / 2
```


There are **2800 km** of burned area according to modis.

How did we do get that variable value to print in our .Rmd output?
To do this, we use the following syntax:

<div class="highlighter-rouge">
<pre class="highlight"><code>2800
</code></pre>
</div>

Where the markdown text is surrounded by ticks. Followed by the language "r"
and then the variable that we want to print in our report!