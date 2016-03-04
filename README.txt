Repository of website skywide.in

-------------------------------------------------------------------------------------------------

Changing The Scrolling Background:

This relies entirely on CSS to do its thing, which is cool, but that makes changing it a bit weird/tricky at first. You can still use pretty much any image you want, but for best results make sure yours is:

	- Horizontally tileable.
	- Wide and short.
	- About 1500px wide.
	- Fades to a solid color either at the top of bottom (which is used to fill the empty space above or below your image).

In CSS,	look for this line in css/style.css (line 108 as of this writing):
	background: #348cb2 url("images/bg.jpg") bottom left;
and use it to set the page background color, URL, and placement of your image. It should be as close to 1500px wide as you can get it.

-------------------------------------------------------------------------------------------------

Website Design Credit:
Aerial by HTML5 UP
html5up.net | @n33co
n33.co @n33co dribbble.com/n33

-------------------------------------------------------------------------------------------------

Other Credits:
- Background Image:
Ryan Schroeder via Unsplash (unsplash.com - CC0 licensed)
"Icefields" (flickr.com/photos/ryanschroeder/11876741703)

- Icons:
Font Awesome (fortawesome.github.com/Font-Awesome)

- Misc:
html5shiv.js (@afarkas @jdalton @jon_neal @rem)
CSS3 PIE (css3pie.com)
Sass (sass-lang.com)
Respond.js (j.mp/respondjs)
Skel (skel.io)

-------------------------------------------------------------------------------------------------
