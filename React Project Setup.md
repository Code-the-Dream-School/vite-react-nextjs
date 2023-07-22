---
tags: react 
week: 1
---

# React Project Setup

## Introduction

### Topics Covered

- development requirements
- git repo and development workflow
- Vite react template installation
- helper tools installation (Prettier, ESLint)
- project structure

### Lessons Outcome

After completing this section, you will gain an understanding on:

- how to install the project for each week's lesson
- the repo's folder and document structure
- how to navigate between directories in the console

At the conclusion of the project instructions below, your project should:

- contain all the directories needed to complete part 1 of this course
- be version controlled using git
- have your first installed React application

## Project Instructions

### Development Requirements

- Use a browser that meets these requirements:
  - Chrome >=87
  - Firefox >=78
  - Safari >=14
  - Edge >=88
- Code Editor (VS Code preferred)
- Node.js version 14.18.x or any version equal or greater to 16.0.0
  - Go with the [current LTS](https://nodejs.org/en/download) (long-term support) release if you do not have it installed.

### Git Repo and Development Workflow (Part 1: React Core)

The Part 1: React Core instruction requires the project to be in a precise state at the start of each lesson. To ensure this happens each lesson will have its own folder. That folder will contain a partially completed application coded to a point that will be ready to be worked on.

This may feel odd starting work on someone else's code at first but this will allow us to collectively build on our understanding of React in a consistent way. As an added bonus, this will also give us extra opportunity to practice the terminal and git!

#### 0. Create a Copy of the Part 1 Project Repo

 *This step is only done once.*

> *Further Reading: Refer to [CTD resources](https://learn.codethedream.org/resources/student-resources/) or [GitHub quick-start](https://docs.github.com/en/get-started/quickstart/hello-world) for more information on working with GitHub and git.*

1. Fork the repo [ctd-react-news](https://github.com/Code-the-Dream-School/ctd-react-news) into your personal GitHub account.
 1. Select the fork button which is above the About section.
 2. Keep all the settings the same on the next screen and select Create fork button.
2. Clone the new repo into your local development environment.
 1. In the newly forked repo, select the green Code button beside the About section.
 2. From the dropdown, select HTTPS, SSH, or GitHub CLI - whichever way you prefer to clone your repo. Read more [here](https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories) about these options.
 3. Copy the text field containing the remote git url.
 4. Open the terminal in your local development environment then navigate to where you want your project to reside.
 5. Clone the repo locally by typing `git clone` and then pasting that remote git url. Then hit enter.
 6. `cd`

#### 1. Complete the "Before Each Lesson" Tasks (lesson weeks 1-9)

*This step not needed for lesson 0 as there is no work to merge yet.*

-1. In GitHub, merge previous week's approved work.

```bash
# in ctd-react-news

git checkout main
git pull
```

2. Create new branch for lesson <student-name/lesson-name>
 - For example `roy-mosby/react-router`

#### 2. Install React (lesson weeks 0-9)

1. Navigate to current week's directory `cd week-{n}` where `n` is the week number.
2. Use the command `npm -i` to install the React project
 - don't use `npm create vite@latest my-vue-app -- --template react`
 - CTD's curriculum targets specific versions of the libraries we will use in this class.

#### 4. Start Vite

- npm run start (or npm start)
- get coding!

#### 5. Submit Work

- make sure it works!
- perform code cleanup
- navigate to the repo root
- commit, push
- pull request
  - against own! not CTD
  - take note of PR link
- Fill out weekly assignment form & include link
