---
layout: recipe
date: {{ .Date }}
title: "{{ replace .Name "-" " " | title }}" # The title of my awesome recipe
draft: true # it won't be published/rendered

image: plated.jpg # main image of the recipe

# Source section
authorName: "Original author name"
authorURL: https://original.author.url.com/about
sourceName: "original recipe name"
sourceURL: https://original.recipe.link/original-recipe-name

# Recipe information
category: Breakfast # For example: "Dinner", "Breakfast", or "Dessert".
# cuisine: Misc

tags: # add as many as I want
  - Plant Based
  - foo
yield: 1 recipe
prepTime: 5 min
cookTime: 8 min

tools:
- Tool 1
- Tool 2

ingredients:
- foo
- bar
- foo-bar

## if using sub-components
#components:
#- title of the component

directions:
- step 1
- step 2
- enjoy
---

Some extra markdown text to ilustrate, it goes after the recipe after
all it's a cook book, not a story book!
