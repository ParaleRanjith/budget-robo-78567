---
title: STRATEGIES
sections:
  - type: QuoteSection
    colors: colors-h
    quote: >
      Through our new venture BUDGET ROBO-APP, we can help people to find the
      suitable ROBOTS for rent from the market without any hassle to use for a
      day-to-day life without thinking about buying the robot by paying a whole
      lot of money. Our APP will be designed to help people to find Robots
      according to their needs and the robots will be delivered to the customer.
      In addition, all the robots will be connected to our Budget ROBO-APP, to
      help the people to use them with ease. In the initial stages, only a
      limited access will be given to the customer with a preference to old,
      aged people. In coming 5 years, with the help of customer feedback and
      reports, we make the robots more and more advanced and will be provided to
      more and more people. Making the venture one of the top ROBO-APP in the
      world. The robots can help the people for grocery purchase, gardening,
      driving, cooking and so on.
    name: RANJITH
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
