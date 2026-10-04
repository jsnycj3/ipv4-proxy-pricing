# buy ipv4 proxy: what you're actually paying for, 9Proxy's real per-IP rates, and how not to overpay

Type "buy ipv4 proxy" into a search box and you get a wall of price tables. Most of them quote a number you will never pay — the headline rate is usually the 500,000-IP tier, while the 100-IP package sitting in your cart costs several times more per address.

So before any plan tables, it's worth separating the two things people mean by this search.

## First: which kind of IPv4 proxy are you actually buying?

"IPv4" tells you the address family, not the product. Three very different things get sold under that label:

**Datacenter proxies.** Hosted on cloud subnets. Fast, cheap per IP, and widely flagged. Fine for pulling public data from sites that don't check ASN origin.

**Static residential (ISP) proxies.** Real ISP-assigned addresses hosted on datacenter hardware, so they stay yours for a month or longer. This is what most account-based work actually needs — logins, seller dashboards, ad accounts.

**Rotating residential proxies.** Addresses from real home connections, sold in a pool you draw from. Either you buy a fixed number of IPs with unlimited bandwidth, or you buy a traffic allowance and rotate.

The IPv4 part matters because the cheap end of the market has quietly moved to IPv6. IPv6 addresses are abundant, so providers can sell hundreds of thousands of them for almost nothing — and then you discover that most social platforms, marketplaces, payment systems and ad networks either reject IPv6 outright or treat it as a bot signal. IPv4 is the address family that still works against the targets people care about.

If you already know which of the three types you need, you can skip ahead. If you're not sure, the rest of this is organized so you can find out in about two minutes.

## Three questions that decide your bill

**1. Does the same IP have to persist?**
If a task breaks when the address changes mid-session — a logged-in dashboard, a checkout flow, an account you're warming up — you're in the per-IP model. If every request can come from a different address, traffic-based billing is usually cheaper.

**2. Are you paying per IP or per GB?**
Per-IP with unlimited bandwidth inverts the math: scraping 100 pages or 10,000 pages through the same address costs the same. Per-GB flips it back — cheap for light requests, expensive the moment you're pulling images, video, or large product catalogs.

**3. How many IPs need to be live at once?**
Concurrency is the number that actually drives spend. Ten thousand IPs in inventory you never run in parallel is $10,000 of unused balance.

## Where 9Proxy fits into that picture

9Proxy runs a residential network — its own documentation describes 20M+ residential IPs across 90+ countries, with targeting that goes down to country, city, ZIP code and ISP. Protocols are HTTP/HTTPS and SOCKS5, which covers the standard scraping stacks, antidetect browsers and automation tools.

Two billing models, and they behave quite differently:

- **Residential by IPs.** You buy a quantity of addresses. Bandwidth is unmetered while an IP is active, and unused IPs never expire. Each address stays usable for a few hours up to roughly 24 hours — so this is *not* a permanent static IPv4 lease.
- **Residential by GB.** You buy a traffic allowance and generate endpoints on demand, in rotating or sticky mode. Traffic is valid 180 days, or unlimited on the enterprise GB tiers.

One honest caveat for this particular search: the documentation doesn't publish an IPv4/IPv6 breakdown of the pool. The addresses come from real residential connections, which in practice means IPv4, and the targeting is sold by country/city/ZIP/ISP rather than by address family. If your stack has a hard IPv4-only routing requirement, confirm it with support before you pay rather than assuming.

👉 [Check what 9Proxy's residential pool covers](https://bit.ly/9-Proxy)

## The June 2026 price change you need to know about

9Proxy raised prices on its IP-based and bundle packages on June 1, 2026 — the first adjustment in the company's history. GB-based packages were explicitly left untouched. The tables below use the post-adjustment numbers, because those are the ones you'll see at checkout.

The headline rate is now **$0.018 per IP at the 500,000-IP tier** and **$0.68 per GB at the 10,000 GB tier**. You'll still find older comparison pages quoting $0.015/IP; that number predates the change.

### IP-based residential packages

Bandwidth is unmetered on every tier. Price is a one-time charge; unused IPs don't expire.

| Package | Price per IP | Total | Purchase |
| --- | --- | --- | --- |
| 100 IPs | $0.24 | $24 | [Get the 100 IP package](https://bit.ly/9-Proxy) |
| 500 IPs | $0.144 | $72 | [Get 500 residential IPs](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | $0.084 | $126 | [Get 1,500 IPs for $126](https://bit.ly/9-Proxy) |
| 2,500 IPs | $0.084 | $210 | [Get 2,500 IPs](https://bit.ly/9-Proxy) |
| 5,000 IPs | $0.072 | $360 | [Get 5,000 IPs](https://bit.ly/9-Proxy) |
| 15,000 IPs | $0.048 | $720 | [Get 15,000 IPs](https://bit.ly/9-Proxy) |
| 25,000 IPs | $0.035 | $863 | [Get 25,000 IPs](https://bit.ly/9-Proxy) |
| 50,000 IPs | $0.029 | $1,438 | [Get 50,000 IPs](https://bit.ly/9-Proxy) |
| 100,000 IPs | $0.023 | $2,300 | [Get the 100,000 IP business package](https://bit.ly/9-Proxy) |
| 200,000 IPs | $0.021 | $4,140 | [Get the 200,000 IP business package](https://bit.ly/9-Proxy) |
| 500,000 IPs | $0.018 | $8,625 | [Get the 500,000 IP business package](https://bit.ly/9-Proxy) |

The 1,000 + 500 tier is the one worth staring at. At $126 it lands at the same effective per-IP cost as the 2,500 package, which makes it the natural first step if you're testing whether residential IPv4 works against your targets before committing to volume.

### GB-based residential packages

Pay for traffic, generate as many endpoints as you want. No fixed IP count.

| Package | Price per GB | Total | Validity | Purchase |
| --- | --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | 180 days | [Get the 5 GB pack](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $2.10 | $105 | 180 days | [Get the 55 GB pack](https://bit.ly/9-Proxy) |
| 100 GB | $1.50 | $150 | 180 days | [Get 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | $1.00 | $200 | 180 days | [Get 200 GB](https://bit.ly/9-Proxy) |
| 1,000 GB | $0.80 | $800 | 180 days | [Get 1,000 GB](https://bit.ly/9-Proxy) |
| 2,000 GB | $0.75 | $1,500 | 180 days | [Get 2,000 GB](https://bit.ly/9-Proxy) |
| 3,000 GB (Enterprise) | $0.72 | $2,160 | No expiry | [Get the 3,000 GB enterprise pack](https://bit.ly/9-Proxy) |
| 6,000 GB (Enterprise) | $0.70 | $4,200 | No expiry | [Get the 6,000 GB enterprise pack](https://bit.ly/9-Proxy) |
| 10,000 GB (Enterprise) | $0.68 | $6,800 | No expiry | [Get the 10,000 GB enterprise pack](https://bit.ly/9-Proxy) |

Note the cliff between the 5 GB pack at $3.00/GB and the 55 GB pack at $2.10/GB. If you're rotating at any real volume, the small pack exists for testing, not for production.

### Bundle packages (IPs + GB)

| Bundle | Includes | Total | Purchase |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | [Get the Starter bundle](https://bit.ly/9-Proxy) |
| Growth | 1,500 IPs + 50 GB | $180 | [Get the Growth bundle](https://bit.ly/9-Proxy) |
| Pro | 5,000 IPs + 500 GB | $720 | [Get the Pro bundle](https://bit.ly/9-Proxy) |

Bundled traffic on these carries the same 180-day validity as the standalone GB packs.

## IP-based vs GB-based: the differences that actually bite

|  | Residential by IPs | Residential by GB |
| --- | --- | --- |
| Billing | Fixed package by IP count | Fixed package by traffic |
| Usage period | Until you've used the IPs — no expiry | 180 days (unlimited on Enterprise) |
| IP lifetime | A few hours up to ~24h | Rotates per request or per sticky session |
| Traffic cap | None while an IP is active | Capped by purchased GB |
| Rotation | No natural rotation; auto-rotation available on selected ports | Rotating or sticky, configurable |
| Authentication | Requires the 9Proxy desktop app (local port forwarding, optional proxy auth) | Username/password or IP whitelist |
| Setup | Desktop client needed | Straight from the dashboard |

That authentication row is the one people miss. The per-IP model runs through a desktop app, which is fine if you're on a machine you control and awkward if you're deploying to a remote server. The GB model talks directly to the dashboard with credentials, so it slots into containers and CI more easily.

## What to check before you pay

**Refund terms.** Geekflare's review notes that the negative Trustpilot reviews cluster around refund expectations rather than the IP quality itself — people bought a plan that didn't fit their use case and couldn't recover the spend. Read the policy, then buy the smallest package that can answer your question.

**The hourly IP lifetime.** If your task needs a *static* IPv4 address — a permanent login identity, a whitelisted endpoint, a persistent seller account — the IP-based residential packages are the wrong shape, and you should be looking at an ISP/static residential product instead.

**Whether a desktop app is acceptable.** Per-IP plans need it.

**Payment methods.** 9Proxy accepts credit cards, bank cards, Alipay, Apple Pay, Google Pay and crypto (USDT, BTC, ETH, LTC, DOGE and others). Crypto matters if your card issuer is twitchy about proxy merchants.

**Trial access.** There's no self-serve free trial on the site. The company has said on its own channels that it hands out a limited number of trials to new users depending on availability, and that you need to specify whether you want an IP-based or GB-based trial when you ask. Support via live chat is the route.

## How buying works, start to finish

1. Create an account through the referral sign-up link — the referral program advertises a 5% discount to referred users, which is applied to your order rather than typed in as a coupon.
2. Pick the model first, then the size. IP-based if sessions must hold; GB-based if requests can rotate.
3. Check out. If you have a coupon code from a past promotion, the field is on the checkout page, and the discount shows in the order summary before you confirm. Codes from the April GB promotion and the Lunar New Year sale have expiry dates that have already passed, so don't count on either.
4. Complete payment by card, wallet or crypto.
5. For IP-based plans, install the desktop client, sign in, and the IP list appears there. For GB plans, copy the credentials from the dashboard into your tool.

👉 [Start a 9Proxy account and pick a plan](https://bit.ly/9-Proxy)

## buy ipv4 proxy: the questions that show up right before checkout

**Does 9Proxy sell IPv4 or IPv6 addresses?**
The published product documentation describes two residential models and sells targeting by country, city, ZIP and ISP. There's no published IPv4/IPv6 split, so if your target environment requires an IPv4-only exit, ask support to confirm before purchasing.

**Do the IPs stay the same forever?**
No. On per-IP plans each address holds for a few hours to about 24 hours, with no natural rotation. Unused IPs in your balance don't expire.

**What does "unlimited bandwidth" mean here?**
On IP-based packages, traffic through an active IP isn't metered — one address pulling 100 pages and 10,000 pages costs the same $0.24. The constraint is how many IPs you bought and how many you can run at once.

**Can I use SOCKS5?**
Yes, alongside HTTP/HTTPS.

**Is there a minimum commitment or subscription?**
No. Packages are one-off balance purchases rather than recurring monthly subscriptions.

**How does the performance look from outside?**
Geekflare's testing recorded a 97.7% success rate against Cloudflare-protected targets and described the IP pool as good enough for most scraping, research and testing work, while noting it isn't the largest pool on the market and lacks the enterprise tooling of the big incumbents.

## Who should buy here, and who shouldn't

Buy the per-IP packages if you need residential IPv4 addresses with unpredictable bandwidth usage and you'd rather your cost be capped by IP count than by gigabytes. The $24 entry point is genuinely low, and the unlimited-bandwidth model means a heavy scraping job doesn't blow past a traffic allowance on day three.

Buy the GB packages if your requests rotate freely and you want to draw from the full 20M+ pool without managing inventory.

Skip it if you need permanent static IPv4 addresses with month-long or longer lifetimes — that's an ISP proxy product, and 9Proxy's residential IPs turn over in under a day. Skip it too if you need a self-serve free trial before paying; there isn't one, and the refund path has generated enough complaints that "buy small first" is the safer sequencing.

👉 [Compare the current 9Proxy IP and GB packages](https://bit.ly/9-Proxy)
