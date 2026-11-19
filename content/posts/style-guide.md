---
title: "Style guide"
date: 2026-11-18
description: "Reference for headings, code, and the other formatting this site renders."
tags:
  - reference
  - markdown
toc: true
---

For future Joey

Copy from this post when writing a new one. The source is `content/posts/style-guide.md`. The title, date, and tags above the line come from the front matter. Set `toc: true` when a post is long enough to need a table of contents.

## Headings

The post title is the only first-level heading. This section title is a second-level heading. The ones below are the deeper levels.

### Third level

#### Fourth level

##### Fifth level

###### Sixth level

## Inline text

A paragraph can mix **bold**, *italic*, ***both***, ~~strikethrough~~, and a [link](https://joey.foo/). Use `backticks` for a short name such as a command, file, or function.

Footnotes sit at the bottom of the page.[^1]

[^1]: The footnote marker in the paragraph jumps here.

## Code

A fenced block with a language name:

```bash
# Build the site
hugo --minify

# Preview it
hugo server
```

A second language, so the label changes:

```go
package main

import "fmt"

func main() {
    fmt.Println("hello")
}
```

The same block written with Hugo's highlight shortcode:

{{< highlight html >}}
<p>Hello</p>
{{< /highlight >}}

## Lists

Unordered:

- First
- Second
- Third

Ordered:

1. Write the post in `content/posts/`
2. Save the file
3. Refresh the preview

Nested:

- Fruit
  - Apple
  - Orange
- Dairy
  - Milk

Tasks:

- [x] Draft
- [ ] Publish

Definition list:

Hugo
: The static site generator.

Chicago7
: The look this site is based on.

## Quote

> Don't communicate by sharing memory, share memory by communicating.
>
> — Rob Pike

## Table

| Syntax | Renders as |
| --- | --- |
| `**bold**` | **bold** |
| `*italic*` | *italic* |
| `` `code` `` | `code` |

## Rule

Three dashes on their own line:

---

## Picture

![Site logo](/logo.svg)

## Small HTML

These need raw HTML in the Markdown file.

<abbr title="Graphics Interchange Format">GIF</abbr> is an image format.

H<sub>2</sub>O and E = mc<sup>2</sup>

Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to stop the preview.

<mark>Highlighted</mark> words use the mark tag.
