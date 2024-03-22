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