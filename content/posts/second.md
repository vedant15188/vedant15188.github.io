+++ 
draft = true
date = 2026-06-22T00:21:00+02:00
title = "Developers Aren't a Dashboard"
description = "Every few years we crown a new way to measure developer productivity, and every few years it gets gamed into meaninglessness. A short, slightly annoyed tour of the treadmill, and why we keep running on it."
slug = ""
authors = ["Vedant Kashyap"]
tags = ["Developer productivity", "metrics", "opinion"]
categories = ["commentary"]
externalLink = ""
series = []
+++

Every few years, someone discovers The one true metric for developer productivity. We hold it up to the light, like simba from the lion-king was just born, declare the measurement problem solved, slap it on a dashboard, and start ranking people by it. Eventually every single time it quietly rots into nonsense, usually right around the moment somebody's bonus starts depending on it which is pretty quick.

I've experienced a few of these cycles now, and at this point I'm mostly tired of pretending each new one is different. So let me save us all some time: it isn't.

## A short tour of the graveyard

**Story points.** The original sin. Such a fuzzy, relative measure of effort. "Velocity" became a target, estimates quietly inflated to hit it, and a number meant to help a team plan its own week became a club for comparing teams that should never have been compared in the first place. Congratulations, we weaponized a planning poker card and now you're spending more time in JIRA than solving actual problems.

**Number of commits.** Counting commits to measure work is like counting brushstrokes to judge a painting. Squash your work into one clean, considered commit and you look like you did nothing next to the person pumping out `fix typo` forty times before lunch. It rewards the exact instinct you should be training out of people.

**Pull requests merged.** Slightly more "grownup" at least a PR is a unit of change someone actually reviewed. But it still says nothing about whether the change *mattered*. Ten cosmetic PRs that shuffle config around beat one PR that silently prevents a 3am pager alert.

**Tokenmaxxing.** And here's the freshest one, hot off the hype cycle. (*tokenmaxxing* is judging productivity by how much you lean on your AI assistant i.e. tokens burned, lines generated, suggestions accepted, percentage of code written by AI.) Refactoring a piece of software that might not need refactoring has never been easier. AI can easily manufacture more numbers of the metrics mentioned above without any human intervention while burning through your company's dollars and probably giving a poor family in rural Georgia brown drinking water. [[Source](https://www.bbc.com/news/articles/cy8gy7lv448o)]

## They all die the same death, and it has a name

**[Goodhart's Law:](https://en.wikipedia.org/wiki/Goodhart%27s_law)** *when a measure becomes a target, it ceases to be a good measure.* It's older than every methodology that keeps rediscovering it the hard way.

Every metric in that graveyard measures activity, not value. Commits, PRs, points, tokens are all just proxies for "stuff happened." And the second you reward the proxy instead of the outcome, the people on your team do the only rational thing: they optimize the proxy and quietly stop caring about the thing it was standing in for.

**The more skilled your engineers, the sooner the metric breaks.** The people clever enough to boost the number without delivering the real outcome are the same ones you hired for their skill. Especially in organizations where competition is high and you're constantly under scrutiny every quarter and bad performance might translate into a PIP or a layoff.

## Tokenmaxxing earns its own paragraph

The entire pitch of AI-assisted development is reaching a good outcome with **less** effort, which I do slightly agree on, however the ratio of using up tokens and getting real value from the tokens you burn is quite skewed. 

It's "lines of code as productivity" reanimated except now it's much more effortless to produce the lines, so the number balloons faster than any metric in history. A high token count might mean someone shipped something brilliant. It might also mean they spent an hour losing an argument with a chatbot. Your dashboard cannot tell the difference. Neither, it turns out, can the person who built the dashboard. Uber learned this the hard way, burning through their entire annual AI spending budget in just four months before hitting the brakes. [[Source](https://techstory.in/uber-hits-the-brakes-on-ai-spending-after-burning-through-annual-budget-in-just-four-months/)]

## So what do we actually do?

I don't have a shiny replacement number to sell you, and frankly, anyone who *does* should set off every alarm you have. Big metric is coming for you! The next metric is already on its way. It'll feel fresh, it'll have a gorgeous dashboard, and someone will swear to you it finally cracks the measurement problem for good. Just smile and wave. We've seen this before.

{{< figure
src="/images/smile-and-wave.jpg"
alt="The penguins from Madagascar captioned 'Just smile and wave boys... smile and wave.'"
width="320"
>}}

A few things I've actually come around to:

- **Prioritize outcomes over mere activity.** Did the change make the system faster, more reliable, or the developer experience less painful? Those outcomes are harder to measure and therefore harder to game.
- **Use metrics to start conversations, not to hand down verdicts.** If you see a weird spike/dip on a graph that makes you think "why is that?", you've struck gold! The same number stapled to a performance review is poison.
- **Trust the people doing the work.** The most productive and collaborative teams I've seen weren't the ones being measured the hardest. They were the ones handed enough room to do good work and enough trust that they didn't have to *perform* productivity for an audience.

---

**This post's soundtrack:**

So recently, I've discovered listening to latin music more specifically the slow paced ones makes me feel like Anthony Bourdain: cultured, does effortless cooking and playing off my love for alcohol as having a saucy personality. I do love him and have my [own reasons](https://x.com/Bourdain/status/960322190993477632) for it.

Anyway, [fast high bpm songs](https://open.spotify.com/track/22FDcOa0zHs7sLd7vLD8s1?si=9a327ae95d8745c1) aren't exactly conducive for someone who is already multi-tasking and sort of 
{{< tooltip 
note="Fuck I might have used the work panick too many times in a space of just two sentences." 
cursor="default" >}}
panicking
{{< /tooltip >}}
at juggling multiple things, although I do love them and think they have their own place in the universe.

{{< spotify id="2n1MTLCis6qPSDKdr5XSDI" width="100%" >}}
