---
layout: ../../layouts/MarkdownPostLayout.astro
title: "Astro Markdown Showcase"
pubDate: 2025-09-30
description: "A demonstration of Markdown capabilities in Astro."
author: "Astro Learner"
image:
url: "https://docs.astro.build/assets/rose.webp"
alt: "The Astro logo on a dark background with a pink glow."
tags: ["astro", "markdown", "showcase", "features"]
---

## Table of Contents

1. [Headings](#headings)
2. [Text Formatting](#text-formatting)
3. [Lists](#lists)
4. [Links & Images](#links--images)
5. [Blockquotes](#blockquotes)
6. [Code Blocks](#code-blocks)
7. [Tables](#tables)
8. [Task Lists](#task-lists)
9. [Horizontal Rule](#horizontal-rule)
10. [Emoji & Inline HTML](#emoji--inline-html)

---

## Headings

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Text Formatting

_Italic_, **Bold**, **_Bold Italic_**, ~~Strikethrough~~, <u>Underline (HTML)</u>

Superscript: 2^10^, Subscript: H~2~O

## Lists

**Ordered List:**

1. First item
2. Second item
   1. Nested first
   2. Nested second

**Unordered List:**

- Astro
- Markdown
  - Nested bullet
  - Another nested

## Links & Images

[Astro Documentation](https://docs.astro.build)

![Astro Logo](https://docs.astro.build/assets/astro-logo-light.png "Astro Logo")

## Blockquotes

> "Astro makes building websites fun again!"
>
> — The Astro Team

## Code Blocks

Inline code: `npm create astro@latest`

```js
// JavaScript code block
function greet(name) {
  return `Hello, ${name}!`;
}
```

```astro
---
const name = 'Astro';
---
<h1>Hello {name}!</h1>
```

## Tables

| Feature  | Supported |
| -------- | :-------: |
| Headings |    ✅     |
| Lists    |    ✅     |
| Code     |    ✅     |
| Images   |    ✅     |
| Tables   |    ✅     |

## Task Lists

- [x] Use headings
- [x] Add code blocks
- [x] Insert images
- [ ] Write more posts

## Horizontal Rule

---

## Emoji & Inline HTML

Astro is awesome! 🚀 <span style="color: orange;">Custom HTML works too!</span>
