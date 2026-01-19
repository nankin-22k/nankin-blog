---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
slug: "{{ .Name | replaceRE `^[0-9]{4}-[0-9]{2}-[0-9]{2}-` `` | lower }}"
robots: "noindex"
draft: false
secret_tags:
  - "タグ1"
  - "タグ2"
secret_categories:
  - "カテゴリー"
---