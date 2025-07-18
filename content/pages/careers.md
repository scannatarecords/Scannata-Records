---
title: Careers
slug: careers
sections:
  - title:
      text: A team that works closely together
      color: text-dark
      styles:
        self:
          textAlign: center
          fontWeight: 700
      type: TitleBlock
    subtitle: At Scannata we value teamwork
    text: >
      Scannata Records believes in an honest team that is determined to grow and
      expand Scannata as not only a team, but as a family.
    actions:
      - label: See open positions
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
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
        fontStyle: italic
        textDecoration: underline
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
  - title:
      text: Meet the team
      color: text-dark
      styles:
        self:
          textAlign: center
          fontWeight: 700
      type: TitleBlock
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
    variant: three-col-grid
    colors: bg-neutral-fg-dark
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
      text: Open positions
      color: text-dark
      styles:
        self:
          textAlign: center
          fontWeight: 700
      type: TitleBlock
    subtitle: Looking for a job? Apply for one at Scannata Records!
    items:
      - title: Accountant
        subtitle: Federal Taxes
        text: >+
          Are you an experienced accountant (5+ years), then we would love to
          welcome you on our team!




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
      - title: Open Source Engineer
        subtitle: Marketing
        text: >+
          Are you a passionate marketeer and have finished college with atleast
          9 months experience? Scannata Records would love to have you on the
          team!

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
      - title: Software Engineer
        subtitle: Engineering
        text: >+
          Are you done with college and have 2+ years of experience with
          developing software, then apply for this amazing position @ Scannata
          Records.




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
    actions:
      - label: Apply now
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
    variant: three-col-grid
    colors: bg-neutral-fg-dark
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
