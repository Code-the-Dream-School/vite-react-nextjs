---
tags: react
week: 0
---

# Course Overview

parent::[[React-Vite & Next JS Curriculum]]
related::[[Curriculum Outline]]

## Overview

This course is an introduction to React and will provide you exposure to code from 4 React applications: 2 plain React and 2 using NextJS. Along the way, we will:

- learn core React concepts
- figure out what React is doing for us behind the scenes
- explore troubleshooting tools ~~if~~ when things go wrong

As lessons build upon themselves and you work on your projects you will be able to watch them become fully-featured web applications.

In **Part 1**, you will be introduced to [Vite](https://vitejs.dev/), a popular build tool that can get us started with a React application with minimal setup. Of historic interest, Create React App — "CRA" for short, was the most popular approach to scaffold a React project. In 2023 it is no longer being recommended by the core React development team and has fallen out of favor.

In **Part 2**, we expand our knowledge of the React ecosystem by adopting [NextJS](https://nextjs.org/). NextJS is a fully-fledged framework which, at its core, is a React application but with some [nice additional functionality](https://nextjs.org/docs#main-features). While it is a "full-stack framework" we will mostly be focusing on the React front-end. We will also take advantage of some server-side rendering technologies built into NextJS but we will not be will not be building an API or a database. We'll save that for another day ;-)

## Basic Structure of Each Lesson

### Introduction

#### Topics Covered

Each topic will be bulleted out

#### Lesson Outcome

This section will explain what a student should understand after reading that week's lesson and coding out.

### Discussion

This section will explore each topic in depth. We'll cover the "how"s, "why"s, and I'll provide resources for further reading. Where possible, code examples will come from a todo list application that will progress with the lessons.

### Project Instructions

The beginning of this section will tell you what your app will be capable of after completing the week's instructions.

The week's project instructions will be broken out into easily to read steps that will instruct you on what to add to the application. We will provide relevant function/variable/component names and enough details to be able to build out that week's code. In the early lessons, instructions will be very specific. As the weeks progress, the instructions will become more higher-level, allowing you to figure out how to implement certain functionality based on previous lessons.

### References and Further Reading

This will have a list of references, useful articles, videos for further learning.

## Course Part 1: Introduction to React

The examples used throughout the lessons will focus on building out a full [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) todo list that uses an [Airtable](https://airtable.com/) [base](https://support.airtable.com/docs/airtable-bases-overview) as an [API](https://en.wikipedia.org/wiki/Web_API). The codebase can be found in [this repo](https://github.com/royemosby/vite-react-todo) . Each branch in the repo represents the code progress by the end of the named week's lesson. You are encouraged to code the todo application on your own for additional practice but it will not be turned in. Please make sure that you use a separate repo for this and do not include it in the repo you will be submitting.

The app that you will be building for review will be a local news and weather forecast reader. I think we'll call it "CTD-React-News". We will develop it by following the "Project Instructions" section below each lesson discussion.

> [!note]
> See the [[General Instructions]] page for information on how to maintain your repo and submit each week's lesson.

Over 8 lessons (and 2 review weeks), we will cover:

| Week# | Dates                       | Lesson                            |
|:-----:|-----------------------------|:-----------------------------------|
|   1   | {{dd-mm-yyyy}} - {{dd-mm-yyyy}} | React Project Setup               |
|   2   |                             | Introduction to React             |
|   3   |                             | Working with Components           |
|   4   |                             | Controlled and Uncontrolled Forms |
|   5   |                             | REVIEW                            |
|   6   |                             | useEffect and Working with APIs   |
|   7   |                             | React-Router                      |
|   8   |                             | CSS and Images                    |
|   9   |                             | Refactoring Components            |
| 10    |                             | REVIEW                            |

## Course Part 2: NextJS

Like part 1, you will get to see the evolution of 2 apps. This time, the code examples will be from a team blog. You will be building out a portfolio site where you will be able to showcase some of your coding projects that you have done. It will be this portfolio site you will be submitting but feel free to code along with the team blog too.

Over 7 lessons (and 1 review week), we will cover:

| Week# | Dates                       | Lesson                                                     |
|:-----:|-----------------------------|:------------------------------------------------------------|
|   11  | {{dd-mm-yyyy - dd-mm-yyyy}} | Introduction to NextJS                                     |
|   12  |                             | Setting up server side rendering and deploying an app      |
|   13  |                             | Routing, linking, client-side navigation                   |
|   14  |                             | Dynamic routing, API routing                               |
|   15  |                             | REVIEW                                                     |
|   16  |                             | Styling using css modules, styled components, TailwindsCSS |
|   17  |                             | Authentication, authorization                              |
|   18  |                             | PROJECT WEEK                                               |

After 6 weeks of NextJS lessons and a review week, you'll be given another week to extend and embellish on your portfolio application. We'll provide some ideas that can help get your creative juices flowing.
