# Basic konwledge about the CSS

>The second blog for the Front-end.

## What is the CSS?

CSS(Cascading Style Sheets) is the style sheet language for design the web pages, includes font-size, color, and layouts.

##Basic Box Model

Each of element has different spaces, apperence, and the box model also do. For example:

1. Padding: One of space around the content.
2. Border: The solid line beside of the padding.
3. Margin: One of space around the outside of element.

![google.com](https://inknight.cn/pic/note/%E6%A0%87%E5%87%86%E7%9B%92%E6%A8%A1%E5%9E%8B.png)

## Application of CSS

It is mainly designed to enable the distinction between presentation and content, including colors, layouts, and fonts. It can be used in different types of devices, like large or small screens and printers. It is independent of HTML and can be used with any XML-based markup language.

1. External Stylesheet
<link rel="stylesheet" href="xxxx.css">
2. Internal Stylesheet
<style> h1{font-size:30px;}<style>
3. Inline Stylesheet
<p style="background-color: burlywood; font-size: 10px;">Derek Sun</p>

##CSS‘s operating principle

1. Load HTML
2. Parse HTML>Load CSS>Parse CSS>Attach style to DOM nodes
3. Create DOM tree
4. Display

![google.com](https://user-images.githubusercontent.com/12515800/28882583-3b577798-77de-11e7-9078-24689495b143.jpg)

## CSS selectors

1. CSS Element Selector
2. CSS Id Selector
3. CSS Class Selector
4. CSS Universal Selector
5. CSS Group Selector

![google.com](https://cf.ppt-online.org/files/slide/k/Kbp3XcismqFREgGuz9OBIWY1vDx6MwHVeZQjC5/slide-8.jpg)

### Selectors priority

!important>inline stysheet>id selector>class selector>group selector>element selector>universal selector
