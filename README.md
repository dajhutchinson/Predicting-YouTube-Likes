# Predicting YouTube Likes

**Table of Contents**
- [The Task](#The-Task)
- [Summary of Results](#Summary-of-Results)
- [Guide to Project](#Guide-to-Project)
  - [The Data](#The-Data)
  - [Notebooks](#Notebooks)

## The Task
Create a model for predicting the number of likes a YouTube video receives, given its tags, view count and comment count.

## Summmary of Results

## Guide to Project

### The Data
Data used is the [GBvideos.csv](https://www.kaggle.com/datasnaek/youtube-new?select=GBvideos.csv) & [GB_category_id.json](https://www.kaggle.com/datasnaek/youtube-new?select=GB_category_id.json) files from the Kaggle dataset [Trending YouTube Video Statistics](https://www.kaggle.com/datasnaek/youtube-new). I have provided the file [data/explanation.md](data/explanation.md) to explain the field of the dataset.

### Notebooks
 - [**Exploration**](Exploration.ipynb)
    - Prepared the data for analysis by applying the most appropriate datatypes and manipulating some of the fields to be more usable. Namely I converted the `tags` values from single `string`s to `set`s containing the tags used as separate elements.
    - Analysed the distribution of views, ratings and comments. Explored how many tags typically used, and which tags are most commonly used. (77% of tags were used by only one video).
