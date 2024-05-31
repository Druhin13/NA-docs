# Proper Usage of Heading Tags and Titles

## Purpose

This documentation provides guidelines for designers and developers on the correct usage of heading tags and titles. The goal is to ensure semantic structure, enhance accessibility, optimize SEO, and maintain clarity in our workflows.

## Introduction

To avoid confusion and maintain consistency, it is essential to standardize how we name and use heading tags and text styles. Heading tags in HTML range from `h1` to `h6`. Occasionally, designers may name text styles as `h7` or `h8`, which do not exist in HTML. This can lead to confusion for developers. By adhering to the guidelines outlined here, we can ensure a seamless collaboration between design and development teams.

<br>

## Guidelines for Designers

When creating text styles on Figma, please use the following naming conventions:

- **Titles:** `title1`, `title2`, `title3`, etc.
- **Body Text:** `para1`, `para2`, `para3`, etc. (Alternatively: `copy1`, `copy2`, `copy3`)

**Avoid** naming text styles as `h1`, `h2`, `h3`, etc., as these names are reserved for specific semantic roles in HTML. Instead, use "title" with as many numbers as necessary, starting from 1. The same goes for paragraph styles.

### Flexibility in Naming

Designers have the flexibility to use any naming convention for text styles they prefer, as long as they avoid using `h1`, `h2`, `h3`, etc. For instance:

- `title1` can be the main title, a subtitle, or any other style the designer prefers.
- `title2` could be any secondary style, regardless of its size or prominence.
- `para1` (or `copy1`) can be used for the main paragraph style, or any other paragraph style.

### Font Size and Hierarchy

The numeric order of text style names does not need to correspond to their font sizes. For example:

- `title1` does not have to be the largest font size.
- `title6`, `title7`, and `title8` do not have to be the smallest font sizes.

### Avoid Creating Variants

Avoid creating variants of one text style. For instance, instead of naming styles as `h3` and `h3 v2`, create distinct text styles such as `title3` and `title4`.

<br>



## Guidelines for Developers

### Semantic Structure

Ensuring a clear and logical structure using heading tags is crucial for accessibility and SEO. Follow these principles:

1. **Single `h1` Tag Per Page:** Each page should contain only one `h1` tag, representing the main heading.
2. **Maintain Numeric Order:** Heading tags should follow a hierarchical structure. For instance, an `h2` should be a sub-heading of an `h1`, and an `h3` should be a sub-heading of an `h2`.
3. **Avoid Skipping Levels:** Do not skip heading levels. For example, avoid directly jumping from `h1` to `h3`. The correct order is `h1` > `h2` > `h3`, etc.

### Font Size and Hierarchy

The numeric order of heading tags does not need to correspond to their font sizes. For instance:

- An `h1` does not have to be the largest font size.
- An `h6` does not have to be the smallest font size.

The focus should be on the logical and semantic structure, which aids both screen readers and search engine bots in understanding the content hierarchy.

### Practical Example

```html
<h1>Main Heading</h1>
<p>This is a paragraph under the main heading.</p>

<h2>Sub-heading 1</h2>
<p>This is a paragraph under sub-heading 1.</p>

<h3>Sub-heading 1.1</h3>
<p>This is a paragraph under sub-heading 1.1.</p>

<h2>Sub-heading 2</h2>
<p>This is a paragraph under sub-heading 2.</p>
```

<br>

## Summary

- **Designers:** Use flexible names like `title1`, `title2`, `para1`, etc. (or `copy1`, `copy2`), instead of `h1`, `h2`, `h3`.
  - The numeric order of text style names does not need to correspond to their font sizes. For example, `title1` does not have to be the largest font size.
  - Avoid creating variants of one text style. Instead of `h3` and `h3 v2`, use distinct names like `title3` and `title4`.
- **Developers:** Ensure that each page has only one `h1` tag and maintain a proper hierarchical structure with heading tags (`h1`, `h2`, `h3`, etc.).
- **Font Sizes:** Font sizes are not tied to heading tag levels; focus on the semantic meaning of each tag.
- **Avoid Inconsistencies:** Refrain from naming text styles as `h7`, `h8`, etc., to prevent confusion.

By following these guidelines, we can ensure our web pages are accessible, SEO-friendly, and maintain a logical structure. This standardization will facilitate effective and efficient collaboration between our design and development teams, improving project outcomes.


<br>

## What's Next

I am currently working on developing a text-style sheet frame for Figma. This frame will allow designers to add their text styles, including sizes, spacings, and other attributes. Once completed, developers can export the entire frame to Webflow, enabling them to import all the text styles at once. This initiative aims to streamline our design-to-development workflow further and ensure consistency across all projects. Stay tuned for updates on this exciting development!

---
<br>

**Written by Druhin from Not Another™.**
<br>
*Last updated on May 31.*
