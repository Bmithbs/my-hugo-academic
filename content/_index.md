---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 🌏 Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news
    content:
      title: 🔥 Latest News
      text: |-
        - **[Nov. 2023]** The paper <a href='publication/dg-coperception'>*Towards Full-scene Domain Generalization in Multi-agent Collaborative Bird's Eye View Segmentation for Connected and Autonomous Driving*</a> was submitted to IEEE Transactions on Intelligent Transportation Systems (**TITS**).
        - **[Oct. 2023]** The paper <a href='publication/pacs'>*PACS: Priority-Aware Collaborative Sensing for Connected and Autonomous Vehicles*</a> was submitted to **IEEE JSAC**.
        - **[Sep. 2023]** The paper <a href='publication/adaptive-communication'>*Adaptive Communications in Collaborative Perception with Domain Alignment for Autonomous Driving*</a> was submitted to **IEEE ICRA 2024**.
        - **[Sep. 2023]** Senkang got the Institutional Research Tuition Grant, nearly 170 thousand Hong Kong dollars.
        - **[Jul. 2023]** 🎉 Congratulations to Senkang, finally move to Hong Kong 🇭🇰🇭🇰🇭🇰 to start his new career!
        - **[Jun. 2023]** Thanks for Prof. Fang's strong spport, Senkang got the <a href='https://www.innohk.gov.hk/en/about-us/'>InnoHK Funding</a> (Nearly a million Hong Kong dollars) from the Government of the Hong Kong Special Administrative Region to support his research and PhD career. 
        - **[Jun. 2022]** Senkang graduated from Beijing Institute of Technology. Thanks for all the professors, senior students and friends who helped him in the past four years.
        - **[Dec. 2021]** Senkang got the **National Scholarship** with his excellent academic performance (Top 1% in the whole department), which is the highest honor for chinese unversity students. 
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: 🎓 Publications
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
  - block: experience
    id: experience
    content:
      title: 🚀 Experiences
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Assistant
          # company: <b><span style="color:#0096FF">BeyondFuture.AI</span></b>
          company:  City University of Hong Kong
          company_url: ''
          company_logo: cityu
          location: Hong Kong
          date_start: '2023-07-01'
          date_end: ''
          description: 
        - title: Founder & CEO
          # company: <b><span style="color:#0096FF">BeyondFuture.AI</span></b>
          company:  Beyond Future.AI
          company_url: ''
          company_logo: bf
          location: Beijing
          date_start: '2023-03-01'
          date_end: ''
          description: 
        - title: Quantitative Strategy Intern
          company: Prism Private Equity 
          company_url: ''
          company_logo: prism
          location: Beijing
          date_start: '2022-09-01'
          date_end: '2022-12-31'
          description: Responsible for financial data processing, stock data mining, trading strategy research and testing, etc.
        - title: Computer Vision Intern
          company:  HAOMO.AI 
          company_url: ''
          company_logo: haomo
          location: Beijing
          date_start: '2022-04-01'
          date_end: '2022-08-31'
          description: Responsible for the maintenance and iteration of 3D point cloud object detection algorithm, the generalization of 3D object detection algorithm, data cleaning algorithm research, research and experiment of training methods, etc.
        - title: Research Assistant
          company: Chinese Academy of Sciences 
          company_url: ''
          company_logo: CAS
          location: Beijing
          date_start: '2021-10-01'
          date_end: '2022-03-31'
          description: Responsible for literature research, the experiment of algorithm, algorithm implementation, etc.
        - title: Research Assistant
          company: Beijing Institute of Technology
          company_url: ''
          company_logo: bit
          location: Beijing
          date_start: '2020-03-01'
          date_end: '2021-10-31'
          description: 
    design:
      columns: '2'

  - block: accomplishments
    id: awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: '🥇 Awards & Honors'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2023-09-15'
          description: 'Nearly 170 thousand Hong Kong dollars.'
          organization: City University of Hong Kong
          organization_url: 
          title: <span style="">Institutional Research Tuition Grant</span> 
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2023-06-01'
          description: 'Nearly a million Hong Kong dollars support his research and PhD career.'
          organization: The Government of the Hong Kong Special Administrative Region
          organization_url: 
          title: <span style="">InnoHK Funding</span> 
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2021-12-25'
          description: 'The highest honor for chinese unversity students.'
          organization: Ministry of Education of the People's Republic of China
          organization_url: 
          title: <span style="">National Scholarship</span> 
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2020-10-01'
          description: 
          organization: The China Aerospace Science and Technology Corporation
          organization_url: 
          title: <span style="">CASC Scholarship, *Top 1%*</span>
          url: 
        - certificate_url: 
          date_end: '2021-12-21'
          date_start: '2018-09-01'
          description: ''
          organization: Beijing Institute of Technology
          organization_url: 
          title: <span style="">First Class Academic Scholarship, *4 times*</span>
          url: ''
        - certificate_url: 
          date_end: '2021-12-21'
          date_start: '2018-09-01'
          description: ''
          organization: Beijing Institute of Technology
          organization_url: 
          title: <span style="">Excellent Student of Beijing Institute of Technology, *3 times*</span>
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2020-09-01'
          description: ''
          organization: Beijing Institute of Technology
          organization_url: 
          title: <span style="">Example of Scientific Research Innovation, *Top 1%*</span>
          url: ''
    design:
      columns: '2'
      view: card
  # - block: markdown
  #   id: service
  #   content:
  #     title: 💻 Services
  #     text: |-
  #       ### Reviewer
  #       - AAAI Conference on Artificial Intelligence
  #   design:
  #     columns: '2'

  - block: contact
    id: contact
    content:
      title: 🏫 Contact
      subtitle:
      text: |-

  #   # Contact (add or remove contact options as necessary)
      email: senkanhu@cityu.edu.hk
  #     # phone: 888 888 88 88
  #     # appointment_url: 'https://calendly.com'
      address:
        # street: 450 Serra Mall
        city: 83 Tat Chee Avenue
        region: Kowloon, Hong Kong
        # postcode: '94305'
        # country: 
      coordinates:
        latitude: '22.33703'
        longitude: '114.173196'
        # country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      # autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
  - block: markdown
    content:
      title:
      subtitle:
      text: |

        # <div style="width: 100%; height: auto;">
        <script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=5nkevw8m6m7&amp;m=0&amp;c=ff0000&amp;cr1=ffffff&amp;f=arial&amp;l=0" async="async"></script>
        # </div>
    design:
      columns: '1'
      background:
        image:
          filename: 
---
