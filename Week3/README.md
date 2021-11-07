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

## 0. Video Lectures

Your teacher Arco has made video lectures for this week's material. You can find them here: [Videos 12 - 15](https://www.youtube.com/playlist?list=PLVYDhqbgYpYXbAL_Hps1Y--THRmaTFipj)

<a href="https://www.youtube.com/playlist?list=PLVYDhqbgYpYXbAL_Hps1Y--THRmaTFipj" target="_blank"><img src="../assets/week1-arco.png" width="600" height="400" alt="HYF Video" /></a>

## 1. GIT branching

### Local branches

`Branches` are a core feature of GIT. A branch allows you to work on a different "version" of your project. Take a look at the following image:

![branches](assets/branches.png)

Whenever you make a branch, you're creating an exact copy of your workspace that you can work with. Try it out:

```md
Go into a folder and initialize GIT to create a local repository. Then create a branch. In this new branch, create some basic files. **stage** and **commit** the changes you've made. Now, switch back to the original branch (**main**). What do you see? Nothing! That's because in that branch you didn't make those changes. If you switch back to the other branch you will see the files you've created again. Magic!
```

You can see a branch as an experiment, a possible way your project can evolve. Usually, each branch (except the `main` branch) contains code for what is called a new `feature`: a piece of functionality that you want to add to your software. Let's take Facebook as a simple example: After creating an account (which is a feature itself) you can do multiple things. Each "thing" is a feature: having a news feed, being able to send friend requests or liking posts.

Working with branches is especially important when working with other developers. This only applies when working with a **remote** repository, which we'll talk about in the next section.

When working with different branches it is useful to have one single branch that contains all the working and finished code: the `main` branch (we call it main out of convention, but in actuality you can name it whatever you want). Whenever you're working on a project that has already been put on the internet, it is the code from the main branch that is online.

However, usually there's a separate branch that contains all the development code. Of course, this is called the `development` branch. This branch is an almost exact copy of main, but contains features that have not been tested yet.

After finishing a feature, it is time to merge the branch into the main branch. This is usually either the `main` or `development` branch.

Once the new version of the software has been tested and approved, the cycle repeats!

Go through the following resources to learn more:

- [Git Tutorial: Branches](https://www.youtube.com/watch?v=sgzkY5vFKQQ)
- [Introduction to GIT - Branching and Merging](https://www.youtube.com/watch?v=FyAAIHHClqI)

### Working with branches on GitHub

While working with branches works a bit differently on GitHub (because of its user interface) the concept remains the same: you always want to have a main branch that holds all your stable, working code. Any other branches will contain software features that eventually will be merged into main.

Go through the following project to learn how to work with branches on GitHub:

- [GitHub 'Hello World' Project](https://guides.github.com/activities/hello-world/)

### Making pull requests

A **pull request** is a term GitHub uses to refer to a request to incorporate code changes from one branch made by a developer (whether it's you or another developer) into the code stored in a different branch of a repository.

> Sometimes you'll hear developers speak of "merge requests". This is just another name for the same thing: pulling changes from another branch or fork into your branch and merging the changes with your existing code. Software development platforms like GitLab (an alternative to GitHub) use this the term "merge request" instead of "pull request".

These changes are made in one branch, and the pull request usually is made to merge into the `main` branch. However, this doesn't happen directly: in normal circumstances, there has to be at least one other person reviewing the proposal before it is approved to be merged. The reason why is simple: it's very easy to merge code that might be buggy or conflicts with what's already there.

- [GitHub Pull Request in 100 Seconds](https://www.youtube.com/watch?v=8lGpZkjnkt4)

Pull requests only happen in remote repositories. This can happen in 2 ways:
(1) From one branch to another **within the same repository**. For more information on this, read:

- [Creating a pull request](https://help.github.com/en/articles/creating-a-pull-request)

(2) From one branch to another branch **from a forked repository into the original repository**. A `fork` is a copy of a repository, that is stored in your personal GitHub account. Forks let you make changes to a project without affecting the original repository. You can fetch updates from or submit changes to the original repository with pull requests.

While both are important to know about, it's useful to study the second way a little more in-depth because that's how you'll submit your homework:

- [About forks](https://help.github.com/en/articles/about-forks)
- [GitHub Homework flow](https://www.youtube.com/watch?v=CpYARPYGQU8)

## 2. CSS Frameworks

In order to explain CSS frameworks, we first must understand what a framework is. Let's illustrate this using an analogy.

Let's suppose you want to make a ginger tea on daily basis. You do this with several ingredients: water, pieces of ginger and sugar. Doing so you will find it is really difficult to put all ingredients in the right proportions, to get the right flavor, all the time.

One morning you come up with idea of mixing all the ingredients in one jar in the correct proportion, such that every spoon will serve the right amount to make the tea.

This jar is your framework. By using it you don't have to think about the ingredients, nor the proportions. Only about how much you want to use to fit your needs.

Or here's another analogy:

Imagine you want to make star-shaped pancakes. That's pretty hard to do by itself, so you choose to use a mold. The mold helps you "structure" the pancake. All you need to add is the right content, which is the pancake batter.

This mold is your framework. By using it, you need only think about the actual content you want to use. The rest will be taken care of for you.

> Tip: The concept of a framework will come back many times, as we don't want to reinvent the wheel every time we create a new application. The point of any piece of software is to write it as simply as possible, and a framework really helps with that. So keep it in mind!

### Why use a CSS framework?

A CSS framework allows you to style your HTML reliably, by making use of pre-defined CSS rules. This way you don't have to think about what custom CSS you have to write to make something the way you want. This is useful mainly to **speed up development**.

There are other reasons as well which you can learn about in the following article:

- [What are the benefits of using a CSS framework](https://css-tricks.com/what-are-the-benefits-of-using-a-css-framework/)

It does come with a drawback, however, and that is that it forces you into a specific design and adjusting things to your needs will be more difficult.

### Most popular frameworks

There are a lot of different CSS frameworks out, each with their pros and cons. In the following video you'll learn about several of the top ones used and what problems exactly they're trying to solve:

- [CSS frameworks](https://www.youtube.com/watch?v=AMDx0IIgiK4)

### CSS Framework vs. custom CSS

As a general rule, you always want to be able to write custom CSS when needed. And if you're using a framework, you need to at least know why it works the way it does. This means that you look at the **documentation** of that particular CSS framework first. Alternatively, you could also look into the class definition within the stylesheet (you can use the browser inspector for this, more on that later).

However, writing custom CSS is in practice not always possible. This could be because of project deadlines, lack of skill or wanting to do rapid prototyping (a technique to quickly build a working version in order to test if it works). This is when we use frameworks to help us out.

Keep in mind that a framework should be there only to assist, not compensate or define your application. Research the following resources to learn about the pros and cons of CSS frameworks:

- [Are CSS Frameworks Bad?](https://www.youtube.com/watch?v=VlY5CfkL760)
- [Discussing the Pros and Cons of Using a CSS Framework](https://speckyboy.com/discussing-the-pros-and-cons-of-using-a-css-framework/)

## Finished?

Are you finished with going through the materials? Nice job!!! If you feel ready to get practical, click [here](./MAKEME.md).
