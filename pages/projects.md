---
title: Projects - Adkimsm
display: Projects
subtitle: List of projects that I am proud of
description: List of projects that I am proud of
plum: true
projects:
  Clis:
    - name: 'Create OSP'
      link: 'https://github.com/Adkimsm/create-osp'
      desc: 'A Create Starter Template for Open Source Project in Node.js'
      icon: 'i-mdi-clock-fast'
    - name: 'Yun Gen'
      link: 'https://github.com/Adkimsm/yue-gen'
      desc: 'generate yue.css html'
      icon: 'i-mdi-clock-fast'

  Themes:
    - name: "Typora Theme Panfrie"
      link: "https://github.com/Adkimsm/typora-theme-panfrie"
      desc: "a theme for Typora,Based on panda."
      icon: 'i-mdi-clock-fast'
    - name: "Cnblogs Theme CnGth"
      link: "https://github.com/Adkimsm/Cnblogs-Theme-CnGth"
      desc: "老牛逼了"
      icon: 'i-mdi-clock-fast'
    - name: "Hexo Theme G"
      link: "https://github.com/Adkimsm/hexo-theme-g"
      desc: "A theme Form Typecho."
      icon: 'i-mdi-clock-fast'
    - name: "Hexo Theme NanoAs"
      link: "https://github.com/Adkimsm/hexo-theme-nanoas"
      desc: "A white and simple hexo theme, originated from a Farbox theme."
      icon: 'i-mdi-clock-fast'
---

<ListProjects :projects="frontmatter.projects" />

<StarsRanking />
