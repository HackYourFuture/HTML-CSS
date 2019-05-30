# Reading Material HTML/CSS/GIT Week 1

## Agenda

These are the topics for week 1:

1. What do HTML and CSS do?
2. Introduction to HTML:
   - Crash course
   - The essentials
   - Semantic HTML
3. Introduction to CSS:
   - Crash course
   - Where to write it?
   - The box model
   - The cascading effect
4. Working with the browser
   - What is a web browser?
   - Choosing the right web browser
   - How to use the inspector

## 1. What do HTML and CSS do?

HTML is an acronym for **HyperText Markup Language**. It is used to structure content on a webpage. What do we mean by content? Plain text, images, videos or links to other websites, for example. The structure gives content structure and meaning by defining that content as, for example, headings, paragraphs, or images.

CSS is an acronym for **Cascading Style Sheets**. It is a language created to change the appearance of content. By referring to the HTML tags you can `style` it in various ways: change the font size, increase the height or attach a background image to it.

The two languages—HTML and CSS—are independent of one another and should remain that way. CSS should not be written inside of an HTML document and vice versa. As a rule, HTML will always represent content, and CSS will always represent the appearance of that content.

The products of HTML and CSS comprise a two-thirds of what is called `frontend` (the final third is client-side JavaScript, which you will learn about in later modules). What is frontend? It's another word for the presentational part of a piece of software. In terms of web development we're talking about "what you see" when you go to any website.

## 2. Introduction to HTML

### Crash course

HTML is the foundation of web development. In order to learn this properly it's important to know

- [HTML Crash Course](https://www.youtube.com/watch?v=UB1O30fR-EE)

### The commonly used tags

If at any point you came to believe you would have to learn a whole list of tags by heart in order to write great HTML, you are in luck: that's not needed.

### Further research

## 3. Introduction to CSS

### Where to write it?

There are 3 basic ways to write CSS:

- In an external stylesheet: a `.css` file, that is linked to a `.html` file.
- In the <head> of a `.html` file. This is done using the <style> tag.
- As part of the attribute `style` inside any HTML tag.

As a rule, you want to write your CSS in separate `.css` files. This is because you want to make sure **every file has a single purpose**: an HTML file should only contain the content and structure of a page, while a stylesheet should only contain styling rules that apply to a page.

### The box model

"In CSS, everything is a box". This phrase summarizes a central concept in HTML/CSS: the box model. When building a web page each element can be considered a box that has the following properties: `margins`, `borders`, `paddings` and `content`. Starting from the first element within the <body>, everything that comes after will be pushed down (thanks to these 4 properties).

Watch the following video to [learn more](https://www.youtube.com/watch?v=rIO5326FgPE).
Read the following article to [learn more](https://learn.shayhowe.com/html-css/opening-the-box-model/).

### The cascading effect

The first C in CSS stands for Cascading and it's crucial to learning how to use CSS correctly. Essentially, it means that it matters
(1) **in which order** and
(2) **how specific**
you write CSS rules.

Read the following articles to learn about it:

- [The "C" in CSS](https://css-tricks.com/the-c-in-css-the-cascade/).
- [How CSS works: understanding the cascade](https://blog.logrocket.com/how-css-works-understanding-the-cascade-d181cd89a4d8)

## 4. Working with the browser

### What is a web browser?

You probably use it daily. Let's take a closer look at what it actually is.

A web browser is software that allows you view websites, either retrieved from the internet or loaded from your computer. The primary function of a web browser is to render HTML, transforming all the code (HTML, CSS and JavaScript) as well as the references (images, videos, etc.) to render a webpage.

For further study, watch the following:

- [What is a browser?](https://www.youtube.com/watch?v=TcbhVv9ty44)
- [How web browsers work](https://www.youtube.com/watch?v=WjDrMKZWCt0)

Read:

- [About your web browser](http://www.allaboutcookies.org/browsers/)

### Choosing the right browser

As a web developer you will write code that will display in browsers. As such it is important that you get familiar with most major browsers in use today. These are:

- [Internet Explorer](https://support.microsoft.com/en-us/help/17621/internet-explorer-downloads)
- [Google Chrome](https://www.google.com/chrome/)
- [Safari](https://support.apple.com/downloads/safari)
- [Mozilla Firefox](https://www.mozilla.org/en-GB/firefox/new/)
- [Microsoft Edge](https://www.microsoft.com/en-us/windows/microsoft-edge) (Not available for Mac/Linux yet)
- [Opera](https://www.opera.com/download)

In your HackYourFuture journey you'll mainly be using **Google Chrome** when developing, as is has great developer tools that allow us to develop web applications in an easy and clear way.

### How to use the browser inspector :mag:

The inspector is part of browsers developers can use to take a closer look at the

Watch the following video and follow along:

- [Google Chrome Developer Tools Crash Course](https://www.youtube.com/watch?v=x4q86IjJFag)

## Finished?

Are you finished with going through the materials? Nice job!!! If you feel ready to get practical, click [here](./MAKEME.md)
