# Recipe-GUI

## How it works
A GUI that scrapes recipes and nutrition information depending on the ingredients you input. This collaborative project uses multiple APIs, one of which is the Spoonacular API. 
Spoonacular may require a key to fetch data!!!!

This Tkinter app also uses selenium, which goes through a Chrome driver to scan Spoonacular and federal nutrition websites to give back results.

## How to use it

On the left side of the screen, you can input the foods you want to incorporate into a recipe in the search bar, separated by a comma. 
(EX: bread, eggs, bacon). After a little wait, roughly a minute since selenium tends to take a little bit to load, you'll get back a few recipes and a corresponding frame will become visible below the recipe information frame. 

Within this new frame, you can input one of the recipes the GUI gave you and view some additional nutrition information about it.

You can build your recipes on the right side of the screen, like a calorie and nutrition calculator. Here you enter a food, and its weight, then press the "select food and gram weight" button, and repeat. Once you have all your foods listed you can press the "Get nutrients for your recipe below" button to receive the nutrition information for your custom recipe.
