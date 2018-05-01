+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "projects"
active = true
date = "2018-04-11"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Database"
subtitle = "Bioinformatics database is the starting point and operating platform for all bioinformatics work"

# Order that this section will appear in.
weight = 20

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "base2"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 0

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.


[[filter]]
  name = "RNA"
  tag = ".rna"
  
[[filter]]
  name = "DNA"
  tag = ".dna"

[[filter]]
  name = "Gene Expression"
  tag = ".expression"
  

  
[[filter]]
  name = "Protein"
  tag = ".protein"
  
[[filter]]
  name = "Phenotype"
  tag = ".phenotype"
  
[[filter]]
  name = "Pathway"
  tag = ".pathway"

[[filter]]
  name = "Specialized"
  tag = ".specialized"
  
+++

