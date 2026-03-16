---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Research Assistants
          - Grad Students
          - Administration
          - Visitors
          - Collaborators
          # - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true
      show_organizations: true

  - block: markdown
    content:
      title: Collaborators Across the Globe
      text: |
        {{< collaborators_map >}}
    design:
      columns: '1'
---