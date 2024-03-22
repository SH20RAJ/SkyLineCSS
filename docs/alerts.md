# Alerts

SkyLineCSS provides utility classes to create alert messages for displaying important information, warnings, or notifications to users. Alerts are commonly used to convey messages that require attention.

### Basic Alert

To create a basic alert, use the `.alert` class:

```html
<div class="alert">
  This is a basic alert message.
</div>
```

### Alert Colors

SkyLineCSS provides predefined color classes for alerts:

- `.alert-primary`: Primary alert color
- `.alert-secondary`: Secondary alert color
- `.alert-success`: Success alert color
- `.alert-danger`: Danger alert color
- `.alert-warning`: Warning alert color

Example:

```html
<div class="alert alert-primary">
  This is a primary alert message.
</div>

<div class="alert alert-success">
  This is a success alert message.
</div>

<div class="alert alert-danger">
  This is a danger alert message.
</div>

<div class="alert alert-warning">
  This is a warning alert message.
</div>
```

### Dismissible Alerts

You can create dismissible alerts with a close button using the `.alert-dismissible` class:

```html
<div class="alert alert-info alert-dismissible">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close">
    <span aria-hidden="true">&times;</span>
  </button>
  This is a dismissible alert message.
</div>
```

### Alert Links

You can include links in alerts:

```html
<div class="alert alert-info">
  This is an alert message with <a href="#">a link</a>.
</div>
```

### Alert Headings

You can add headings to alerts using the `.alert-heading` class:

```html
<div class="alert alert-info">
  <h4 class="alert-heading">Alert Heading</h4>
  This is an alert message with a heading.
</div>
```

### Alert Icons

You can include icons in alerts using popular icon libraries like Font Awesome:

```html
<div class="alert alert-info">
  <i class="fas fa-info-circle"></i>
  This is an alert message with an icon.
</div>
```

### Alert Transitions

SkyLineCSS provides transition effects for alerts:

- `.alert-fade`: Fade in/out effect
- `.alert-slide`: Slide up/down effect

Example:

```html
<div class="alert alert-success alert-fade">
  This is a success alert with fade effect.
</div>

<div class="alert alert-danger alert-slide">
  This is a danger alert with slide effect.
</div>
```

### Alert Sizes

You can adjust the size of alerts using the following classes:

- `.alert-sm`: Small alert size
- `.alert-lg`: Large alert size

Example:

```html
<div class="alert alert-info alert-sm">
  This is a small alert.
</div>

<div class="alert alert-info alert-lg">
  This is a large alert.
</div>
```

### Complete Example

Here's a complete example combining different alert styles:

```html
<div class="alert alert-primary">
  This is a primary alert message.
</div>

<div class="alert alert-success alert-dismissible">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close">
    <span aria-hidden="true">&times;</span>
  </button>
  This is a dismissible success alert message.
</div>

<div class="alert alert-warning alert-heading">
  <h4 class="alert-heading">Warning Alert</h4>
  This is a warning alert message with a heading.
</div>

<div class="alert alert-danger alert-lg">
  This is a large danger alert message.
</div>
```

These are some of the available alert styling utilities in SkyLineCSS. You can combine these classes to create various types of alert messages for your projects.