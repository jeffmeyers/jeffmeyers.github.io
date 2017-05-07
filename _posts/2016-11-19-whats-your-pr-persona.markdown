---
layout: post
title:  "What’s your PR persona?"
date:   2016-11-19
categories: software code-review github
---

Software engineers often rely on feedback loops to perform their jobs: unit and integration tests, radical honesty and real-time performance reviews, pull requests.

A pull request is a way to propose a change-set to your team. It can be as informal as “hey, I want a record of having merged this and why, so here’s a PR before I merge,” or they can be as formal as using a dedicated review process that blocks merges until the team has OK’d the change-set.

The way that you respond to any piece of feedback is important. But the way that you respond to pull request feedback — what I’m now calling the “PR persona” — is monumentally important. It can mean the difference between happiness and dissatisfaction in your career. It can mean the difference between a performing team and a storming one.

It matters whether you’re on the proposing or reviewing side, and it matters no matter what the decision turns out to be. It matters because it’s on record, and because others look at it as a reflection of the type of person you are to work with.

It’s easy to be the “sure, I’ll change it” guy. It’s easy to be the “please change this” girl. It’s easy to be dogmatic about stylistic preferences, and even easier to jam up an entire team with indecision. These are, in my opinion, anti-patterns for high-performing teams, and entirely avoidable. Here are a few pieces of advice I’ve seen help:

- **Avoid dogmatic style discussions.** If you care about style, have a style guide. If you really care, then automate style checking. Use linters — use them locally, use them in git hooks, use them in CI. Do whatever you have to, but don’t ever argue about style in pull requests when it’s completely easy to automate.

- **Be open, but don’t always roll over.** Write code with purpose. Having a reason for the things you do is important, and your team should respect that. It’s okay to open up a discussion — I did this because X, and I don’t think Y is the right answer because Z. Give folks a chance to convince you, but don’t get stuck in an infinite loop.

- **Don’t feel like you must have criticisms.** Sometimes a PR is fine. It’s okay to give it a thumbs up and move on. Sometimes a PR has potential for improvement, and you should leave some feedback. But don’t feel like you have to.

- **Remember why you write code.** I mean a couple things here. One is that code is a minuscule part of your job description. You’re writing code to build a business, to make customers happy, to make money so you can continue building a great team. Don’t lose sight of that and get caught up in religious debates. But also remember that you write code because you love it; take every piece of feedback as an opportunity to learn. Be enthusiastic. Be fun to work with. Be the person you would want to have review your pull request.

- **Come up for air if things look unrecoverable.** Sometimes there’s domain knowledge that got lost, or someone’s new to an entire language or ecosystem. That’s fine. If you find yourself leaving tons of comments, take a breath; it’s often better to grab someone in person (or on TMate, or ScreenHero) and pair through the correct solution than it is to harp on a PR for days.

No matter what, remember that you’re reviewing code to produce a high-quality product and build a high-functioning, productive, happy team. These things all go hand in hand.

So next time you’re tagged to review a pull request, ask yourself: what’s your PR persona?
