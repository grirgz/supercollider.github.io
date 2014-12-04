---
layout: catpage
title: "Code examples"
description: ""
category: "examples"
sort_order: 2
---

You can find a lot of code on [SuperCollider Code](http://sccode.org)


A babbling brook by [James McCartney 2007](http://www.listarc.bham.ac.uk/lists/sc-users-2007/msg02698.html).

{% highlight javascript %}
{
({RHPF.ar(OnePole.ar(BrownNoise.ar, 0.99), LPF.ar(BrownNoise.ar, 14)
		* 400 + 500, 0.03, 0.003)}!2)
	+ ({RHPF.ar(OnePole.ar(BrownNoise.ar, 0.99), LPF.ar(BrownNoise.ar, 20)
	* 800 + 1000, 0.03, 0.005)}!2)
	* 4
}.play
{% endhighlight %}

<iframe width="100%" height="400" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?visual=true&url=http%3A%2F%2Fapi.soundcloud.com%2Fgroups%2F3574&show_artwork=true">hello</iframe>
