+++
title = "VirtualDOM"
description = "Virtual DOM concept explained in eli5 terms"
date = 2014-09-28T02:13:50Z
author = "Rohan Shetty"
+++

## Why & What

The primary purpose is to minimize re-renders or **(minimize the likelihood of janky experiences.)**

So mostly it’s for optimizing the rendering part. Virtual DOM is a copy of the actual DOM tree that React maintains. It’s an in-memory object. 

Whenever there’s a change in DOM, it updates Virtual DOM first and then syncs up with the actual DOM tree, this kinda optimizing helps when there are a lot of DOM elements to track