# Reading Material HTML/CSS/GIT Week 1

## Agenda

These are the topics for week 1:

1. What do HTML and CSS do?
2. Introduction to HTML:
   - The essentials
   - Semantic HTML
   - Parents, children, attributes
   - Indentation
3. Introduction to CSS:
   - Where can we write it and what difference does that make?
   - The box model
   - The cascading effect
   - Selectors (id, class, element type), properties
   - How to structure a CSS file
   - Naming things
4. Introduction to ARIA:
   - What is ARIA and why is it important?
   - Using ARIA in HTML
   - Validating ARIA

## 1. What do HTML and CSS do?

HTML is an acronym for **HyperText Markup Language**. It is used to structure content on a webpage. What do we mean by content? Plain text, images, videos or links to other websites, for example. The structure gives content structure and meaning by defining that content as, for example, headings, paragraphs, or images.

CSS is an acronym for **Cascading Style Sheets**. It is a language created to change the appearance of content. By referring to the HTML tags you can `style` it in various ways: change the font size, increase the height or attach a background image to it.

The two languages—HTML and CSS—are independent of one another and should remain that way. CSS should not be written inside of an HTML document and vice versa. As a rule, HTML will always represent content, and CSS will always represent the appearance of that content.

The products of HTML and CSS comprise a two-thirds of what is called `frontend` (the final third is client-side JavaScript, which you will learn about in later modules). What is frontend? It's another word for the presentational part of a piece of software. In terms of web development we're talking about "what you see" when you go to any website.

## 2. Introduction to HTML

### The essentials

There are four sets of HTML tags that are needed to form the basic structure for every HTML file:

```html
<html></html>
<head></head>
<title></title>
<body></body>
```

Let's take a closer look at each of them:

```
Definition - <html> </html>
```

This basically defines the document as a web page. It also identifies the beginning and end of the HTML document. All other tags must fall between the html tags.

```
Header - <head> </head>
```

The header contains meta information: information about the information displayed in the document, such as the title, the author, stylesheet references and others.

```
Title - <title> </title>
```

The title tag defines the title that will appear in the title bar of your web browser. The title must appear between the head tags.

```
Body - <body> </body>
```

The body tags contain all the information and other visible content on the page. All your images, links and plain text must go between the <body></body> tags.

These four tags are special. There must only be one set of each and they must be in the correct order.

### Semantic HTML

You're probably familiar with basic tags like <div> or <p>. The use of these might be obvious, but if you would read an HTML file full of these tags you most likely wouldn't be able to understand what's going on.

This is where semantic tags are helpful. 'Semantic' is another word for 'meaningful'. With the arrival of HTML5 tags like <header>, <section> and <footer> it's much more clear to the reader what the role and purpose of any given HTML section would be.

### The commonly used tags

If at any point you came to believe you would have to learn a whole list of tags by heart in order to write great HTML, you are in luck: that's not needed.

### Further research

## 3. Introduction to CSS

## Where to write it

## The box model

"In CSS, everything is a box". This phrase summarizes a central concept in HTML/CSS: the box model. When building a web page each element can be considered a box that has the following properties: `margins`, `borders`, `paddings` and `content`. Starting from the first element within the <body>, everything that comes after will be pushed down (thanks to these 4 properties).

Watch the following video to [learn more](https://www.youtube.com/watch?v=rIO5326FgPE).
Read the following article to [learn more](https://learn.shayhowe.com/html-css/opening-the-box-model/).

## The cascading effect

The first C in CSS stands for Cascading and it's crucial to learning how to use CSS correctly.

Read the following article to [learn about it](https://css-tricks.com/the-c-in-css-the-cascade/).

## 4. Introduction to ARIA

- [What is ARIA and why is it important?](https://www.youtube.com/watch?v=HtTyRajRuyY)
- [Introduction to ARIA](https://www.youtube.com/watch?v=g9Qff0b-lHk)
- [Web applications and ARIA FAQ](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Web_applications_and_ARIA_FAQ)

> Don't worry if you don't understand everything, but make sure to prepare some questions for your first session about the reading material.

## [Optional] Browsers & the Internet:

Have time left over? Or just curious? Check out the following videos to get more background information:

- <a href="https://www.youtube.com/watch?v=7_LPdttKXPc" target="_blank">How the Internet Works in 5 Minutes</a>
- <a href="https://www.youtube.com/watch?v=WjDrMKZWCt0" target="_blank">How Web Browsers Work</a>

## Add a card in Trello:

- In Trello, create a card with your name (there is an example in there) and add the link to your CodePen that contains you technical assignment.
