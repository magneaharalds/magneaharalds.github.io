---
layout: page
title: Week 7
permalink: /week7/
published: false
---

# Include a static image
This is an image of a cool cat

![A cool cat](/images/cool_cat.jpg){:class="img-responsive"}

# Include a bokeh plot
This is a plot showing crimes per hour by category that we made in week 6. 

{% include week6.html %}

# Write latex equations
$$
r^2 \cdot \frac{1}{2} \pi 
$$

# Write code
```python
for i in range(10):
    print("This is line number", i)
```