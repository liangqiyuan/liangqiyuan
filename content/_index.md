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
      view: citation
  - block: service
    id: service
    content:
      title: Academic Service
      text: 
        * Reviewer of [_IEEE International Conference on Mobility: Operations, Services, and Technologies (MOST) 2023_](http://ieeemobility.org/)
        * Reviewer of [_IEEE Internet of Things Journal_](https://ieee-iotj.org/)
        * Reviewer of [_IEEE Transactions on Intelligent Vehicles_](https://ieee-itss.org/pub/t-iv/)
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
