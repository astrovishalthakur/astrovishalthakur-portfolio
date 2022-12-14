---
title: About
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-0
          - pb-4
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    colors: colors-d
    variant: variant-a
    title: About me
    text: "**Hello there! This is Vishal \U0001F64C\U0001F3FD**\n\nI'm a Data Science student based in India. So yeah, I'm a data nerd, and I like sharing knowledge about Data science skills, tech and stuff.\n\nIn my free time, I like watching vlogs and listening to audiobooks. I hope to pursue my masters in Deep Learning with computer vision in focus.\n\n***and yeah, I Love Cats!!!***\n\n\n\n"
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-32
          - pb-16
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: FeaturedPeopleSection
    colors: colors-d
    elementId: ''
    variant: variant-c
    actions: []
    people:
      - content/data/team/desmond-eagle.json
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-7
          - pb-7
          - pl-96
          - pr-0
        justifyContent: flex-end
        margin:
          - ml-36
          - mr-36
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
  - elementId: ''
    colors: colors-b
    quote: |-
      <p align="center">"I'm not smart, I'm just passionately curious."
      </p>
    backgroundImage:
      type: BackgroundImage
      url: /images/bg.webp
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 70
    styles:
      self:
        height: auto
        width: full
        margin:
          - mt-0
          - mb-6
          - ml-0
          - mr-0
        padding:
          - pt-96
          - pb-0
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: left
      name:
        fontWeight: '400'
        textAlign: left
      title:
        fontWeight: '400'
        textAlign: left
    type: QuoteSection
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: full
        padding:
          - pt-4
          - pb-4
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
---
