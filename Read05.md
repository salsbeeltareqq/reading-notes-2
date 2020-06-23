[Home](https://sayefdeen.github.io/reading-notes/home)

# 1. CH 10 Intro To CSS

## 1.1 What is CSS?

CSS refer to cascading style sheet, CSS allows you to create rules that specify how the content of an element should appear, for example you can change the background color or change the background image.

The key to understand how CSS works it to imagine that there is an invisible box around every HTML element

- Block Level elements : look like they start on a new line. Examples include the `<h1-h6>`, `<p>` and `<div>` elements.

- Inline elements : flow within the text and do not start on a new line. Examples include `<b>`, `<i>`,
  `<img>`, `<em>` and `<span>`.

## 1.2 How it works?

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule
contains two parts: a **selector** and a **declaration**.

`p { color : red; }`

| Tag   | Means    |
| ----- | -------- |
| p     | Selector |
| color | property |
| red   | value    |

## 1.3 How Can I Use It?

You have three ways to use CSS into your HTML file.

- `<link>` : you can link it as an externail file at the `<head>` tag in your HTML file, using the `href` attribute

- `<style>` : you can make your CSS rules inside HTML file by using this tag in the `<head>` tag. **_not Recommended_**

- Inline : by using the `style` attrubute inside the HTML elements **_not Recommended_**

### 1.3.1 CSS selectors.

| Name                      | Symbol        | Targets                                                                                    |
| ------------------------- | ------------- | ------------------------------------------------------------------------------------------ |
| Universal selector        | `*{}`         | Target all the elements within the page                                                    |
| Type Selector             | `h1,h2,h3 {}` | Target the `<h1>`,`<h2>`,`<h3>` elements                                                   |
| Class Selector            | `.note {}`    | Target each elemnt that hade `class="note"` as a class                                     |
| ID Selector               | `#note {}`    | Target each elemnt that hade `id="note"` as a class                                        |
| Child Selector            | `li>a {}`     | Target each `<a>` that it is inside a `<li>` tag                                           |
| Descendant Selector       | `p a {}`      | Target each `<a>` that it is inside a `<p>` tag even there is another elemnts between them |
| Adjacent Sibling Selector | `h1+p {}`     | Target the **first** `<p>` element after any `<h1>` element (But no other elements)        |
| General Sibling Selector  | `h1~p {}`     | if you had two `<p>` elements after any `<h1>` element this rule apply to both             |
