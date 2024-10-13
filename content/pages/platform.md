---
title: Platform
slug: platform
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: My Platform
      color: text-dark
      styles:
        self:
          fontWeight: 700
    subtitle: for Ward 5 Fredericton City Council.
    text: >
      I will be visiting door to door throughout 2024 to learn about your needs
      and desires for Marysville and Fredericton in general. This will help me
      to focus on what matters most to you. I intend to follow up in 2025 and
      2026 with additional outreach and surveys to make sure I am on track and
      stay aligned with community needs.


      If elected, I will continue to listen and stay on course to support all of
      Ward 5 and Fredericton.
    actions:
      - type: Button
        label: Schedule a Meeting
        altText: ''
        url: 'https://calendly.com/jacobcloutier/30min'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Link
        label: Feedback Survey
        altText: 'Ward 5: Marysville Feedback Survey'
        url: >-
          https://docs.google.com/forms/d/e/1FAIpQLScpOHV8b15clE_aoBj7Jo_BqqpUWUu49Uhgg27mJFD16yPQOw/viewform
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
        padding:
          - pt-9
          - pl-6
          - pb-9
          - pr-6
      subtitle:
        fontWeight: 700
      text:
        textAlign: left
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: bottom
      backgroundRepeat: no-repeat
      opacity: 41
      url: /images/TownHall.png
  - title:
      text: Flexible Pricing
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: This is the subtitle for the pricing section
    plans:
      - title: Developers
        price: Free
        details: No credit card required
        description: >-
          Sed ut perspiciatis unde omnis, iste natus error sit voluptatem
          accusantium doloremque.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
        image:
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
          type: ImageBlock
        actions:
          - label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: Professional
        price: $99
        details: per month
        description: >-
          Sed ut perspiciatis unde omnis, iste natus error sit voluptatem
          accusantium doloremque.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
        image:
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
          type: ImageBlock
        actions:
          - label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: Enterprise
        price: Custom
        details: per month
        description: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
          - Feature five
        image:
          url: /images/abstract-feature3.svg
          altText: Pricing plan 3
          type: ImageBlock
        actions:
          - label: Contact us
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: PricingSection
seo:
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
