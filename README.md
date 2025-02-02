# Introduction
I find myself building a company in the age of AI where I'm supposed to generate more revenue per employee than previously thought possible.

This new world that we live in comes with expectations that technical founders are expected to generate massive leverage for themselves and their teams. Yet everytime I try to introduce that leverage AI falls short.

It falls short because it just can't one-shot the things I need to create a great product, to create a great GTM motion, to create great content, to create a great company.

AI today lives in fragmented silos and tools. The best expeirence I've had with AI is using Cursor to write code. Cursor allows me to iteratively write code, test it, and iterate on it.

Cursor let's me compose code snippets into production ready functionality and ultimately into a full product.

I want to create a system that allows me to compose code, content, and processes into a company that scales with the help of humans and AI.

I want to create a system that creates leverage for me, empowers my team, and to deliver more value to this world.

# The vision
I want to create a tool that helps me create a company from my IDE. Where I can see all my files, all my code, all my notes, all my content. I want check that company into version control and I want to iterate on it with my team. My team of humans and AI agents. I want to be able to unleash the full power of the collective intelligence of everyone on my team, human or not. 

# The solution
Introducing BizOS. A business operating system that helps you create, iterate, and scale your company with AI.

## Focus areas
* Business objects
* Content
* KPIs
* Methodologies
* Story telling
* Strategy
* Integrations
* Forecasting and Modeling
* Budgetting (time, money, resources)
* Resources


## Ideas

### Markdown + TOML based metadata
The idea behind this approach is that the markdown file is the current notes about a business object that's stored in the system of record and the metadata is the reference to the system of record for that content. I think we should also extend TOML to support markdown in multi-line strings that have a md extension.

``` markdown
---
title="My Blog Post"
description="This is a blog post about my company"
author="John Doe"
date="2024-01-01"
---

# My Blog Post
This is a blog post about my company.
```

### Business Object Modeling
Business objects should be modeled using Typescript interfaces and we should do data model validation using Typia. There should be a library of built in data objects for getting started but we should be able to extend or support brand new business objects.

#### Interacting with business objects
Business objects should be pullable from a remote, system of record, modifiable locally and pushable back to the system of record.

# Where to start?
Help manage the overall projects that we have going on in the company (in linear), the companies we're interested in targeting (in Hubspot) and overall content we're pushing through our CMS (Sanity). 
