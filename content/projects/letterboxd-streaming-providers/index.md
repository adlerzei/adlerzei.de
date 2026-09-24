---
title: "Letterboxd Streaming Providers"
description: "A browser extension that adds a streaming service filter to Letterboxd."
summary: "A browser extension that adds a streaming service filter to Letterboxd, so you can see which movies are included in your streaming subscriptions."
weight: 10
tags: ["browser extension", "javascript", "open source"]
---

<div class="az-project-header">
  <img src="/img/lsp-logo.png" alt="Letterboxd Streaming Providers logo">
  <div class="az-facts">
    <span><strong>Since</strong> 2019</span>
    <span><strong>Platforms</strong> Chromium · Firefox</span>
    <span><strong>License</strong> MIT</span>
  </div>
</div>

{{< lead >}}
Which of the films on my Letterboxd watchlist can I actually stream right now?
{{< /lead >}}

**Letterboxd Streaming Providers** is a browser extension that adds a filter for streaming services
(e.g. Netflix, Amazon Prime Video) to [Letterboxd](https://letterboxd.com/). It lets you see at a
glance which movies are included in your streaming flat rate. I have been maintaining it since 2019.

{{< button href="https://chrome.google.com/webstore/detail/letterboxd-streaming-prov/egmanfnfgmljjmdncfoeghfmflhlmhpj" target="_blank" >}}Chrome Web Store{{< /button >}}
&nbsp;
{{< button href="https://addons.mozilla.org/en-US/firefox/addon/letterboxd-streaming-providers/" target="_blank" >}}Firefox Add-ons{{< /button >}}

## Features

- Filter any Letterboxd film list by the streaming services you subscribe to.
- Works in all countries supported by JustWatch: more than 130 of them.
- Available for all Chromium-based browsers (Chrome, Edge, Opera, Brave, …) and Firefox.

## How it works

The extension is built on the WebExtensions API. It uses the [TMDB](https://www.themoviedb.org/) API
to access streaming availability data, which is provided by [JustWatch](https://www.justwatch.com/).
Builds for Firefox and Chrome are produced automatically with GitHub Actions.

## Source code

{{< github repo="adlerzei/letterboxd-streaming-providers" showThumbnail=false >}}

Thanks to everyone using, supporting and contributing to the extension, and especially to
Philipp Emmer for the original idea.

{{< alert "circle-info" >}}
This is a third-party extension and is not affiliated with Letterboxd. It uses the TMDB API but is
not endorsed or certified by TMDB, and it uses information provided by JustWatch but is not endorsed
or certified by JustWatch.
{{< /alert >}}
