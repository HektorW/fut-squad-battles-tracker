# FUT Squad Battles Tracker

This is a website that will track the rankings for Squad Battles in FUT.

The idea is to track how many points are required for each rank at different times throughout every week.

The data will be used to graph out how the points increase over each week and
hopefully be able to predict the future for how many points will be needed.

## Data

The data will be scraped from https://www.futbin.com/squad-battles/points.
The idea is to have scheduled job that scrapes the data once every hour.

## Sveltekit

Sveltekit is used because I want to try it in a project.
There won't be many pages so the need isn't really justified but ¯\\_(ツ)_/¯.

## Graph

The data should be graphed out for the week (maybe even more granular as well).
This should help give a visual feel for when during a week the points increase more or less.

Possible graphing libraries in Svelte:

- https://github.com/Rich-Harris/pancake
- https://layercake.graphics/

## Tensorflow

It would be cool to be able to make predicitions about the final points for a week
and Tenserflow might be a good candidate for it.

https://codelabs.developers.google.com/codelabs/tfjs-training-regression/#0

## Deployment

Plan is do deploy to Heroku.
