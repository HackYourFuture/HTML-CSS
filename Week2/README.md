# Reading Material HTML/CSS/GIT Week 2

## Agenda

These are the topics for week 2:

1. Introduction to GIT
   - What is GIT?
   - Installing GIT
   - Basic GIT commands
   - What is GitHub?
   - Working with SSH
2. More advanced CSS
   - Flexible organizing with flexbox
   - Using the grid layout
   - Pseudo class selectors
   - Responsive design with media queries
3. Markdown

## 0. Video Lectures

Your teacher Arco has made video lectures for this week's material. You can find them here: [Videos 7 - 11](https://www.youtube.com/playlist?list=PLVYDhqbgYpYXbAL_Hps1Y--THRmaTFipj)

<a href="https://www.youtube.com/playlist?list=PLVYDhqbgYpYXbAL_Hps1Y--THRmaTFipj" target="_blank"><img src="../assets/week1-arco.png" width="600" height="400" alt="HYF Video" /></a>

## 1. Introduction to GIT

### What is GIT?

GIT is software that allows you to save your work at any given moment in time. It's typically called a `version control system`, which essentially means that it allows you to create `versions` of your workspace and makes possible to switch between older and newer states.

You can think of it like a video game. You get to a certain point in the game, after hours of struggle. You're really proud of how far you've come, and don't want to do it over again in case you die. So you decide to _save your game_. If something bad happens after that point you can always reload your game and start from that point on.

This is exactly what happens with GIT: however, instead of calling it _saving your game_ we call it **committing your changes**. A "change" is a code modification you made in one or more files. It's recommended to commit multiple times a day, every time you make something that is worth saving. Making commits often also makes it easier to reset your work to the last working state. Discarding changes with GIT is better than to trust on CTRL-Z to undo failed attempts.

If you ever would want to go back to a previous _game save_ you can make GIT help you do so by **checking out to that commit**. You will learn more about that in the next sections.

Check out the following short clip to learn about the essentials of GIT:

- [GIT explained in 100 seconds](https://www.youtube.com/watch?v=hwP7WQkmECE)

### Installing GIT

In order to use GIT you first have to install it. The software is different depending on your operating system:

- For Windows, install [Git Bash](https://git-scm.com/download/win)
- For MacOS, install [GIT](https://git-scm.com/download/mac)
- For Linux, install [GIT](https://git-scm.com/download/linux)

After you've installed it you can use it through the CLI. To verify that it worked, enter the command:

```bash
git --version
```

It should say that the version is **2.21** (or up if you've installed a new version).

You can work with GIT using only the CLI but you can also use a GUI (graphical user interface).
Two free cross-platform examples are [SourceTree](https://www.sourcetreeapp.com/) and [Gitkraken](https://www.gitkraken.com/).
It's up to personal preference what works the best, both CLI and GUI will use the same underlying system.
You can even use both in the same project, e.g. commands on the CLI will reflect instantly in the GUI.
The main advantage of a GUI is that it has a visual overview of all commits and branches, local and remote.

Now that you have GIT installed, it's important to make a basic configuration. Inside your CLI, type in the following (Replace "Your name" and "your.email@youremailserver.com" with your own name and email address, respectively).
In case you are using a GUI, it will probably ask the same data the first time you open the application, and it will do these commands for you.

```bash
git config --global user.name "Your name"
git config --global user.email "your.email@yourmailserver.com"
```

This makes sure GIT is able to identify you as the person that uses it to save your files and folders.

### Basic GIT commands

You'll use GIT like any software you execute through the CLI.

There are different ways of using GIT. For now we'll learn one procedure: **committing your workspace to a local repository**. Let's take that phrase apart first:

- **Committing** is another word for saving or storing the changes you've made to the files in your workspace. For example, changing the content of a file is a "change".
- **Workspace** is another word for the project folder (and its contents). When making a repository it will be in the root (in other words, the top level) of the folder.
- **Local** refers to your computer, with no involvement of the internet. When you create a file or folder on your computer, you are creating it "locally".
- **Repository** is a storage location containing the data regarding your project folder. GIT creates a hidden folder `.git` that functions as the local repository.

Before we start we must know the most basic command of all:

```bash
git init
```

What it does is creating a brand new **local** repository in your project folder. Only after doing this you will be able to follow along the next procedure.

Now we can continue with the actual procedure itself. This happens in 3 stages:

1. **Untracked**. In this stage GIT is not aware of the changes in your workspace.
2. **Staged**. In this stage the changes are selected for the next commit.
3. **Committed** In this stage your changes have been saved into the local repository. If you need to refer to a previous version of your workspace you can safely do that now.

This might sound very abstract, and it is. So to make it more comprehensible, you can watch the following videos and/or try stuff in the Git playground:

- [GIT command line basics](https://www.youtube.com/watch?v=HVsySz-h9r4)
- [Learn Git - using CLI & GitKraken](https://www.youtube.com/playlist?list=PLe6EXFvnTV7-_41SpakZoTIYCgX4aMTdU)
- [Introduction to GIT - Core Concepts](https://www.youtube.com/watch?v=uR6G2v_WsRA)
- [GIT & GitHub Crash Course](https://www.youtube.com/watch?v=SWYqp7iY_Tc)
- [Git Playground](https://git-school.github.io/visualizing-git/)

## What is GitHub?

GitHub is **NOT the same** as GIT. While GIT is software that allows you to keep track of your files, GitHub is an online software development platform that allows you to store a copy of your code online. Check the following video to learn more:

- [What is GitHub?](https://www.youtube.com/watch?v=w3jLJU7DT5E)

We use GitHub because of its main benefit: it allows us to freely store our code online (or `remote`, as we developers also call it). This is useful, for example, in the case that our computer crashes and our projects are lost.

The second benefit of using an online code storage is that it allows us to work together with other developers, using one central (and remote) repository. This is done using branches, which you will learn about [next week](../Week3/README.me).

- [GIT Good: A Practical Introduction to GIT and GitHub I](https://codeburst.io/git-good-part-a-e0d826286a2a)
- [GIT Good: A Practical Introduction to GIT and GitHub II](https://codeburst.io/git-good-a-practical-introduction-to-git-and-github-in-git-we-trust-f18fa263ec48)

### Working with SSH

SSH stands for Secure Shell and is a way of providing users a secure way of accessing (the content of) a computer over an unsecure network. Simply put, it makes the connection much more difficult to hack or intercept.

When working with online (or what you'll hear more often: `remote`) code repositories, you might be dealing with unsecure connections. In order to make the connection more secure, you have to use an **SSH key**. Similar to a real key, this digital key allows your computer to be identified by the network you're trying to access. If the connection has been made you can access and modify the contents of network.

> The concept of secure networking through use of identifiers (like an SSH key) is also known as "authentication": are you who you say you are? Authentication is a central idea within programming and you should keep it in mind. You'll also be seeing more of it in later modules!

Check the following resources for more information:

- [Beginners Guide To SSH](https://www.youtube.com/watch?v=qWKK_PNHnnA)
- [How SSH works](https://www.youtube.com/watch?v=zlv9dI-9g1U)

When working with GitHub we want to ensure the same level of security. Thus, we will have to make an SSH key and link it to GitHub!

- [How to generate an SSH key](https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [Adding SSH Key to GitHub](https://www.youtube.com/watch?v=H5qNpRGB7Qw)

## 2. More advanced CSS

By now you've had some practice with CSS. In the following sections you'll learn about some more essentials concepts in order to write modern stylesheets for the web!

### Flexible organizing with flexbox

CSS is used to order and style HTML elements. A big part of this is organising elements in a visually attractive way. This can be done using `flexbox`.

What it does is helping you to think according to `grid-based web design`: elements are not randomly placed on the page, but are neatly organised along a grid.

Read the following to learn more about 'grid-based web design':

- [Introduction to grids in web design](https://webdesign.tutsplus.com/articles/a-comprehensive-introduction-to-grids-in-web-design--cms-26521)
- [Intro to Web Design Grids](https://www.youtube.com/watch?v=gjYZoPEk0ow)

Once you understand this way of thinking you'll know why it makes sense to use `flexbox`.

In order to make use of it we have to access it through the `display` CSS property:

```css
display: flex;
```

This will give us the `flexbox`-specific properties, so we can develop clean and organised CSS. Check the following links to understand how this is done:

- [CSS Flexbox in 100 Seconds](https://www.youtube.com/watch?v=K74l26pE4YA)
- [What is Flexbox and Why to Learn it](https://www.youtube.com/watch?v=CXSwNIPsyTs)
- [CSS Flexbox Course](https://www.youtube.com/watch?v=-Wlt8NRtOpo)

### Using the grid layout

The most recent addition to the css toolkit for organising your layout is using `display: grid`. Where every other layout always goes from top to bottom, grid allows you to create a two-dimensional layout.

The complete guide to grid by css-tricks is the go to guide, read it here:

- [CSS-tricks complete guide to grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Pseudo class selectors

Every HTML element can be in different states. The default state is when an element is untouched. You already know how to style for this.

```css
button {
  background-color: white;
}
```

There are times when a user interacts with an element. For example: clicking a button that opens another page. As frontend developers we need to give the user feedback on that particular action. When they place the mouse on top of the button it lights up (we call this a `hover state`). We need to write instructions for that to happen:

```css
button:hover {
  background-color: blue;
}
```

Like the hover state there are others as well: `click`, `focus`, `visited`, and others. For most of these element states we have special selectors. Read the following article to learn about them. Once you have done that, try them out for yourself!:

- [Pseudo class selectors](https://css-tricks.com/pseudo-class-selectors/)
- [Pseudo-Classes vs Pseudo-Elements in CSS](https://www.youtube.com/watch?v=0VDx1570X3U)

### Responsive design with media queries

Nowadays people use different devices to access websites: desktops, tablets and mobile phones of all different sizes. Responsive design is a way to put together a website so that it automatically scales its content and elements to match the screen size of the viewer. It prevents that images are larger than the screen width, so visitors on mobile devices will see a visually attractive website as well

For more information about responsive design, check this article: [Responsive Design](https://www.internetingishard.com/html-and-css/responsive-design/).

The primary way of making a responsive website is by writing custom CSS code that makes it so. This can be done using `media queries`: CSS instructions that only apply to certain screen sizes.

Learn more about media queries here:

- [Introduction to Media Queries](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Media_queries).
- [Learn CSS Media Query in 7 Minutes](https://www.youtube.com/watch?v=yU7jJ3NbPdA)

### Layouts

Now that you know about all the tools at your disposal it is time to look at creating layouts, which are the most basic design of your app/website. It is important to always do this step first as any changes in the layout will affect all of the other parts in the website, whereas the smaller parts should not affect the layout.

Learn more about them here:
- [The fundamentals of css layouts](https://www.youtube.com/watch?v=yMEjLBKyvEg)

## 3. Markdown

As you've probably seen, every project on GitHub comes with a file called `README.md`
This readme file is used in general to outline the goal of the project and usually includes some code examples.

Even the page you are reading now is also created using Markdown.

Markdown is not a syntax that browsers understand, it is however really simple to write and read with any text editor.
Many online GIT platforms, like GitHub, will parse Markdown files and display them as pretty HTML pages.
Another good example on Markdown support is Slack. You can style your Slack messages using Markdown!

A few examples of what you can do with Markdown:

| HTML                         | Markdown                                     |
| ---------------------------- | -------------------------------------------- |
| H1                           | `# title`                                    |
| H2                           | `## title`                                   |
| _Emphasis_                   | `*italic`                                    |
| **Bold**                     | `**bold**`                                   |
| ~~Strikethrough~~            | `~~Scratch this.~~`                          |
| [Link](#)                    | `[link text](https://somewhere)`             |
| `<p>Single line of code</p>` | `` use single `backticks` around your code`` |

If you want to show a bigger block of code, you start and end with 3 backticks

````markdown
```
   <html>
      <head>...</head>
      <body>...</body>
   </html>
```
````

With Markdown you can to more things like images, list, checklists, tables and more.
If you want to learn more about Markdown you could check these sources:

- [Markdown Crash Course](https://www.youtube.com/watch?v=HUBNt18RFbo)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Finished?

Are you finished with going through the materials? Nice job!!! If you feel ready to get practical, click [here](./MAKEME.md).
