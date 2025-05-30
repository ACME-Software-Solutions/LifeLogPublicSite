---
layout: blocks
title: Home
date: 2017-11-22T23:00:00.000+00:00
page_sections:
  - template: navigation-header-w-button
    block: header-2
    logo: "/uploads/images/logo.png"
    site_title: FLOGGER
    navigation:
      - link: "#voice-and-wearables"
        link_text: "Use Your Voice"
      - link: "#built-in-public"
        link_text: "Built in Public"
      - link: "#features"
        link_text: "Features"
  
  - template: hero-banner-w-image
    block: hero-2  
    media_alignment: Right
    slug: features
    headline_super: Building
    headline: <strong>Flogger</strong>
    subtitle: <i>A minimalist and unobtrusive life improvement tool.</i>
    content_file: content/hero-content.md
    cta:
      enabled: true
      url: "/blog/"
      button_text: "Read the Dev Blog"
    image:
      image: "/uploads/images/main-product-image.png"
      alt_text: Product Shot
    background_image: ""
  
  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: voice-and-wearables
    headline:
      <span class="light">Voice and Wearables:&nbsp;</span><strong>First-Class Citizens</strong>
    content_file: content/voice-and-wearables.md
    media:
      image: "/uploads/images/voice-mobile-first.png"
      alt_text: Frog speaking to a smart watch
  
  - template: content-feature
    block: feature-1
    media_alignment: Right
    slug: features
    headline:
      <span class="light">Know Thyself:&nbsp;</span><strong>Actionable Insights, not Gamification</strong>
    content_file: content/know-thyself.md
    media:
      image: "/uploads/images/know-thyself.png"
      alt_text: Frogs doing self improvement stuff
  
  - template: 1-column-text
    block: one-column-1
    slug: built-in-public
    headline: Built in Public
    background_image: "/uploads/images/build-in-public.png"
    content_file: content/build-in-public.md

  - template: cta-bar
    block: cta-bar
    headline: Get notified
    content_file: content/receive-updates.md
  
  - template: simple-footer
    block: footer-1
    links:
      - icon: "/uploads/images/youtube.svg"
        url: "https://www.youtube.com/@BuildingFlogger"
        alt_text: "youtube"
      - icon: "/uploads/images/github.svg"
        url: "https://github.com/adamking0126"
        alt_text: "github"
      - icon: "/uploads/images/substack.png"
        url: "https://adamking0126.substack.com/"
        alt_text: "substack"
      - icon: "/uploads/images/linkedin.png"
        url: "https://www.linkedin.com/in/adamking0126/"
        alt_text: "linkedin"
      - icon: "/uploads/images/reddit.svg"
        url: "https://www.reddit.com/user/adamking0126/"
        alt_text: "reddit" 
---
