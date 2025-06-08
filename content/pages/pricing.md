---
title: Pricing
slug: pricing
sections:
  - title:
      text: Flexible Pricing
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: This is the subtitle for the pricing section
    plans:
      - title: Basic
        price: £5
        details: per month
        description: |
          Online private storage for those who need it.
        features:
          - 500 GB of SSD Storage
          - 1 Gig Bandwidth allocation (May be slowed during peak hours)
          - AES-256 Encryption on all files
          - Basic Support
          - Payment via Card or Mailed in Cash
          - Students get 20 % off
        image:
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
          type: ImageBlock
        actions:
          - label: Free for 1 month
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
          - 2 TB of SSD Storage
          - Additional 2 TB for an additional £5 per month
          - 5 Gig Bandwidth allocation
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
          - label: Free for 1 month
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
        description: |
          Online storage for Enterprises.
        features:
          - Choice of the amount of storage
          - Choice of network allocation (Automatically set to 5 Gig)
          - AES-256 Encryption on all files
          - Pro Support
          - Choice of the amount of users
          - Admin dashboard
          - Payment only via Business Cards
          - ''
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
