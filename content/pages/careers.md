---
title: Careers
slug: careers
sections:
  - title:
      text: Careers at Light Up Playhouse
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Be Part of Something Bright ✨
    text: >
      Are you passionate about early childhood development, playful learning,
      and making a difference in young lives? Join our growing team of
      educators, therapists, and support staff who light up every child’s
      world—one day at a time.
    actions:
      - label: See open positions
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - title:
      text: Meet the team
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedPeopleSection
  - title:
      text: Open Positions
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: >-
      Are you passionate about early childhood development, playful learning,
      and making a difference in young lives? Join our growing team of
      educators, therapists, and support staff who light up every child’s
      world—one day at a time.
    items:
      - title: SPED Teacher
        subtitle: Full Time
        text: >
          Create meaningful learning moments through structured play and
          personalized instruction. Help children thrive in a supportive,
          inclusive environment where every small win is celebrated.
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: Shadow Teacher
        subtitle: Part-time
        text: >
          Support our learners during classes and free play. Be a guiding
          presence for children who need a bit more help navigating their day,
          while learning alongside experienced educators and/or therapists.
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: Speech Pathologist
        subtitle: Consultant
        text: >
          Provide communication-focused intervention in a fun, play-based
          setting. Join our team as a valued consultant to support children in
          reaching their speech and language goals.
        colors: bg-neutral-fg-dark
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
      - type: FeaturedItem
        title: Occupational Therapist
        tagline: ''
        subtitle: Consultant
        text: >
          Support children’s growth in sensory processing, fine motor skills,
          and daily routines. As a consultant OT, you'll work in a collaborative
          and child-led environment that values development through play.
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions:
      - label: Apply now
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
