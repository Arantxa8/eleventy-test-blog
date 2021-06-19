---
layout: layouts/blog.njk
tags: blog
title: Pseudocode for fix start
date: 2021-06-19T16:45:33.497Z
thumbnail: /images/uploads/_20210619_174419.jpg
rating: 4
---
FUNCTION fixStart(inputString)
  VARIABLE firstCharacter = GET FIRST CHARACTER OF inputString
  VARIABLE newString = REMOVE FIRST CHARACTER FROM inputString
  newString = newString REPLACE firstCharacter WITH "*"
  RETURN firstCharacter + newString 