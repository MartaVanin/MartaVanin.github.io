---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  # - block: experience
  #   id: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: Assistant Professor
  #         company: KU Leuven - Technology Campus Ghent
  #         company_url: ''
  #         company_logo:
  #         location: Ghent, Belgium
  #         date_start: '2024-10-01'
  #         date_end: ''
  #         description: 

  - block: collection
    id: posts
    content:
      title: Blog Posts
      subtitle: No blog posts currently.
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
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  - block: markdown
    id: worktogether
    content:
      title: Work Together?
      subtitle: This website is work in progress, please check the section on my research interests above.
      text:
    design:
      columns: '1'
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: Work in progress.
      text:
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: If you would like to contact me, please do so at the e-mail address below.
      # Contact (add or remove contact options as necessary)
      email: marta(dot)vanin(at)kuleuven.be
      contact_links:
        - icon: twitter
          icon_pack: fab
          link: 'https://twitter.com/martabot_'
          name: 'Twitter'
        - icon: google-scholar
          icon_pack: ai
          link: 'https://scholar.google.com/citations?user=D-5tDxoAAAAJ&hl=it'
          name: Google Scholar
        - icon: github
          icon_pack: fab
          link: https://github.com/MartaVanin
          name: GitHub
        - icon: orcid
          icon_pack: ai
          link: http://orcid.org/0000-0001-9474-0170
          name: Orcid
        - icon: linkedin
          icon_pack: fab
          link: https://www.linkedin.com/in/marta-vanin-80434083/
          name: LinkedIn
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
    design:
      columns: '1'
---