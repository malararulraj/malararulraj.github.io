---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
  - block: experience
    content:
      title: Affiliations
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Post-doctoral Associate
          company: University of Maryland
          company_url: 'https://umd.edu'
          company_logo: 
          location: College Park
          date_start: '2020-06-01'
          date_end: ''
          description: 
        - title: Post-doctoral Associate
          company: Duke University
          company_url: 'https://duke.edu'
          company_logo:
          location: Durham
          date_start: '2020-02-01'
          date_end: '2020-05-31'
          description:
        - title: Graduate Research Assistant
          company: Duke University
          company_url: 'https://duke.edu'
          company_logo: 
          location: Durham
          date_start: '2014-08-01'
          date_end: '2019-11-30'
          description: 
        - title: Graduate Teaching Assistant
          company: Duke University
          company_url: 'https://duke.edu'
          company_logo:
          location: Durham
          date_start: '2017-01-01'
          date_end: '2017-05-31'
          description:
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: marulraj (at) umd (dot) edu
      address:
        street: 5825 University Research Ct Suite 4001
        city: College Park
        region: MD
        postcode: '20740'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
