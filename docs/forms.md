# Forms

SkyLineCSS provides utility classes to style HTML forms quickly and efficiently. These classes can be used to style form elements such as inputs, selects, checkboxes, and radio buttons.

### Basic Form Input

To style a basic form input, use the `.form-input` class:

```html
<input type="text" class="form-input" placeholder="Enter your name">
```

### Form Sizes

You can adjust the size of form inputs using the following classes:

- `.input-sm`: Small input size
- `.input-lg`: Large input size

Example:

```html
<input type="text" class="form-input input-sm" placeholder="Small Input">
<input type="text" class="form-input input-lg" placeholder="Large Input">
```

### Form Colors

SkyLineCSS provides predefined color classes for form inputs:

- `.bg-gray-200`: Background color
- `.text-blue-500`: Text color
- `.border`: Border color

Example:

```html
<input type="text" class="form-input bg-gray-200 text-blue-500 border" placeholder="Custom Color Input">
```

### Form Validation States

You can style form inputs based on validation states using the following classes:

- `.valid-input`: Valid input
- `.invalid-input`: Invalid input

Example:

```html
<input type="text" class="form-input valid-input" placeholder="Valid Input">
<input type="text" class="form-input invalid-input" placeholder="Invalid Input">
```

### Checkboxes and Radio Buttons

You can style checkboxes and radio buttons using the following classes:

- `.checkbox`: Checkbox style
- `.radio`: Radio button style

Example:

```html
<input type="checkbox" id="checkbox1" class="checkbox">
<label for="checkbox1">Checkbox</label>

<input type="radio" id="radio1" name="radio" class="radio">
<label for="radio1">Radio Button</label>
```

### Select Boxes

To style select boxes, use the `.select` class:

```html
<select class="select">
  <option value="1">Option 1</option>
  <option value="2">Option 2</option>
  <option value="3">Option 3</option>
</select>
```

### Form Buttons

You can style form buttons using the `.btn` class:

```html
<button class="btn btn-primary">Submit</button>
<button class="btn btn-secondary">Cancel</button>
```

### Form Groups

You can group form elements using the `.form-group` class:

```html
<div class="form-group">
  <label for="name">Name:</label>
  <input type="text" id="name" class="form-input">
</div>

<div class="form-group">
  <label for="email">Email:</label>
  <input type="email" id="email" class="form-input">
</div>
```

### Form Layouts

SkyLineCSS provides classes for form layouts:

- `.form-inline`: Inline form layout
- `.form-horizontal`: Horizontal form layout

Example:

```html
<form class="form-inline">
  <input type="text" class="form-input" placeholder="Username">
  <button class="btn btn-primary">Submit</button>
</form>

<form class="form-horizontal">
  <div class="form-group">
    <label for="username" class="col-sm-2">Username:</label>
    <div class="col-sm-10">
      <input type="text" id="username" class="form-input">
    </div>
  </div>
  <div class="form-group">
    <label for="password" class="col-sm-2">Password:</label>
    <div class="col-sm-10">
      <input type="password" id="password" class="form-input">
    </div>
  </div>
</form>
```

These are some of the available form styling utilities in SkyLineCSS. You can combine these classes to create stylish and responsive forms for your projects.