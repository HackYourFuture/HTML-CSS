# Lesson Plan Week 1

## Agenda

The purpose of this class is to introduce to the student:

1. The basics of working with the command line interface
2. Basic HTML/CSS concepts:
   - HTML basics
   - Difference between `<head>` and `<body>` tags
   - Semantic HTML5
   - CSS basics
   - The box model

## Core concepts

**FIRST HALF (12.00 - 13.30)**

## 1. Command line interface basics

### Explanation

- The command line interface (CLI) is a way to navigate your computer by issuing direct commands
- In the past the computer had **ONLY** a command line
- The CLI doesn't always give feedback, like any other program on your computer would give
- Desktop application icons are visual shortcuts (Windows: show `$ calc` to launch the calculator)

### Example

| Command                                                         | Description                                                                                |
| --------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| `pwd`                                                           | present working directory                                                                  |
| `ls`                                                            | List files in the directory                                                                |
| `cd`                                                            | change the directory                                                                       |
| `touch`                                                         | Create an empty file                                                                       |
| `echo`                                                          | display the string                                                                         |
| `echo -n`                                                       | Display the string without newline                                                         |
| `echo “something” > file`                                       | Redirect the output of echo and create file                                                |
| `echo “another thing” >> file`                                  | Append the string to the file                                                              |
| `mkdir`                                                         | make a new directory                                                                       |
| `cd ~`                                                          | home                                                                                       |
| `cd -`                                                          | previous directory                                                                         |
| `cd ..`                                                         | parent directory                                                                           |
| `ls -a`                                                         | List all files including hidden files                                                      |
| `cd /`                                                          | change to the root directory                                                               |
| `cat`                                                           | Concatenate the file line by line and display it on the terminal                           |
| `less`                                                          | Print the big file line by line                                                            |
| `vim <file>`                                                    | open the editor with <file> {`a:` to go to the insert mode, <ESC>`:wq` to write and quit } |
| `for var in {START..END}; do <COMMAND1>; <COMMAND2>;..; ; done` |                                                                                            |
| `head <file>`                                                   | display the first 10 lines of file                                                         |
| `tail <file>`                                                   | display the last 10 lines of file                                                          |
| `head -n <file>`                                                | display first n lines of file                                                              |
| `tail -n <file>`                                                | display last n lines of file                                                               |
| `man <COMMAND>`                                                 | Display manual of the COMMAND                                                              |

### Exercise

- Open a command line (Git Bash on Windows)
- Create a project folder to contain all your HYF work (mkdir)
- Create a module folder (cd, mkdir)
- Create a text file: notes.txt (cd, touch)
- Open Visual Studio Code and add some notes (code .)
- Rename the file to lecture1.txt (mv)

_"I go on holiday and I take with me"_ with CLI commands:

- They have to repeat the commands said before them.
- Add a new command and explain what it does.
- Let the round continue twice otherwise the students that went first don't have to repeat all the commands.

E.g., first student says _"ls : lists commands"_. Second student must say _"ls and cd: change directory"_. Then third student must say _"ls, cd and pwd : show print working directory"_ and so on.
_By [@unmeshvrije](https://github.com/unmeshvrije)_

### Essence

SECOND HALF (14.00 - 16.00)

## 2. HTML basics

### Explanation

- HTML is just plain text, nothing special
- Browsers read the HTML and CSS and render a beautiful webpage
- HTML of a website comes from a server (which is just another computer somewhere)
- Difference `<head>` and `<body>`

Box model

- Everything is a box
- The "box" refers to the attributes universal to every element: `margin`, `padding`, `border`
- Every element pushes against one another

### Example

- Show most basic HTML structure, also show how Visual Studio Code can autocomplete html structure by just typing: html
- `<title>`, `<link>`, `<meta>`
- Show example of the box model by using the browser inspector on various elements

### Exercise

- Using the command line create a project folder, a html file and css file
- Create a basic html structure, and link to an external css file
- Create a webpage which uses all the html tags and css properties which were have discussed

### Essence

## 3. Semantic HTML5

### Explanation

- Explain why there are `<h1>`, `<h2>`, `<h3>`
- In theory a page can be constructed using only `<div>`s
- Semantic tags make the code more comprehensible
- It helps organize the page

### Example

- Show examples of semantic HTML: `<header>`, `<footer>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<aside>`

### Exercise

### Essence
