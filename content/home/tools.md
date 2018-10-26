+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "projects"
active = true
date = "2018-04-11"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Software"
subtitle = "Here we provide some popular tools for various kinds of fields."

# Order that this section will appear in.
weight = 30

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "too2"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 1

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "Genomics"
  tag = ".genomics"

[[filter]]
  name = "Epigenomics"
  tag = ".epigenomics"
  
[[filter]]
  name = "Transcriptomics"
  tag = ".transcriptomics"

[[filter]]
  name = "Proteomics"
  tag = ".proteomics"
  
[[filter]]
  name = "Metabolomics"
  tag = ".metabolomics"
[[filter]]
  name = "Phenomics"
  tag = ".phenomics"

+++

