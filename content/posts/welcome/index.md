---
title: "Welcome to my blog"
date: 2026-11-27
draft: false
description: "First post: what you'll find here."
summary: "First post: an introduction to the blog and its topics — SOC, detection engineering, purple teaming."
tags: ["blog", "meta"]
categories: ["Misc"]
---

## Why this blog?

To document what I learn, share writeups and keep track of my research — from the alert in the SIEM
to the technique that triggered it.

## Code block example

```bash
nxc smb 10.10.10.0/24 -u user -p 'Password123!' --shares
```

{{< alert icon="circle-info" >}}
Blowfish shortcodes (`alert`, `carousel`, `mermaid`, `badge`…) are available in every post.
{{< /alert >}}

## Diagram example

{{< mermaid >}}
graph LR
  A[Emulate<br/>red] --> B[Detect<br/>blue] --> C[Tune rule] --> D[Re-test<br/>purple]
  D --> A
{{< /mermaid >}}
