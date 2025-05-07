---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Cryptography and Blockchain 
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        We are based at the Faculty of Mathematics, Informatics, and Mechanics of the University of Warsaw and IDEAS NCBR. We are mostly interested in the foundations of cryptography and data security, in particular in provably-secure leakage- and tamper-resilient cryptography, cryptographic countermeasures against malicious software attacks, blockchain, and smart contracts.  The group leader is Stefan Dziembowski. Our research and teaching have been supported by the European Research Council (ERC), the Foundation for Polish Science (FNP), the National Science Centre (NCN), the COST Actions, Intel, and Ethereum Foundation.  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
