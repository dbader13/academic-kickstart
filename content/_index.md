---
# Leave the homepage title empty to use the site title
title:
date: 2023-08-07
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin
  - block: markdown
    content:
     title: Biography
     subtitle:
     columns: 1
     text: David A. Bader is a Distinguished Professor and founder of the Department of Data Science and inaugural Director of the Institute for Data Science at New Jersey Institute of Technology.  Prior to this, he served as founding Professor and Chair of the School of Computational Science and Engineering, College of Computing, at Georgia Institute of Technology.  Bader is an elected Board Member of the [Computing Research Association (CRA)](https://cra.org/), and previously served on the [IEEE Computer Society](https://www.computer.org/) Board of Governors.<br><br>Dr. Bader is a Fellow of the IEEE, ACM, AAAS, and SIAM; a recipient of the [IEEE Sidney Fernbach Award](https://www.computer.org/press-room/2021-news/david-bader-to-receive-2021-ieee-cs-sidney-fernbach-award); and the 2022 [Innovation Hall of Fame](https://eng.umd.edu/ihof/david-bader) inductee of the University of Maryland's A. James Clark School of Engineering. He advises the White House, most recently on the National Strategic Computing Initiative (NSCI) and Future Advanced Computing Ecosystem (FACE). Bader is a leading expert in solving global grand challenges in science, engineering, computing, and data science. His interests are at the intersection of high-performance computing and real-world applications, including cybersecurity, massive-scale analytics, and computational genomics, and he has co-authored over 300 scholarly papers and has best paper awards from ISC, IEEE HPEC, and IEEE/ACM SC.  Dr. Bader has served as a lead scientist in several DARPA programs including High Productivity Computing Systems (HPCS) with IBM, Ubiquitous High Performance Computing (UHPC) with NVIDIA, Anomaly Detection at Multiple Scales (ADAMS), Power Efficiency Revolution For Embedded Computing Technologies (PERFECT), Hierarchical Identify Verify Exploit (HIVE), and Software-Defined Hardware (SDH). Recently, Bader received an NVIDIA AI Lab (NVAIL) award, and a Facebook Research AI Hardware/Software Co-Design award.<br><br>Dr. Bader is Editor-in-Chief of the *ACM Transactions on Parallel Computing*, and previously served as Editor-in-Chief of the *IEEE Transactions on Parallel and Distributed Systems*. He serves on the leadership team of Northeast Big Data Innovation Hub as the inaugural chair of the Seed Fund Steering Committee.  ROI-NJ recognized Bader as a technology influencer on its 2021 inaugural and 2022 lists. In 2012, Bader was the inaugural recipient of University of Maryland's Electrical and Computer Engineering Distinguished Alumni Award.  In 2014, Bader received the Outstanding Senior Faculty Research Award from Georgia Tech.  Bader is a member of [Tau Beta Pi]({{<relref "/post/19891204-taubetapi">}}) (National Engineering Honor Society), [Eta Kappa Nu]({{<relref "/post/19890410-hkn">}}) (Electrical Engineering Honor Society), and [Omicron Delta Kappa]({{<relref "/post/19950404-odk">}}) (National Leadership Honor Society). Bader has also served as Director of the Sony-Toshiba-IBM Center of Competence for the Cell Broadband Engine Processor and Director of an NVIDIA GPU Center of Excellence. [In 1998, Bader built the first Linux supercomputer that led to a high-performance computing (HPC) revolution,]({{<relref "/post/20210426-linuxsupercomputer">}}) and Hyperion Research estimates that [the total economic value of Linux supercomputing pioneered by Bader has been over $100 trillion over the past 25 years.]({{<relref "/publication/2022-HyperionResearch">}}) The [Computer History Museum](https://www.computerhistory.org/timeline/1998/) recognizes Bader for developing the first Linux-based supercomputer which became the predominant architecture for all major supercomputers in the world. Bader is a cofounder of the Graph500 List for benchmarking "Big Data" computing platforms. He is recognized as a "RockStar" of High Performance Computing by InsideHPC and as HPCwire's People to Watch in 2012 and 2014.
  - block: markdown
    content:
     title: Media Appearances
     subtitle:
     columns: 1
     text: <center>{{<figure src="media.jpg">}}</center>
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
        - title: Distinguished Professor
          company: New Jersey Institute of Technology
          company_url: 'http://www.njit.edu/'
          company_logo: org-njit
          location: Newark, NJ
          date_start: '2019-07-01'
          date_end:
          description: Department of Data Science, Ying Wu College of Computing
        - title: Professor
          company: Georgia Institute of Technology
          company_url: 'http://www.gatech.edu/'
          company_logo: org-gatech
          location: Atlanta, GA
          date_start: '2005-08-01'
          date_end: '2019-06-30'
          description: Chair, School of Computational Science and Engineering.
        - title: Associate Professor and Regents' Lecturer
          company: University of New Mexico
          company_url: 'http://www.unm.edu/'
          company_logo: org-unm
          location: Albuquerque, NM
          date_start: '1998-01-01'
          date_end: '2005-07-30'
          description: Department of Electrical and Computer Engineering.
    design:
      columns: '2'
  - block: experience
    content:
      title: Recent Boards
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
      
      - title: Board Member
        company: Computing Research Association
        company_url: 'https://cra.org/'
        company_logo: org-cra
        location: Washington, DC
        date_start: '2024-07-01'
#        date_end: '2027-06-30'
        date_end: ''
    
      - title: Scientific Advisory Board Member
        company: Flatiron Institute, Simons Foundation
        company_url: 'https://www.simonsfoundation.org/flatiron/'
        company_logo: org-flatiron
        location: New York, NY
        date_start: '2023-07-01'
        date_end: ''
    
      - title: Committee Member
        company: Information Systems Engineering, Johns Hopkins University
        company_url: 'https://www.jhu.edu/'
        company_logo: org-jhu
        location: Baltimore, MD
        date_start: '2023-01-01'
        date_end: ''
    
      - title: Advisory Council Member
        company: EdgeDiscovery, NJEdge Inc. 
        company_url: 'https://njedge.net/research/'
        company_logo: org-njedge
        location: Newark, NJ
        date_start: '2020-08-01'
        date_end: ''
    
      - title: Advisory Board Member
        company: ARLIS, University of Maryland
        company_url: 'https://www.arlis.umd.edu/'
        company_logo: org-maryland
        location: College Park, MD
        date_start: '2020-07-01'
        date_end: ''
    
      - title: Steering Committee Chair, Seed Fund
        company: Northeast Big Data Innovation Hub
        company_url: 'http://nebigdatahub.org/'
        company_logo: org-nebdih
        location: New York, NY
        date_start: '2020-05-01'
        date_end: ''
    
      - title: Advisory Board Member
        company: OpenCilk
        company_url: 'http://cilk.mit.edu/'
        company_logo: org-opencilk
        location: Cambridge, MA
        date_start: '2020-03-10'
        date_end: ''
    
      - title: Strategic Advisory Board Member
        company: Open Source Election Technology Institute
        company_url: 'https://www.osetfoundation.org/'
        company_logo: org-oset
        location: Palo Alto, CA
        date_start: '2019-09-01'
        date_end: ''
    
      - title: Advisory Board Member
        company: Trovares
        company_url: 'https://trovares.com/'
        company_logo: org-trovares
        location: Seattle, WA
        date_start: '2019-01-01'
        date_end: '2020-04-30'
    
      - title: Advisory Council Member
        company: Electrical and Computer Engineering Department, Lehigh University
        company_url: 'https://engineering.lehigh.edu/ece/about-department-electrical-and-computer-engineering/ece-advisory-council'
        company_logo: org-lehigh
        location: Bethlehem, PA
        date_start: '2018-01-01'
        date_end: ''
    
      - title: Advisory Board Member
        company: Accelogic, LLC
        company_url: 'https://Accelogic.com/'
        location: Weston, FL
        company_logo: org-accelogic
        date_start: '2015-06-12'
        date_end: '2019-06-30'
    
      - title: Advisory Committee on High Performance Computing
        company: Council on Competitiveness
        company_url: 'https://www.compete.org/'
        company_logo: org-coc
        location: Washington, DC
        date_start: '2014-01-01'
        date_end: '2019-06-30'
    
      - title: Advisory Committee on Cyberinfrastructure
        company: National Science Foundation
        company_url: 'https://www.nsf.gov/'
        company_logo: org-nsf
        location:
        date_start: '2014-01-01'
        date_end: '2017-12-31'
    
      - title: Board of Governors
        company: IEEE Computer Society
        company_url: 'https://www.computer.org/'
        company_logo: org-ieeecs
        location:
        date_start: '2014-01-01'
        date_end: '2016-12-31'
    
      - title: Board Member
        company: Computing Research Association
        company_url: 'https://cra.org/'
        company_logo: org-cra
        location: Washington, DC
        date_start: '2013-01-01'
        date_end: '2014-12-31'
    
      - title: Advisory Council Member
        company: Internet2
        company_url: 'https://www.internet2.edu/'
        company_logo: org-internet2
        location:
        date_start: '2007-01-01'
        date_end: '2011-12-31'
    
      - title: Advisory Board Member
        company: DSPlogic, Inc.
        company_url: 'https://DSPlogic.com/'
        company_logo: org-dsplogic
        location: Frederick, MD
        date_start: '2006-08-01'
        date_end: '2019-06-30'

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

  - block: people
    id: people
    content:
      title: People
      user_groups:
          - Faculty
          - Staff
          - Postdoctoral Alumni
          - PhD Students
          - PhD Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
      
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
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: portfolio
    id: books
    content:
      title: Books
      filters:
        folders:
          - books
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
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
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
#      text: |-
#        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
#      email: 'dbader13@gmail.com'
#      phone: '973-596-6340'
#      appointment_url: 'https://calendly.com'
      address:
        street: 'Institute for Data Science, New Jersey Institute of Technology, 101 Hudson St., Suite 3610'
        city: 'Jersey City'
        region: NJ
        postcode: '07302'
        country: United States
        country_code: US
      coordinates:
        latitude: '40.7161'
        longitude: '-74.0344'
#      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Prof_DavidBader'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
        - icon: keybase
          icon_pack: fab
          name: Chat on Keybase
          link: 'https://keybase.io/dbader13'
      # Automatically link email and phone or display as text?
#      autolink: true
      # Email form provider
      form:
         provider: formspree
         formspree:
          id: 'xnqoylgb'
#          captcha: true
#          captcha_key: 6Lel-uIdAAAAAFxCgi3qQgszGtibPnS9Eoc8YGMF
    design:
      columns: '2'
---
