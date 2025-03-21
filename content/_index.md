---
# Leave the homepage title empty to use the site title
title:
date: 2024-01-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Database & Internet Privacy
      image:
        filename: dipr_lab.jpg
        # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/a-small-bird-sitting-on-a-branch-in-the-water-3Jykr2JSpRs)'
        # focal_point: Bottom
      text: |
        <br>
        
        The **Database & Internet PRivacy - DIPr** (pronounced as [Dipper](https://en.wikipedia.org/wiki/Big_Dipper) or [Dipper](https://www.allaboutbirds.org/guide/American_Dipper/overview)) Lab at Portland State University studies privacy challenges within data management and Internet technologies. 
  
  # - block: features
  #   content:
  #     title: Research Themes
  #     # subtitle: Section subtitle
  #     # text: Section text
  #     items:
  #       - name: Data Management 
  #         # description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Location Privacy
  #         # description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Privacy Regulations & Policies
  #         # description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  #       - name: Access Control
  #         # description: 10%
  #         icon: lock-closed
  #         icon_pack: fas
  #       - name: Inference Control
  #         # description: 10%
  #         icon: se
  #         icon_pack: fas


  - block: collection
    id: section-1
    content:
      title: Lab Projects
      subtitle: 
      text: 
      count: 10
      # Display content from the `content/post/` folder
      filters:
        folders:
          - project
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true

  - block: collection
    id: section-2
    content:
      title: Latest News
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'


  # - block: slider
  #   content:
  #     slides:
  #     - title: 👋 Welcome to the group
  #       content: Take a look at what we're working on...
  #       align: center
  #       background:
  #         image:
  #           filename: dipr_lab.jpg
  #           filters:
  #             brightness: 0.7
  #         position: right
  #         color: '#666'
  #     - title: Lunch & Learn ☕️
  #       content: 'Share your knowledge with the group and explore exciting new topics together!'
  #       align: left
  #       background:
  #         image:
  #           filename: contact.jpg
  #           filters:
  #             brightness: 0.7
  #         position: center
  #         color: '#555'
  #     - title: World-Class Semiconductor Lab
  #       content: 'Just opened last month!'
  #       align: right
  #       background:
  #         image:
  #           filename: contact.jpg
  #           filters:
  #             brightness: 0.5
  #         position: center
  #         color: '#333'
  #       link:
  #         icon: graduation-cap
  #         icon_pack: fas
  #         text: Join Us
  #         url: ../contact/
  #   design:
  #     # Slide height is automatic unless you force a specific height (e.g. '400px')
  #     slide_height: ''
  #     is_fullscreen: true
  #     # Automatically transition through slides?
  #     loop: false
  #     # Duration of transition between slides (in ms)
  #     interval: 2000

  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Interested in joining the group? →" %}}
  #   design:
  #     columns: '1'
---
