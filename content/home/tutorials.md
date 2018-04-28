+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "projects"
active = true
date = "2018-04-11"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Tutorials"
subtitle = "Bioinformatics is a computional biology, here we provide some tutorials for the common tools of bioinformatics"

# Order that this section will appear in.
weight = 10

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "tutorial"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.

[[filter]]
  name = "Getting started with R"
  tag = ".start"
  
[[filter]]
  name = "BMS4001_part1"
  tag = ".bms4001_p1"

[[filter]]
  name = "BMS4001_part2"
  tag = ".bms4001_p2"

[[filter]]
  name = "Find More"
  tag = ".online"
  

+++

