GitHub rulesets
---
title: GitHub rulesets
tags: 
  - git
---

## What

Rulesets help you to control how people can interact with branches and tags in a repository. 
A ruleset is a named list of rules that applies to a repository. You can have up to 75 rulesets per repository.

## Who can use them

- Public repos for GitHub free, public and private repositories with paid plans
- Paid feature: you can set up organisation level rulesets

## What can you control

- Who can push to a branch
- Require approvals (how many, who can review)
- Commit style (paid only)

## How are they different from branch protection?

- Can be toggled as active / inactive without being deleted
- Can apply at the same time
- Visible to anyone with read access, meaning as a developer you can understand what the issue is
- You can enforce conventional commits. (paid only) 
    - Can I enforce gitmoji commits on my repo?


## How do I get started?

GitHub has a couple of pre-made rulesets: https://github.com/github/ruleset-recipes

You can also use the GUI to make some rulesets, and then export them and share them.

- You can protect main - here's how

- You can skip the approval - handy for bots like all-contributors

- You can export / import them