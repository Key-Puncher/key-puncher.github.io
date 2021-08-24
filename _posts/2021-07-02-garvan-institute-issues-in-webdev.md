---
layout: post
title: Garvan Institute Issues in Web Dev
---

5 weeks in, and I have experienced the first significant cross-browser challenge. Chrome for some reason behaves differently to both firefox and safari. In order to tackle this challenge, I poked around the internet for answers. I found a lot of problems that were *similar* to mine, but not quite the same. It's hard to tell exactly what is causing this issue. However, because of it only being a problem in specific browsers, it's most likely not a bug in my code but some way chrome handles the rendering that's different from the rest. 

I don't expect to get a resolution from Chrome, though I reported the issue.

UPDATE: it turns out that this is a known issue, and has been a problem since 2018. There's a few workarounds that has been suggested, and I've implemented a 'hack' way of getting around it. It's definitely not ideal, but it works fine and that'll have to be enough. This kind of problem is fairly new to me. I don't have a background in web-dev, and usually I expect my code to run the same on any given machine with the same OS. With JavaScript requiring browser support for the application, I've had to adapt to these new challenges.

### Situation, Task, Action, Result

I have found a significant bug in chrome that causes the SVG to fail specifically in that browser. In order to resolve this issue, I had to post it on tech forums asking for any advice, and reported the issues to chrome bug tracker. Unfortunately there does not seem to be an easy solution to it. After discussions with the supervisor, I implemented a solution in chrome that will render a different thing depending on the browser in question.
