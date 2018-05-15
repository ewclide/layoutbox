

# LayoutBox - css library of templates

	Attention! it based on flex technology.

### Directions:

- **--row** - defines internal elements as columns
- **--col** - places elements in a vertical column
-  **--static** - saves the row direction at lower screen resolutions

### Positions:

- **--left** - places internal elements to the left
- **--right** - places internal elements to the right
- **--bottom** - places internal elements to the bottom
- **--center** - places internal elements to the center
- **--around** - places internal elements of the block evenly
- **--between** - places internal elements across the entire width of the block

### Dividing:

- **--tile-(3,4)** - converts the internal elements of a block to a tile
- **--grid-(2-6)** - converts the internal elements of a block to a grid

### Containers  and sections:

- **_container** - max width 1200px
- **_container-hd** - max width 1280px
- **_container-thin** - max width 1024px
- **_footer** - pushes the footer to the bottom. It works also on **footer tag**

### Size affect:

- **_screen** - stretches the element to full screen
- **_full** - stretches the element to full parent block

### Hide affect:

- **_hide-1024**
- **_hide-768**
- **_hide-420**
- 
### Additional:

- **_trans-250** - assigns the transition property
- **_trans-500**
- **_trans-250-full** - assigns the transition property to all child elements and subelements
- **_trans-500-full**
- **_icon-left** - addes left space for the icon

## How to use

This method is based on class inheritance, which allows you to use name overload.
Classes are also divided into types:

- **positional** (start with "--") - use only for positioning elements
- **global** (start with "_") - allows you to customize common element styles
- **decorators** (starting with "-" ) - are used to change certain properties of the element
- **simple** - user-defined classes. You can use class inheritance and overload


### Exapmles

```html
<div class="_container">
	<div class="--left --center">
		<div class="some"></div>
		<div class="some"></div>
		<div class="some"></div>
	</div>
</div>
<div class="_container">
	<div class="product-list --tile-4">
		<div class="product"></div>
		<div class="product"></div>
		<!-- ... -->
		<div class="product"></div>
	</div>
</div>
```

-------------
Thank's for using.
Developed by Ustinov Maxim - [ewclide](http://vk.com/ewclide)