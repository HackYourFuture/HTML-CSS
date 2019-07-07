# Lesson Plan Week 3

## Agenda

The purpose of this class is to introduce to the student

- What is GIT branching?
- Remote vs. local branches
- What's a pull request?

* What is a framework?
* Popular CSS frameworks
* Framework vs custom CSS

## Core Concepts

FIRST HALF (12.00 - 13.30)

1. **What is GIT branching?**

- A branch is an experiment, a possible way your project can evolve.
- Local branch can be created with `git branch <name>` command. Remote branch must be set using `--set-upstream` option while pushing
- Pull request is a `diff` between two commit points. It can be merged when we want to suggest changes to a Github repository to which we don't have write access.

_Create a repository and initialize GIT. Show the use of `git branch`, `git checkout -b`_

SECOND HALF (14.00 - 16.00)

2. **What is a CSS framework?**

- A software framework is prewritten code that provides generic functionality and a structure to build applications with
- Analogy of pot of ingredients (see [example](./README.md) at section 2)
- CSS frameworks allow for faster development

_Show various CSS frameworks: [MaterializeCSS](https://materializecss.com/), [Bootstrap](https://getbootstrap.com/), [Foundation](https://foundation.zurb.com/)_

- Pros and cons of framework
  - PRO: Speeds up your development
  - PRO: Enables cross-browser functionality
  - PRO: Are usually maintained by a community of developers
  - CON: It takes time to learn a framework
  - CON: Lack of understanding the underlying CSS

_Give students an exercise to rebuild a button and navbar with custom CSS_

_Make a couple of html components with a CSS framework you're comfortable with (preferably MaterializeCSS): a button, navbar, tabs and accordion_

- Pros and cons of custom CSS
  - PRO: Satisfies your specific needs
  - PRO: Total control over the direction of CSS
  - PRO: Creates a unique look
  - CON: Have to maintain own code
  - CON: You have to make sure it works cross-browser

_Start discussion when it's appropriate to use framework or custom_
