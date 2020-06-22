[Home](https://sayefdeen.github.io/reading-notes/home)

# 1. CH 18 Proccess and Design
Before starting to desing your web site you have to ask yourself a punch of questions.

## 1.1 Who is the site for?
Every web site should be desinged for the tareget audience, it is therefor very important to understand who your target audience is, it can be helpful to ask some question to know your visitors more, the qustions are different between individuals or companies.

*Now that you know your visitors you have to ask yourself some questions.*

* Why People visit Your website
* What Your Visitors are
Trying to Achieve
* What Information
Your Visitors Need
* How Of ten People Will
Visit Your Site

answering these questions will help you design your website to fulfill these questions, since you need visitors to make your website successful.

## 1.2 Site Map.

Now that you know what needs to appear on your site, you can start to organize the information into sections or pages, tha aim to create a diagram of the pages that will be used to structure the site, this known as a **site map** this map will show you how the pages can be grouped.

Ok now i know the term Site Map, but how am I suppose to use it? , you can use a technique called *card sorting*, it means that you have to write on a single paper the use of what the user is expecting from this page, these papers should be organized in a group then these groups are turned into the digram that is known as site map.

## 1.3 Wireframe.

This term is a simple sketch of the key information that needs to go on each page of a site, this will help make sure that you will never forget any information that needs to be on the page included.

Do not include the color scheme, font choices, backgrounds of images for the website in the wireframe, it should focus on what information needs to be on each page and create a visual hierarchy to indicate the most important parts of each page.

## 1.4 Desing.

Since you did the site map and the wireframe you are ready to begin desinging your website, design is all about communication this should be clear in your designe,organizing and prioritizing
information on a page helps users understand
its importance and what order to read it in.

always remeber not to make everything that appeard in the same style, because it would be much harder to understand (key messages would not stand out).

## 1.5Visual hierarchy.

Most web users do not read entire pages. Rather, they skim to find information. You can use contrast to create a visual hierarchy that gets
across your key message and helps users find what they are looking for, by Playing with :

* Size : Larger elements will grab the user attension.
* Color : Foreground and background
color can draw attention to key
messages.
* Style : An element may be the same
size and color as surrounding
content but have a different style
applied to it to make it stand out.

## 1.6 Grouping and Similarity

When making sense of a design, we tend to organize visual elements into groups. Grouping related pieces of information together can make a
design easier to comprehend. Here are some ways this can be achieved.

* Proximity: When several items are placed close together, they are perceived as more related than
items that are placed further apart.
* Closure: When faced with a complicated arrangement of items.
* Continuance: When elements are placed in
a line or a curve then they are perceived to be more related than those that are not following
the same direction.
* White Space: Placing related items closer
together and leaving a bigger gap between unrelated items.
* Color: A background color placed
behind related items to emphasize their connection.
* Borders: A line can be drawn around the
border of the group or between it and its neighbors.

## 1.7 Designing Navigation.

Site navigation not only helps people find where they want to go, but also
helps them understand what your site is about and how it is organized.
Good navigation tends to follow these principles..

* Concise: Ideally, the navigation should
be quick and easy to read.
* Clear: Users should be able to predict
the kind of information that they will find on the page before clicking on the link.
* Selective: The primary navigation should
only reflect the sections or content of the site.
* Context: Good navigation provides
context. It lets the user know where they are in the website at that moment.
* Interactive: Each link should be big enough
to click on and the appearance of the link should change when the user hovers over each item
or clicks on it.
* Consistent: The more pages a site contains,
the larger the number of navigation items there will be.

# 2. Ch 17 HTML5 Layout.

## 2.1 Past and Now.

for a long time HTML developers was using `<div>` with a specific id for each use example `<div id="header">` this div is for a header, in HTML5 we have a new tags such as

| Tag Name    | Usage       |
| ----------- | ----------- |
| `<header>`  | used to hold the site name and the main navigation    |
| `<footer>`  | used to hold copyright information along with links to the privacy policy|
| `<nav>`  | element is used to contain the major navigational blocks on the site such as the primary site navigation.|
| `<section>` | element groups related content toghether      |
| `<hgroup>`  | group a set of hraders `<h1-h4>`       |
| `<div>`     | Such a container       |
| `<Figure>`  | it can be used to contain ant content that is referenced form the main flow|



# 3. Ch 8 HTML5 Layout.

Since the web was first created, there have
been several different versions of HTML. Each new version was designed to be an improvement on the
last (with new elements and attributes added and older code removed).

There have also been several versions of each browser used to view web pages, each of which
implements new code. Not all web users, however, have the latest browsers installed on their computers, which means that not everyone will be able to view all of the latest features and markup.

* HTML 4 Released 1997
* XHTML 1.0 Released 2000
*  **XHTML5 Released 2000**

*HTML5 is the version we use write now*

* DOCTYPES : because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using (although
browsers usually display the page even if it is not included).

* Comments : If you want to add a comment
to your code that will not be visible in the user's browser, you can add the text between these
characters: `<!-- comment goes here -->` 

* ID attribute : Every HTML element can carry
the id attribute. It is used to uniquely identify that element from other elements on the
page. Its value should start with a letter or an underscore (not a number or any other character).
It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).

* Class attribute : Every HTML element can
also carry a class attribute. Sometimes, rather than uniquely identifying one element within
a document, you will want a way to identify several elements as being different from the
other elements on the page. For example, you might have some paragraphs of text that
contain information that is more important than others and want to distinguish these elements, or
you might want to differentiate between links that point to other pages on your own site and links that point to external sites.

* Block Elements : Some elements will always
appear to start on a new line in the browser window. These are known as **block level** elements.
    * `<h1-h6>`
    * `<p>`
    * `<ul>`
    * `<li>`
* Inline Elements : html Some elements will always
appear to continue on the same line as their neighbouring elements. These are known as
inline elements.
    * `<a>`
    * `<b>`
    * `<em>`
    * `<img>`

* Grouping Text & Elements In a Block :
 `<div>` element allows you to
group a set of elements together
in one block-level box, In a browser, the contents of the `<div>` element will start on
a new line, but other than this
it will make no difference to the
presentation of the page.

* Grouping Te xt & Elements Inline : `<span>`  element acts like an inline equivalent of the `<div>` element. It is used to either:
    * Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text.

    * Contain a number of inline
elements


*Follow this [Link](https://www.w3schools.com/html/html_entities.asp) to see more Info about Escape Characters in HTML5*


