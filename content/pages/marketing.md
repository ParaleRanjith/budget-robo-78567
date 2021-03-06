---
title: MARKETING
sections:
  - type: HeroSection
    colors: colors-h
    title: We’re growing fast
    text: You should join us.
    media:
      type: ImageBlock
      url: /images/hero-4.jpg
      caption: Team meeting
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      text:
        textAlign: center
      actions:
        justifyContent: flex-start
  - type: QuoteSection
    colors: colors-h
    quote: >
      # social media is the most effective and reliable platform to market my
      APP
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
  - type: MediaGallerySection
    colors: colors-a
    title: ''
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/careers.jpg
        caption: Meeting room
        altText: People in the meeting room
      - type: ImageBlock
        url: /images/post-2.jpg
        caption: Team meeting
        altText: Team meeting
    columns: 2
    spacing: 3
    imageSizePx: 400
    aspectRatio: '1:1'
    showCaption: false
    enableHover: false
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: JobsSection
    colors: colors-a
    title: OTHER MARKETING AREAS
    subtitle: ''
    jobLists:
      - type: JobList
        title: INFLUENCER MARKETING
        items:
          - type: JobListItem
            text: >
              Influencer marketing is the use of influencers to reach new users
              and promote your brand. Influencers can be employed in a variety
              of ways to help you reach your marketing objectives. You can
              either provide an influencer “freebie” to share with their
              audience or pay for product placement. A paid ad has the advantage
              of giving you greater creative control, whereas merely presenting
              your products to the right influencer is a cost-effective method
              to reach an audience.
            actions: []
          - type: JobListItem
            location: APP STORE OPTIMIZATION
            text: >
              It is the process of improving the apps visibility in the Apple
              store & Google Play store. It is an important step to do as the
              APP should be visible to the customer easily without having any
              trouble to find it in the play store. There is ton of applications
              available as of now and there is high chance that there may be
              applications with logo having resemblance to my APP
            actions: []
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: inset
    title: Not seeing the right role? Contact us
    text: >-
      We might have more roles soon, and we’ll contact you if we think there
      might be a good match
    form:
      type: FormBlock
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          placeholder: Your name
          isRequired: 'true'
          width: 1/2
        - type: EmailFormControl
          name: email
          placeholder: Your email
          isRequired: 'true'
          width: 1/2
        - type: TextFormControl
          name: address
          placeholder: Your home address
          isRequired: 'false'
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          isRequired: 'false'
          width: full
      submitLabel: Send Message
    media: null
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-36
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: center
      text:
        textAlign: center
layout: PageLayout
---
