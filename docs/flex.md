# Flexbox Utilities

SkyLineCSS provides a set of utility classes to quickly create flexible layouts using Flexbox. These classes allow you to control the alignment, direction, wrapping, and other properties of flex containers and items.

### Display Flex

To create a flex container, use the `.flex` class:

```html
<div class="flex">
  <!-- Flex items go here -->
</div>
```

### Align Items

You can align flex items along the cross axis using the following classes:

- `.items-start`: Align items at the start
- `.items-center`: Align items at the center
- `.items-end`: Align items at the end
- `.items-baseline`: Align items baseline
- `.items-stretch`: Stretch items to fill the container

Example:

```html
<div class="flex items-center">
  <!-- Centered items -->
</div>

<div class="flex items-end">
  <!-- Items aligned at the end -->
</div>
```

### Justify Content

You can justify flex items along the main axis using the following classes:

- `.justify-start`: Justify content at the start
- `.justify-center`: Justify content at the center
- `.justify-end`: Justify content at the end
- `.justify-between`: Justify content with space between items
- `.justify-around`: Justify content with space around items

Example:

```html
<div class="flex justify-center">
  <!-- Centered content -->
</div>

<div class="flex justify-between">
  <!-- Content with space between items -->
</div>
```

### Flex Direction

You can change the direction of the flex container using the following classes:

- `.flex-row`: Flex direction row
- `.flex-row-reverse`: Flex direction row-reverse
- `.flex-col`: Flex direction column
- `.flex-col-reverse`: Flex direction column-reverse

Example:

```html
<div class="flex flex-row">
  <!-- Flex items in a row -->
</div>

<div class="flex flex-col">
  <!-- Flex items in a column -->
</div>
```

### Flex Wrap

You can enable flex item wrapping using the `.flex-wrap` class:

```html
<div class="flex flex-wrap">
  <!-- Flex items with wrapping -->
</div>
```

### Responsive Flex

SkyLineCSS also provides responsive classes for flex properties. Here's an example:

```html
<div class="flex flex-col md:flex-row">
  <!-- Flex items with column layout on mobile and row layout on desktop -->
</div>
```

These are some of the available Flexbox utilities in SkyLineCSS. You can combine these classes to create flexible and responsive layouts for your projects.
