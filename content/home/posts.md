+++
# Recent Posts widget.
# This widget displays recent posts from `content/post/`.
# UPDATE: changed to have it behave more like projects, in order to be able to include list and filter toolbar. To revert back to original "posts" layout, rename posts_orig.md posts.md and change this to posts_proj.md (and change active = false)
widget = "projects"
active = true
date = "2016-04-20T00:00:00"

title = "Recent Posts"
subtitle = ""

# Order that this section will appear in.
weight = 5

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "post"

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
  name = "All"
  tag = "*"
  
[[filter]]
 name = "R-Ladies"
 tag = ".r-ladies"

[[filter]]
 name = "R"
 tag = ".R"

[[filter]]
 name = "PhD"
 tag = ".phd"
 
[[filter]]
 name = "Praat"
 tag = ".praat"
 
[[filter]]
 name = "SLP"
 tag = ".slp"
+++