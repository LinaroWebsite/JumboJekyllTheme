---
title: Get your flow on!
layout: flow
permalink: /flow/
description: >
    This page showcases the power of the flow.html Jekyll include provided in this theme.
keywords: flow, jekyll, automation, simple, bootstrap 3
jumbotron:
    title: Get your flow on!
    background-image: /assets/images/content/background-image1.jpg
flow:
    - row: container_row
    #   style: dark
      sections:
        - format: title
          size: h2
          content: Members Section Example
        - format: text
          content: >
                Linaro Connect Bangkok 2019 will be the 25th Connect since Linaro started in June 2010. Hundreds of the world’s best Linux on Arm developers come to Linaro Connect each time because they know it is the leading place to meet with the global community and to learn about what is going on in the industry. Sponsorship of the event puts your brand in front of all the event attendees – both the 400+ on-site and all those who participate remotely, as well as the thousands who view the website and social media before, during and after the [event](https://connect.linaro.org).
        - format: members
          #data_source: members-section-example
          style: zoom
          item_width: 3 #bootstrap col-sm- value e.g 3, 4, 5ths etc
          content:
              - name: Arm
                image:
                    path: https://connect.linaro.org/assets/images/sponsors/arm.jpg
                    alt: Arm Logo
                url: https://github.com/linaro-marketing/jumbo-jekyll-theme
              - name: Packet
                image:
                    path: https://connect.linaro.org/assets/images/sponsors/packet.png
                    alt: Packet Logo
                url: https://github.com/linaro-marketing/jumbo-jekyll-theme
              - name: Qualcomm Logo
                image:
                    path: https://connect.linaro.org/assets/images/sponsors/qualcomm.jpg
                    alt: Qualcomm Logo Logo
                url: https://github.com/linaro-marketing/jumbo-jekyll-theme
              - name: Cannonical
                image:
                    path: https://connect.linaro.org/assets/images/sponsors/canonical.png
                    alt: Cannonical Logo
                url: https://github.com/linaro-marketing/jumbo-jekyll-theme
        - format: buttons
          style: text-center
          content:
              - title: More Details
                url: /about/
                icon: fa fa-arrow-right
                style: btn-primary
    - row: container_row
      style: fixed
      background_image: /assets/images/content/background-image1.jpg
      sections:
        - format: title
          size: h2
          content: Members Section Example
        - format: buttons
          style: text-center
          content:
              - title: More Details
                url: /about/
                icon: fa fa-arrow-right
                style: btn-primary
    - row: container_row
      style: block_row
    #   background_image: /assets/images/content/background-image1.jpg
      sections:
        - format: title
          size: h2
          content: Block Row
        - format: block
          style: text-center text-white
          item_width: 4
          content:
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
                    - title: Read
                      url: /flow/
                      icon: fa fa-book
                      style: btn-primary
    - row: container_row
      style: block_row fixed
    #   background_image: /assets/images/content/background-image1.jpg
      sections:
        - format: block
          style: text-center text-white
          item_width: 3
          content:
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
                    - title: Read
                      url: /flow/
                      icon: fa fa-book
                      style: btn-primary
    - row: container_row
      #style: fixed
      background_image: /assets/images/content/background-image1.jpg
      sections:
        - format: title
          size: h2
          content: Custom Include Section
        - format: custom
          include_name: custom_include.html
    - row: full_width_row
      style: fixed block_row
      sections:
        - format: title
          content: Full Width Block Row
          size: h2
        - format: block
          style: text-center text-white
          item_width: 3
          content:
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
              - title:
                    size: h3
                    content: Members Section Example
                url: /about/
                background_image: /assets/images/content/background-image1.jpg
                text:
                    content: >
                        See our photos from Connect.
                buttons:
                    - title: More Details
                      url: /flow/
                      icon: fa fa-arrow-right
                      style: btn-primary
                    - title: Read
                      url: /flow/
                      icon: fa fa-book
                      style: btn-primary
    - row: full_width_row
      #style: new
      sections:
        - format: title
          content: Feature Block Row (Full Width)
          size: h2
        - format: feature_block
        #   style: text-center text-white
          content:
            side_content:
                position: left
                type: youtube_video
                content:
                    url: https://www.youtube.com/watch?v=iNMhpvHCXRU
            title: Featured Block
            text: page_content
            text: >
                The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.
            buttons:
                - title: Button 1
                  url: /about/
                  style: btn-primary
                - title: Button 2
                  url: /about/
                  style: btn-primary
        - format: feature_block
        #   style: text-center text-white
          content:
            side_content:
                position: right
                type: image
                # type: video
                # type: slider
                content: /assets/images/content/background-image1.jpg
            title: Featured Block
            text: page_content
            text: >
                The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.
            buttons:
                - title: Button 1
                  url: /about/
                  style: btn-primary
                - title: Button 2
                  url: /about/
                  style: btn-primary
    - row: container_row
      #style: new
      sections:
        - format: title
          content: Feature Block Row
          size: h2
        - format: feature_block
        #   style: text-center text-white
          content:
            side_content:
                position: left
                # type: image
                # type: video
                # type: slider
                type: slider
                content:
                    lightbox_enabled: true
                    seconds_per_slide: 5
                    nav: true
                    dots: false
                    xs_items: 1
                    sm_items: 1
                    md_items: 1
                    lg_items: 1
                    items:
                        - image: /assets/images/content/background-image1.jpg
                          alt: Background Image
                          title: Background Image 1
                        - image: /assets/images/content/background-image2.png
                          alt: Background Image
                          title: Background Image 1
                        - image: /assets/images/content/background-image3.jpg
                          alt: Background Image
                          title: Background Image 1
                        - image: /assets/images/content/background-image1.jpg
                          alt: Background Image
                          title: Background Image 1
                        - image: /assets/images/content/background-image2.png
                          alt: Background Image
                          title: Background Image 1
                        - image: /assets/images/content/background-image3.jpg
                          alt: Background Image
                          title: Background Image 1
                        - image: /assets/images/content/background-image1.jpg
                          alt: Background Image
                          title: Background Image 1
                        - image: /assets/images/content/background-image2.png
                          alt: Background Image
                          title: Background Image 1
                        - image: /assets/images/content/background-image3.jpg
                          alt: Background Image
                          title: Background Image 1
            title: Featured Block
            text: page_content
            text: >
                The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.
            buttons:
                - title: Button 1
                  url: /about/
                  style: btn-primary
                - title: Button 2
                  url: /about/
                  style: btn-primary
        - format: feature_block
        #   style: text-center text-white
          content:
            side_content:
                position: right
                type: image
                # type: video
                # type: slider
                content: /assets/images/content/background-image1.jpg
            title: Featured Block
            text: page_content
            text: >
                The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.
            buttons:
                - title: Button 1
                  url: /about/
                  style: btn-primary
                - title: Button 2
                  url: /about/
                  style: btn-primary
        - format: feature_block
        #   style: text-center text-white
          content:
            side_content:
                position: left
                type: youtube_video
                content:
                    url: https://www.youtube.com/watch?v=iNMhpvHCXRU
            title: Featured Block (with youtube video)
            text: page_content
            text: >
                The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.
            buttons:
                - title: Button 1
                  url: /about/
                  style: btn-primary
                - title: Button 2
                  url: /about/
                  style: btn-primary
    - row: container_row
      #style: new
      sections:
        - format: title
          content: Slider Row Example
          size: h2
        - format: slider
          style: customCSS
          lightbox_enabled: true
          seconds_per_slide: 5
          nav: true
          dots: false
          xs_items: 1
          sm_items: 2
          md_items: 4
          lg_items: 6
          items:
            - image: /assets/images/content/background-image1.jpg
              alt: Background Image
              title: Background Image 1
            - image: /assets/images/content/background-image2.png
              alt: Background Image
              title: Background Image 1
            - image: /assets/images/content/background-image3.jpg
              alt: Background Image
              title: Background Image 1
            - image: /assets/images/content/background-image1.jpg
              alt: Background Image
              title: Background Image 1
            - image: /assets/images/content/background-image2.png
              alt: Background Image
              title: Background Image 1
            - image: /assets/images/content/background-image3.jpg
              alt: Background Image
              title: Background Image 1
            - image: /assets/images/content/background-image1.jpg
              alt: Background Image
              title: Background Image 1
            - image: /assets/images/content/background-image2.png
              alt: Background Image
              title: Background Image 1
            - image: /assets/images/content/background-image3.jpg
              alt: Background Image
              title: Background Image 1
    - row: full_width_row
      #style: new
      sections:
        - format: title
          content: Slider Row Example (Full Width)
          size: h2
        - format: text
          style: text-center
          content: >
            Some block of text to describe something about such and such...
        - format: slider
          style: customCSS
          lightbox_enabled: true
          seconds_per_slide: 5
          nav: true
          dots: false
          xs_items: 1
          sm_items: 3
          md_items: 6
          lg_items: 9
          data_source: example-carousel-data-source
    - row: custom_include_row
      source: custom_include_row.html
---
Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of styleical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in styleical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.

The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.
