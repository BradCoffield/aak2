---
title: Home
sections:
  - type: hero_section
    title: 'Hi, I’m Ashley.'
    subtitle: >-
      I'm a creative writing professor and freelance editor living in Billings, MT.
    actions:
      - label: Contact Me
        url: /contact
        style: primary
    image: images/hero.png
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: features_section
    title: My Work
    subtitle: What I do
    features:
      - title: Creative Writing
        # subtitle: 'Fiction, Poetry, and Creative Nonfiction.'
        content: >-
          Write some stuff here. Qui quis velit exercitation proident dolore in magna enim. Consectetur in excepteur pariatur aliqua duis. Nostrud minim qui dolor reprehenderit nisi id et laboris officia mollit adipisicing. 
        actions:
          - label: Explore My Writing
            url: /faq
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-1.svg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: Teaching &amp; Scholarship
        # subtitle: 'Product updates, inventory and pricing.'
        content: >-
             Write some stuff here. Qui quis velit exercitation proident dolore in magna enim. Consectetur in excepteur pariatur aliqua duis. Nostrud minim qui dolor reprehenderit nisi id et laboris officia mollit adipisicing. 
        actions:
          - label: Learn More
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-2.svg
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - title: Editing Services
        # subtitle: 'Your products and services, at scale.'
        content: >-
         Write some stuff here. Qui quis velit exercitation proident dolore in magna enim. Consectetur in excepteur pariatur aliqua duis. Nostrud minim qui dolor reprehenderit nisi id et laboris officia mollit adipisicing. 
        actions:
          - label: See Past Work
            url: /Learn More
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-3.svg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
       
  - type: form_section
    content: >-
      ## Let's talk


      If you would like more information about my services and pricing, please
      contact me using the form below.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  
    
seo:
  title: Ashley Kunsa, Ph.D.
  description: Homepage for Ashley Kunsa, Ph.D.  that shares her creative writing, academic work, and editing services.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Ashley Kunsa, Ph.D.
      keyName: property
    - name: 'og:description'
      value: Homepage for Ashley Kunsa, Ph.D.  that shares her creative writing, academic work, and editing services.
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Ashley Kunsa, Ph.D.
    - name: 'twitter:description'
      value: Homepage for Ashley Kunsa, Ph.D.  that shares her creative writing, academic work, and editing services.
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
