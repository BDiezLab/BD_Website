---
# An instance of the People widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Meet the BD Team
subtitle:

content:
  # Page type to display. E.g. project.
  page_type: people
  
  reading_time: true
  share: false

  # Choose which groups/teams of users to display.
  #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
  user_groups:
  - Principal Investigator
  - Staff
  - Postdoctoral Fellow
  - Grad Students
  - Undergraduate
  - Visitors
  - Researchers Network
  - Former Lab Members
  
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: Current Members
  - name: Staff
    tag: Staff
  - name: Postdocs
    tag: Postdoctoral Fellow
  - name: Grad Students
    tag: Grad Students
  - name: Undergraduate
    tag: Undergraduate
  - name: Former Members
    tag: Former Lab Members

design:
  show_image: true
  show_social: true
  show_interests: true
  show_role: true

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2
  
  # For Showcase view, flip alternate rows?
  flip_alt_rows: true
---