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

# 2. CH11 Color.

Colors can really bring your pages to life, it is important to select a nice color to your visitors, and make sure note to make them so bright.

Colors could be used in three different ways :

- RGB values : These express colors in term of how much red,green,and blue are used to make it up for example: rgb(100,100,90)

- HEX codes : These are six-digit codes that
  represent the amount of red, green and blue in a color, preceded by a pound or hash #
  sign. For example: #ee3e80

- Color names : There are 147 predefined color
  names that are recognized by browsers. For example: DarkCyan

## 2.1 Contrast.

When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.

- Low Contrast : Text is harder to read when
  there is low contrast between background and foreground colors.

- High Contrast : Text is easier to read when
  there is higher contrast between background and foreground colors.

- Medium Contrast : For long spans of text, reducing the contrast a little bit improves
  readability.

## 2.2 Opacity.

CSS3 introduces the opacity property which allows you to specify the opacity of an element
and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15% opacity).

## 2.3 HSL & HSLA.

The hsl color property has been introduced in CSS3 as an alternative way to specify colors.
The value of the property starts with the letters hsl, followed by individual values inside parentheses for:

- HUE : This is expressed as an angle (between 0 and 360 degrees).

- saturation : This is expressed as a
  percentage.

- lightness : This is expressed as a
  percentage with 0% being white, 50% being normal, and 100% being black.

- alpha : This is expressed as a
  number between 0 and 1.0. For example, 0.5 represents 50% transparency, and 0.75
  represents 75% transparency.
