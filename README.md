# Freedom CSS
## Your free CSS library

Freedom CSS is a CSS typographic library that was created as a school project.

## Usage
This library is meant to speed up the proces of creating a simple webpage overwring default behaviour of some HTML elements. This includes headings 
(h1-h6), basic lists, quotes, tables, buttons, images and more.

## Implementation
1. Clone repository or download *freedom.css* library
2. Link to every HTML page where you want to use it:
    ```HTML
    <link rel="stylesheet" href="freedom.css">
    ```
3. Thats it!

## Example
You can preview the library **[here](https://pslib-cz.github.io/2021l4web-typographic-library-Svobodao/example.html)**.
## Dependecies
- **[necolas/normalize.css](https://github.com/necolas/normalize.css/)**
-

## Components
### Typography
#### Headings
The font varies on your browser or system. Used fonts include Segoe UI, Roboto, Helvetica, Arial, Noto Sans and Liberation Sans. You can use headings `<h1>` to `<h6>`. The default font sizes are 48px for `<h1>`, 36px for `<h2>`, 24px for `<h3>`, 20px for `<h4>` and 18px for `<h5>`. Headings `<h1>` and `<h2>` are underlined.
#### Text
Other tags you can use are:
- `<b>` for **bold** text.
- `<u>` to __underline__ text.
- `<s>` to ~~strike~~ text.
- `<u>` to make text *italic*.

You can add `class="align--left"`, `class="align--middle"` or `class="align--right"` to align text to left, middle or right respectively.

### Lists
You can use tags `<ul>` and `<ol>` to make simple unordered or ordered lists up to 3 levels.
```HTML
<ul>
    <li>List item</li>
    <li>List item
        <ul>
            <li>Second List item</li>
            <li>Second List item</li>
        </ul>
    </li>
 </ul>
```

### Quotes
Standard tag `<q>` is used for inline qoutes.
Blockquote can be multiple lines and author is displayed under the qoute. The syntax looks like this:
```HTML
<blockquote class="blockQuote">
    <p class="blockQuote__text">Only two things are infinite, the universe and human stupidity, and I'm not sure about the former.</p>
    <figcaption class="blockQuote__author">Albert Einstein</figcaption>
</blockquote>
```

### Buttons
You can simply add `class="button"` to create a button. You can use both the `<input>` and `<button>` tags. Examples:
```HTML
<input class="button" type="button" value="Click Me!">
<button class="button" type="button">Click Me!</button>
```

...
