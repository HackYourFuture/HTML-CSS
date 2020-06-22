# Reading Material HTML/CSS/GIT Week 3

## Agenda

These are the topics for week 3:

1. GIT branching
    - Local branches
    - Working with branches on GitHub
    - Making pull requests
2. CSS Frameworks
    - Why use a framework?
    - Most popular frameworks
    - CSS Framework vs. custom CSS
3. Working with the browser
    - What is a web browser?
    - Choosing the right web browser
    - How to use the inspector
    - Useful browser extensions

## 1. GIT branching

### Local branches

`Branches` are a core feature of GIT. A branch allows you to work on a different "version" of your project. Take a look at the following image:

![branches](assets/branches.png)

You can see a branch as an experiment, a possible way your project can evolve. Usually, each branch (except the `master` branch) contains code for what is called a new `feature`: a piece of functionality that you want to add to your software. Let's take Facebook as a simple example: After creating an account (which is a feature itself) you can do multiple things. Each "thing" is a feature: having a news feed, being able to send friend requests or liking posts.

Working with branches is especially important when working with other developers. This only applies when working with a **remote** repository, which we'll talk about in the next section.

When working with different branches it is useful to have one single branch that contains all the working and finished code: the `master` branch (we call it master out of convention, but in actuality you can name it whatever you want). Whenever you're working on a project that has already been put on the internet, it is the code from the master branch that is online.

However, usually there's a separate branch that contains all the development code. Of course, this is called the `development` branch. This branch is an almost exact copy of master, but contains features that have not been tested yet.

After finishing a feature, it is time to merge the branch into the main branch. This is usually either the `master` or `development` branch.

Once the new version of the software has been tested and approved, the cycle repeats!

Go through the following resources to learn more:

-   [Git Tutorial: Branches](https://www.youtube.com/watch?v=sgzkY5vFKQQ)
-   [Introduction to GIT - Branching and Merging](https://www.youtube.com/watch?v=FyAAIHHClqI)

### Working with branches on GitHub

While working with branches works a bit differently on GitHub (because of its user interface) the concept remains the same: you always want to have a master branch that holds all your stable, working code. Any other branches will contain software features that eventually will be merged into master.

Go through the following project to learn how to work with branches on GitHub:

-   [GitHub 'Hello World' Project](https://guides.github.com/activities/hello-world/)

### Making pull requests

A **pull request** is a term GitHub uses to refer to merge requests; a request to incorporate code changes made by a developer (whether it's you or another developer) into the code stored in a branch of a repository.

These changes are proposed in a branch, and the pull request usually is made to merge into the `master` branch. Code changes through pull requests never merge directly into the target branch, unless the administrator uses their rights to do so. In normal circumstances, there has to be at least one other person reviewing the proposal before it is approved to be merged.

-   [GitHub Pull Request in 100 Seconds](https://www.youtube.com/watch?v=8lGpZkjnkt4)

Pull requests only happen in remote repositories. This can happen in 2 ways:
(1) From one branch to another **within the same repository**. For more information on this, read:

-   [Creating a pull request](https://help.github.com/en/articles/creating-a-pull-request)

(2) From one branch to another branch **from a forked repository into the original repository**. A `fork` is a copy of a repository, that is stored in your personal GitHub account. Forks let you make changes to a project without affecting the original repository. You can fetch updates from or submit changes to the original repository with pull requests.

While both are important to know, it's useful to study the second way because that's how you'll submit your homework:

-   [About forks](https://help.github.com/en/articles/about-forks)
-   [GitHub Homework flow](https://www.youtube.com/watch?v=2qJPAVTiKPE)

## 2. CSS Frameworks

In order to explain CSS frameworks, we first must understand what a framework is. Let's explain using an analogy.

Let's suppose you want to make a ginger tea on daily basis. You do this with several ingredients: water, pieces of ginger and sugar. Doing so you will find it is really difficult to put all ingredients in the right proportions all the time.

One morning you come up with idea of mixing all the ingredients in one jar in the correct proportion, such that every spoon will serve the right amount to make the tea.

This jar is your framework. By using it you don't have to think about the ingredients, nor the proportions. Only about how much you want to use to fit your needs.

> Tip: the concept of a framework will come back many times, as we don't want to reinvent the wheel every time we create a new application. The point of any piece of software is to write it as simply as possible, and a framework really helps with that. So keep it in mind!

### Why use a CSS framework?

A CSS framework allows you to style your HTML reliably, by making use of pre-defined CSS rules. This way you don't have to think about what custom CSS you have to write to make something the way you want. This is useful mainly to **speed up development**.

There are other reasons as well which you can learn about in the following article:

-   [What are the benefits of using a CSS framework](https://css-tricks.com/what-are-the-benefits-of-using-a-css-framework/)

### Most popular frameworks

There are a lot of different CSS frameworks out, each with their pros and cons. In the following video you'll learn about several of the top ones used and what problems exactly they're trying to solve:

-   [CSS frameworks](https://www.youtube.com/watch?v=AMDx0IIgiK4)

### CSS Framework vs. custom CSS

As a general rule, you always want to be able to write custom CSS when needed. And if you're using a framework, you need to at least know why it works the way it does. This means that you look into the class definition within the stylesheet (you can use the browser inspector for this, more on that later).

However, writing custom CSS is in practice not always possible. This could be because of project deadlines, lack of skill or wanting to do rapid prototyping (a technique to quickly build a working version in order to test if it works). This is when we use frameworks to help us out.

Keep in mind that a framework should be there only to assist, not compensate or define your application. Research the following resources to learn about the pros and cons of CSS frameworks:

-   [Are CSS Frameworks Bad?](https://www.youtube.com/watch?v=VlY5CfkL760)
-   [Discussing the Pros and Cons of Using a CSS Framework](https://speckyboy.com/discussing-the-pros-and-cons-of-using-a-css-framework/)

## 3. Working with the browser

### What is a web browser?

You probably use it daily. Let's take a closer look at what it actually is.

A `web browser` is software that allows you to view webpages, either retrieved from the internet or loaded from your computer. The primary function of a web browser is to render HTML files, transforming all the code (HTML, CSS and JavaScript) as well as the references (images, videos, etc.) to display a page correctly.

For further study, delve into the following:

-   [What is a browser?](https://www.youtube.com/watch?v=TcbhVv9ty44)
-   [How web browsers work](https://www.youtube.com/watch?v=WjDrMKZWCt0)
-   [About your web browser](http://www.allaboutcookies.org/browsers/)

### Choosing the right browser

As a web developer you will write code that will display in different browsers. As such it is important that you get familiar with most major browsers in use today. These are:

-   [Internet Explorer](https://support.microsoft.com/en-us/help/17621/internet-explorer-downloads)
-   [Google Chrome](https://www.google.com/chrome/)
-   [Safari](https://support.apple.com/downloads/safari)
-   [Mozilla Firefox](https://www.mozilla.org/en-GB/firefox/new/)
-   [Microsoft Edge](https://www.microsoft.com/en-us/windows/microsoft-edge) (Not available for Mac/Linux yet)
-   [Opera](https://www.opera.com/download)

In your HackYourFuture journey you'll mainly be using **Google Chrome** when developing, as is has great developer tools that allow us to develop web applications in an easier and clearer way.

### How to use the browser inspector

The inspector is a part of web browsers developers can use to take a closer look at the composition of the HTML elements. This makes it easier to write HTML and CSS code that works.

Watch the following videos and follow along:

-   [Using browser inspector tools](https://www.youtube.com/watch?v=WJIqIDm7CoA)
-   [Google Chrome Developer Tools Crash Course](https://www.youtube.com/watch?v=x4q86IjJFag)

### Useful browser extensions

As web developers we'll be dealing with the browser all the time. Why not upgrade our browser so it can make our programming life easier?

A `browser extension` is a piece of software someone has written to increase the capability of the web browser. For example, if you hate receiving advertisements you probably use something like [Adblock](https://chrome.google.com/webstore/detail/adblock/gighmmpiobklfepjocnamgkkbiglidom) to block all the unwanted ads you might find in your webpages (if not, download it as soon as possible!).

The following is a list of extensions that have proven to be useful during web development. This list only applies for Google Chrome, so if you don't have it [install it](https://www.google.com/chrome/).

Extensions:

-   Modify the technologies underlying each website, in real time, using [Web developer](https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm/related?hl=en-US)
-   Expose what technologies a website is using with [WhatRuns](https://chrome.google.com/webstore/detail/whatruns/cmkdbmfndkfgebldhnkbfhlneefdaaip?hl=en-US)
-   If you ever wanted to know the exact color of any element in a page, you can now do so with [ColorZilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?hl=en-US)
-   When developing you'll be using dummy text to populate your elements. Enter [Loren Ipsum Generator](https://chrome.google.com/webstore/detail/lorem-ipsum-generator-def/mcdcbjjoakogbcopinefncmkcamnfkdb?hl=en%20)

There are many more of these extensions and we encourage you to explore. See what fits your needs!

## Finished?

Are you finished with going through the materials? Nice job!!! If you feel ready to get practical, click [here](./MAKEME.md).
