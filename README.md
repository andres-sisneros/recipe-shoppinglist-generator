# recipe-shoppinglist-generator

## Run
https://andres-sisneros.github.io/recipe-shoppinglist-generator/

Select at least one meal and scroll to the very bottom.

## Solves two problems
1. I go shopping and do not know, which ingredients I should by - I always forget which recipes/meals I can cook.
2. I am at home and I want to cook a certain meal, but I do not have all the necessary ingredients.

## Input
Select the meals you want to cook from a recipe list.

Meals are ordered by priority, e.g. Priority 1 meals (the healthy meals) will appear at the top of the list. Priority 2 meals will appear below that, etc. Within each priority group recipes are displayed in random order. 

## Output
Accumulated list with ingredients you need to buy in order to cook the selected meals.
The ingredient list is sorted by supermarket departments.

Workflow: Copy the shopping list into memories (Mac), Wunderlist or any other tool that helps you during your shopping trip.

Recipe explanations can be concise, because the contained recipes are your own recipes you know very well.

## Use your own recipes
1. Clone this repository.
2. Change the `recipes.json` file so that it fits your own recipes. Then check [here](https://jsonformatter.curiousconcept.com/#), if your `recipes.json` content has a valid json format.
2. Copy the raw version of your `recipes.json` into line 9 in the `recipes.js` file.
3. Use Github Pages to create an application link. Bookmark this link and you can always generate your shoppinglist on the go. 

Done!
