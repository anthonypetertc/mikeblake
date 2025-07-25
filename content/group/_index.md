title: "Our Group"
subtitle: "We study X, Y, and Z."
# Use the existing People block
block: people
# Give this instance the id "group" (so you can link to it or style it)
id: group
weight: 30  # position on the home page; lower = higher up

# ----- What to show -----
content:
  # Option A: Show everyone except Alumni
  user_groups:
    - Principal Investigator
    - Postdocs
    - PhD Students
    - Research Assistants
  # OR, if you only want to exclude a group, some sites support:
  # exclude_user_groups:
  #   - Alumni

  # If you prefer to hand-pick the people instead of using groups:
  # authors:
  #   - alice-doe
  #   - bob-smith
  #   - carol-lee

  # Sort (these keys work if you set first_name/last_name in each profile)
  sort_by: last_name
  sort_ascending: true

# ----- How to show it -----
design:
  columns: 3              # Number of cards per row
  show_social: true
  show_interests: true
  show_role: true
  show_bio: true
  # Options that may exist in your version:
  # show_organizations: false
  # show_user_groups: false
---