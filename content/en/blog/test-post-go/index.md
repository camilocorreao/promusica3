---
title: "TEST"
date: 2023-09-03T16:29:51+02:00
draft: false
categories: ["voice"]
tags: [Rodrigo, Monsalvage]
images: []
---

<iframe src="//player.bilibili.com/player.html?bvid=BV1jz4y1f7yo&page=1&high_quality=1&danmaku=0"
        scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>

Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ratione sit fuga ea omnis, veritatis perspiciatis minima ab porro. Consequuntur, sunt. Nobis ducimus veritatis aspernatur ipsam provident quam, incidunt iste sed ab veniam! Doloremque eligendi tempore numquam, nemo asperiores veniam, cumque voluptatem eos laboriosam commodi quaerat excepturi, placeat corporis facilis quis.

{{< img-index "0" "Test Post Picture" >}}

```go-html-template
{{/*  production options  */}}
{{- $opts := dict "minify" true "target" "es2015" -}}
{{- /*  development options  */ -}}
{{- if eq hugo.Environment "development" -}}
{{- $opts = dict "sourceMap" "inline" "target" "es2015" -}}
{{- end -}}
{{- $built := resources.Get . | js.Build $opts | fingerprint }}

<script type="text/javascript" src="{{ $built.RelPermalink }}" integrity="{{ $built.Data.Integrity }}"></script>
```
