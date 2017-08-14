---
layout: post
title:  "VacationStation "
date:   2017-08-14 15:44:12 +0000
---

## a list of budget friendly destinations for 2017

I sort of finished my CLI data gem project. I mean, it's finished. I feel like it could be better but it's time to hand it in and receive feedback. I had really anticipated this to be the easy part of the project. I thought the other projects in this group would be more difficult. Turns out it was the other way around. I really missed having the tests around to check my project against. I just kept running it through the console, utilizing pry, and hacking away at it until it gave me what I wanted.

![](https://media.giphy.com/media/fQZX2aoRC1Tqw/giphy.gif)

I originally chose TravelZoo's top 20 deals of the week website. I realized after throwing rocks at that for a while that in order to drill down a user needs to login on their website and I anticipated that being a problem. So two days later I abandoned that idea and looked around some more. Browsed some other websites. Almost did a movies-releasing-this-weekend gem but realized that one of the example gems was pretty much the exact same thing. 

So I came back to travel options and ended up on Lonely Planet's best value destinations for 2017. My gem lists 10 budget-friendly destinations and then allows you to pick a location to read a quick summary about it. 

![](http://i.imgur.com/ZQ1CpcQ.png)

I would have liked to have had a more dynamic website but after looking at the html it seemed pretty straight forward and I was struggling to have completed ANY scraping to this point. I screwed up on the syntax while scraping and pretty much floundered around for a couple of hours until I went back through some of the lessons. Finally, I was getting the data that I wanted but for some reason my hash created with my scrape was only pulling random items from my list. This had me stumped. I finally got it to collect everything, but then it was just a big clump of data and I didn't know how to output it correctly and then allow the user to drill into it. I realized I was trying to jump from A - D and in my head I really needed to back up and get something working. I know I oversimplified this by putting the data into two arrays but I think I needed to be able to visually see where my information was in order to present it. A, B, C, D...etc. It's not the best format. I would have liked to have been instatiating objects and not just referencing arrays, but it works! 

After a few days of frustration I decided to turn it in and get the feedback for how to make it work better. I know I said this already but I really missed the tests working on this project. I learned that I rely on them pretty hard and I should be thinking big picture about this stuff rather than just one test, and then the next test, and then the next test... I think having that frame of mind would have helped me quite a bit. I also re-watched some videos from OOR and I guess my conclusion was, okay, I get it, but how do implement that for THIS project. I had a hard time replicating it which tells me I need to practice more. The upside to this project was getting a lot of practice adding, committing, and pushing to github. I had to do a short refresher and I remember thinking 5 days ago, "ugh...so many commands, I'll never remember this flow or all of these commands." It got better. I got better. I did have a dream Friday night about creating a new branch for potential scraping class aanndd I didn't do it aanndd I was kicking myself later when I was deleting, pry, writing and deleting and writing, pry, and not committing and then forgetting what worked and what didn't work. I also got a lot more comfortable using pry which was pretty crucial getting through my scraping.

My project is very basic and I already have ideas of how to improve it. My conclusion is that I wouldn't award myself 100% on it but I learned some valuable things and have an idea of where I need to improve my code. I'm excited to move into SQL but I definitely want to jump into OOR study groups to build my understanding and keep sharp. I remember just a week or so ago thinking I needed a refresher on procedural ruby, putting in the time and feeling more confident in the end. I should definitely be doing the same with OOR.
