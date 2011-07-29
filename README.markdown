# NetFinancials Website Instructions

## Add Photos to Partners Slideshow
1. Find `slide-show` in the HTML.
2. Add a line to the `UL` element:

```html
<li><a href="#"><img src="images/the-image.gif" alt="" width="230" height="117" /></a></li>
```

The maximum width of the image is 230px. The maximum height of the image is 117px. Less is okay.

Refresh the page to see changes.

## Add Photos to Quotes Slideshow
1. Find `slide-show2` in the HTML.
2. Add a line to the `UL` element:

```html
<li>
	<div class="blockquote">
		<blockquote cite="#">
			<q>&#8220;QUOTE GOES HERE&#8221;</q>
			<cite>-SOURCE GOES HERE</cite>
		</blockquote>
	</div>
</li>
```
	
Refresh the page to see changes.