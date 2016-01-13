---
author: manasgarg
comments: true
slug: the-problem-of-solving-problems
date: 2016-01-13 06:00:00+05:30
title: The Problem of Solving Problems
layout: post
---

The job of a Software Architect is to identify problems, prioritize them, craft the solution by evaluating trade-offs and guide the implementation. Things vary here and there but this is generally a good outline.

I find it amusing that Architects are the recipients of extreme praise _and_ extreme criticism; that too for the same product. Mostly praised when they are part of the team and mostly criticized after they exit.

As I was going through some of this praise-criticism cycle, I was forced to look deeper into it to understand what's really happening here. I work with rational people who are also well intentioned. So, I ruled out flick-mindedness or malice as the root cause. Also, I have observed this across the board for all the Architects that I have worked with. So, it had to be something else.

Then's what I realized the problem of solving problems.

Every problem that's solved within a software product has its own lifecycle. Problem is discovered and prioritized; a solution is designed and implemented. Solution itself has its own lifecycle. As the product runs in more environments or is loaded with more functionality, the solution needs to change.

Based on the problem lifecycle, I categorize them in 6 buckets:

1. **Invisible-Problems**. These problems are not known yet. If the Architect is around when these problems become visible, she will just solve it and get praise for solution. But if the Architect has exited, she could be criticized for overlooking such an _obvious_ thing.

2. **Visible-But-Unclear-Problems**. You can see these problems coming from a distance but you don't really understand them well. The praise-criticism duality in this case is same as #1.

3. **Not-Yet-Prioritized-Problems**. These problems are cleared defined but they haven't found their way on roadmap because of other priorities. The praise-criticism duality in this case can easily follow the same path as #1 (how could someone not prioritize such an _obvious_ problem).

4. **Not-Fully-Solved-Problems**. These problems have been solved but the solution is either not correct or it's not complete. These may or may not earn praise for the Architect when she is around. But if the Architect has exited, they certainly become the largest source of criticism.

5. **Solved-With-Trade-Offs-Problems.** The solution to these problems involved some tricky trade-offs that could have gone either way. The generally do not earn praise. And when a situation arises where the trade-off could be questioned, it is definitely questioned.

6. **Solved-Problems**. These problems are solved in such a way that they don't surface anymore. They are the main source of the praise when the Architect is around. But after the Architect exits, they fall below the visibility line and cease to be a source of the praise. They don't even offset for the criticism because they fall below the visibility line.

So, when the Architect is around, the right decisions are more visible. The wrong/questionable decisions remain invisible OR they get handled in time to not cause a disturbance.

However, once the Architect exits, the right decisions fall below the visibility line and wrong/questionable decisions are the only ones that remain in sight.
