# Frontend Basics

Frontend development focuses on how data is structured, displayed, and interacted with in the browser.

## HTML Attributes

Attributes define additional information about HTML elements.
They are written inside the opening tag and usually appear as name–value pairs.

Example:
`<input type="text" placeholder="Enter name" />`

Attributes control behavior, styling, metadata, accessibility, and more.

## Types of HTML Tags

* Opening tag: `<p>`
* Closing tag: `</p>`
* Self-closing tag: `<img />`, `<input />`, `<br />`

Most elements have opening and closing tags. Self-closing tags do not wrap content.

## Viewport

The viewport is the visible area of a web page within the browser window.
It determines how content is displayed on different screen sizes, especially on mobile devices.

Example meta tag:
`<meta name="viewport" content="width=device-width, initial-scale=1.0">`

## Domain Name

A domain name is the human-readable address of a website (e.g., example.com).
It maps to an IP address through DNS (Domain Name System).

## Types of Paths

* Relative Path (not “Present Path”)
  Refers to a file location relative to the current file.
  Example: `./images/nabin.png`

* Absolute Path
  Refers to the complete URL or full file system path.
  Example: `https://example.com/images/logo.png`


---



# Tags
## Basic structure tags

* `<!DOCTYPE html>` – Declares the document as HTML5.
* `<html> `– Root element that wraps the entire page.
* `<head>` – Contains metadata (title, meta tags, links, scripts).
* `<body>` – Contains all visible content.

## Text and content tags

* `<h1>` to `<h6>` – Headings from highest to lowest importance.
* `<p>` – Paragraph of text.
* `<div>` – Block-level container used for grouping content.
* `<span>` – Inline container for styling or grouping small text portions.
* `<br>` – Line break.
* `<hr>` – Thematic horizontal divider.

## Formatting tags

* `<strong>` – Indicates important text (semantic emphasis).
* `<em>` – Emphasized text (usually italicized).
* `<b>` – Bold text (visual only, no semantic meaning).
* `<i>` – Italic text (visual only).
* `<mark>` – Highlighted text.
* `<small>` – Smaller-sized text.

## Links and media

* `<a>` – Creates a hyperlink.
* `<img>` – Embeds an image (self-closing).
* `<audio>` – Embeds audio content.
* `<video>` – Embeds video content.
* `<source>` – Specifies media source for audio/video.

## Lists

* `<ul>` – Unordered (bulleted) list.
* `<ol>` – Ordered (numbered) list.
* `<li>` – List item.

## Tables

* `<table>` – Creates a table.
* `<tr>` – Table row.
* `<td>` – Table data cell.
* `<th>` – Table header cell.
* `<thead>` – Groups header content in a table.
* `<tbody>` – Groups body content in a table.

## Forms

* `<form>` – Container for user input fields.
* `<input>` – Single-line input field.
* `<textarea>` – Multi-line text input.
* `<select>` – Dropdown menu.
* `<option>` – Option inside a dropdown.
* `<button>` – Clickable button.
* `<label>` – Label associated with an input field.

## Semantic layout tags

* `<header>` – Introductory content or navigation area.
* `<nav>` – Navigation links.
* `<main>` – Main content of the document.
* `<section>` – Thematic grouping of content.
* `<article>` – Independent, self-contained content.
* `<aside>` – Sidebar or secondary content.
* `<footer>` – Footer section of a page or section.
