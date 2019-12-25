---
title: "Turning Off Syntax Highlighting"
description: "Experimenting with turning off syntax hightlighting on code."
date: 2019-12-08T09:32:32+05:30
tags: [code, workflow]
---

Few weeks back I stumbled on this [blog post](https://www.robertmelton.com/project/syntax-highlighting-off/) which stated the obvious benefits of disabling syntax highlighting for your code. I would have been surprised if I hadn't read [this one](https://www.benkuhn.net/syntax) before. Both the blog posts advocate disabling colors schemes completely or minimally.

At the outset this seems absurd for anyone who has been coding for any length of time and insane for the cool kids who started learning to code in the age of color monitors. Syntax highlighting helps differentiate the syntax of the code using different colors making the code more scannable. Spend some time with your favorite color scheme and you can gloss over the code with realtive ease with minimal brain power. Almost everyone and their nannies are using syntax highlighting so if there was something inherently wrong you would have known by now right ?

That's what I thought until these posts urged me to try the non-syntax bandwagon. Since syntax-highlighting is an integral part of all editors now, there isn't an easy way to disable for most of them. The easiest is for Vim with `:syntax off`. I'm an avid Spacemacs user and I couldn't find any single option to disable highlighting easily, so I had to find a syntax color scheme that did not color the syntax. After trying out a couple of them I settled on `minimal` a really great monochrome no-frills syntax theme. I made some minor tweaks and off I went on the white text on the black background route and surprisingly feel in love with it.

{{<figure src="/images/emacs_screenshot.png" title="minimal spacemacs setup with elixir">}}

### What has changed ?
Much to my surprise I experienced most of the benefits explained in the posts.

- Less distraction, I am a huge proponent of minimalist industrial design and really dig simple minimal designs that get the job done.
- Understanding the code better, Without the bright colors to distract and guide my eyes along the path I am reading the code more deeply. The overall structuring has also improved.
- Less jarring, Since there aren't that many colors as before to tire your brain I think I can code for longer stretches of time. I use org-mode time tracking and did found a marked increase in productivity from when I disabled color scheme.

### Will I continue using it ?
Yes, It's like a breath of fresh air once you get used to it and trust me you'll get used to it fast. I loved it so much that I disabled the syntax highlighting on my fish shell and VSCode.

### Should you use it ?
How am I supposed to know :) ? We have had color schemes for so long and it might seem stupid to turn it off, but how would you know if you haven't tried it. I urge you to try this for one week and see if you like it or not. Don't turn back in one day if you're doing it commit for a week. 

This is one of the reasons I love computing so much, there are like a million ways of doing something including the way we write code. So give `:syntax off` a try and see how that goes.

[Discuss on HN](https://news.ycombinator.com/item?id=21734436)
