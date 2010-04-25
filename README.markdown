---
layout: default
branch: projects
title: README
description: Quick project overview and tutorial on using this blogging template.
---

### Project purpose:
* Refresh myself on using git
* Create an online CV with project links to be hosted by githubpages

### Site design:
jekyll extended blog template
* Home page with custom content and list of posts organized by site branch and reverse chronological order
* Site banner with title & tag
* Branch navigation menu that returns to branch's anchored position on home page

### Site functionality:
Template is in place to provide generic, quick blogging solution. Follow these steps to get started:
  1. Look over [mojombo's jekyll tutorial](http://wiki.github.com/mojombo/jekyll/)
  2. Setup _config.yml variables
    * title - Name of your blog, used as title and main header
    * description - tag for your blog that's displayed with title
    * branches - The main organization of your blog, posts assigned to a branch will be listed under that branch. Branches are displayed in order in both the navigation menu and post list.
  3. Create posts with these variables in the YAML front matter block:
      layout: post
      branch: <name of branch which contains post>
      title: <post title>
      description : <short post description>

That's about it. Add style sheets, some homepage content, create new templates or extend existing ones, and have fun.

### TODO:
  * basic CSS style sheet
  * Add footer section
    


