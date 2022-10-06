<!--
Add here global page variables to use throughout your website.
-->
+++
author = "JuliaCN"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "JuliaCN Meetups"
website_descr = "JuliaCN meetup website"
prepath = get(ENV, "PREVIEW_FRANKLIN_PREPATH", "meetup-website") # In the third argument put the prepath you normally use
website_url = get(ENV, "PREVIEW_FRANKLIN_WEBSITE_URL", "cn.julialang.org") # Just put the website name
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
