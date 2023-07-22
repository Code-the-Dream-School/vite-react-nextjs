# Lesson Submission Workflow Idea (Needs refinement and finalization)

## What it is

### working environment

- student forks class repo or creates new repo (full control)
- 1 repo, 13 lessons + final project
  - lessons in class repo
- Airtable submission form (combines fork submission and mindset responses)

### submission workflow

- student creates working branch for lesson
- student creates PR on their repo, noting the PR's link
- student fills out submission webform + includes link
- reviewer reviews assignment + PR/ Provides praise + improvement
- reviewer fills out webform with optional reviewer notes

### Advantages

- lesson and mindset submitted together
- reviewers have dashboard overview of assignments

### Shortcomings

- some students leaving mindset responses blank
  - should mentors not review and students resubmit?
  - should student be encourage to fill out in their native language?
- instructions on feedback from reviewers ambiguous
  - where put?
  - how does student know reviewer complete if they don't have commentary on PR?
  - does mentor provide any feedback on mindset response?
- students can merge PRs that are still under review or need corrections
- person with Airtable permissions have to make corrections to submissions
  - changed links
  - delete old submissions if student submits new
- student loses access to mindset responses (unless they proactively keep them in another tool)

## Improved workflow

### working environment

- 13 class repos owned by CTD, 1 owned by student for final project
  - lessons in readme.md
  - reviewers subscribed to repo activity (or check daily)
  - if possible would include tests
    - has test pipeline to run tests (blocks submissions that fail tests automatically)
- Airtable submission form for mindset responses. (lesson PR links not included)

### submission workflow

- student pulls down repo
- student creates local working branch ("lesson1.1/roy_mosby")
- student does work then publishes branch
- student submits lesson by creating PR against main
- reviewer initiates review in PR (regardless of corrections)
  - provides comments, requests revisions, approves PR (no one ever merges)
- if PR needs revisions, student can continue to work on local working branch and push up changes
  - (should student ping reviewer on Slack?)
- student submits mindset response as separate weekly assignment
- final project done in student's own repo

### advantages

- student doesn't accidentally submit work from Road to React book in beginning
- workflow similar found to working environment of Jr. Dev
  - they work from org repo, not personal
  - they don't have merge rights on main
- reviewers have explicit channel of interaction during review
- simplifies Airtable submission maintenance
- no more wiki that is difficult to replicate/maintain between classes

### Shortcomings

- mentors don't have centralized dashboard to monitor lesson submissions
- student have 2 separate submissions weekly (but we can do one on review weeks now)
- more repo maintenance by CTD staff (14 repos vs 1, giving access, assigning permissions)
- test pipeline requires additional maintenance from CTD staff (if using)
