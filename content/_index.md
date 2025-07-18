---
# This file controls your homepage layout.
type: landing

sections:
  - block: about.biography
    id: about
    content:
      # The username of the author to display (should match the folder name in content/authors/)
      username: admin

  - block: portfolio
    id: projects
    content:
      title: Research Projects
      # Choose how many projects to show on the homepage (0 = all)
      count: 0
      # Order projects by date or title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # See options at https://docs.hugoblox.com/widgets/portfolio/
      view: showcase
---
