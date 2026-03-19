+++
date = '{{ .Date | time.Format ":date_full" }}'
draft = false
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
tags = []
[params]
    author = 'Sage C'
[sites]
    [sites.matrix]
        languages = ['en', 'zh']
translationKey = '{{ .File.ContentBaseName }}'
+++