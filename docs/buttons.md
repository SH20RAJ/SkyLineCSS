# Buttons

SkyLineCSS provides a set of utility classes to quickly style buttons. These classes can be used to create buttons of different sizes, colors, and styles.

### Basic Button

To create a basic button, use the `.btn` class:

```html
<button class="btn">Button</button>
```

### Button Sizes

You can also specify the size of the button using the following classes:

- `.btn-sm`: Small button
- `.btn-lg`: Large button

Example:

```html
<button class="btn btn-sm">Small Button</button>
<button class="btn btn-lg">Large Button</button>
```

### Button Colors

SkyLineCSS provides predefined color classes for buttons:

- `.btn-primary`: Primary color
- `.btn-secondary`: Secondary color
- `.btn-success`: Success color
- `.btn-danger`: Danger color
- `.btn-warning`: Warning color

Example:

```html
<button class="btn btn-primary">Primary Button</button>
<button class="btn btn-secondary">Secondary Button</button>
<button class="btn btn-success">Success Button</button>
<button class="btn btn-danger">Danger Button</button>
<button class="btn btn-warning">Warning Button</button>
```

### Rounded Buttons

You can create rounded buttons using the `.rounded` class:

```html
<button class="btn rounded">Rounded Button</button>
```

### Full-Width Button

To create a full-width button, use the `.btn-block` class:

```html
<button class="btn btn-block">Full-Width Button</button>
```

### Disabled Button

To create a disabled button, add the `disabled` attribute and use the `.btn-disabled` class:

```html
<button class="btn btn-disabled" disabled>Disabled Button</button>
```

### Button with Icons

You can include icons inside buttons using classes like `.btn-icon-left` and `.btn-icon-right`:

```html
<button class="btn btn-primary btn-icon-left">
  <i class="fas fa-home"></i> Home
</button>

<button class="btn btn-success btn-icon-right">
  Profile <i class="fas fa-user"></i>
</button>
```

### Hover and Focus Styles

SkyLineCSS provides hover and focus styles for buttons:

- `.hover:bg-gray-200`: Background color on hover
- `.hover:text-white`: Text color on hover
- `.focus:outline-none`: Remove outline on focus
- `.focus:ring-2`: Add ring on focus
- `.focus:ring-purple-600`: Ring color on focus
- `.focus:ring-offset-2`: Ring offset on focus

Example:

```html
<button class="btn btn-primary hover:bg-gray-200 hover:text-white focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-offset-2">
  Hover and Focus Button
</button>
```

### Complete Example

Here's a complete example combining different button styles:

```html
<button class="btn btn-primary btn-lg rounded-full">
  Primary Large Rounded Button
</button>

<button class="btn btn-success btn-icon-left hover:bg-green-500">
  <i class="fas fa-check"></i> Success Button
</button>

<button class="btn btn-danger btn-sm btn-block">
  Danger Small Full-Width Button
</button>

<button class="btn btn-warning btn-lg disabled">
  Disabled Warning Button
</button>
```

These are some of the available button styles in SkyLineCSS. Feel free to mix and match these classes to create various button designs for your projects.