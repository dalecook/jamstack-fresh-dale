---
title: Home
sections:
- type: heroblock
  template: heroblock
  section_id: hero
  component: hero_block.html
  content: ''
  title: Dale Cook
  actions: []
- type: contentblock
  template: contentblock
  title: About
  section_id: about
  actions:
  - label: Contact Me
    url: "/contact"
  component: content_block.html
  content: This is the "about" excerpt. It can be used to provide a paragraph about
    yourself that people can read on the homepage to get a sense of who you are. There
    also exists a dedicated about page where you can write more about yourself for
    those who are interested.
  image: ''
- type: postsblock
  template: postsblock
  title: Recent Posts
  section_id: recent-posts
  actions:
  - label: View Blog
    url: blog/index.html
  component: posts_block.html
  num_posts_displayed: 4
layout: home
menu:
  main:
    weight: 1

---
