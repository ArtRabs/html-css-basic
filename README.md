# HTML and CSS Basics

Another day with Bro Code learning his [HTML & CSS Full Course for free 🌎](https://youtu.be/HGTJBPNC-Gw?si=a0IynkT4bDszamhX).

I want to be Backend Developer but who knows.

## 📚 Table of Contents
- [Lesson 1: HTML Basics](#lesson-1-html-basics)
- [Lesson 2: Hyperlinks](#lesson-2-hyperlinks)
- [Lesson 3: Images](#lesson-3-images)
- [Lesson 4: Audio](#lesson-4-audio)
- [Lesson 5: Video](#lesson-5-video)
- [Lesson 6: Favicons](#lesson-6-favicons)
- [Lesson 7: Text Formatting](#lesson-7-text-formatting)
- [Lesson 8: Span and Div](#lesson-8-span-and-div)
- [Lesson 9: Lists](#lesson-9-lists)
- [Lesson 10: Tables](#lesson-10-tables)
- [Lesson 11: Buttons](#lesson-11-buttons)
- [Lesson 12: Forms](#lesson-12-forms)
- [Lesson 13: Headers and Footers](#lesson-13-headers-and-footers)
- [Lesson 14: CSS Basics](#lesson-14-css-basics)
- [Lesson 15: Colors](#lesson-15-colors)
- [Lesson 16: Fonts](#lesson-16-fonts)
- [Reference](#reference)

## 📝 Lessons

Press the Lesson #: **Name** to be redirected to the .html of the said lesson.

### **Lesson 1: [HTML Basics](./lesson-01-html-basic/index.html)**  

  Covers the foundational HTML structure:

  - `<!DOCTYPE html>` declaration
  - `<html>`, `<head>`, `<title>`, `<body>` elements
  - Text elements: `<p>`, `<pre>`
  - Separators: `<hr>`, `<br>`
  - Comments: `<!-- ... -->`

  **Demo Files:**
  - [lyrics.html](./lesson-01-html-basic/lyrics.html) — A simple page with a song title and lyrics

<hr>

### **Lesson 2: [Hyperlinks](./lesson-02-hyperlinks/index.html)**  

  Demonstrates different ways to use the `<a>` tag:

  - External links (`href="https://..."`)
  - Opening links in a new tab (`target="_blank"`)
  - Adding tooltips with the `title` attribute
  - Relative links to other lessons (`../lesson-01-html-basic/lyrics.html`)
  - Placeholder/anchor links (`href="lyrics.html"`)
  - Email links (`mailto:`)

  **Demo Files:**
  - [lyrics.html](./lesson-02-hyperlinks/lyrics.html) — Now with link to the original video

<hr>

### **Lesson 3: [Images](./lesson-03-images/index.html)**  

  Shows how to embed images with the `<img>` tag:

  - Basic image embedding with `src`, `alt`, `height`, and `width` attributes
  - Linking an image to an external site using `<a>` + `<img>`
  - Displaying animated GIFs
  - Using descriptive `alt` text for accessibility

  **Demo Files:**
  - [images folder](./lesson-03-images/images/)  
  - [lyrics.html](./lesson-03-images/lyrics.html)  
  - Contains image (`nah id win.jpg`), (`pc_kv1.png`) and GIF (`gojo.gif`).

<hr>

### **Lesson 4: [Audio](./lesson-04-audio/index.html)**  

  Covers different ways to use the `<audio>` tag:

  - Basic audio embedding with `src` and `type` attributes
  - Adding playback controls (`controls`)
  - Autoplaying audio (`autoplay`) — note: may require `muted` due to browser restrictions
  - Looping audio (`loop`)
  - Providing multiple formats (`.mp3`, `.wav`, etc.) for compatibility
  - Labeling audio clips with descriptive text for clarity

  **Demo Files:**
  - [audio folder](./lesson-04-audio/audio/) — presents multiple audio files:
    - `ultra-instinct-theme-official-version.mp3`
    - `batida-de-porta-troll.mp3`
    - `fahhh_KcgAXfs.mp3`
    - `ping_missing.mp3`
    - `tuco-get-out.mp3`
    - `kono-dio-da99.mp3`

<hr>

### **Lesson 5: [Video](./lesson-05-video/index.html)**  

  Shows how to embed and control video playback with the `<video>` tag, kinda like the `<image>` too:

  - Basic video embedding with `<video>` and `<source>`
  - Attributes:
    - `controls` → adds play/pause/volume UI
    - `autoplay` → starts playback automatically
    - `muted` → required for autoplay in most browsers
    - `height` / `width` → set video dimensions
  - Wrapping a video in a hyperlink (`<a>`) to redirect when clicked
  - Supporting multiple video files with `<source>` elements (I do not have any video files here other than `.mp4`, but `.webm`, `.avi`, `.ogg` will work)

  **Demo Files:**
  - `clip_1,764,935,995,030.mp4` — autoplay + muted demo, wrapped in a link to [Monster Hunter Rise on Steam](https://store.steampowered.com/app/1446780/MONSTER_HUNTER_RISE/)  
  - `Hollow Knight- Silksong - 2025-10-02 6-01-13 PM.mp4` — manual controls demo

<hr>

### **Lesson 6: [Favicons](./lesson-06-favicons/index.html)**  

  Explains how to add a favicon to your website using the `<link>` tag:

  - Basic favicon setup with `<link rel="icon">`
  - Supported image formats: `.ico`, `.png`, `.svg`, `.jpg`
  - Using the `type` attribute (`image/image-type`, `image/image-name`, etc.)
  - Best practice: edit the image itself to the correct size (e.g., 96×96) instead of relying on `sizes` like `width` and `length`, but not restricted of course


  **Demo Files:**
  - [index.html](./lesson-06-favicons/index.html) — includes:
    ```html
    <link 
        rel="icon" 
        type="image/png" 
        href="images/favicon 96x96.png">
    ```
    - Uses a `favicon.png` edited to 96×96 pixels  
    - Demonstrates clean setup without `sizes` attribute

<hr>

### Lesson 7: [Text Formatting](./lesson-07-text-formatting/index.html)  

  Demonstrates various text formatting tags in HTML:

  - `<b>` and `<strong>` for bold text
  - `<i>` and `<em>` for italic text
  - `<u>` for underlined text
  - `<del>` for deleted text
  - `<big>` for larger text
  - `<small>` for smaller text
  - `<sub>` for subscript text
  - `<sup>` for superscript text
  - `<tt>` for monospace text
  - `<mark>` for highlighted text

  **Demo Files:**
  - [index.html](./lesson-07-text-formatting/index.html) — showcases all the above formatting tags

<hr>

### Lesson 8: [Span and Div](./lesson-08-span-and-div/index.html)  

  Explains the use of `<span>` and `<div>` for grouping and styling content:

  - `<span>`: inline container for text, useful for styling parts of a sentence
  - `<div>`: block-level container for larger sections of content
  - Applying inline styles using the `style` attribute (e.g., `background-color`)

  **Demo Files:**
  - [index.html](./lesson-08-span-and-div/index.html) — includes examples of both `<span>` and `<div>` with different background colors

<hr>

### Lesson 9: [Lists](./lesson-09-lists/index.html)  

  Covers the creation of ordered and unordered lists in HTML:

  - `<ul>` for unordered (bulleted) lists
  - `<ol>` for ordered (numbered) lists
  - `<li>` for list items
  - Nesting lists within lists for sub-items
  - `<dt>`, and `<dd>` for description lists

  **Demo Files:**
  - [index.html](./lesson-09-lists/index.html) — demonstrates both unordered, ordered and description lists with nested items

<hr>

### Lesson 10: [Tables](./lesson-10-tables/index.html)  

  Introduces HTML table elements for displaying tabular data:

  - `<table>`: defines the table
  - `<tr>`: defines a table row
  - `<th>`: defines a header cell
  - `<td>`: defines a standard data cell
  - `width`: sets the width of the header cell
  - Using attributes like `border`, `cellpadding`, and `cellspacing` to style tables

  **Demo Files:**
  - [index.html](./lesson-10-tables/index.html) — includes a sample table with headers and data cells

<hr>

### Lesson 11: [Buttons](./lesson-11-buttons/index.html)  

  Explains how to create and style buttons:

  - `<button>`: defines a clickable button
  - Adding `<a>` inside buttons
  - Using inline styles to customize button appearance (e.g., `font-size`,`background-color`, `color`)
  - A sneak peek of JavaScript with `onclick` attribute to trigger actions when the button is clicked

  **Demo Files:**
  - [index.html](./lesson-11-buttons/index.html) — showcases button styles
  - [page2.html](./lesson-11-buttons/page2.html) — includes buttons with JavaScript actions

<hr>

### Lesson 12: [Forms](./lesson-12-forms/index.html)  

Introduces HTML form elements for user input:

- `<form>`: defines the form, with `action`, `method`, and `enctype`
- `<label>`: labels for form elements
- `<input>`: various types
  - `text` with `minlength`, `maxlength`, `required`
  - `password` with length restrictions
  - `email` with `placeholder`
  - `tel` with `pattern` for validation
  - `date` for birthdate
  - `number` with `min` and `max`
  - `radio` buttons grouped with `name`
  - `checkbox` for subscription
  - `file` with `accept` filter
  - `reset` and `submit` controls
- `<select>` and `<option>`: dropdown menus
- `<textarea>`: multi-line text input
- Attributes like `placeholder`, `pattern`, `required`, `min`, `max`, `accept`

**Demo Files:**
- [index.html](./lesson-12-forms/index.html) — includes a sample form with different input types, validation attributes, and file upload

<hr>

### Lesson 13: [Headers and Footers](./lesson-13-headers-and-footers/index.html)

  Covers the semantic HTML5 elements `<header>` and `<footer>`:

  - `<header>`: defines the header section of a webpage, typically containing the site title, logo, and navigation links.
  - `<footer>`: defines the footer section, usually containing copyright information, contact links, and additional navigation

  **Demo Files:**
  - [index.html](./lesson-13-headers-and-footers/index.html) — Portrays the use of `<header>` and `<footer>` with sample content, including an image (`Lloyd OK.png`)

<hr>

### Lesson 14: [CSS Basics](./lesson-14-css-basic/index.html)

  Introduces the basics of CSS for styling HTML elements:

  - Inline CSS using the `style` attribute
  - Internal CSS within a `<style>` tag in the `<head>`
  - External CSS using a separate `.css` file linked with `<link>`
  - Basic CSS properties like `color`, `background-color`, and text styling
  - Class selectors for styling multiple elements

  **Demo Files:**
  - [index.html](./lesson-14-css-basic/index.html) — demonstrates inline, internal, and external CSS
  - [page2.html](./lesson-14-css-basic/page2.html) — another page styled with CSS classes
  - [style.css](./lesson-14-css-basic/style.css) — external CSS file with class definitions

<hr>

### Lesson 15: [Colors](./lesson-15-colors/index.html)

  Explores color usage in CSS:

  - Different color formats: `named colors`,  `RGB`, `HEX`, and `HSL`
  - Applying colors to text and backgrounds using CSS properties

  **Demo Files:**
  - [index.html](./lesson-15-colors/index.html) — showcases various color formats applied to text and backgrounds
  - [style.css](./lesson-15-colors/style.css) — external CSS file defining color styles

### Lesson 16: [Fonts](./lesson-16-fonts/index.html)

  Covers the use of custom fonts in web design:

  - Importing fonts from Google Fonts using `<link>` in the `<head>`
  - Applying imported fonts to HTML elements using CSS `font-family` property
  - Using multiple font families for fallback options

  **Demo Files:**
  - [index.html](./lesson-16-fonts/index.html) — demonstrates importing and applying Google Fonts remotely
  - [style.css](./lesson-16-fonts/style.css) — external CSS file defining font styles and using local fonts

## 📜 Reference <a id="reference"> </a>

Bro Code's [HTML & CSS Full Course for free 🌎](https://youtu.be/HGTJBPNC-Gw?si=a0IynkT4bDszamhX) and thank you for being such a chad.

Lesson 3:

- Jujutsu Kaisen Chapter 221 `nah id win.jpeg`

- Jujustsu Kaisen Season 2 Episode 4 `gojo.gif`

- [`pc_kv1.png`](https://heavenburnsred.yo-star.com/fankit/pc-wallpaper/) is from official website of Heaven Burns Red.

All audio in Lesson 4 is from [Myinstants](https://www.myinstants.com/en/categories/sound%20effects/). (Nah, I ain't one by one it, help)

Videos from lesson 5: 
  - `clip_1,764,935,995,030.mp4` (My Monster Hunter Rise Sunbreak gameplay clip)  
  - `Hollow Knight- Silksong - 2025-10-02 6-01-13 PM.mp4` (My Hollow Knight - Silksong gameplay clip)  

In Lesson 6, both `favicon.png` is from Blazblue Entropy Effect, a given wallpaper.

Lesson 13: `Lloyd OK.png` is from [The Greatest Estate Developer](https://www.webtoons.com/en/fantasy/the-greatest-estate-developer/list?title_no=3596), I forgot what chapter is the picture, but you can read the entire thing to see it. (Definitely not baitin- suggesting you to read it)

Lesson 16 from Google Fonts:     

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@100..900&family=Science+Gothic:wght@100..900&display=swap" rel="stylesheet">
```