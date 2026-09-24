---
title: "Letterboxd Streaming Providers"
description: "A browser extension that shows you which films on Letterboxd you can stream right now."
summary: "Which films on your Letterboxd watchlist can you actually stream tonight? This extension fades out everything that isn't on your streaming service."
weight: 10
tags: ["browser extension", "javascript", "open source"]
---

{{< project-hero name="Letterboxd Streaming Providers" logo="img/lsp-logo.png" since="2019" repo="adlerzei/letterboxd-streaming-providers" chrome="https://chrome.google.com/webstore/detail/letterboxd-streaming-prov/egmanfnfgmljjmdncfoeghfmflhlmhpj" firefox="https://addons.mozilla.org/en-US/firefox/addon/letterboxd-streaming-providers/" >}}
Your watchlist is huge. Your evening isn't. Find out what you can actually stream tonight.
{{< /project-hero >}}

If you use [Letterboxd](https://letterboxd.com/), you probably know the problem: a watchlist full of
films you really want to see, and no idea which of them are on the streaming service you're paying for.
Checking them one by one gets old fast.

So I built a small browser extension for it back in 2019, and I've been looking after it ever since.
You tell it where you live and which streaming service you have, and it fades out every film you can't
stream there. What's left is your shortlist for tonight.

## What it does

{{< features >}}
{{< feature icon="eye" title="See it at a glance" >}}
Films that aren't on your streaming service fade into the background. The ones you can watch right now stand out.
{{< /feature >}}
{{< feature icon="globe" title="Works where you are" >}}
Every country JustWatch covers is supported. That's more than 130 at the moment.
{{< /feature >}}
{{< feature icon="list" title="Not just your watchlist" >}}
It works on watchlists, lists, liked films and the film browsing pages, yours or anyone else's.
{{< /feature >}}
{{< feature icon="code" title="Free and open source" >}}
No account, no ads. The code is MIT-licensed and lives on GitHub.
{{< /feature >}}
{{< /features >}}

## How it works

{{< steps >}}
{{< step title="Pick your country and service" >}}
Click the extension icon, choose your country and your streaming service, and switch the filter on.
{{< /step >}}
{{< step title="Open any list on Letterboxd" >}}
The extension collects the films on the page you're looking at.
{{< /step >}}
{{< step title="It checks what's streaming" >}}
For each film it asks [TMDB](https://www.themoviedb.org/) where it's available. That data comes from [JustWatch](https://www.justwatch.com/).
{{< /step >}}
{{< step title="Everything else fades out" >}}
Films that aren't on your service get dimmed. Switch the filter off and everything goes back to normal.
{{< /step >}}
{{< /steps >}}

<details class="az-more">
<summary>Show all supported countries</summary>

{{< chips >}}
Andorra, United Arab Emirates, Antigua and Barbuda, Albania, Angola, Argentina, Austria, Australia, Azerbaijan, Bosnia and Herzegovina, Barbados, Belgium, Burkina Faso, Bulgaria, Bahrain, Bermuda, Bolivia, Brazil, Bahamas, Belarus, Belize, Canada, Congo, Switzerland, Cote D'Ivoire, Chile, Cameroon, Colombia, Costa Rica, Cuba, Cape Verde, Cyprus, Czech Republic, Germany, Denmark, Dominican Republic, Algeria, Ecuador, Estonia, Egypt, Spain, Finland, Fiji, France, United Kingdom, French Guiana, Ghana, Gibraltar, Guadaloupe, Equatorial Guinea, Greece, Guatemala, Guyana, Hong Kong, Honduras, Croatia, Hungary, Indonesia, Ireland, Israel, India, Iraq, Iceland, Italy, Jamaica, Jordan, Japan, Kenya, South Korea, Kuwait, Lebanon, St. Lucia, Liechtenstein, Lithuania, Luxembourg, Latvia, Libyan Arab Jamahiriya, Morocco, Monaco, Moldova, Montenegro, Madagascar, Macedonia, Mali, Malta, Mauritius, Malawi, Mexico, Malaysia, Mozambique, Niger, Nigeria, Nicaragua, Netherlands, Norway, New Zealand, Oman, Panama, Peru, French Polynesia, Papua New Guinea, Philippines, Pakistan, Poland, Palestinian Territory, Portugal, Paraguay, Qatar, Romania, Serbia, Russia, Saudi Arabia, Seychelles, Sweden, Singapore, Slovenia, Slovakia, San Marino, Senegal, El Salvador, Turks and Caicos Islands, Chad, Thailand, Tunisia, Turkey, Trinidad and Tobago, Taiwan, Tanzania, Ukraine, Uganda, United States of America, Uruguay, Holy See, Venezuela, Kosovo, Yemen, South Africa, Zambia, Zimbabwe
{{< /chips >}}

</details>

## Want to help?

Found a bug, or is your streaming service missing? Open an issue on
[GitHub](https://github.com/adlerzei/letterboxd-streaming-providers). Pull requests are always welcome.

{{< alert "circle-info" >}}
This is a third-party extension and isn't affiliated with Letterboxd. It uses the TMDB API but isn't
endorsed or certified by TMDB, and it uses data from JustWatch but isn't endorsed or certified by JustWatch.
{{< /alert >}}
