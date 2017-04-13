---
layout: page
title: Making it easier to reduce food's carbon impact
bkg-color: 9CEBFE
contributions: Product Design &mdash; Visual Design &mdash; Front-End &mdash; User Research
qtr-date: Fall 2016

---
{% include styles.md %}
{{ writing }}
## Background

MyDomino's mission is to help people reduce their carbon impact. But getting people to reduce their carbon impact is hard because there are so many moving parts: Going solar, reducing food waste, switching to renewable energy — the options are varied.

We decided to build out a guided path that makes the whole process of reducing carbon emissions easy and fun.

## The Product

Our product is divided into 3 different categories: Food, Transportation, Energy.

We started with food first because it was something that a lot of users were curious about. We figured we could use that curiosity to our advantage and build repertoire before moving onto larger/other categories.

In terms with how it works, it's food tracking but measured in carbon footprint. We realized early on that many people are curious about reducing their carbon footprint, but they don't know much about it. Our product prioritized the learning of the relationship of food and carbon footprint, while using competition to create a compelling experience.

I was responsible for designing the product from sketching to shipping. I also supported in user research duties and front-end development.

## Wireframes

I started by organizing Actions and Information into specific hierarchies and then iterated in a Crazy 8s fashion to quickly generate ideas.
I then took the best ideas so see how well they held up on the screen.

{{end_block}}
{{image-three}}
<img class="w-100 w-33-ns" src="assets/food-challenge/wireframes-1.png">
<img class="w-100 w-33-ns" src="assets/food-challenge/wireframes-2.png">
<img class="w-100 w-33-ns" src="assets/food-challenge/wireframes-3.png">



{{end_block}}
<p class="db center tc mono gray f6 mt0  mb5"> Input UI explorations</p>
{{writing}}

## Visual Design
We decided on a data visualization design that placed focus on a user's food impact progress. Below the progress tile, we also offered other resources such as helpful articles and local events in the area.
{{end_block}}
{{image-md}}
<img class="w-100" src="/assets/food-challenge/myhome-v1.png">
{{end_block}}
{{image-md}}
<img class="w-100" src="assets/food-challenge/hover.gif">
<p class="center tc mono gray f6 mt0 mb5"> Hover interaction</p>
{{end_block}}

{{image-md}}
<img class="w-100" src="/assets/food-challenge/foodModal@1.5x.gif">
<p class="center tc mono gray f6 mt0 mb5">The dynamic gauge gives instant feedback on their carbon impact (Prototyped in Framer)</p>
{{end_block}}
{{writing}}
In the food view, after a user finishes food input flow, they are brought back to the dashboard. We felt that this experience created a dead-end without enough incentive for the user to return.

## Feedback

I suggested that we should do some user interviews even if the product wasn't fully functional to test our assumption. I supported user research by distilling findings into insights.

Here are some insights we found:
- Measurement for carbon dioxide wasn't a clear indicator of how well they were doing
- There wasn't enough context for the graph to be meaningful
- The gauge was easy to miss because it was below the fold

My product manager suggested a week graph as that UI is clearer than  . Our engineers were working on some back-end issues, so I designed and implemented the feature.

We also noticed that the graph would be a lot of valuable once users have established context. I suggested we move the graph into the results view.

{{end_block}}

{{image-md}}

<img class="w-100" src="https://canvas-files-prod.s3.amazonaws.com/uploads/765259d3-f505-4557-9b53-d95472ea333a/My-Home%20%207a%20.png">

<img class="w-100" src="https://canvas-files-prod.s3.amazonaws.com/uploads/3f945c0b-b83c-4676-ae3e-5b189c6dfc5d/desktop 1f--flip.png">
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
When I first joined the company, it was all legacy code leftover various contractors. I led the restructuring of the entire CSS stack (a lot concepts borrowed from Tachyons and Basscss). I focused on making sure the code was readable through comments, organization, and most of all communication.

[Marketing Design]
[Various marketing designs (print & digital) I worked on for MyDomino]
{{end_block}}
{{image-md}}
<img class="w-100" src="https://canvas-files-prod.s3.amazonaws.com/uploads/aa9fbee6-8bf6-4824-ac89-7a27e137d3dd/Screen Shot 2017-04-03 at 7.55.12 PM.png">
{{end_block}}
{{writing}}
# Marketing Design & Product Concepts
#### Besides working on the main product, I explored different product concepts and shipped marketing collateral

I created a brand mark for our Clean Score

At one point, we were sending PDF reports of people's carbon impact. This a "report card" I designed.

I also redesigned our marketing website



{{end_block}}
