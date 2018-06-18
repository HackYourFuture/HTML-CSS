## Homework Week 2

>[Here](/Week3/README.md) you find the readings you have to complete before the third lecture.

### Learning goals for this week:
```
 • CLI
    • To know the terminal/bash/command line for UNIX based systems.
    • Navigate the file system without using a UI explorer.
    • Copy, rename and move files with terminal commands. 
 • Student presentations
 • Last week recap and questions
 • Responsive web development
    • Relative measurements (%, (r)em, vw)
    • Media queries
    • Positioning (absolute, relative, fixed)
    • Floating and clearing
    • Flexbox
 • How to work with the inspector
```

## Step 1: Give feedback:

_Deadline Monday_

- In Trello you are added to one of the cards of your fellow students.
- Give feedback CV assignment of one of your fellow student. Please be critical but most of all give constructive feedback. If there are resources that you used and might be useful, share them.
- Revisit you own CV assignment and improve it with the feedback and suggestions given by one of your classmates.  

## Step 2: Command Line

_Deadline Tuesday_

>We covered a bit of command line usage in the first class and got a program running which is great. If you need a refresher for the command line please have a look here: https://github.com/HackYourFuture/CommandLine/blob/master/Lecture-1.md

```
1. Research how to create a hidden file and how to display it using ls command.

2. Research how to create multiple nested directories with one mkdir command.
E.g. How would you create 'fun' directory along with all directories in the path below:
/c/Users/unmesh/these/folders/are/just/for/fun

3. Execute following commands terminal:
echo "test" > fun
echo "another test" >> fun
wc -c fun

Verify number of characters in the file.

4. Research how to append something in the file *WITHOUT* a newline character.
E.g.
echo "test" > fun
echo "another test" >> fun
cat fun
Output of "cat fun" is
test
another test

How would you use echo command, so that output would be:
testanother test

```

## Step 3: Read/do/watch
 - [Introduction to media queries](https://teamtreehouse.com/library/css3/media-queries/introduction)
 - [More about media queries](https://css-tricks.com/css-media-queries/)
 - [HTML syntax](http://www.w3schools.com/html/html5_syntax.asp)
 - [How CSS selectors work](https://css-tricks.com/how-css-selectors-work/)
 - [Article about multiple ways to select classes and id's](https://css-tricks.com/multiple-class-id-selectors)
 - [Read about nice color combinations](http://www.colorcombos.com/index.html)

### Exercises:
 - CodeAcedemy: [Learn Responsive Design](https://www.codecademy.com/learn/learn-responsive-design)

### Super fun flexbox and grid practice 
 - [flexboxfroggy](https://flexboxfroggy.com/)
 - [cssgridgarden](http://cssgridgarden.com/)

## Step 4: Assignment

_Deadline Saturday_

> Use the command line to create a directory "week2" inside your hyf-html-css directory. There should already be a week1 inside that contains your homework of last week.

 - Grids exercise
    - Download the HTML and images in the folder Homework 2 ([or click this link to download](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/HackYourFuture/HTML-CSS/tree/master/Week2/Homework2))
    - You are going to write the CSS for this page
    - You are not allowed to change the HTML
    - The page contains two grids: the first one should work using floats, the second using flex box. Be careful not to mix the two!
    - We want the grid to look as follows (check the wireframe below):
      - On mobile phones: a two column grid, with the exception that the first item spans the full width
      - On tablets: a three column grid, with the exception that the first two items span the full width together (so first we have two columns, then after the first two items we have three columns)
      - On desktops: a four column grid, with the exception that the first item spans two columns.
    - There should be some space between the grid items
    - Make the page look beautiful by adding some more CSS! Some tips:
      - How about some nice colors, fonts, hover styles?
      - According to the grid specification, some products are bigger than others. Maybe these are "highlighted" products, so the rest of the styling could also be different.
    - BEFORE you hand it in, read [the Style guide](http://www.w3schools.com/html/html5_syntax.asp) again and check your files

![Wireframe](assets/wireframe.png)

```
How to hand in your homework:
• Upload your homework in your Github repository. 
• Make sure to create a new folder "week2" first. 
• Your hyf-html-css/week2 should now contain an index.html and a main.css file (and the images folder)
• Place the link to your repository in Trello.
```

## Extra extra (bonus assignment :star: ):

- Add one of the following to your page:
    - An animation using CSS keyframes
    - SVG

## Step 5: Prepare for next class

_Deadline Sunday morning_

Go trough the reading material in the [README.md](/Week3/README.md) to prepare for your next class
