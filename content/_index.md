---
# Leave the homepage title empty to use the site title
title:
date: 2022-11-30
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
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
        - name: Oakland University
          tag: oakland
        - name: Purdue University
          tag: purdue
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      count: 0
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: compact
  - block: markdown
    id: service
    content:
      title: Academic Service
      subtitle: ''
      text: |-
        - Reviewer of [_IEEE International Conference on Mobility: Operations, Services, and Technologies (MOST) 2023_](https://ieeemobility.org/)
        
        - Reviewer of [_IEEE Internet of Things Journal_](https://ieee-iotj.org/)
        
        - Reviewer of [_IEEE Transactions on Intelligent Vehicles_](https://ieee-itss.org/pub/t-iv/)
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: yuan383@purdue.edu
      address:
        street: Hampton Hall 2155, 550 Stadium Mall Drive
        city: West Lafayette
        region: IN
        postcode: '47907'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
