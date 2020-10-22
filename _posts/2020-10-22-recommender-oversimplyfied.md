---
title: Recommender Systems Oversimplified
tags: [Recommender Systems, Infographic]
style: fill
color: info
description: These four “clean code” tips will dramatically improve your engineering team’s productivity
---

A few years ago at VideoBlocks we had a major code quality problem: “spaghetti” logic in most files, tons of duplication, no tests and more. Writing new features and even minor bug fixes required a couple of Tums at best and entire bottles of Pepto-Bismol and Scotch far too often. Our WTFs per minute were sky-high.

{% include elements/figure.html image="https://media-exp1.licdn.com/dms/image/C4E22AQFvcNlQzGtclA/feedshare-shrink_1280/0?e=1606348800&v=beta&t=iVxSrolLobHDFCWzG3DheLYtWkGFf-ETlQ2pmq1ofAI" caption="Image description" %}

Today, the overall quality of our codebases are significantly better thanks in large part to a deliberate effort to improve code quality. A couple ago when we identified the problem, we read Robert Martin’s Clean Code as a team and did our best to implement his recommendations and even introduced “clean code” as a core cultural tenant for the engineering team. I highly recommend doing both as you start scaling. Implementing “clean code” practices appropriately will double productivity in the long run (at a bare minimum) and significantly improve moral on the engineering team. Who wants to be in the room on the right given the choice?

Out of all the ideas we implemented from Clean Code and other sources, five provided at least 80% of the gains in productivity and team happiness.

Let’s walk through each one in detail so you can understand and start applying them in your day-to-day life on an engineering team.

---

In summary, make sure to remember and apply these four “clean code” principles to dramatically improve your team’s productivity:

1. **“If it isn’t tested, it’s broken”**
1. **Choose meaningful names**
1. **Classes and functions should be small and obey the Single Responsibility Principle (SRP)**
1. **Functions should have no side effects**