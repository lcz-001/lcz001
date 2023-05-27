---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Welcome to my homepage # Hugo Academic Theme
      image:
        filename: 太殷定稿-01.png # hero-academic.png
      cta:
        label:'**自强不息  厚德载物**' 
        url: '' # https://wowchemy.com/templates/
      # cta_alt:
      #  label: Ask a question
      #  url: https://discord.gg/z8wNYzb
      # cta_note:
      #   label: >-
      #     <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **I will supplement the content not mentioned in my resume here, and of course, you can also consider it as my journal of some trivial matters...**
        
        ** **
        **Here, I will also share some of my experiences, interesting stories, record the small achievements made by me and my team and so on.**

        
        ** **
        **You can also use this webpage to jump to my other pages, such as poetries and experiences.**

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 85%
          # icon: r-project
          # icon_pack: fab
        - name: EPL
          description: 92%
          # icon: chart-line
          # icon_pack: fas
        - name: C
          description: 70%
          # icon: camera-retro
          # icon_pack: fas
        - name: Swim
          description: 70%
          # icon: camera-retro
          # icon_pack: fas
        - name: Painting
          description: 65%
          # icon: camera-retro
          # icon_pack: fas
        - name: Versify
          description: 70%
          # icon: camera-retro
          # icon_pack: fas
        - name: Network Technique
          description: 50%
          # icon: camera-retro
          # icon_pack: fas
        - name: Video Clips
          description: 65%
          # icon: camera-retro
          # icon_pack: fas
        - name: See More
          # icon: camera-retro
          # icon_pack: fas
          
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Leader of the AI Interest Group # CEO
          company: Our University
          company_url: ''
          company_logo: TeamLeader02 # org-x gc
          location: QuanZhou China
          date_start: '2021-05-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Organizing Competitions
              * Personnel Management
              * Transaction Processing
        
        - title: CAAI Individual Member # CEO
          company: CAAI
          company_url: https://www.caai.cn/index.php?s=/home/index/index/login/go.html&user_code=YTM1OW1CaUVuS0JvaGp2THRDZGREekVoVFVjdlR4ekoxcWRzYmFGVzVHMURwaHc=&ssaid=82210561148&ssn=13e138326107704e42543459d9491804
          company_logo: CAAI_ICO # gc
          location: China
          date_start: '2021-05-03'
          date_end: ''
          description: Through Professor Wang's introduction, I have learned about and joined a personal member of the Chinese Association of Artificial Intelligence. Here, I can learn about the cutting-edge information of artificial intelligence in real-time and broaden my horizons.
        
        - title: A Poet On Chinese Poetry Network # CEO
          company: 中国诗歌网
          company_url: https://www.zgshige.com/c/2021-08-16/18874686.shtml
          company_logo: 中国诗歌网_图标 # gc
          location: China
          date_start: '2021-08-13'
          date_end: ''
          description: 有幸认证成为中国诗歌网蓝V诗人，并在这诗人的家园中学习、分享，使我的精神生活更加丰富多彩。
        
        - title: President of Artificial Intelligence
          company: Our University
          company_url: ''
          company_logo: TeamLeader02
          location: QuanZhou China
          date_start: '2022-10-14'
          date_end: ''
          description: Organize and manage artificial intelligence homework clubs and impart experience to lower grade students, etc.
          
          
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2020-10-10'
          description: ''
          organization: 林存智
          organization_url: https://www.coursera.org
          title: 'My Papers'
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2020-10-10'
          description: Intellectual property rights that have been applied for or are currently being applied for. (the homepage may not be updated in a timely manner, and the situation may lag)
          organization: 林存智
          organization_url: https://www.edx.org
          title: 'Intellectual Property'
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: ''
          date_start: '2020-10-10'
          description: Including various types of awards since my undergraduate studies, such as competitions.
          organization: 林存智
          organization_url: https://www.datacamp.com
          title: 'Awards'
          url: ''
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2020-10-10'
          description: Perhaps you can see my other achievements here.
          organization: 林存智
          organization_url: https://www.coursera.org
          title: 'Other Achievements'
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: 'Show More'
      url: 'https://calendly.com'
      # content:
      # cta_alt:
      # label: Show More
      # url: ''
      # url: '' # 链接网页暂未确定
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: My Poetry Collection # Featured Publications 我的诗集
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
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
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
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
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
