---
# Leave the homepage title empty to use the site title
title: Tarun Kota
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      username: admin
      text:
      education: education
      
  - block: experience
    id: experience
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
        - title: Lead Researcher | Project Manager
          company: Caltech Infrared Processing Analysis Center
          company_url: 'https://www.ipac.caltech.edu/'
          company_logo: 
          location: Pasadena, CA
          date_start: '2020-08-01'
          date_end: '2022-07-01'
          description: |2-
              **Research and Managerial responsibilities:**:
              - Designed a supervised machine learning framework that employed a binary classification model to detect proper motion brown dwarfs.
              - Preprocessed ~900,000,000 data instances of unstructured data from CatWISE and refactored data to feed into machine learning model.
              - Collaborated with cross-functional teams to integrate and deploy ML model on CatWISE, leading to a discovery of 16 new brown dwarfs. 
              - Communicated technical results to both technical and non-technical during weekly lab meetings            
              - Cofounded a research group comprised solely of high schoolers and undergraduate students that focused on building a stellar motion detector.
              - Mentored 5+ junior researchers through their own research projects, resulting in two publications.
              
              
        - title: Research intern (Basketball Analytics)
          company: Carnegie Mellon University, Tepper School of Business
          company_url: 'https://www.cmu.edu/tepper/'
          company_logo:
          location: Pittsburgh, PA
          date_start: '2022-06-01'
          date_end: ''
          description: |2-
              **Responsibilities:**

              * Conducted feature analysis on 2022-2023 NBA lineup data to identify pertinent variables to lineup efficiency and team success.
              * Studied coaches substitutions through stackleberg equilbrium analysis, analyzing the efficiacy of decisions made.
              * Created a deliverable that contained a case study of the NBA Finals Matchup (warriors vs. celtics), highlighting key coaching decisions and contributors.
           
              
        - title: Research intern 
          company: Western University, Department of Physics & Astronomy
          company_url: 'https://physics.uwo.ca/'
          company_logo:
          location: London, ON
          date_start: '2021-05-01'
          date_end: '2021-08-23'
          description: |2-
            **Responsibilities:**
            - Led project that focused on determining observation targets for POET, a robotic telescope funded by the Canadian Space Agency.
            - Mined and analyzed data from 10+ astronomical databases to drive optimization and improvement of target selection.
            - Proposed and implemented a candidate selection model, considering all the specifications of the telescope, to analyze possible targets.
            - Presented list of 100+ targets to POET leadership, many of which are currently being imaged by the telescope.
          
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
        - certificate_url: 
          date_end: ''
          date_start: '2021-03-25'
          description: 'One of 3 winners in the United States and criterion is based on excellence in astronomy research. I got an all-expense paid trip to New Mexico and (more importantly!) a free personal telescope'
          organization: The Astronomical League
          organization_url: https://www.astroleague.org
          title: National Young Astronomer Award
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2021-05-01'
          description: First person in school district's history to be a finalist | Competed in the category of Physics and Astronomy
          organization: Regeneron
          organization_url: https://www.societyforscience.org/isef/
          title: Regeneron ISEF Finalist
          url: https://abstracts.societyforscience.org/Home/FullAbstract?ISEFYears=0%2C&Category=Any%20Category&AllAbstracts=True&FairCountry=Any%20Country&FairState=Any%20State&ProjectId=20524
        - certificate_url: 
          date_end: 
          date_start: '2021-07-01'
          description: Presnted research conducted at Caltech IPAC | Only 7/520 presenters were high schoolers
          organization: American Astronomical Society
          organization_url: https://aas.org/
          title: Presenter @ American Astronomical Society Meeting 
          url: ''
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Media
      subtitle: Places my work has been recognized as well some of my personal goals of 2023!
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
        - name: Publications
          tag: Publications
        - name: Service
          tag: Service
        - name: Personal
          tag: Personal
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
