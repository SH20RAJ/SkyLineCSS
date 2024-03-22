# Cards

SkyLineCSS provides utility classes to create flexible and responsive cards for displaying content. Cards are a popular UI component for organizing and presenting information in a structured format.

### Basic Card

To create a basic card, use the `.card` class:

```html
<div class="card">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This is a basic card with some text content.</p>
  </div>
</div>
```

### Card with Image

You can include an image in the card using the `.card-img-top` class:

```html
<div class="card">
  <img src="image.jpg" class="card-img-top" alt="Card Image">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card includes an image at the top.</p>
  </div>
</div>
```

### Card with Links and Buttons

You can add links and buttons inside the card body:

```html
<div class="card">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card contains links and buttons.</p>
    <a href="#" class="card-link">Card Link</a>
    <a href="#" class="card-link">Another Link</a>
    <button class="btn btn-primary">Button</button>
  </div>
</div>
```

### Card Header and Footer

You can add headers and footers to the card using the `.card-header` and `.card-footer` classes:

```html
<div class="card">
  <div class="card-header">
    Featured
  </div>
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card includes a header.</p>
  </div>
  <div class="card-footer">
    Footer content
  </div>
</div>
```

### Card Borders

You can add borders to the card using the `.border` class:

```html
<div class="card border">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card has a border.</p>
  </div>
</div>
```

### Card Colors

SkyLineCSS provides predefined color classes for cards:

- `.bg-primary`: Primary background color
- `.bg-secondary`: Secondary background color
- `.bg-success`: Success background color
- `.bg-danger`: Danger background color
- `.bg-warning`: Warning background color

Example:

```html
<div class="card bg-primary">
  <div class="card-body">
    <h5 class="card-title">Primary Card</h5>
    <p class="card-text">This card has a primary background color.</p>
  </div>
</div>

<div class="card bg-success">
  <div class="card-body">
    <h5 class="card-title">Success Card</h5>
    <p class="card-text">This card has a success background color.</p>
  </div>
</div>
```

### Card Shadows

You can add shadows to the card using the `.shadow` and `.shadow-md` classes:

```html
<div class="card shadow">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card has a shadow.</p>
  </div>
</div>

<div class="card shadow-md">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card has a medium shadow.</p>
  </div>
</div>
```

### Responsive Cards

You can make cards responsive using the `.card-deck` and `.card-columns` classes:

```html
<div class="card-deck">
  <!-- Cards displayed in a deck -->
</div>

<div class="card-columns">
  <!-- Cards displayed in multiple columns -->
</div>
```

### Complete Example

Here's a complete example combining different card styles:

```html
<div class="card bg-primary text-white">
  <div class="card-header">
    Featured
  </div>
  <div class="card-body">
    <h5 class="card-title">Primary Card Title</h5>
    <p class="card-text">This card has a primary background color.</p>
    <a href="#" class="btn btn-outline-light">Button</a>
  </div>
</div>

<div class="card shadow mt-4">
  <img src="image.jpg" class="card-img-top" alt="Card Image">
  <div class="card-body">
    <h5 class="card-title">Card with Image</h5>
    <p class="card-text">This card includes an image with a shadow.</p>
    <a href="#" class="btn btn-primary">Button</a>
  </div>
</div>
```

These are some of the available card styling utilities in SkyLineCSS. You can combine these classes to create stylish and responsive cards for your projects.


I assume you're asking for a dark mode version of the documentation for cards. Here's how you can modify the `cards.md` file for dark mode:

### `docs/cards.md` (Dark Mode)

# Cards

SkyLineCSS provides utility classes to create flexible and responsive cards for displaying content. Cards are a popular UI component for organizing and presenting information in a structured format.

### Basic Card

To create a basic card, use the `.card` class:

```html
<div class="card bg-gray-800 text-white">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This is a basic card with some text content.</p>
  </div>
</div>
```

### Card with Image

You can include an image in the card using the `.card-img-top` class:

```html
<div class="card bg-gray-800 text-white">
  <img src="image.jpg" class="card-img-top" alt="Card Image">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card includes an image at the top.</p>
  </div>
</div>
```

### Card with Links and Buttons

You can add links and buttons inside the card body:

```html
<div class="card bg-gray-800 text-white">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card contains links and buttons.</p>
    <a href="#" class="card-link text-purple-300">Card Link</a>
    <a href="#" class="card-link text-purple-300">Another Link</a>
    <button class="btn btn-primary">Button</button>
  </div>
</div>
```

### Card Header and Footer

You can add headers and footers to the card using the `.card-header` and `.card-footer` classes:

```html
<div class="card bg-gray-800 text-white">
  <div class="card-header bg-gray-700">
    Featured
  </div>
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card includes a header.</p>
  </div>
  <div class="card-footer bg-gray-700">
    Footer content
  </div>
</div>
```

### Card Borders

You can add borders to the card using the `.border` class:

```html
<div class="card bg-gray-800 text-white border border-purple-600">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card has a border.</p>
  </div>
</div>
```

### Card Colors

SkyLineCSS provides predefined color classes for cards:

- `.bg-primary`: Primary background color
- `.bg-secondary`: Secondary background color
- `.bg-success`: Success background color
- `.bg-danger`: Danger background color
- `.bg-warning`: Warning background color

Example:

```html
<div class="card bg-primary text-white">
  <div class="card-body">
    <h5 class="card-title">Primary Card</h5>
    <p class="card-text">This card has a primary background color.</p>
  </div>
</div>

<div class="card bg-success text-white">
  <div class="card-body">
    <h5 class="card-title">Success Card</h5>
    <p class="card-text">This card has a success background color.</p>
  </div>
</div>
```

### Card Shadows

You can add shadows to the card using the `.shadow` and `.shadow-md` classes:

```html
<div class="card bg-gray-800 text-white shadow">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card has a shadow.</p>
  </div>
</div>

<div class="card bg-gray-800 text-white shadow-md">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">This card has a medium shadow.</p>
  </div>
</div>
```

### Responsive Cards

You can make cards responsive using the `.card-deck` and `.card-columns` classes:

```html
<div class="card-deck">
  <!-- Cards displayed in a deck -->
</div>

<div class="card-columns">
  <!-- Cards displayed in multiple columns -->
</div>
```

### Complete Example

Here's a complete example combining different card styles:

```html
<div class="card bg-gray-900 text-white">
  <div class="card-header bg-gray-800">
    Featured
  </div>
  <div class="card-body">
    <h5 class="card-title">Primary Card Title</h5>
    <p class="card-text">This card has a primary background color.</p>
    <a href="#" class="btn btn-outline-purple">Button</a>
  </div>
</div>

<div class="card bg-gray-800 text-white shadow mt-4">
  <img src="image.jpg" class="card-img-top" alt="Card Image">
  <div class="card-body">
    <h5 class="card-title">Card with Image</h5>
    <p class="card-text">This card includes an image with a shadow.</p>
    <a href="#" class="btn btn-primary">Button</a>
  </div>
</div>
```

These are some of the available card styling utilities in SkyLineCSS. You can combine these classes to create stylish and responsive cards for your projects in dark mode.