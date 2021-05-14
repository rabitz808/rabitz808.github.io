---
layout: essay
type: essay
title: The Great Chip Shortage of 2021
# All dates must be YYYY-MM-DD format!
date: 2021-04-29
labels:
  - Software Engineering
  - Design Patterns
  - Bots
  - Graphics Cards
---

## The Chip Shortage, The Scalpers, and The Miners
It's 2021 and there's a global chip shortage! So what does this mean for you? It means you can't get your hands on that sweet new rtx 3080 graphics card unless you're willing to fork up some cash and pay a premium to scalpers. I'm here to tell you NO, don't you dare do that! There is a way you can get one that doesn't involve you selling a kidney on the black market. Keep reading cause I'm about to spill the beans. That's right, the answer you've been searching for all this time is two words, DESIGN PATTERNS. Not what you were expecting huh? Well let me explain what it has to do with anything at all. In simple terms, a design pattern is a solution that you can apply to solve a reoccurring problem. The problem we're facing is that every graphics card on the market goes out of stock within minutes of restock. Online retailers like Zotac, BestBuy, Amazon, and WallMart all suffer from this problem. Using an observer design pattern and event handlers, you can design a bot that monitors these websites and does an action when it notices a change. It's that simple! Now I know you're lazy so let me do you a favor and present you with one already made. Just click [here](https://github.com/Hari-Nagarajan/fairgame) and follow the instructions on github. Its an open source bot that refreshes amazon listings and attempts to purchase the item if it meets the given price range. Now get to it and help save a rtx 3080 graphics card from working to death as an Etherium miner.

## That's Not All
Maybe you've already gotten your hands on a new graphics card, don't have the money to get one, or never needed one in the first place. If that's the case, let me waste more of your time telling you just how good design patterns are and how I've been using them. An observer design pattern is just one of the many out there. Theres also more common ones like factory, singleton, and mvc. I'm not going to explain each one to you, but I did want to mention some things about mvc. MVC stands for model view controller and if you've ever done anything even remotely related to web development or user interface you've used this pattern before. It consists of the model that encapsulates application states, the controller that defines application behavior, and the view that handles the rendering. In my case, I've used it when working with Meteor and am currently using it for our UH-Ratings github project. The model is mongoDB, the controller is React Router, and the view is React. These all work together to grab and display data on the website. I'm still fairly new to this topic, but I encourage you to take some time to learn more about what other design patterns there are out there!