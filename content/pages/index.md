---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Allow yourself to feel at ease knowing your data is safe
      color: text-dark
      type: TitleBlock
    subtitle: with 256-Encryption as standard
    text: >
      In addition to that, we do not use your data to train AI (unlike otherrrr
      provider services <*cough* Microsoft*>*, we as a team are not fond of AI,
      so you will not even see one bit of AI anywhere on this site.
    actions:
      - label: Pricing
        altText: ''
        url: /pricing
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Privacy
        altText: ''
        url: /privacy
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Making cloud storage private
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
  - type: FeaturedItemsSection
    title:
      text: 'What we offer:'
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Access to two Networks
        subtitle: ''
        text: >
          Access to the vodafone UK and EE network, allowing you to switch
          manually between both networks.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: Eco-friendly
        subtitle: for the planet
        text: >
          Running on 100 % renewable electricty, using second hand parts or
          refurbished parts before buying new components, giving a second chance
          for components.
        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Super Private
        subtitle: with one time cloud
        text: >
          Create a one time cloud drive. We will not collect your: email
          address, IPs, passwords. You will log in with a 24 character
          automatically generated key and that will be your log in.
        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: Pricing
        altText: ''
        url: /pricing
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - type: Button
        label: What else we offer & our claims
        altText: ''
        url: /claims
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      text: Individuals have a choice
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: Plans don't suit you? Create your own
    text: >
      You can contact us and create your own plan, you will have to contact us
      and this isn't an instant process. 
    actions:
      - type: Button
        label: Create your own plan
        altText: ''
        url: /contact
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
    elementId: null
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - title:
      text: Discount
      color: text-dark
      type: TitleBlock
    subtitle: Students get 20 % off on all plans.
    text: >
      With multiple ways to verify! Verification is manual so this process may
      take some time.
    actions:
      - label: Pricing
        url: /pricing
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: Privacy
        url: /privacy
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero3.svg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: Student
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Questions or want to create your own plan?
      color: text-dark
      type: TitleBlock
    subtitle: You can contact us here
    text: >
      We will try our best to get back to you within 1 - 4 business days. If you
      have any questions, then ask away. If you want to create your own plan,
      please specifiy: Amount of storage you want, Bandwidth allocation and
      anything else that may be relevant.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
        - type: CheckboxFormControl
          name: I agree for my data to be processed by Svara
          label: >-
            I agree for my data to be processed by Svara, your data will be
            stored internally and won't be shared outside of the organisation.
          isRequired: true
          width: full
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Svara
  metaDescription: Svara UK offering multiple services with privacy in mind.
  socialImage: /images/abstract-feature1.svg
  type: Seo
type: PageLayout
---
