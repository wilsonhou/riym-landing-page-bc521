---
title: Home
sections:
  - type: hero_section
    title: Welcome to DIYJam Podcast
    subtitle: Optional hero section subtitle
    content: >-
      A podcast for Web developers interested in building Jamstack websites.
      Hosted by Miles Tone.
    actions:
      - label: Subscribe to Podcast
        url: /thank-you
        style: primary
    image: /images/Right In Your Mind.png
    image_alt: Hero section placeholder image
    media_position: left
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/hero-background.jpg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 20
    has_border: true
  - type: blog_feed_section
    title: Latest Episodes
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 6
    show_image: true
    show_date: true
    show_categories: false
    show_author: false
    show_excerpt: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: none
    background_image: images/pattern.svg
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 98
  - type: grid_section
    title: Subscribe
    grid_items:
      - title: Apple Podcasts
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: /thank-you
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-1.svg
        image_alt: Apple Podcasts icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: Spotify
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: /thank-you
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-2.svg
        image_alt: Spotify icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: Overcast
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: /thank-you
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-3.svg
        image_alt: Overcast icon
        image_position: top
        image_align: center
        image_has_padding: true
    grid_cols: three
    grid_gap_horiz: medium
    grid_gap_vert: medium
    enable_cards: false
    align: center
    padding_top: large
    padding_bottom: large
    has_border: true
    background_color: secondary
    background_image: images/subscribe-background.jpg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 10
  - type: grid_section
    title: Partners
    subtitle: 2021 Supporters
    align: center
    grid_items:
      - image: images/logo-1.svg
        image_alt: Stackbit logo
        image_align: center
      - image: images/logo-2.svg
        image_alt: Netlify logo
        image_align: center
      - image: images/logo-3.svg
        image_alt: Sticker Mule logo
        image_align: center
      - image: images/logo-4.svg
        image_alt: GitHub logo
        image_align: center
      - image: images/logo-5.svg
        image_alt: Gatsby logo
        image_align: center
      - image: images/logo-6.svg
        image_alt: Twilio logo
        image_align: center
      - image: images/logo-7.svg
        image_alt: Contentful logo
        image_align: center
      - image: images/logo-8.svg
        image_alt: Forestry logo
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
    has_border: true
    background_color: none
  - type: form_section
    content: >-
      ## Ask A Question

      I'm OK with any kind of questions and will answer as many as I possibly
      can.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
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
        label: Question
        default_value: Your question
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Submit
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: none
    background_image: images/pattern.svg
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 98
seo:
  title: Right In Your Mind
  description: >-
    Right In Your Mind is a podcast exploring lessons learnt from changemakers
    in mental health - including researchers, experts, founders and investors.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Right In Your Mind
      keyName: property
    - name: 'og:image'
      value: /images/Right In Your Mind-b459e7ca.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Right In Your Mind
    - name: 'twitter:description'
      value: >-
        Right In Your Mind is a podcast exploring lessons learnt from
        changemakers in mental health - including researchers, experts, founders
        and investors.
    - name: 'twitter:image'
      value: /images/Right In Your Mind-d636ac15.png
      relativeUrl: true
    - name: 'og:description'
      value: >-
        Right In Your Mind is a podcast exploring lessons learnt from
        changemakers in mental health - including researchers, experts, founders
        and investors.
      keyName: property
      relativeUrl: false
layout: advanced
---
