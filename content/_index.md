---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        CV4DT
      image:
        filename: home.png
      text: |
        <br>
        
        The **Computer Vision for Digital Twins (CV4DT)** is a research group based at the [University of Cambridge](https://www.cam.ac.uk/) and led by [Olaf Wysocki](https://olafwysocki.github.io/). The CV4DT centres on developing methods and datasets for pushing the boundaries of 3D computer vision for accurate transfer of reality into the digital world to enable simulation before any action is taken. 
  - block: markdown
    content:
#      title: Latest News
      text: |
        <div style="column-count: 2; column-gap: 2rem;">
          <ul>
            <li><b>2026-01</b> — We'll be co-organsing 2x <a href="https://cvpr.thecvf.com/" target="_blank">CVPR 2026</a> workshops: <a href="https://pbvs-workshop.github.io/" target="_blank">PBVS</a> and <a href="https://drivex-workshop.github.io/cvpr2026/" target="_blank">DriveX</a>!</li>
            <li><b>2025-12</b> — 3x 3D Computer Vision and Robotics projects together with TUM (<a href="https://www.linkedin.com/posts/olaf-wysocki_tum-3dcomputervision-robotics-activity-7404455847042428929-F6wa?utm_source=share&utm_medium=member_desktop&rcm=ACoAACOtQZsB2yD5oTgXmH7yFLu2VpwKVxPJ19Q" target="_blank">more</a>)</li>
            <li><b>2025-11</b> — Brian gives a keynote about multimodality at <a href="https://www.linkedin.com/posts/brian-sheil-34940a28_super-excited-to-be-on-my-way-to-sheffield-activity-7399712763801018368-HNNN?utm_source=share&utm_medium=member_desktop&rcm=ACoAACOtQZsB2yD5oTgXmH7yFLu2VpwKVxPJ19Q" target="_blank">BMVC 2025</a>!.</li>
            <li><b>2025-10</b> — Our <a href="https://lnkd.in/dvrHQXaN" target="_blank">TrueCity</a> paper goes to <a href="https://3dvconf.github.io/2026/" target="_blank">3DV 2026</a>!</li>  
          </ul>
        </div>

        <details style="margin-top: 0.5rem;">
          <summary><b>Older news</b></summary>
          <div style="column-count: 2; column-gap: 2rem; margin-top: 0.4rem;">
            <ul>
              <li><b>2025-08</b> — The <a href="https://www.linkedin.com/posts/olaf-wysocki_cv4dt-cv4dt-computer-activity-7358059156118892544-IXFe?utm_source=share&utm_medium=member_desktop&rcm=ACoAACOtQZsB2yD5oTgXmH7yFLu2VpwKVxPJ19Q" target="_blank">CV4DT</a> is born!</li>
            </ul>
          </div>
        </details>
    design:
      columns: '1'
      background:
        color: '#ffffff'
        text_color_light: false
      spacing:
        padding: ['0.5rem', '0', '0.1rem', '0']



  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the CV4DT world
        content: 'Check out our research focus...'
        align: center
        background:
          image:
            filename: zahaAnimated.gif
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
      - title: 3D Semantic Understanding
        content: '3D scene understanding with imbalanced data'
        align: left
        background:
          image:
            filename: zahaAnimated.gif
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 3D Semantic Object Reconstruction
        content: 'Reconstructing high-detail semantic 3D models'
        align: left
        background:
          image:
            filename: relod3.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: 3D Models as Novel Modality
        content: 'High-detail structured 3D models as new sensor signal'
        align: left
        background:
          image:
            filename: pose.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2200

  - block: collection
    content:
      title: Latest Papers
      text: ""
      count: 5
      filters:
        folders:
          - publication
   #       publication_type: 'article'
    design:
      view: citation
      columns: '1'

#  - block: markdown
#    content:
#      title:
#      subtitle:
#      text: |
#        {{% cta cta_link="./contact/" cta_text="Contact us →" %}}
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: ingolstadt.jpg
#          filters:
#            brightness: 0.5
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['200px', '0', '2px', '0']
#      css_class: fullscreen
---
