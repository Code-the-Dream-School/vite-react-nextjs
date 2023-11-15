---
tags:
  - react
week: 0
dateCreated: 2023-07-08 10_26_39
dateModified: 2023-11-11 10_07_23
status: draft
---

# General Instructions

## Assignment Repo Setup

> *⚠️ Avoid any directories that use cloud syncing services with such as DropBox, Google Drive, or iCloud.*

- Installation instructions for the React project is covered [[React Project Setup]]
- Installation instructions for the Next.js project is covered in [[Introduction to NextJS]]

## Before Each Lesson

> *⚠️ Be sure that you already have your previous lesson's PR (pull request) reviewed, approved, and merged before making additional changes to the codebase. Having PRs open that are reliant on other PR's code changes can get very complicated and can result in [merge conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts) .*

1. On GitHub, merge your approved PR on from the previous lesson into `main`. **[View tutorial on how to merge](https://github.com/Code-the-Dream-School/common-instructions/blob/main/common/how-to-merge.md)**
2. In your local development environment, checkout your `main` branch and pull changes down from Github. This will integrate the latest code from the merged PR.

```bash
git checkout main
git pull
```

1. If, in the previous lesson, you installed a new NPM package, run `npm install` again.
2. Create a new branch for the lesson.

```bash
git checkout -b <lesson-name>
```

*Note: Replace `<branch>` with your new branch name (ex. `lesson-1-1` or `working_with_components`)*

1. Open the project directory in your code editor and begin the lesson.

## After Each Lesson

1. Ensure your React or NextJS application works as expected in browser before submission.
2. Perform code cleanup:
	- remove any
		- private comments
		- commented-out code
		- `console.log()` or `debugger` statements
	- clean up formatting (indentation, spaces around brackets, etc.)
3. Check the status of your local repository to double-check the changes you made:

```bash
git status
```

1. Stage the file(s) that you edited:

```bash
# use a period to stage all changes
# or add files separately using their filename
git add .
```

1. Check the status again and notice that the changes from before are now staged:

```bash
git status
```

1. Create a commit for the changes you made and add a message describing the changes you made:

*Note: Replace `<message>` with your message*

```bash
git commit -m "<message>"
```

1. Push your commit to the remote repository (visible in GitHub):

```bash
git push
```

1. Check the log to make sure your commit has been published:

```
git log --oneline
```

1. Go to the repo in GitHub and create a pull request.
2. Copy the link of the pull request in the browser's URL bar and keep handy for assignment submission. The structure of the link should resemble:

```text
                  | username     | repo name         | contains "pull" in URL
https://github.com/starstudent123/ctd-react-albatross/pull/18
```

*Note: PRs increment so the number does not represent the lesson number. The example above is the 18th PR opened on that repo.*

[Visual instructions to create PR](https://github.com/Code-the-Dream-School/common-instructions/blob/main/common/how-to-pull-request-sq2-link.md)

## Common Mistakes

### PR Against CTD Repo

A common occurrence is that students open PRs on original class repo:

```text
INCORRECT: wrong repo

                  |should not contain CTD GitHub org name
https://github.com/Code-the-Dream-School/ctd-react-albatross/pull/51
```

In this case, close out the PR then make the PR on your personal repo. It's courteous to clean up after yourself.

### Submitting Wrong Link

Another common mistake is submitting links that are not to a PR:

```text
# INCORRECT: wrong types of links; not PRs

https://github.com/starstudent123/ctd-react-albatross 
https://github.com/starstudent123/ctd-react-albatross/tree/main/src
https://github.com/starstudent123/ctd-react-albatross/blob/main/src/App.js

# CORRECT:
https://github.com/starstudent123/ctd-react-albatross/pull/18

```

In this case, create a new submission for the same lesson then let your reviewer know over Slack that you had to re-submit. There's no need to re-answer the mindset prompt or other exercise questions in the submission form.
