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
      # - **[Dec. 2023]** The paper <a href='publication/dg-coperception-magazine'>Collaborative Perception for Autonomous Driving: Challenges, Countermeasures and Opportunities</a> was submitted to *IEEE Communications Magazine (**COMMAG**)*.
      text: |-
        - **[Nov. 2024]** One paper was accepted by **IEEE Transactions on Intelligent Transportation Systems (TITS)**, congratulations 🎉!!! [[PDF](https://arxiv.org/abs/2311.16754)]
        - **[Nov. 2024]** Senkang was awarded the **IEEE ComSoc Student Grant** to support his conference travel.
        - **[Sep. 2024]** Senkang was nominated as a **Program Committee Member** of AAAI'25 and ICLR'25!
        - **[Aug. 2024]** One paper was accepted by **IEEE Transactions on Mobile Computing (TMC)**!
        - **[Jul. 2024]** Two papers were accepted by **GLOBECOM'24**, see you in Cape Town 🇿🇦!
        - **[Sep. 2023]** Senkang was awarded the <b>Institutional Research Tuition Grant</b>, nearly HK$170,000.
        - **[Jul. 2023]** Congratulations to Senkang 🎉, finally moved to <b>Hong Kong</b> 🇭🇰🇭🇰🇭🇰 to start his new career!
        - **[Jun. 2023]** Thanks to [**Prof. Fang**](https://www.cs.cityu.edu.hk/~yugufang/)'s strong support, Senkang received the <a href='https://www.innohk.gov.hk/en/about-us/'><b>InnoHK Award Funding</b></a>, around HK$900,000 from the Government of the Hong Kong Special Administrative Region to support his research and PhD career. 
        - **[Jun. 2022]** Senkang **graduated** from Beijing Institute of Technology. Thanks to all the professors, senior students and friends who helped him in the past four years.
        - **[Dec. 2021]** Senkang was awarded the **National Scholarship** for his top 1% academic performance in the whole department, which is the highest honor for Chinese university students.
    design:
      columns: '1'
  - block: markdown
    id: research
    content:
      title: 🎯 Research
      text: |-
        ## **Collaborative Perception (CP) for Autonomous Driving**
        - **CP System Design**: CP can overcome the limitations of single-agent perception systems, such as occlusion and sensing range, by leveraging the information from multiple vehicles.
        - **Security Issues in CP**: As CP needs to leverage the information from other vehicles, it expands the system's attack surface. Therefore, designing defense method is curial for secure CP.
  

        ## **Large Language Models (LLMs)**
        - **Multi-Agent LLM Systems for Autonomous Driving**: Similar as CP, not only multi-agent perception but also multi-agent collaborative decision-making is important for next-generation autonomous driving. Here, LLM is leveraged as a powerful tool to build the multi-agent collaborative decision-making systems.
        - **LLM Task Adaptation**: Adapting pre-trained LLMs to specific tasks, such as collaborative decision-making, better and more efficiently.
  - block: markdown
    id: publications
    content:
      title: 🎓 Publications
      text: |-
        
        ## **Preprints**
        1. **[Preprint]** **<u>Senkang "Forest" Hu</u>**, Yihang Tao, Yuguang Fang, et al. "Robost Agent Detection in Collaborative Perception."
        2. **[Preprint]** **<u>Senkang "Forest" Hu</u>**, Yihang Tao, Guowen Xu, Yiqin Deng, Xianhao Chen,  Yuguang Fang, Sam Kwong. "Agent Detection in Collaborative Bird's Eye View Perception."
        3. **[Preprint]** **<u>Senkang "Forest" Hu</u>**, Zhengru Fang, Zihan Fang, Yiqin Deng, Xianhao Chen, Yuguang Fang, Sam Kwong. "AgentsCoMerge: Large Language Model Empowered Collaborative Decision Making for Multi-Lane Merging." [[PDF](https://arxiv.org/abs/2408.03624)]
        4. **[Preprint]** **<u>Senkang "Forest" Hu</u>**, Zhengru Fang, Zihan Fang, Xianhao Chen, Yuguang Fang. "AgentsCoDriver: Large Language Model Empowered Collaborative Driving with Lifelong Learning." [[PDF](https://arxiv.org/abs/2404.06345), [Blog](https://mp.weixin.qq.com/s/HVfs4-PT58WujCvEZZboug)]
        5. **[Preprint]** **<u>Senkang "Forest" Hu</u>**, Zhengru Fang, Yiqin Deng, Xianhao Chen, Yuguang Fang. "Collaborative Perception for Autonomous Driving: Challenges, Possible Solutions and Opportunities." [[PDF](https://arxiv.org/abs/2401.01544)]
        6. **[Preprint]** Zhengru Fang, **<u>Senkang "Forest" Hu</u>**, Jingjing Wang, Yiqin Deng, Xianhao Chen, Yuguang Fang. "Prioritized Information Bottleneck Theoretic Framework with Distributed Online Learning for Edge Video Analytics." [[PDF](https://arxiv.org/abs/2409.00146), [Code](https://github.com/fangzr/PIB-Prioritized-Information-Bottleneck-Framework)]
        7. **[Preprint]** Yihang Tao, **<u>Senkang "Forest" Hu</u>**, Zhengru Fang, Yuguang Fang. "Direct-CP: Directed Collaborative Perception for Connected and Autonomous Vehicles via Proactive Attention". [[PDF](https://arxiv.org/abs/2409.08840)]
        8. **[Preprint]** Zihan Fang, Zheng Lin, **<u>Senkang "Forest" Hu</u>**, Hangcheng Cao, Xianhao Chen, and Yuguang Fang. "IC3M: In-Car Multimodal Multi-object Monitoring for Abnormal Status of Both Driver and Passengers." [[PDF](https://arxiv.org/abs/2410.02592)]

        ## **Accepted Papers in 2024**

        
        9.  **[TITS'24]** **<u>Senkang "Forest" Hu</u>**, Zhengru Fang, Xianhao Chen, Yuguang Fang, and Sam Kwong. "Towards Full-scene Domain Generalization in Multi-agent Collaborative Bird's Eye View Segmentation for Connected and Autonomous Driving." *IEEE Transactions on Intelligent Transportation Systems.* [[PDF](https://arxiv.org/abs/2311.16754)]
        10. **[GLOBECOM'24]** **<u>Senkang "Forest" Hu</u>**, Zhengru Fang, Haonan An, Guowen Xu, Yuan Zhou, Xianhao Chen, and Yuguang Fang. "Adaptive Communications in Collaborative Perception with Domain Alignment for Autonomous Driving", *IEEE Global Communications Conference*, Cape Town, South Africa, December 2024. [[PDF](https://arxiv.org/abs/2310.00013)]
        11. **[GLOBECOM'24]** Zhengru Fang, **<u>Senkang "Forest" Hu</u>**, Yuguang Fang, et al. "PIB: Prioritized Information Bottleneck Framework for Collaborative Edge Video Analytics", *IEEE Global Communications Conference*, Cape Town, South Africa, December 2024. [[PDF](https://arxiv.org/abs/2408.17047), [Code](https://github.com/fangzr/PIB-Prioritized-Information-Bottleneck-Framework)] 
        12. **[TMC'24]** Zhengru Fang, **<u>Senkang "Forest" Hu</u>**, Haonan An, Yuang Zhang, Jingjing Wang, Hangcheng Cao, Xianhao Chen, Yuguang Fang. "PACP: Priority-Aware Collaborative Perception for Connected and Autonomous Vehicles." *IEEE Transactions on Moblie Computing.* [[PDF](https://arxiv.org/abs/2404.06891)]
        
        <sup>#</sup>equal contribution, *corresponding author.

        

        

    
    design:
      columns: '1'
      # view: citation
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
        - title: <span style="color:#000000">Co-Founder & CTO</span>
          company: Pivot Biomedical Engineering Ltd.
          company_logo: PivotBME
          company_url: 'https://pivotbme.com/'
          location: Hong Kong
          date_start: '2024-06-01'
        - title: <span style="color:#000000">Research Assistant</span>
          company:  City University of Hong Kong
          company_url: 'https://www.cityu.edu.hk/'
          company_logo: cityu
          location: Hong Kong
          date_start: '2023-07-01'
          date_end: '2023-12-31'
          description: 
        # - title: Founder & CEO
        #   # company: <b><span style="color:#0096FF">BeyondFuture.AI</span></b>
        #   company:  Beyond Future.AI
        #   company_url: ''
        #   company_logo: bf
        #   location: Beijing
        #   date_start: '2023-03-01'
        #   date_end: ''
        #   description: 
        - title: <span style="color:#000000">Quantitative Strategy Intern</span>
          company: Prism Private Equity Fund Management Co. LTD
          company_url: 'https://lengjing.fund/'
          company_logo: prism
          location: Beijing
          date_start: '2022-09-01'
          date_end: '2022-12-31'
          description: 
        - title: <span style="color:#000000">Computer Vision Intern</span>
          company:  HAOMO.AI 
          company_url: 'https://haomo.ai/'
          company_logo: haomo
          location: Beijing
          date_start: '2022-04-01'
          date_end: '2022-08-31'
          description: 
        - title: <span style="color:#000000">Research Assistant</span>
          company: Chinese Academy of Sciences 
          company_url: ''
          company_logo: CAS
          location: Beijing
          date_start: '2021-10-01'
          date_end: '2022-03-31'
          description: 
        - title: <span style="color:#000000">Research Assistant</span>
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
          date_start: '2024-11-15'
          description: ''
          organization: IEEE Communications Society
          organization_url: 
          title: <span style="color:#000000">IEEE ComSoc Student Grant</span>
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2023-09-15'
          description: 'HK$170,000 to cover part of his tuition fees during PhD.'
          organization: City University of Hong Kong
          organization_url: 
          title: <span style="color:#000000">Institutional Research Tuition Grant</span>
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2023-06-01'
          description: 'Around HK$900,000 to support his research and PhD career.'
          organization: The Government of the Hong Kong Special Administrative Region
          organization_url: 
          title: <span style="color:#000000">InnoHK Award Funding</span> 
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2021-12-25'
          description: 'The highest honor for Chinese university students.'
          organization: Ministry of Education of the People's Republic of China
          organization_url: 
          title: <span style="color:#000000">National Scholarship</span> 
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2020-10-01'
          description: 
          organization: The China Aerospace Science and Technology Corporation
          organization_url: 
          title: <span style="color:#000000">CASC Scholarship, *Top 1%*</span>
          url: 
        - certificate_url: 
          date_end: '2021-12-21'
          date_start: '2018-09-01'
          description: ''
          organization: Beijing Institute of Technology
          organization_url: 
          title: <span style="color:#000000">First Class Academic Scholarship, *4 times*</span>
          url: ''
        - certificate_url: 
          date_end: '2021-12-21'
          date_start: '2018-09-01'
          description: ''
          organization: Beijing Institute of Technology
          organization_url: 
          title: <span style="color:#000000">Excellent Student of Beijing Institute of Technology, *3 times*</span>
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2020-09-01'
          description: ''
          organization: Beijing Institute of Technology
          organization_url: 
          title: <span style="color:#000000">Example of Scientific Research Innovation, *Top 1%*</span>
          url: ''
    design:
      columns: '2'
      view: card
  - block: markdown
    id: service
    content:
      title: 💻 Services  
      text: |-
        ## **Technical Program Committee**
        - The International Conference on Learning Representations (ICLR'25)
        - AAAI Conference on Artificial Intelligence (AAAI'25)
        ## **Reviewer**
        - ACM SIGCHI Conference on Computer-Supported Cooperative Work & Social Computing (CSCW'25)
        - IEEE International Conference on Robotics and Automation (ICRA'25)
        - The Conference on Neural Information Processing Systems (NeurIPS'24)
        - The Conference on Empirical Methods in Natural Language Processing (EMNLP'24)
        - IET Information Security
        - IEEE Transactions on Network and Service Management (TNSM)
        - ACM Transactions on Autonomous and Adaptive Systems (TAAS)
        - Information Fusion
        - Pattern Recognition (PR)
        - 2024 IEEE/CIC International Conference on Communications in China (ICCC'24)
        - IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS'24)
        - IEEE Robotics and Automation Letters (RA-L)
        - Proceedings of the IEEE
        - etc......
        ## **Teaching Assistant**
        - Computer Networks, 2024 Fall
        - Cloud Computing: Theory and Practice, 2024 Spring

        

    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: 🏫 Contact
      subtitle:
      

  #   # Contact (add or remove contact options as necessary)
      email: senkang.forest@gmail.com
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
      text: |-

        
    design:
      columns: '2'
  - block: markdown
    content:
      title:
      subtitle:
      text: |

        <div style="width: 30%; height: auto; margin: auto;">
        <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=qLWVVAAvtN_5u37gNS4Dm-rflExCdP123yF9uf4KZnk"></script>
        </div>
    design:
      columns: '1'
      background:
        image:
          filename: 
---

