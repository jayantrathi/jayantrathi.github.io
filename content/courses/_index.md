---
title: Courses
summary: My courses
type: landing

cascade:
  - target:
      path: '{/courses/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: courses
    content:
      title: Courses
      filters:
        tag: Course
      # To show all pages, count: 0
      count: 0
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 3
---
