---
title: Blog
slug: /blog
numOfPostsPerPage: 12
enableSearch: true
topSections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic section with a video
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: Section with a video subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: VideoBlock
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
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - title:
      text: Featured Post
      color: text-dark
      type: TitleBlock
    subtitle: This is the subtitle
    posts:
      - content/pages/blog/top-ten-lessons-we-learned.md
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    variant: big-list
    colors: bg-light-fg-dark
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
    actions: []
styles:
  title:
    textAlign: center
seo:
  metaTitle: Blog - Demo site
  metaDescription: >-
    This is the blog of the demo site where we post about technology, product,
    and design.
  socialImage: /images/img-placeholder.svg
  type: Seo
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
  colors: bg-light-fg-dark
  hoverEffect: move-up
---
