# Tables

SkyLineCSS provides utility classes to style HTML tables with ease. These classes can be used to add borders, padding, alignment, and other styling to tables and their elements.

### Basic Table

To create a basic table, use the `.table` class:

```html
<table class="table">
  <thead>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
      <th>Header 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data 1</td>
      <td>Data 2</td>
      <td>Data 3</td>
    </tr>
    <tr>
      <td>Data 4</td>
      <td>Data 5</td>
      <td>Data 6</td>
    </tr>
  </tbody>
</table>
```

### Table Borders

You can add borders to the table and its cells using the following classes:

- `.table-bordered`: Add borders to the table and cells
- `.border`: Add border to individual cells

Example:

```html
<table class="table table-bordered">
  <!-- Table with borders -->
</table>

<table class="table">
  <tr>
    <td class="border">Cell 1</td>
    <td class="border">Cell 2</td>
    <td class="border">Cell 3</td>
  </tr>
</table>
```

### Table Striped Rows

To add striped rows to the table, use the `.table-striped` class:

```html
<table class="table table-striped">
  <!-- Table with striped rows -->
</table>
```

### Table Hover Effect

You can add a hover effect to the table rows using the `.table-hover` class:

```html
<table class="table table-hover">
  <!-- Table with hover effect -->
</table>
```

### Table Padding

To add padding to the table cells, use the following classes:

- `.p-1`: Small padding
- `.p-2`: Medium padding
- `.p-4`: Large padding

Example:

```html
<table class="table">
  <tr>
    <td class="p-1">Cell 1</td>
    <td class="p-2">Cell 2</td>
    <td class="p-4">Cell 3</td>
  </tr>
</table>
```

### Table Border Collapse

You can control the border collapse behavior using the following classes:

- `.border-collapse`: Collapse borders
- `.border-separate`: Separate borders

Example:

```html
<table class="table border-collapse">
  <!-- Table with collapsed borders -->
</table>

<table class="table border-separate">
  <!-- Table with separate borders -->
</table>
```

### Table Border Spacing

To adjust the border spacing between cells, use the following classes:

- `.border-spacing`: No border spacing
- `.border-spacing-2`: 2px border spacing
- `.border-spacing-4`: 4px border spacing

Example:

```html
<table class="table border-spacing-2">
  <!-- Table with 2px border spacing -->
</table>

<table class="table border-spacing-4">
  <!-- Table with 4px border spacing -->
</table>
```

### Table Layout

You can control the table layout using the following classes:

- `.table-auto`: Automatic table layout
- `.table-fixed`: Fixed table layout

Example:

```html
<table class="table table-auto">
  <!-- Automatic table layout -->
</table>

<table class="table table-fixed">
  <!-- Fixed table layout -->
</table>
```

### Table Caption Side

You can position the table caption using the following classes:

- `.caption-top`: Position caption on top
- `.caption-bottom`: Position caption on bottom

Example:

```html
<table class="table caption-top">
  <caption>Table Caption</caption>
  <!-- Table with caption on top -->
</table>

<table class="table caption-bottom">
  <caption>Table Caption</caption>
  <!-- Table with caption on bottom -->
</table>
```

### Responsive Tables

SkyLineCSS provides responsive classes for tables. Here's an example:

```html
<div class="table-responsive">
  <table class="table">
    <!-- Responsive table -->
  </table>
</div>
```

### Complete Example

Here's a complete example combining different table styles:

```html
<div class="table-responsive">
  <table class="table table-bordered table-striped table-hover">
    <thead>
      <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="border p-2">Data 1</td>
        <td class="border p-2">Data 2</td>
        <td class="border p-2">Data 3</td>
      </tr>
      <tr>
        <td class="border p-2">Data 4</td>
        <td class="border p-2">Data 5</td>
        <td class="border p-2">Data 6</td>
      </tr>
    </tbody>
  </table>
</div>
```

These are some of the available table styling utilities in SkyLineCSS. You can combine these classes to create stylish and responsive tables for your projects.