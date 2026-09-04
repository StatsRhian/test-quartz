--- 
title: Use the force, wisely
tags:
  - git
---

I used to be scared to force push to a repo. Once I got more comfortable with @sec-gitrebase I started doing it more often. However, I never type `git push --force` instead I always use `git push --force-with-lease`.

The latter will not overwrite any work on the remote branch if more commits have been added. This ensures you do not overwrite someone elses work by force pushing - much safer.