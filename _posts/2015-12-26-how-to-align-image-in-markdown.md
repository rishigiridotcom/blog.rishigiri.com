---
layout: post
title: "How to align image in markdown"
description: "align image in markdown in jekyll"
author: impiza
modified: 2015-12-26
tags: [Align image in markdown, Add image align feature in jekyll]
image:
  feature: abstract-13.jpg
  background: triangular.png
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
---

>its been a long time that i am searching how to align image in markdown language & i have find an easy way to do it,to add this feature to jekyll, just follow below procedure

### Align Code for CSS

Add below given CSS code in your  `/_sass/_page.scss`. and save it

{% highlight css %}
// align image center/left/right
// --------------------------------------------------
/* To center images */

.center {
    text-align: center;
}

/* To left images */

.align-left {
    text-align: left;
}

/* To right images */

.align-right {
    text-align: right;
}
{% endhighlight %}





## For Align your images in markdown language use this examples

### For Center Align
{% highlight css %}
{% raw %}
{: .center}
![image]({{ site.url }}/images/Adobe-dreamweaver-js-icon.png)
{% endraw %}
{% endhighlight %}
{: .center}
![image]({{ site.url }}/images/Adobe-dreamweaver-js-icon.png)


### For Left Align
{% highlight css %}
{% raw %}
{: .align-left}
![image]({{ site.url }}/images/Adobe-dreamweaver-js-icon.png)
{% endraw %}
{% endhighlight %}
{: .align-left}
![image]({{ site.url }}/images/Adobe-dreamweaver-js-icon.png)

### For Right Align
{% highlight css %}
{% raw %}
{: .align-right}
![image]({{ site.url }}/images/Adobe-dreamweaver-js-icon.png)
{% endraw %}
{% endhighlight %}
{: .align-right}
![image]({{ site.url }}/images/Adobe-dreamweaver-js-icon.png)

i hope you find this post usefull !  :)  enjoy 

by impiza 

