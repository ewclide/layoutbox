#LayoutBox - is easy library of CSS templates
-------------

### Description

	Attention! it based on flex technology.

### Classes

- **--row** ( divides the block to stretched columns )
- **--row-2, --row-3, --row-4, --row-5** ( divides the block on equal columns )
- **--col** ( disposes the elements to vertical column )
- **--left** ( disposes the elements to left of the block)
- **--right** ( disposes the elements to right of the block)
- **--bot** ( disposes the elements to botttom of the block)
- **--mid** ( disposes the elements to middle of the block, can uses with left, top, right, bot.. )
- **--arnd** ( disposes the elements to around of the block )
- **--betw** ( disposes the elements to between of the block )
- **--tile-3** ( defines three columns of tile )
- **--tile-4** ( defines four columns of tile )
- **_cont** ( defines main container - max width 1200px )
- **_cont-hd** ( defines main container - max width 1280px )
- **_hid-768** ( hides the elemets when size less 768px )
- **_screen** ( stretch the elemets to fullscreen )
- **_full** ( stretches the elemet in all the parent block )
- **_trans-250** ( defines "transition" option to 250ms to the elements )
- **_trans-500**  ( defines "transition" option to 500ms to the elements )
- **_trans-250-full** ( defines "transition" option to 250ms to the element and all child elements)
- **_trans-500-full** ( defines "transition" option to 250ms to the element and all child elements)
- **_icon-left** ( addes left space for the icon )
- **_icon-right** ( addes right space for the icon ) // need to add


	css classes divided on:
	1. positioning (begin with --) - use only for positioning
	2. absolute classes (begin with _) - allow to customize common styles of elements
	3. decorators - simple classes come up by user. You can use inheriting and overloading of classes tree
	4. specify 	(begin with -) - use for moving out specific parameters of elements


### Exapmles

```html
<div class="_cont">
	<div class="--left --mid">
		<div class="someclass"></div>
		<div class="someclass"></div>
		<div class="someclass"></div>
	</div>
</div>

<div class="_cont">
	<div class="product-list --tile-4">
		<div class="product"></div>
		<div class="product"></div>
		<div class="product"></div>
		<div class="product"></div>
		<div class="product"></div>
		<div class="product"></div>
		<div class="product"></div>
	</div>
</div>

```

![layoutbox on page](result.jpg)

-------------
Thank's for using.
Developed by Ustinov Maxim - [ewclide](http://vk.com/ewclide)