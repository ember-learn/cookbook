This recipe will walk you throught the best way to suggest a new recipe.

There is a different recipe for [suggesting an update to a recipe](./contributing/suggesting_a_recipe_update).

## The challenge

You have a recipe you want to add to the Cookbook but you are not sure whats the best way to suggest a new recipe. 
Please note there is a seperate recipe for updating existing recipes. 

## Steps
### Before Suggesting a recipe
Check [Deciding If A Recipe is a Good Fit](./contributing/deciding_if_a_recipe_is_a_good_fit). Make sure that the recipe that you are planning to submit has not already been submited. If it was then you can update an existing recipe. 

### Fork the repo 
Fork the [Ember Learn Cookbook repo](https://github.com/ember-learn/cookbook/).

### Create a feature branch 
A [feature branch](http://nvie.com/posts/a-successful-git-branching-model/) is a branch in a local git
repository. Its name should be the camel-cased or underscored name of your recipe. For example, the branch
name for this recipe "Suggesting a Recipe" would be `SuggestingARecipe` or `suggesting_a_recipe`.

### Create the recipe file
Decide what sub folder does your recipe fit in the best. For example this recipe fits well with other Recipes that tal about Contributing to the Cookbook so the file for this recipe was created in `guides/cookbook/comtributing` folder.

When you decided on the location create a markdown (.md) file.

### Update pages.yml file
Go to `guides/pages.yml` and add the title and the url to your newly added recipe by following the existing pattern.

### Naming your file
File naming follows a similar convention as the branch name your suggested recipe should be the lowercase, underscored version of your recipe's name. The
filename name for this recipe "Suggesting a Recipe" is `suggesting_a_recipe.md`.

### Writing your new recipe
New recipes should follow the [Cookbook template](./contributing/understanding_the_cookbook_format).

### Submitting your recipe
When you are ready to submit your recipe, push your local branch to the remote branch on your GitHub fork and
submit a pull request. 

## Results

When you are finished, your recipe should be available on the Cookbook website.

## Learn more

[fork_repo]: https://github.com/ember-learn/ember-website
[feature_branch]: http://nvie.com/posts/a-successful-git-branching-model/
[understanding]: ./understanding_the_cookbook_format
[deciding]: ./deciding_if_a_recipe_is_a_good_fit

_Tags: contributing, getting started_