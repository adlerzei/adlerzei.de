---
title: "Old Wiki"
description: "A browser extension that brings back the classic Wikipedia look."
summary: "Miss the old Wikipedia look? Old Wiki switches Wikipedia and its sister sites back to the classic Vector skin, automatically."
weight: 20
tags: ["browser extension", "javascript", "open source"]
---

{{< project-hero name="Old Wiki" logo="img/old-wiki-logo.png" since="2023" repo="adlerzei/old-wiki" chrome="https://chrome.google.com/webstore/detail/old-wiki/cphagceemhgokfclmbnkpfkmchbfnclb" firefox="https://addons.mozilla.org/en/firefox/addon/old-wiki/" >}}
Wikipedia, the way you remember it.
{{< /project-hero >}}

In early 2023 Wikipedia switched to a new default design. Honestly? I liked the old one better.

The good news: the old "Vector" skin is still there, you just have to ask for it on every single page.
Old Wiki does exactly that for you, on every Wikipedia language and on the other Wikimedia sites too.

## What it does

{{< features >}}
{{< feature icon="wand-magic-sparkles" title="Set it and forget it" >}}
Install it and every Wikipedia page opens in the classic layout. No account and no per-site settings.
{{< /feature >}}
{{< feature icon="language" title="Every language" >}}
English, German, Japanese, whatever you read: all language versions are covered.
{{< /feature >}}
{{< feature icon="globe" title="The whole Wikimedia family" >}}
Wiktionary, Wikiquote, Wikivoyage, Commons, Wikidata and more get the classic look as well.
{{< /feature >}}
{{< feature icon="eye" title="Clean address bar" >}}
The trick behind it stays hidden from your address bar, so links you copy look normal.
{{< /feature >}}
{{< /features >}}

## How it works

It's a simple trick. MediaWiki, the software behind Wikipedia, still ships the old skin. You just have to
ask for it in the URL:

<div class="az-urlbar">en.wikipedia.org/wiki/Red_fox</div>
<div class="az-urlbar">en.wikipedia.org/wiki/Red_fox<mark>?useskin=vector</mark></div>

<div class="az-howto">

{{< steps >}}
{{< step title="You open a Wikimedia page" >}}
Just like always, from a search, a bookmark or a link.
{{< /step >}}
{{< step title="Old Wiki adds the magic bit" >}}
The request gets `?useskin=vector` added before it even reaches Wikipedia.
{{< /step >}}
{{< step title="Wikipedia serves the classic look" >}}
And if you want, the extension keeps the address bar clean, too.
{{< /step >}}
{{< /steps >}}

{{< popup-shot src="img/old-wiki-popup.png" alt="The Old Wiki popup with the switches Apply vector skin, Auto reload and Hide URL query all turned on" width="320" >}}
Three switches: the classic skin itself, reloading your open Wikipedia tabs right away when you flip
it, and keeping the extra bit out of your address bar.
{{< /popup-shot >}}

</div>

### Supported sites

{{< chips >}}
Wikipedia, Wiktionary, Wikiquote, Wikibooks, Wikisource, Wikispecies, Wikinews, Wikiversity, Wikivoyage, Wikimedia Commons, Wikidata, MediaWiki, Meta-Wiki, Wikimedia Incubator, Wikimedia Cloud Services
{{< /chips >}}

## Want to help?

Something looks off, or is a Wikimedia site missing? Open an issue on
[GitHub](https://github.com/adlerzei/old-wiki). Pull requests are always welcome.

{{< alert "circle-info" >}}
This is a third-party extension and isn't affiliated with the Wikimedia Foundation or the Wikipedia team.
{{< /alert >}}
