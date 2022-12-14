---
layout: PostLayout
metaTitle: null
addTitleSuffix: true
metaTags: []
title: Movies Recommender System
colors: colors-d
date: '2022-12-14'
excerpt: 'Have you ever wondered how youtube recommends you videos '
featuredImage:
  type: ImageBlock
  url: /images/hero.webp
  altText: Post Image
media:
  type: ImageBlock
  url: /images/mov-rec-sys-img.jpg
  altText: Post Image
bottomSections:
  - elementId: ''
    variant: variant-d
    colors: colors-d
    title: Read next
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 3
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: RecentPostsSection
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
metaDescription: >-
  Sunset fishing is a beautiful time of day to relax and get in touch with
  nature
socialImage: /images/desmond-eagle.png
author: content/data/team/hugh-saturation.json
---
Reading the local TV guides, renting CDs and DVDs, watching tapes or filmstrip projectors... Today, this is all a relic of the past. The largest movie libraries in the world are all digitized and transferred to online streaming services, like Netflix, HBO, or YouTube. Enhanced with AI-powered tools, these platforms can now assist us with probably the most difficult chore of all — picking a movie.

Well, you don’t have to worry about that anymore. It’s officially showtime for machine learning to demonstrate its capabilities in the world of cinema as known today. Data scientists are all set to explore our behavioural patterns and the ones of the movies to build sophisticated predictive systems for true movie fans.

A movie recommendation system, or a movie recommender system, is an ML-based approach to filtering or predicting the users’ film preferences based on their past choices and behaviour. It’s an advanced filtration mechanism that predicts the possible movie choices of the concerned user and their preferences towards a domain-specific item, aka movie.

I created this project as a class assignment. It's a content-based movie recommender system which recommends movies based on movies liked by the user.

Movies data was downloaded from Kaggle.

### Steps taken in creating the projects were as follows

1.  Import data from Kaggle.

2.  Perform analysis on data and clean it as you go.

3.  Perform feature extraction on movie data.

4.  Apply algorithms and find one which performs best.

I used cosine similarity to find movies which are similar to each other.

You can check the project on [Github](https://github.com/astrovishalthakur/Mov-Rec-Sys-Advanced).
