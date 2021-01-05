# Lesson Plan Week 3

## Agenda

The purpose of this class is to introduce to the student:

-   What is GIT branching?
-   Remote vs. local branches
-   What's a pull request?

-   What is a framework?
-   Popular CSS frameworks
-   Framework vs custom CSS

## Core Concepts

FIRST HALF (12.00 - 13.30)

## 1. GIT branching

### Explanation

-   A branch is an experiment, a possible way your project can evolve.
-   Local branch can be created with `git branch <name>` command. Remote branch must be set using `--set-upstream` option while pushing
-   Pull request is a `diff` between two commit points. It can be merged when we want to suggest changes to a Github repository to which we don't have write access.

### Example

Create a repository and initialize GIT. Show the use of `git branch`, `git checkout -b`

### Exercise

A fun exercise by [Arco](https://github.com/ArcoMul) to practise creating pull requests: [Cat pull request exercise](https://github.com/ArcoMul/netlify-cats)

Instruction on how to set things up at Netlify: https://github.com/ArcoMul/netlify-cats/blob/main/SETUP.md

### Essence


SECOND HALF (14.00 - 16.00)

## 2. CSS framework

### Explanation

-   A software framework is prewritten code that provides generic functionality and a structure to build applications with
-   Analogy of pot of ingredients (see [example](./README.md) at section 2)
-   CSS frameworks allow for faster development

-   Pros and cons of framework

    -   PRO: Speeds up your development
    -   PRO: Enables cross-browser functionality
    -   PRO: Are usually maintained by a community of developers
    -   CON: It takes time to learn a framework
    -   CON: Lack of understanding the underlying CSS

-   Pros and cons of custom CSS
    -   PRO: Satisfies your specific needs
    -   PRO: Total control over the direction of CSS
    -   PRO: Creates a unique look
    -   CON: Have to maintain own code
    -   CON: You have to make sure it works cross-browser

### Example

Show various CSS frameworks: [MaterializeCSS](https://materializecss.com/), [Bootstrap](https://getbootstrap.com/), [Foundation](https://foundation.zurb.com/)

### Exercise

Give students an exercise to rebuild a button and navbar with custom CSS. Then let them do the same with any of the CSS frameworks you feel most comfortable with!

### Essence

A CSS framework is used to speed up development: it's prewritten code that provides the developer with basic structure and styling in order to create a presentable user interface.
