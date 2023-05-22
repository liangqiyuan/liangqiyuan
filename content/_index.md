---
# Leave the homepage title empty to use the site title
title:
date: 2022-11-30
type: landing

sections:
  - block: v1/about
  # - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: markdown
    id: news
    content:
      title: News
      subtitle: ''
      text: |-
        - [May 20, 2023] One paper has been accepted to [IEEE Internet of Things Journal](https://ieee-iotj.org/)!
        - [Apr 13, 2023] Two papers have been accepted to the [7th AI City Challenge Workshop at CVPR 2023](https://www.aicitychallenge.org/)!
        - [Mar 25, 2023] One papers has been accepted to [IEEE Internet of Things Journal](https://ieee-iotj.org/)!
        - [Nov 04, 2022] One papers has been accepted to [ICCE 2023](https://icce.org/2023/)!
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      sort_by: 'Date'
      sort_ascending: false
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
          tag: Oakland University
        - name: Purdue University
          tag: Purdue University
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
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
  - block: collection
    id: presentations
    content:
      title: Presentations
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: markdown
    id: service
    content:
      title: Academic Service
      subtitle: ''
      text: |-
        ### Journal Reviewer
        - [IEEE Transactions on Intelligent Transportation Systems](https://ieee-itss.org/pub/t-its/)
        - [IEEE Access](https://ieeeaccess.ieee.org/)
        - [IEEE Sensors Journal](https://ieee-sensors.org/sensors-journal/)
        - [IEEE Internet of Things Journal](https://ieee-iotj.org/)
        - [IEEE Transactions on Intelligent Vehicles](https://ieee-itss.org/pub/t-iv/)  
        ### Conference Reviewer
        - [The 6th International Conference on Mechanical, Electric, and Industrial Engineering (MEIE 2023)](http://www.icmeie.com/)
        - [The First IEEE International Conference on Mobility: Operations, Services, and Technologies (MOST 2023)](https://ieeemobility.org/)
        - [The 6th International Conference on Computer Science and Application Engineering (CSAE 2022)](http://www.csaeconf.org/2022/)
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: liangqiy@purdue.edu
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
