---
title: Pricing
slug: pricing
sections:
  - title:
      text: Flexible Pricing made for all
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: >-
      Plans made to suit all, if you are an individual and want something more
      tailored for you, you can always contact us.
    plans:
      - title: Lite
        price: '£2,50'
        details: per month
        description: |
          Online private storage for those who need it.
        features:
          - 100 GB of SSD Storage
          - 600 Mbps Bandwidth allocation (May be slowed during peak hours)
          - AES-256 Encryption on all files
          - Basic Support
          - Payment via Card or Mailed in Cash
          - Students get 20 % off
          - One time drive as an option
        image:
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
          type: ImageBlock
        actions:
          - label: Purchase
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
      - title: Pro
        price: £10
        details: per month
        description: |
          Online private storage, for those who really like storage?
        features:
          - 1 TB of SSD Storage
          - Additional 3 TB for an additional £14 per month (Up to 10 TB)
          - '1,2 Gig Bandwidth allocation'
          - AES-256 Encryption on all files
          - Pro Support
          - Share storage with 2 other users
          - Payment via Card or Mailed in Cash
          - Students get 20 % off
        image:
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
          type: ImageBlock
        actions:
          - label: ''
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
      - title: Indivuduals & Businesses
        price: Contact Us
        details: ''
        description: >

          Online storage for Indivudals and Businesses, who need specific
          demands.
        features:
          - Choice of the amount of storage
          - 'Choice of network allocation (1,2 Gig, 2,4 Gig, 5 Gig)'
          - AES-256 Encryption on all files
          - Pro Support
          - Choice of the amount of users
          - Admin dashboard (For Businesses/Enterprises)
          - Payment only via Card
          - Email hosting available with a custom domain
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
