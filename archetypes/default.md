---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
slug: "{{ .Name | lower }}"
draft: false
tags:
  - "タグ1"
  - "タグ2"
categories:
  - "カテゴリー"
---