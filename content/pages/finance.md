---
title: FINANCE
sections:
  - type: HeroSection
    colors: colors-h
    title: INVESTMENT
    text: |
      .
    media:
      type: ImageBlock
      url: /images/header_robotic_automation-1024x576.jpg
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
      The biggest task is investment. To produce such sophisticated advanced
      robots, it is important to have highly efficient production machines which
      can all together produce such ROBOTS.T here are several big ventures who
      has already have big names in the market producing ROBOTS. This can be a
      barrier as our venture is a new venture and it takes time to get accepted
      by the customers. First stage of the production and sales is going to be
      tough. Convincing the people to try the service is going to be challenging
      as it’s a new trend and people might not accept it at the first place.
      Having a very talented and skilled sales and marketing team is going to
      play a major role in the first stage development.
    title: CEO
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
