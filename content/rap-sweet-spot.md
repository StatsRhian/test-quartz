---
title: Finding the RAP sweet spot
---

Rewrite / delete?

When starting a new project, I like to think about reproducibility and reusability. If I’m building a model, would it work on other datasets? Could it be adapted for different pathways or different NHS regions?

I think one of the hardest parts of a RAP-first project is deciding how far to aim for generalisability.

In some contexts, generalisability might not matter much at all. If you work in a regulated industry like clinical trials, the priority is often reproducibility. You want to lock the analysis down and make it as watertight as possible. Being able to perfectly recreate results on the same dataset, across multiple environments, is the key goal.

In other projects, adaptability is where the value comes from. A workforce model might become much more useful if it can be reused across different regions, pathways, or assumptions.

For me, this is the difficult design aspect of RAP. It comes down to scoping and defining the contract with your users. What inputs should they be allowed to change? What assumptions should stay fixed? What kinds of models or datasets should the tool be able to handle?

I like to start with a big piece of paper and write down all the possible things the model could do. Think big first. Build the most flexible and reusable version imaginable. Then get realistic.

What I’ve found is that the process of coding changes how I think about the design. I’m never going to get the structure exactly right first time. Building a small prototype teaches me far more about the shape of the model, the code, and the user needs than I could ever work out just by thinking about it in advance.

I think of this as finding the RAP sweet spot: enough generalisability to make the project reusable and valuable, without over-engineering it into an inflexible or overly complicated tool.

  