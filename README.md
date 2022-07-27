# whiskey

A Jekyll-based template for [Bourbon](http://boubon.io) + [Neat](http://neat.bourbon.io) + [Bitters](http://bitters.bourbon.io) + [Refills](http://refills.bourbon.io) SASS

This repository simply places the default structures provided in Bourbon.io's Refills templates into the appropriate directories for Jekyll. `html` fragments are in `_includes`, and all the SASS files are provided in `_sass`, which Jekyll `> v2.5` can process automatically to generate the css.    


## Setup

- Fill in appropriate variables in `_config.yml`
- Note that navigation menu is also set in `_config.yml`

## Customizing SASS

All SASS files can be customized directly.  However, the most relevant ones will be those in `refills`, which correspond to the html templates in the subdirectories of `_includes`. 

## Hey Glynnis, this is how you do it:
1. Clone the repo onto your shiny laptop.
1. To run the jeykll build command, enter `bundle exec jekyll serve` and visit `localhost:4000` to see your changes.
1. Make a commit to the `master` branch and/or push a branch and merge it into `master`.
1. Log in to Netlify. Your password is in 1Pass, NOT tied to your GH account.
1. You'll see a recent deploy and can click it to see the server logs as it's deployed to see if it succeeds. If it's been a whole longass time you might need to update the build image on the server before you can deploy successfully.
1. DO IT LIVE!
