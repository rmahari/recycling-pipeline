# Recycling Pipeline

MIT Media Lab Great Problems course MAS.S67 midterm assignment

what is the life cycle of our recycled goods ??


### Local view
Massachusetts data pulled from [https://www.mass.gov/lists/recycling-solid-waste-data-for-massachusetts-cities-towns](MassDEP)


### visualization methods

[https://docs.bokeh.org/en/latest/index.html](Bokeh) - basically write javascript+html visualization in python without needing to do any of the javascript yourself



# jekyll instructions
install jekyll following installation quickstart instructions [https://jekyllrb.com/docs/](here).

for some reason with ruby 3.0.0 bundle exec jekyll serve fails because it needs the webrick package, just install it with `bundle add webrick`

then install the just-the-docs theme: `gem install just-the-docs`
which requires rake so add it to the ruby bundle: `bundle add rake`

Then you can add new markdown pages, just preface them with the jekyll header
```
---
layout: page
title: Data Viz
nav_order: 1
nav_exclude: false
---
```

To view the site locally run
`bundle exec jekyll serve`
