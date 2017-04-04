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

## Wireframes

I started by organizing Actions and Information into specific hierarchies and then do some Crazy 8s to quickly explore ideas.

I then mockup the best ideas in black & white to see which ideas are most promising

{{end_block}}
{{image-md}}
<img class="mw6" src="https://canvas-files-prod.s3.amazonaws.com/uploads/dcf5afae-84cc-4f06-be85-e7405106a94e/Action logging --filled.png">

<img class="mw6" src="https://canvas-files-prod.s3.amazonaws.com/uploads/339fb361-893e-4a08-8451-512e312e6f73/Action logging --empty 2a.png">
{{end_block}}

{{writing}}

## Visual Design
We decided on a design that placed focus on the food challenge progress. Hovering allows the user to see their points. Clicking on a bar opens the view for that date. Below the food challenge tile, we showed linked resources ranging from tips & tricks to discounts.
{{end_block}}
{{image-md}}
<img class="mw7" src="https://canvas-files-prod.s3.amazonaws.com/uploads/04c2e070-f6d3-48ef-b7ad-992e6b5bbb93/Member-home 3f.png">
{{end_block}}

{{writing}}
In the food view, we grouped the categories and a dynamic gauge so users could quickly see their relationships of food and their carbon impact.
{{end_block}}

{{image-md}}
<img class="mw7" src="https://canvas-files-prod.s3.amazonaws.com/uploads/4bc6c1df-3815-4805-b8b2-f290299cbb6e/desktop 1f.png">
{{end_block}}
{{writing}}
At this time, we knew this flow didn't feel complete, but we had been building the product non-stop and needed to conduct user research to give our team better perspective.

## Feedback

I suggested that we should do some user interviews even if the product wasn't fully functional.

From our research, we saw that people were not interested in the graph, because it wasn't clear what the numbers meant. We knew then that we needed to slim down the Food Challenge tile, but without losing the affordance to go into the Food iew.

My product manager suggested we try a week view showing only completion. Our engineers were working on higher priority tasks, so I designed and implemented the idea.

We also noticed that the graph would be a lot of valuable once users have established context. I suggested we move the graph into the results view.

{{end_block}}

{{image-md}}

<img class="mw7" src="https://canvas-files-prod.s3.amazonaws.com/uploads/765259d3-f505-4557-9b53-d95472ea333a/My-Home%20%207a%20.png">
{{end_block}}

{{image-md}}
<img class="mw7" src="https://canvas-files-prod.s3.amazonaws.com/uploads/3f945c0b-b83c-4676-ae3e-5b189c6dfc5d/desktop 1f--flip.png">
{{end_block}}

{{writing}}
## Style Guide & Front-End Architecture
While building the product, I documented our design patterns into a style guide and led the CSS architecture.
{{end_block}}
{{image-md}}

<img class="mw6" src="https://canvas-files-prod.s3.amazonaws.com/uploads/9353e7ef-5a35-407e-8891-e119ab43d110/Desktop.png">
<img class="mw6" src="https://canvas-files-prod.s3.amazonaws.com/uploads/740e0aa2-845c-4f36-bd1d-f7c04344bc77/Page 2.png">
{{end_block}}
{{image-md}}
<img class="mw8" src="https://canvas-files-prod.s3.amazonaws.com/uploads/aa9fbee6-8bf6-4824-ac89-7a27e137d3dd/Screen Shot 2017-04-03 at 7.55.12 PM.png">
{{end_block}}
