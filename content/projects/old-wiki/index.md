---
title: "Old Wiki"
description: "A browser extension that brings back the classic Vector layout on Wikipedia and other Wikimedia sites."
summary: "A browser extension that switches Wikipedia and other Wikimedia sites back to the beloved classic Vector layout."
weight: 20
tags: ["browser extension", "javascript", "open source"]
---

{{< lead >}}
Prefer the classic Wikipedia look? Old Wiki brings it back automatically.
{{< /lead >}}

**Old Wiki** is a browser extension that changes the Wikipedia user interface back to the classic
Vector layout. It works on all language versions and on the other Wikimedia projects too. I started
it in 2023, when Wikipedia switched to its new default skin.

{{< button href="https://chrome.google.com/webstore/detail/old-wiki/cphagceemhgokfclmbnkpfkmchbfnclb" target="_blank" >}}Chrome Web Store{{< /button >}}
&nbsp;
{{< button href="https://addons.mozilla.org/en/firefox/addon/old-wiki/" target="_blank" >}}Firefox Add-ons{{< /button >}}

## Supported sites

Wikipedia, Wiktionary, Wikiquote, Wikibooks, Wikisource, Wikispecies, Wikinews, Wikiversity,
Wikivoyage, Wikimedia Commons, Wikidata, MediaWiki, Meta-Wiki, Wikimedia Incubator and
Wikimedia Cloud Services.

## How it works

Simple and lightweight: the extension appends `?useskin=vector` to requests to Wikimedia sites,
which tells MediaWiki to render the page with the legacy Vector skin. No account or settings needed.
It runs in Chrome, Firefox, Edge, Brave and Opera.

## Source code

{{< github repo="adlerzei/old-wiki" showThumbnail=false >}}

{{< alert "circle-info" >}}
This is a third-party extension and is not affiliated with the Wikimedia Foundation or the Wikipedia
developer team.
{{< /alert >}}
