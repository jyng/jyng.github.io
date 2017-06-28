---
title: Making it easier to reduce food's carbon impact
date: 2017-03-21 00:00:00 Z
layout: page
bkg-color: 9CEBFE
contribution1: Guerilla Testing
contribution2: Product Strategy
contribution3: UX Design
contribution4: Visual Design
qtr-date: Fall 2016
---

{% include styles.md %}

{{image-lg}}

<img class="w-100" src="/assets/food-challenge/food-challenge.png">

{{end_block}}

{{ writing }}
## Background

MyDomino's mission is to help people reduce their carbon impact. However, the act itself is difficult to complete because there are many moving parts: Going solar, reducing food waste, switching to renewable energy — the options are varied.

Therefore, we decided to build out a guided path that makes the whole process of reducing carbon emissions simple and fun.

## The Product

Our product is divided into three different categories: Food, Transportation, Energy.

We started with food first because it was something that a lot of users were curious about. We used this interest to our advantage and built repertoire before moving onto other categories.

In terms of how the app works, it is a food tracker measuring in carbon footprint. Many people are curious about reducing their carbon footprint, but but do not know much about the process. Our product prioritized the learning of the relationship of food and carbon footprint, while using competition to create a compelling experience.

## My Role
I was responsible for designing the entire web app from ideation to implementation.
- Supported my product manager with user research.
- Collaborated with our two developers on front-end development.

## Wireframes

I started by organizing Actions and Information into specific hierarchies and then iterated in a Crazy 8s fashion to quickly generate ideas.
Then, I took the best ideas to see how well they held up on the screen.

{{end_block}}
{{image-three}}
<img class="w-100 w-33-ns self-start" src="assets/food-challenge/wireframes-1.png">
<img class="w-100 w-33-ns self-start" src="assets/food-challenge/wireframes-2.png">
<img class="w-100 w-33-ns self-start" src="assets/food-challenge/wireframes-3.png">



{{end_block}}
<p class="db center tc mono gray f6 mt3 mb5"> Input UI explorations</p>
{{writing}}

## Visual Design
We decided on a graph UI that focused on a user's food impact progress. Below the progress tile, we also offered other resources such as helpful articles and local events in the area.
{{end_block}}
{{image-md}}
<img class="w-100" src="/assets/food-challenge/myhome-v1.png">
{{end_block}}
{{image-md}}
<img class="w-100" src="assets/food-challenge/hover.gif">
<p class="center tc mono gray f6 mt0 mb5"> Hover interaction</p>
{{end_block}}

{{image-md}}
<img class="w-100" src="/assets/food-challenge/foodModal.gif">
<p class="center tc mono gray f6 mt0 mb5">The dynamic gauge gives instant feedback on their carbon impact (Prototyped in Framer)</p>
{{end_block}}
{{writing}}

## Feedback

I suggested that we should do some user interviews even if the product was not fully functional to test our assumption. I supported user research by distilling findings into insights.

Here are some insights we found:
- Measurement for carbon dioxide was not a clear indicator of how well users were doing
- We had a hidden affordance in the graph UI. There is no perceivable information for a user to act upon (The graphs numbers were meaningless to a user).
- The gauge's relationship with their food selection was ambiguous.

## Solution

My product manager suggested that showing the weekday a user has completed would help solve our affordance issue. I volunteered to implement it as the engineers were busy solving a large back-end issue.
While building the Weekday UI, I reasoned that we move the graph into a results view. A graph at the end of flow would have more value for users.

In the food view, after a user finishes food input flow, they are brought back to the dashboard.
{{end_block}}

{{image-two}}

<img class="w-33 self-start" src="/assets/food-challenge/v1-homeboard.png">
<img class="w-33 self-start" src="/assets/food-challenge/v1-food-select.png">
<img class="w-33 self-start" src="/assets/food-challenge/v1-food-results.png">
{{end_block}}

{{writing}}
## Style Guide & CSS Architecture

### Style Guide
While building the product, I documented our design patterns into a style guide so as the product grew our team was able make decisions quickly and build the product consistently.
{{end_block}}


{{image-two}}
<img class="w-40-l ma2 self-start" src="assets/food-challenge/sg-pg1.png">
<img class="w-40-l ma2 self-start" src="assets/food-challenge/sg-pg2.png">

{{end_block}}
{{writing}}
### CSS Architecture
When I first joined the company, it was all legacy code leftover from various contractors. I led the restructuring of the entire CSS stack (concepts borrowed from Tachyons/Basscss). I focused on readability and consistency that allowed our CSS to evolve gracefully.
{{end_block}}
{{image-md}}
<img class="w-100" src="assets/food-challenge/css-architecture.png"/>
{{end_block}}

{{writing}}
<div class="tc">
<a href="mydomino-marketing.html" alt="See Marketing Design for MyDomino" class="mono f4 line">See Marketing Design for MyDomino</a>
</div>
{{end_block}}
