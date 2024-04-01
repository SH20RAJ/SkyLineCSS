# Typography

## SkyLineCSS - Typography Utility Classes

SkyLineCSS provides a set of utility classes for controlling typography-related styles. These classes allow you to easily apply font families, sizes, styles, weights, spacing, alignment, colors, decorations, and more to your text elements.

## Font Family

### Classes

* `.font-sans`: Sans-serif font family.
* `.font-serif`: Serif font family.
* `.font-mono`: Monospace font family.

### Usage

```html
<div class="font-sans">Sans-serif Font</div>
<div class="font-serif">Serif Font</div>
<div class="font-mono">Monospace Font</div>
```

## Font Size

### Classes

* `.text-xs`: Extra small font size.
* `.text-sm`: Small font size.
* `.text-base`: Base font size.
* `.text-lg`: Large font size.
* `.text-xl`: Extra large font size.
* `.text-2xl`: 2x large font size.
* `.text-3xl`: 3x large font size.
* `.text-4xl`: 4x large font size.

### Usage

```html
<div class="text-xs">Extra Small Text</div>
<div class="text-lg">Large Text</div>
<div class="text-4xl">4x Large Text</div>
```

## Font Smoothing

### Classes

* `.font-smooth`: Enable font smoothing.

### Usage

```html
<div class="font-smooth">Smooth Font</div>
```

## Font Style

### Classes

* `.italic`: Italic font style.

### Usage

```html
<div class="italic">Italic Text</div>
```

## Font Weight

### Classes

* `.font-thin`: Thin font weight.
* `.font-light`: Light font weight.
* `.font-normal`: Normal font weight.
* `.font-medium`: Medium font weight.
* `.font-semibold`: Semi-bold font weight.
* `.font-bold`: Bold font weight.
* `.font-extrabold`: Extra bold font weight.
* `.font-black`: Black font weight.

### Usage

```html
<div class="font-thin">Thin Font</div>
<div class="font-bold">Bold Font</div>
<div class="font-black">Black Font</div>
```

## Font Variant Numeric

### Classes

* `.font-ordinal`: Enable ordinal font variants.
* `.font-slashed-zero`: Enable slashed zero font variants.

### Usage

```html
<div class="font-ordinal">1st</div>
<div class="font-slashed-zero">0</div>
```

## Letter Spacing

### Classes

* `.tracking-tight`: Tight letter spacing.
* `.tracking-normal`: Normal letter spacing.
* `.tracking-wide`: Wide letter spacing.

### Usage

```html
<div class="tracking-tight">Tight Letter Spacing</div>
<div class="tracking-wide">Wide Letter Spacing</div>
```

## Line Clamp

### Classes

* `.line-clamp-2`: Clamp text to 2 lines.
* `.line-clamp-3`: Clamp text to 3 lines.
* `.line-clamp-4`: Clamp text to 4 lines.

### Usage

```html
<div class="line-clamp-2">Clamp Text to 2 Lines</div>
<div class="line-clamp-4">Clamp Text to 4 Lines</div>
```

## Line Height

### Classes

* `.leading-none`: No extra line height.
* `.leading-tight`: Tight line height.
* `.leading-normal`: Normal line height.
* `.leading-loose`: Loose line height.

### Usage

```html
<div class="leading-tight">Tight Line Height</div>
<div class="leading-loose">Loose Line Height</div>
```

## List Style Image

### Classes

* `.list-none`: No list style image.
* `.list-disc`: Bulleted list style.
* `.list-decimal`: Numbered list style.

### Usage

```html
<ul class="list-disc">
  <li>Bullet Point 1</li>
  <li>Bullet Point 2</li>
</ul>

<ol class="list-decimal">
  <li>Numbered Point 1</li>
  <li>Numbered Point 2</li>
</ol>
```

## List Style Position

### Classes

* `.list-inside`: List marker inside the list item.
* `.list-outside`: List marker outside the list item.

### Usage

```html
<ul class="list-outside">
  <li>List Item 1</li>
  <li>List Item 2</li>
</ul>

<ol class="list-inside">
  <li>List Item A</li>
  <li>List Item B</li>
</ol>
```

## List Style Type

### Classes

* `.list-none`: No list style.
* `.list-disc`: Disc list style.
* `.list-decimal`: Decimal list style.
* `.list-square`: Square list style.

### Usage

```html
<ul

 class="list-square">
  <li>Square Point 1</li>
  <li>Square Point 2</li>
</ul>

<ol class="list-decimal">
  <li>Decimal Point 1</li>
  <li>Decimal Point 2</li>
</ol>
```

## Text Align

### Classes

* `.text-left`: Left-aligned text.
* `.text-center`: Center-aligned text.
* `.text-right`: Right-aligned text.
* `.text-justify`: Justified text.

### Usage

```html
<div class="text-left">Left Aligned Text</div>
<div class="text-right">Right Aligned Text</div>
```

## Text Color

### Classes

* `.text-black`: Black text color.
* `.text-white`: White text color.
* `.text-gray`: Gray text color.
* `.text-red`: Red text color.
* `.text-blue`: Blue text color.
* `.text-green`: Green text color.

### Usage

```html
<div class="text-red">Red Text</div>
<div class="text-blue">Blue Text</div>
```

## Text Decoration

### Classes

* `.underline`: Underline text.
* `.line-through`: Line through text.
* `.no-underline`: No underline.

### Usage

```html
<div class="underline">Underlined Text</div>
<div class="line-through">Line Through Text</div>
```

## Text Decoration Color

### Classes

* `.underline-black`: Black underline.
* `.underline-white`: White underline.
* `.underline-gray`: Gray underline.

### Usage

```html
<div class="underline-black">Black Underline</div>
<div class="underline-gray">Gray Underline</div>
```

## Text Decoration Style

### Classes

* `.underline-dashed`: Dashed underline.
* `.underline-dotted`: Dotted underline.
* `.underline-double`: Double underline.

### Usage

```html
<div class="underline-dashed">Dashed Underline</div>
<div class="underline-double">Double Underline</div>
```

## Text Decoration Thickness

### Classes

* `.underline-thin`: Thin underline.
* `.underline-medium`: Medium underline.
* `.underline-thick`: Thick underline.

### Usage

```html
<div class="underline-thin">Thin Underline</div>
<div class="underline-thick">Thick Underline</div>
```

## Text Underline Offset

### Classes

* `.underline-offset`: Offset underline.

### Usage

```html
<div class="underline-offset">Offset Underline</div>
```

## Text Transform

### Classes

* `.uppercase`: Uppercase text.
* `.lowercase`: Lowercase text.
* `.capitalize`: Capitalize text.

### Usage

```html
<div class="uppercase">UPPERCASE TEXT</div>
<div class="lowercase">lowercase text</div>
```

## Text Overflow

### Classes

* `.overflow-ellipsis`: Ellipsis overflow.
* `.overflow-clip`: Clip overflow.

### Usage

```html
<div class="overflow-ellipsis">Long Text with Ellipsis Overflow</div>
<div class="overflow-clip">Long Text with Clip Overflow</div>
```

## Text Wrap

### Classes

* `.whitespace-normal`: Normal text wrap.
* `.whitespace-nowrap`: No wrap text.
* `.whitespace-pre`: Preformatted text.

### Usage

```html
<div class="whitespace-normal">Normal Text Wrap</div>
<div class="whitespace-nowrap">No Wrap Text</div>
```

## Text Indent

### Classes

* `.indent`: Text indentation.

### Usage

```html
<div class="indent">Indented Text</div>
```

## Vertical Align

### Classes

* `.align-baseline`: Baseline vertical alignment.
* `.align-top`: Top vertical alignment.
* `.align-middle`: Middle vertical alignment.
* `.align-bottom`: Bottom vertical alignment.

### Usage

```html
<div class="align-top">Top Aligned Text</div>
<div class="align-middle">Middle Aligned Text</div>
```

## Whitespace

### Classes

* `.whitespace-normal`: Normal whitespace.
* `.whitespace-nowrap`: No whitespace.

### Usage

```html
<div class="whitespace-nowrap">No Whitespace</div>
<div class="whitespace-normal">Normal Whitespace</div>
```

## Word Break

### Classes

* `.break-normal`: Normal word break.
* `.break-words`: Break words.
* `.break-all`: Break all.

### Usage

```html
<div class="break-words">LongWordLongWordLongWordLongWord</div>
```

## Hyphens

### Classes

* `.hyphens-none`: No hyphenation.
* `.hyphens-auto`: Auto hyphenation.

### Usage

```html
<div class="hyphens-auto">Hyphenated Text</div>
```

## Content

### Classes

* `.content-center`: Centered content.

### Usage

```html
<div class="content-center">Centered Content</div>
```
