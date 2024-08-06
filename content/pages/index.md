---
title: Home
slug: /
sections:
  - type: HeroSection
    title:
      text: Welcome to the News Portal
      color: text-dark
      type: TitleBlock
    subtitle: Your gateway to industry news
    text: >
      Log in to access the latest industry news and save articles for later.
    actions:
      - label: Log In
        altText: ''
        url: /api/auth/login
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: This is a badge
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: NewsSection
    title:
      text: Latest Industry News
      color: text-dark
      type: TitleBlock
    subtitle: Stay updated with the latest news
    items: []
    elementId: news-section
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
---
