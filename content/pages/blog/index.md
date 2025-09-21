---
title: Blog
slug: /blog
numOfPostsPerPage: 8
enableSearch: true
topSections:
  - title:
      text: Q&A
      color: text-dark
      type: TitleBlock
    subtitle: Questions and Answers
    posts:
      - content/pages/blog/top-ten-lessons-we-learned.md
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    variant: small-list
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-28
          - pb-0
          - pl-4
          - pr-4
        justifyContent: flex-start
    type: FeaturedPostsSection
    hoverEffect: move-up
  - type: CarouselSection
    subtitle: This is a subtitle
    items:
      - type: FeaturedItem
        title: >-
          “A designer knows he has achieved perfection not when there is nothing
          left to add, but when there is nothing left to take away.”
        tagline: Testimonial 1
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: >-
          “Quote from some important person goes right here. I love using
          Netlify.”
        tagline: Testimonial 2
        subtitle: 'Jane Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder-dark.png
          altText: Jane Doe
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
styles:
  title:
    textAlign: center
seo:
  metaTitle: Q&A - Scannata Records
  metaDescription: 'Scannata Records Q&A, Questions and Answers'
  socialImage: /images/Adobe Express - file (19).png
  type: Seo
  addTitleSuffix: true
type: PostFeedLayout
bottomSections: []
postFeed:
  type: PagedPostsSection
  title: null
  subtitle: null
  showThumbnail: true
  showExcerpt: true
  showDate: true
  showAuthor: true
  actions: []
  elementId: null
  variant: three-col-grid
  colors: bg-neutral-fg-dark
  hoverEffect: move-up
---
