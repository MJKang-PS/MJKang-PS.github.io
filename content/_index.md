---
# Leave the homepage title empty to use the site title
title:
date: 2023-06-08
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin
    design:
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Get in touch:
      # Contact (add or remove contact options as necessary)
      email: rkdals54321@snu.ac.kr
      appointment_url: 'https://fantastical.app/cwimpy-yBqk/schedule'
      address:
        street: PO Box 1750
        city: State University
        region: AR
        postcode: '72467'
        country: United States
        country_code: US
      office_hours:
        - By appointment only
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Follow Me
          link: 'https://twitter.com/camwimpy'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://astatecall.zoom.us/my/cwimpy'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
