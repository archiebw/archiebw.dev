---
title: home
description: Home page
date: 2020-01-26T04:15:05+09:00
draft: false
# updatesBanner: "Banner - &nbsp; [Hugo ZDoc theme](https://github.com/archiebw/archiebw.dev) &nbsp; just arrived"
landing:
  height: 500
  image: favicon/android-icon-192x192.png
  title:
    - archiebw
  text:
    - This is my site for all things code
  titleColor:
  textColor:
  spaceBetweenTitleText: 25
  buttons:
    - link: snippets
      text: Snippets
      color: primary
footer:
  sections:
    - title: General
      links:
        - title: Snippets
          link: ./snippets
        - title: Posts
          link: ./posts
    - title: Social
      links:
        - title: GitHub
          link: https://github.com/archiebw
        - title: LinkedIn
          link: https://www.linkedin.com/in/archie-brand-williamson-791ba9123
  contents: 
    align: left
    applySinglePageCss: false
    markdown:
      |
      ## Zzo docs
      Copyright © 2020. All rights reserved.

sections:
  - bgcolor: teal
    type: card
    description: 
    header: 
      title: About me
      hlcolor: "#8bc34a"
      color: '#fff'
      fontSize: 32
      width: 220
    cards:
      - subtitle: Performance
        subtitlePosition: center
        description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id eleifend erat. Integer eget mattis augue."
        image: images/section/keyboard.png
        color: white
        button: 
          name: Naver
          link: https://gohugo.io/
          size: large
          target: _blank
          color: 'white'
          bgcolor: '#283593'
      - subtitle: Reliability
        subtitlePosition: center
        description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id eleifend erat. Integer eget mattis augue. Suspendisse semper laoreet tortor sed convallis. Nulla ac euismod lorem"
        image: images/section/processor.png
        color: white
        button: 
          name: Google
          link: https://gohugo.io/
          size: large
          target: _blank
          color: 'white'
          bgcolor: '#283593'
      - subtitle: Productivity
        subtitlePosition: center
        description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id eleifend erat. Integer eget mattis augue. Suspendisse semper laoreet tortor sed convallis. Nulla ac euismod lorem"
        image: images/section/root-server.png
        color: white
        button: 
          name: Yahoo
          link: https://gohugo.io/
          size: large
          target: _blank
          color: 'white'
          bgcolor: '#283593'
  - bgcolor: DarkSlateBlue
    type: normal
    description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id eleifend erat. Integer eget mattis augue. Suspendisse semper laoreet tortor sed convallis. Nulla ac euismod lorem"
    header:
      title: Build it with Zdoc
      hlcolor: DarkKhaki
      color: "#fff"
      fontSize: 32
      width: 340
    body:
      subtitle: Extensible and customizable.
      subtitlePosition: left
      description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id eleifend erat. Integer eget mattis augue. Suspendisse semper laoreet tortor sed convallis. Nulla ac euismod lorem"
      color: white
      image: images/section/root-server.png
      imagePosition: left
---
