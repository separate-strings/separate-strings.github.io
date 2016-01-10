---
layout: media
title: "The Connector"
categories: articles
excerpt: "Sa central problem of this marvelous technology is the connection between instrument and amplifier"
tags: [intro, hexaphonic, test]
ads: true
---

The traditional mono or stereo 1/4" jack is not suitable for instruments anyway since it does not supply the instrument. its dumb to hear a weak battery distort on stage although the instrument is always connected to an amplifier where plenty electricity is available. battery powered cirquits are more complicated and rather more noisy. and batteries are a serious ambiental problem.
also the 1/4" has its hot contact at the tip so it creates a big noise when its connected which is absolutely unnecessary.
another problem is that the controls on the guitar need to control values in the amplifier where much better filtering can happen and a real volume control (the one in the guitar is a gain control for distortion, or what?)
so we need a better instrument connector anyway which, apart from several audio channels conducts supply and control voltages
solid multipin connectors are not cheap. 1985, Roland found a solution that turned into a standard:
the 13pin DIN has the following problems:
step on the connector once and its not repairable
the ground contact (including supply!) is only on the housing, which is not save, especially since the standard connector tends to oxidate
the control lines available are: volume, preset up, preset down. we need more than this
the connector is not available in standard electronic parts distributors
there is no straight solder or crimp version that can be easily screwed into a guitar

{% include toc.html %}

## Markdown images

![sample image](http://placehold.it/900x450.gif "placeholder")

[![sample image](http://placehold.it/900x450.gif)](http://placehold.it "A simple image placeholder service.")

## Figures (for images or video)

### One Up

<figure>
	<a href="http://placehold.it/900x450.gif"><img src="http://placehold.it/900x450.gif"></a>
	<figcaption>Image caption.</figcaption>
</figure>

### Two Up

Apply the `half` class like so to display two images side by side that share the same caption.

{% highlight html %}
<figure class="half">
	<img src="{{ site.url }}/images/image-filename-1.jpg">
	<img src="{{ site.url }}/images/image-filename-2.jpg">
	<figcaption>Caption describing these two images.</figcaption>
</figure>
{% endhighlight %}

And you'll get something that looks like this:

<figure class="half">
	<a href="http://placehold.it/1200x600.gif"><img src="http://placehold.it/900x450.gif"></a>
	<a href="http://placehold.it/1200x600.gif"><img src="http://placehold.it/900x450.gif"></a>
	<figcaption>Two images.</figcaption>
</figure>

### Three Up

Apply the `third` class like so to display three images side by side that share the same caption.

{% highlight html %}
<figure class="third">
	<img src="{{ site.url }}/images/image-filename-1.jpg">
	<img src="{{ site.url }}/images/image-filename-2.jpg">
	<img src="{{ site.url }}/images/image-filename-3.jpg">
	<figcaption>Caption describing these three images.</figcaption>
</figure>
{% endhighlight %}

And you'll get something that looks like this:

<figure class="third">
	<img src="http://placehold.it/900x450.gif">
	<img src="http://placehold.it/900x450.gif">
	<img src="http://placehold.it/900x450.gif">
	<figcaption>Three images.</figcaption>
</figure>

Testing images with links to larger images:

<figure class="third">
	<a href="http://placehold.it/1200x600.gif"><img src="http://placehold.it/900x450.gif"></a>
	<a href="http://placehold.it/1200x600.gif"><img src="http://placehold.it/900x450.gif"></a>
	<a href="http://placehold.it/1200x600.gif"><img src="http://placehold.it/900x450.gif"></a>
	<figcaption>Three linked images.</figcaption>
</figure>
