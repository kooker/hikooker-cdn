---
layout: post
title: Hello World
tags: ['Git', 'Github']
---
{% include JB/setup %}

第一篇基于 jekyll 创建的文章

一点记录

    git clone https://github.com/kooker/hikooker-cdn.git
    cd hikooker-cdn
    git branch -r
    git checkout origin/gh-pages
    git checkout --orphan gh-pages
    git add .
    git commit -am "First Post"
    git commit -am "Add Post"
    git remote add origin https://github.com/kooker/hikooker-cdn.git
    git push origin -f gh-pages
    git push origin --delete gh-pages

