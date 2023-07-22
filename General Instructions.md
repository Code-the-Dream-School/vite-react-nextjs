---
tags: react 
week: 0
---

# General Instructions

## Assignment Repo Setup

- Installation instructions for the first React project is covered [[React Project Setup]]
- Installation instructions for the Next.js project is covered in [[Introduction to NextJS]]

*⚠️ Avoid any directories that use cloud syncing services with such as DropBox, Google Drive, or iCloud.*

- [ ] CURRICULUM TODO: replace wiki links with relative links

## Before each Lesson

*⚠️  Be sure that you already have your previous lesson's PR reviewed and approved. Working ahead on the project is allowed but be aware that it may take additional time to get feedback from your assigned reviewer.*

1. On GitHub, merge your approved pull request on from the previous lesson into `main`. **[View tutorial on how to merge](https://github.com/Code-the-Dream-School/common-instructions/blob/main/common/how-to-merge.md)**
2. In your local development environment, checkout your main branch and pull changes. This will download the latest code from the merged PR.

```bash
git checkout main
git pull
```

3. If, in the previous lesson, you installed a new NPM package, ru
4. Create a new branch for the lesson.

```bash
git checkout -b <lesson-name>
```

*Note: Replace `<branch>` with your new branch name (ex. `lesson-1-1` or `working_with_components`)*

4. Open the project directory in your code editor and begin the lesson.

## After each Lesson

1. Make sure application works in browser before submission.
2. Perform code cleanup:
 - remove any private comments, commented-out code
 - ensure formatting (indentation, spaces around brackets, etc.) is consistent

3. Check the status of your local repository to double-check the changes you made:

```bash
git status
```

4. Stage the file(s) that you edited:

```bash
git add .
```

5. Check the status again and notice that the changes from before are now staged:

```bash
git status
```

6. Create a commit for the changes you made and add a message describing the changes you made:

*Note: Replace `<message>` with your message*

```bash
git commit -m "<message>"
```

7. Push your commit to the remote repository (visible in GitHub):

```bash
git push
```

8. Check the log to make sure your commit has been published:

```
git log --oneline
```

9. Go to the repo in GitHub and create a pull request.

10. Copy the link of the pull request in the browser's URL bar and keep handy for assignment submission. The structure of the link should resemble:

```text
                  |username      |repo name          |contains "pull" in URL
https://github.com/starstudent123/ctd-react-albatross/pull/18
```

*Note: PRs increment so the number does not represent the lesson number. The example above is the 18th PR opened on that repo.*

[Visual instructions to create PR](https://github.com/Code-the-Dream-School/common-instructions/blob/main/common/how-to-pull-request-sq2-link.md)

## Common Mistakes

A common occurrence is that students open PRs on original class repo:

```text
INCORRECT: wrong repo

                  |should not contain CTD GitHub org name
https://github.com/Code-the-Dream-School/ctd-react-albatross/pull/51
```

Another common mistake is submitting links that are not to a PR:

```text
INCORRECT: wrong types of links; not PRs

https://github.com/starstudent123/ctd-react-albatross 
https://github.com/starstudent123/ctd-react-albatross/tree/main/src
https://github.com/starstudent123/ctd-react-albatross/blob/main/src/App.js

```
