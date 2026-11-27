---
title: "Bienvenue sur mon blog"
date: 2026-11-27
draft: false
description: "Premier article : ce que vous trouverez ici."
summary: "Premier article : présentation du blog et des sujets abordés (AD, web, purple team)."
tags: ["blog", "meta"]
categories: ["Divers"]
---

## Pourquoi ce blog ?

Documenter ce que j'apprends, partager des writeups et garder une trace de mes recherches.

## Exemple de bloc de code

```bash
nxc smb 10.10.10.0/24 -u user -p 'Password123!' --shares
```

{{< alert icon="circle-info" >}}
Les shortcodes Blowfish (`alert`, `carousel`, `mermaid`, `badge`…) sont disponibles dans tous les articles.
{{< /alert >}}

## Exemple de diagramme

{{< mermaid >}}
graph LR
  A[Recon] --> B[Accès initial] --> C[Élévation] --> D[Domain Admin]
{{< /mermaid >}}
