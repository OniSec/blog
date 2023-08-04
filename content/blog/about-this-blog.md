+++
title = "About this blog"
date = "2023-08-04T18:00:00-00:00"
author = "OniSec"
authorTwitter = "" #do not include @
cover = ""
tags = ["Cloudflare", "Hugo", "Privacy", "Setup"]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
color = "" #color from the theme settings
+++

Greetings,

I felt like it was necessary to provide some specific information about this blog, what is running, how it is set up, what it costs and how easy it is to build your own.

This blog is built on [Hugo](https://gohugo.io/), hosted by [Cloudflare](https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site/) (til I have enough content to justify migrating to a paid platform such as [WriteFreely](https://writefreely.org/) or hosting on a VPS like 1984 or privex). Currently, operational costs are less than $0.85/month. This is due to Cloudflare selling domains [at cost](https://www.cloudflare.com/products/registrar/) rather than making profit and buying this domain for $10.11 per year, for 10 years.

[This](https://github.com/janraasch/hugo-bearblog/) theme was specifically chosen to avoid Javascript, to minimize code that runs in your browser. For the base blog, no javascript is required.

Though I do recognize the irony of hosting with the [Cloudflare](https://unixsheikh.com/articles/stay-away-from-cloudflare.html) [honeypot](http://crimeflare.eu.org/), nothing being posted here is private as the goal is to freely share knowledge. Besides, I am using Cloudflare Pages as infrastructure so regardless if it is proxied or not the data still goes to Cloudflare. For the time being, this is the cheapest way to start this blog with as much customization. In the future, I will likely go the VPS route, at which point I'll run an [onion service](https://tb-manual.torproject.org/onion-services/) version for those who prefer onion services as I do.

For that reason, [TOR](https://www.torproject.org/) is supported, feel free to access this site using TOR. I would recommend using [Whonix](https://www.whonix.org/) or [Qubes OS](https://www.qubes-os.org/). Just keep in mind the site is configured to high security, so if the exit node you're using was seen demonstrating attacker behavior in the last 14 days you'll probably get hit with a captcha. Depending on how it goes I may change the settings to be more friendly to TOR users. Please send feedback on your experience via Session.

While the intention is to avoid using javascript, Cloudflare does inject some javascript.

- `https://onisec.org/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js` 
    - This is used to decode my email address to prevent scraping, though the address isn't used for anything other than to be a contact address for this blog.
- `https://static.cloudflareinsights.com/beacon.min.js`
    - Cloudflare analytics: provides data on bandwidth usage, top countries visiting, performance data, client versions like how many visitors use HTTP/3, how many have adopted TLS 1.3. If you're interested in seeing the analytics let me know and I can do a blog post on what it looks like from the Cloudflare dashboard.

There is javascript in Gitbook and it is not FOSS. I can't really do anything about that if I want the features that it comes with. If you have any recommendations as an alternative, let me know as I am researching as well. Logseq is looking good, but I have not used it so I'm asking around.

I may disable the `beacon.min.js` in the future. At this point I am still figuring out the platform, but I have no desire to know specific details about visitors. Still interesting to see spikes in activity from different countries.