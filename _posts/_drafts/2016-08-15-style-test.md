---
layout: post
title: "A Full and Comprehensive Style Test"
description: "Test post for style"
date: 2016-08-15
tags: test, style
comments: true
---

Below is just about everything you'll need to style in the theme. Check the [source code](https://raw.githubusercontent.com/mkchoi212/paper-jekyll-theme/master/_posts/2016-08-15-style-test.md) to see the many embedded elements within paragraphs.

---

## 1. Header 

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

### 1-1. Header Alignment 

##### Left(Default)

##### Center
{: .center}

##### Right
{: .right}

## 2. Body Text

Lorem ipsum dolor sit amet, [test link](https://www.google.com) adipiscing elit. **This is strong.** Nullam dignissim convallis est. Quisque aliquam. *This is emphasized.* Donec faucibus. Nunc iaculis suscipit dui. 5<sup>3</sup> = 125. Water is H<sub>2</sub>O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. <u>Underline</u>. Maecenas ornare tortor. Donec sed tellus eget `COPY filename` sapien fringilla nonummy. <abbr>Mauris a ante</abbr>. Suspendisse quam sem, consequat at, <del>Dinner’s at 5:00.</del> commodo vitae, feugiat in, nunc. Morbi imperdiet augue <mark>mark element</mark> quis tellus.

## 2a. Badges

`<span class="c-badge c-badge-pill c-badge-success">Success</span>`<br><br>
<span class="c-badge c-badge-pill c-badge-primary">Primary</span> <span class="c-badge c-badge-pill c-badge-secondary">Secondary</span> <span class="c-badge c-badge-pill c-badge-success">Success</span> <span class="c-badge c-badge-pill c-badge-info">Info</span> <span class="c-badge c-badge-pill c-badge-warning">Warning</span> <span class="c-badge c-badge-pill c-badge-danger">Danger</span> <span class="c-badge c-badge-pill c-badge-light">Light</span> <span class="c-badge c-badge-pill c-badge-dark">Dark</span>

## 2b. Alerts
<div class="c-alert c-alert-primary" role="alert">
	<span class="c-badge c-badge-pill c-badge-primary">Please note:</span> Text
</div>
<div class="c-alert c-alert-secondary" role="alert">
	<span class="c-badge c-badge-pill c-badge-secondary">Please note:</span> Text
</div>
<div class="c-alert c-alert-success" role="alert">
	<span class="c-badge c-badge-pill c-badge-success">Please note:</span> Text
</div>
<div class="c-alert c-alert-info" role="alert">
	<span class="c-badge c-badge-pill c-badge-info">Please note:</span> Text
</div>
<div class="c-alert c-alert-danger" role="alert">
	<span class="c-badge c-badge-pill c-badge-danger">Please note:</span> Text
</div>
<div class="c-alert c-alert-warning" role="alert">
	<span class="c-badge c-badge-pill c-badge-warning">Please note:</span> Text
</div>
<div class="c-alert c-alert-light" role="alert">
	<span class="c-badge c-badge-pill c-badge-light">Please note:</span> Text
</div>
<div class="c-alert c-alert-dark" role="alert">
	<span class="c-badge c-badge-pill c-badge-dark">Please note:</span> Text
</div>

## 3. Images

![Large example image](http://placehold.it/800x400 "Large example image")
![Medium example image](http://placehold.it/400x200 "Medium example image")
![Small example image](http://placehold.it/200x200 "Small example image")

### 3-1. Image Alignment

![Center example image](http://placehold.it/200x200 "Center")
{: .center}

## 4. Blockquotes

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## 5. List Types

### Unordered List

* Lorem ipsum dolor sit amet, consectetur adipiscing elit.
* Nam ultrices nunc in nisi pellentesque ultricies. Cras scelerisque ipsum in ante laoreet viverra. Pellentesque eget quam et augue molestie tincidunt ac ut ex. Sed quis velit vulputate, rutrum nisl sit amet, molestie neque. Vivamus sed augue at turpis suscipit fringilla.
* Integer pretium nisl vitae justo aliquam, at varius nisi blandit.
  1. Nunc vehicula nulla ac odio gravida vestibulum sed nec mauris.
  2. Duis at diam eget arcu dapibus consequat.
* Etiam vel elit in purus iaculis pretium.

### Ordered List

1. Quisque ullamcorper leo non ex pretium, in fermentum libero imperdiet.
2. Donec eu nulla euismod, rhoncus ipsum nec, faucibus elit.
3. Nam blandit purus gravida, accumsan sem in, lacinia orci.
  * Duis congue dui nec nisi posuere, at luctus velit semper.
  * Suspendisse in lorem id lacus elementum pretium nec vel nibh.
4. Aliquam eget ipsum laoreet, maximus risus vitae, iaculis leo.

### Definition Lists

kramdown
: A Markdown-superset converter

Maruku
: Another Markdown-superset converter

## 6. Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3


## 7. Code Snippets

### Highlighted Code Blocks

```css
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
```

### Standard code block

    <div id="awesome">
      <p>This is great isn't it?</p>
    </div>
