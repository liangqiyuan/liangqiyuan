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
        - May 2024: One paper has been accepted to [IEEE Internet of Things Journal](https://ieee-iotj.org/).
        - Feb 2024: One paper has been accepted to [IEEE Internet Computing](https://www.computer.org/csdl/magazine/ic).
        - Jan 2024: One paper has been accepted to [ICC 2024](https://icc2024.ieee-icc.org/). One abstract has been accepted to [NAML 2024](https://sites.google.com/go.spawar.navy.mil/naml/).
        - Nov 2023: One paper has been accepted to [IEEE Transactions on Intelligent Vehicles](https://ieee-itss.org/pub/t-iv/).
        - Aug 2023: One paper has been accepted to [IEEE Open Journal of Instrumentation and Measurement](https://ieee-ims.org/publication/ieee-ojim/about).
        - Jul 2023: One paper has been accepted to [ITSC 2023](https://2023.ieee-itsc.org/).
        - May 2023: One paper has been accepted to [IEEE Internet of Things Journal](https://ieee-iotj.org/).
        - Apr 2023: Two papers have been accepted to the [7th AI City Challenge Workshop at CVPR 2023](https://www.aicitychallenge.org/). I am honored to have been invited as a speaker at [IV 2023 IoT in ITS Workshop](https://iot-in-its.github.io/iv2023) to present my work in federated learning.
        - Mar 2023: One paper has been accepted to [IEEE Internet of Things Journal](https://ieee-iotj.org/).
        - Nov 2022: One paper has been accepted to [ICCE 2023](https://icce.org/2023/).
        - Aug 2022: One paper has been accepted to [DDDAS 2022](http://1dddas.org/dddas2022). Our paper has been selected as an [issue cover](https://www.mdpi.com/1424-8220/22/15).
        - Jul 2022: One paper has been accepted to [Sensors](https://www.mdpi.com/journal/sensors).
        - Nov 2021: One paper has been accepted to [IEEE Sensors Journal](https://ieee-sensors.org/sensors-journal/).
        - Aug 2021: One paper has been accepted to [IEEE Sensors 2021](https://2021.ieee-sensorsconference.org/).
    design:
      columns: '1'
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
      view: masonry
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
        exclude_featured: false
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
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: |-
        ### Purdue University
        #### Grading Assistant
        - [ECE 60146 - Deep Learning](https://engineering.purdue.edu/DeepLearn/) <span style="float: right;">Spring 2023</span>
        - [ECE 66100 - Computer Vision](https://engineering.purdue.edu/kak/computervision/) <span style="float: right;">Fall 2022</span>

    design:
      columns: '2'
  - block: markdown
    id: activities
    content:
      title: Professional Activities
      subtitle: ''
      text: |-
        ### Technical Program Committee Member
        - [International Conference on Sensor Device Technologies and Applications](https://www.iaria.org/conferences2024/SENSORDEVICES24.html) <span style="float: right;">_2023, 2024_</span>

        ### Journal Reviewer
        - [IEEE Sensors Letters](https://ieee-sensorsletters.org/) <span style="float: right;">_2024 – Present_</span>
        - [IEEE Transactions on Mobile Computing](https://www.computer.org/csdl/journal/tm) <span style="float: right;">_2024 – Present_</span>
        - [Elsevier Measurement](https://www.sciencedirect.com/journal/measurement) <span style="float: right;">_2024 – Present_</span>
        - [IEEE Transactions on Geoscience and Remote Sensing](https://www.grss-ieee.org/publications/transactions-on-geoscience-remote-sensing/) <span style="float: right;">_2024 – Present_</span>
        - [IEEE Transactions on Machine Learning in Communications and Networking](https://www.comsoc.org/publications/journals/ieee-tmlcn) <span style="float: right;">_2024 – Present_</span>
        - [Elsevier Engineering Applications of Artificial Intelligence](https://www.sciencedirect.com/journal/engineering-applications-of-artificial-intelligence) <span style="float: right;">_2024 – Present_</span>
        - [SAE International Journal of Connected and Automated Vehicles](https://www.sae.org/publications/collections/content/E-JOURNAL-12/) <span style="float: right;">_2024 – Present_</span>
        - [Springer Applied Composite Materials](https://www.springer.com/journal/10443) <span style="float: right;">_2023 – Present_</span>
        - [ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies](https://dl.acm.org/journal/imwut) <span style="float: right;">_2023 – Present_</span>
        - [IEEE Transactions on Intelligent Transportation Systems](https://ieee-itss.org/pub/t-its/) <span style="float: right;">_2023 – Present_</span>
        - [IEEE Access](https://ieeeaccess.ieee.org/) <span style="float: right;">_2023 – Present_</span>
        - [IEEE Sensors Journal](https://ieee-sensors.org/sensors-journal/) <span style="float: right;">_2023 – Present_</span>
        - [IEEE Internet of Things Journal](https://ieee-iotj.org/) <span style="float: right;">_2022 – Present_</span>
        - [IEEE Transactions on Intelligent Vehicles](https://ieee-itss.org/pub/t-iv/) <span style="float: right;">_2022 – Present_</span>

        ### Conference Reviewer
        - [Advances in Neural Information Processing Systems (NeurIPS)](https://neurips.cc/) <span style="float: right;">_2024_</span>
        - [IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) AI4CC Workshop](https://ai4cc.net/) <span style="float: right;">_2024_</span>
        - [IEEE International Conference on Distributed Computing Systems (ICDCS)](https://icdcs2024.icdcs.org/) <span style="float: right;">_2024_</span>
        - [IEEE International Conference on Communications (ICC)](https://icc2024.ieee-icc.org/) <span style="float: right;">_2024_</span>
        - [IEEE International Conference on Computer Communications (INFOCOM)](https://infocom2024.ieee-infocom.org/) <span style="float: right;">_2024_</span>
        - [IEEE Sensors Conference](https://2023.ieee-sensorsconference.org/) <span style="float: right;">_2023_</span>
        - [IEEE International Conference on Intelligent Transportation Systems (ITSC)](https://2023.ieee-itsc.org/) <span style="float: right;">_2023_</span>
        - [IEEE International Conference on Mobility: Operations, Services, and Technologies (MOST)](https://ieeemobility.org/MOST2023/) <span style="float: right;">_2023_</span>
        

# [International Conference on Mechanical, Electric, and Industrial Engineering (MEIE)](http://www.icmeie.com/) <span style="float: right;">_2023_</span>
# [International Conference on Computer Science and Application Engineering (CSAE)](https://dl.acm.org/conference/csae) <span style="float: right;">_2022_</span>    
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: liangqiy@purdue.edu
      address:
        street: BHEE 051, 465 Northwestern Ave
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
