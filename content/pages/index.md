---
title: Home
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-d
    elementId: ''
    title: Divider
    styles:
      self:
        width: full
        padding:
          - pt-0
          - pb-1
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: HeroSection
    colors: colors-d
    elementId: ''
    title: 'Heya, I''m Vishal - a data science student in India.'
    subtitle: 'Data nerd, Learning, Creativity.'
    text: ''
    actions:
      - type: Button
        showIcon: true
        icon: arrowRight
        style: primary
        url: /blog
        label: Projects
      - type: Link
        altText: linked in
        url: 'https://www.linkedin.com/in/vishal-thakur-383838190/'
        showIcon: true
        icon: linkedin
        iconPosition: right
        elementId: ''
      - type: Link
        altText: github
        url: 'https://github.com/astrovishalthakur'
        showIcon: true
        icon: github
        iconPosition: left
        elementId: ''
    media:
      type: ImageBlock
      url: /images/IMG20210823111640.jpg
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-9
          - pb-9
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
        fontWeight: 400
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    backgroundSize: full
  - type: QuoteSection
    colors: colors-e
    quote: >+
      “Gentlemen, you need to put the armour plate where the bullet holes aren’t
      because that’s where the holes were on the planes that didn’t return.”

    name: Abraham Wald
    title: Hungarian Mathematician
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-9
          - pb-9
          - pr-4
          - pl-4
        justifyContent: center
        borderRadius: none
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
  - elementId: ''
    colors: colors-d
    variant: variant-a
    title: Recent Projects
    actions:
      - type: Link
        label: See all projects
        url: /blog
        showIcon: true
        icon: arrowRight
    posts:
      - content/pages/blog/movies-recommender-system.md
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeaturedPostsSection
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    readMoreLinkLabel: Join adventure
    showAuthor: false
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: full
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
metaTags: []
---
