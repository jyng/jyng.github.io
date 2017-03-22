---
layout: page
title: Making it easier to reduce people's foodprint
bkg-color: 00CCFF
---
## Background
## The Challenge

MyDomino set out to help make climate change easier for people. In Winter 2015, I co-led a design sprint to validate the team’s assumptions. From the design sprint results, I continued as the design lead focusing on UX and visual design, while assisting in user research and front-end.

## The Product

On the surface, it’s FitBit for carbon footprint, but we prioritized education over data. We realize that the market is filled with data-heavy apps and it would be hard for us to compete.

[ picture of different apps]

We also wanted to teach the relationship between food and how it impacts the environment, so being data-heavy wasn’t a high priority.

## Defining Priorities

We defined priorities internally to maintain focus on the right goals. We first created

### Experiential over Literal

We wanted to offer an engaging experience from copywriting to creative direction.

### Fun over accurate

While developing the copy, we saw how dry our voice came across when we tried to explain carbon impact. The copywriting team developed the copy, while I used color and typography to match the voice.

### Mobile-first web app

Going in, the product team knew that making it easy to access the app while or after eating would be ideal. We focused on core functionality for mobile then added secondary details on desktop.

## Initial Wireframes

First, I split the UI elements into `Actions` and `Text` so I could understand the context.

### [insert rough drawing]

![](https://s3-us-west-2.amazonaws.com/notion-static/906512e63b274f378b28e0b0b4a6e394/food-impact-3a_mobile.png)

![](https://s3-us-west-2.amazonaws.com/notion-static/c95c909a90db4963b2d074f3aa5d6714/food-impact-5a_groups.png)

 _Selector interaction vs Search interaction_

Search feature was a great design feature, but expensive engineering feature.

## Visual Design

### Product Icons

![](https://s3-us-west-2.amazonaws.com/notion-static/fedafb43967c495993f70290a95dbf3f/product-icon.png)

### Home Screen

![](https://s3-us-west-2.amazonaws.com/notion-static/8311ee3078184efe8ab7e1178f820a12/Member-home_3f.png)

## Feedback

When users finished inputting their food, it would return them to the home screen. We assumed that there would be enough context to what all the data meant, but users went through this screen without learning how their food impacted carbon footprint.

We reorganized the flow so that we could make sure the learning was happening. We placed the graph on a Results page to build more context on the graph.

##

![](https://s3-us-west-2.amazonaws.com/notion-static/0523953a28194857aee9de81fc07515f/choose_food_4a.png)

![](https://s3-us-west-2.amazonaws.com/notion-static/20a9c74c5c584d6b92a66028a1bda639/pick_size_4a.png)

![](https://s3-us-west-2.amazonaws.com/notion-static/58da36f5c1fb4986a191b0c4a30ccd94/beeflamb_little_4a.png)

![](https://s3-us-west-2.amazonaws.com/notion-static/25b99a0455584ff7ac5d3728178f2542/desktop_1b_copy.png)

## Design Details

In keeping with the style of the icons, I added an offset underline hover style

[line.gif]

In the alpha version, I added quick and dirty fade-in animation so we could test earlier, but it wasn't an elegant solution. I later went back and added a fade-direction animation in javascript.

[fadeanimation.gif]
