---
title: "{{ replaceRE `([0-9]{2})([0-9]{2})` .Name `20${1}年${2}月` }}"
date: {{ .Date }}
type: diary
draft: false
---

{{</* entry date="20XX年MM月DD日" */>}}
ここに本文を書く
{{</* /entry */>}}
