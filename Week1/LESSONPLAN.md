# Lesson Plan Week 1

## Agenda

The purpose of this class is to introduce to the student (1) the basics of working with the command line interface, and (2) basic HTML/CSS concepts:

**FIRST HALF:**

- Command line interface basics

**SECOND HALF:**

- HTML basics
- Difference `<head>` and `<body>`
- Semantic HTML5
- CSS basics
- The box model

## FIRST HALF (12.00 - 13.30)

### 1. Command line interface basics

- The command line interface (CLI) is a way to navigate your computer by issuing direct commands
- In the past computer had **just** a command line
- Desktop application icons are visual shortcuts (Windows: show `$ calc` to launch the calculator)

_Tell and show basic command line concepts: `~`, `$`, path, avoid spaces, ctrl+c to cancel, arrow up to go through history, Windows: right click paste_

_Show students the most commonly used commands (`ls`, `pwd`, `cd`, `echo`, `cat`, `mkdir`, `touch`, `mv`, `cp`, `clear`, `exit`)_

### 2. Exercise

- Open a command line (Git Bash on Windows)
- Create a project folder to contain all your HYF work (mkdir)
- Create a module folder (cd, mkdir)
- Create a text file: notes.txt (cd, touch)
- Open Visual Studio Code and add some notes (code .)
- Rename the file to lecture1.txt (mv)

## SECOND HALF (14.00 - 16.00)

### 1. HTML basics

- HTML is just plain text, nothing special
- Browsers read the HTML and CSS and render a beautiful webpage
- HTML of a website comes from a server (which is just another computer somewhere)

_Show most basic HTML structure, also show how Visual Studio Code can autocomplete html structure by just typing: html_

### 2. Difference `<head>` and `<body>`

- The `<head>` holds all the page's meta-data: information about the complete webpage

_Show examples of what the `<head>` could hold and why: `<title>`, `<link>`, `<meta>`_

- The `<body>` holds all the elements that will be displayed in the browser

_Show examples of commonly used HTML tags: `<h1>`, `<a href="#">`, `<div>`_

### 3. Semantic HTML5

- Explain why there are `<h1>`, `<h2>`, `<h3>`
- In theory a page can be constructed using only `<div>`s
- Semantic tags make the code more comprehensible
- It helps organize the page

_Show examples of semantic HTML: `<header>`, `<footer>`, `<section>`_

### 4. CSS Basics

- Explain inline css, `<style>` block css and external css
- Roughly two types of CSS, styling (text) and CSS for layout structure

_Show different ways to write css, and some basic css properties: `font-size`, `background-color`, `border`_

### 5. The box model

- Everything is a box
- The "box" refers to the attributes universal to every element: `margin`, `padding`, `border`
- Every element pushes against one another

_Show example of the box model by using the browser inspector on various elements_

### 6. HTML/CSS Exercise

- Using the command line create a project folder, a html file and css file
- Create a basic html structure, and link to an external css file
- Create a webpage which uses all the html tags and css properties which were have discussed
