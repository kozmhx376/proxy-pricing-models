# Cheap Rotating Residential Proxies: How Per-GB and Per-IP Pricing Change Your Real Cost, and Which 9Proxy Plan Fits

Most people searching for cheap rotating residential proxies are chasing the same number: dollars per gigabyte. That number is real, but on its own it answers the wrong question. Two providers can both say "$1 per GB" and end up costing wildly different amounts for the same scraping job, because the thing you actually buy is not bandwidth. It's successfully completed requests.

So before looking at any price table, it helps to separate the cost models, because they fail in different ways.

## Why the lowest per-GB figure rarely wins on its own

A rotating residential proxy rotates your exit IP. With per-request rotation, every request can leave through a different address from a pool that typically runs into the tens of millions of IPs. That spreads your traffic across many addresses, which is why rotating residential works on targets that block datacenter ranges outright.

Cheap, in this market, usually means one of three things: a small pool, loose IP hygiene, or a pricing model that looks attractive at the tier you'll never reach. All three show up as re-requests and retries, and retries consume bandwidth. A $1.00/GB provider that fails one request in five on your target can cost more than a $1.50/GB provider that gets through.

That's the honest framing. Now the mechanics.

## The two billing models, and which one is cheaper for your workload

### Pay per IP, run unlimited bandwidth through it

Here you buy a block of residential IPs and use them for as long as their session lasts. Data doesn't count against you. For workflows with unpredictable or heavy transfer — long browser sessions, video-adjacent pages, big JSON payloads — this is the model that removes the anxiety of watching a GB meter.

The trade-off is that IPs are a finite resource with a natural lifespan. Residential addresses stay online for a few hours up to roughly a day depending on the device behind them, and in 9Proxy's model one forwarded IP counts as one usage. So the model rewards serial work, not thousands of parallel threads.

### Pay per GB, generate as many endpoints as you want

Here you buy traffic and generate proxy endpoints yourself, without paying an activation fee per address. 9Proxy's GB-based system allows unlimited endpoint generation, with billing measured only in consumed traffic, and it's the model that maps directly onto rotating residential work: you point a scraper at the gateway, request rotation, and burn a small amount of data per page.

The catch is expiry. Unused traffic that dies on the shelf is the single most common way budget proxy spend gets wasted.

> 9Proxy's GB-based packages carry a 180-day validity window. The Enterprise GB tiers are the ones with unlimited data validity, and those include team mode for one owner plus up to five members with shared, non-expiring bandwidth.

If your projects come in bursts, a 180-day window is workable. If your projects are truly sporadic across a year, it isn't, and that's worth factoring in before you buy the big pack to get the better per-GB rate.

## What "cheap" looks like across the market right now

It's worth calibrating. Published entry residential rates across well-known providers currently sit in a wide band: DataImpulse starts around $1/GB, Webshare at roughly $1.75 for a 1 GB entry pack, Proxy-Cheap at $1.99/GB, Decodo from about $4/GB, IPRoyal at $7 for 1 GB, and Oxylabs at $30 for 5 GB [1][2]. 9Proxy's entry GB package comes in at $3.00/GB for 5 GB, which is not the cheapest headline figure in that list.

The picture flips at volume. 9Proxy's per-GB rate drops through the tiers to $0.68/GB at the 10,000 GB Enterprise level, and because the GB tiers are pay-as-you-go rather than monthly subscriptions, you're not paying a recurring fee for capacity you didn't use.

For context on how third parties position it: comparison trackers place 9Proxy in the budget residential bracket at roughly $0.70–$2/GB, and ProxyLook rates it 3.9/5 with a 20M+ IP, 90+ country footprint [3][4]. One independent comparison also flags things it doesn't do well, which is covered further down.

## 9Proxy plans and prices, in full

9Proxy sells balance-based packages rather than monthly subscriptions. Pricing changed on 1 June 2026 for IP-based and bundle packages; the company's own announcement states GB-based package prices were left unchanged [5].

### IP-based residential packages

Fixed number of IPs, unlimited bandwidth per active IP, and unused IPs don't expire. These are the packages you want for sticky, session-heavy work.

| Package | What you get | Price | Billing type | Get it |
| --- | --- | --- | --- | --- |
| 100 IPs | 100 residential IPs, unlimited bandwidth | $24 | One-off balance purchase | [ Order the 100-IP package](https://bit.ly/9-Proxy) |
| 500 IPs | 500 residential IPs, unlimited bandwidth | $72 | One-off balance purchase | [ Order the 500-IP package](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | 1,000 IPs plus 500 bonus IPs | $126 | One-off balance purchase | [ Order the 1,500-IP package](https://bit.ly/9-Proxy) |
| 2,500 IPs | 2,500 residential IPs | $210 | One-off balance purchase | [ Order the 2,500-IP package](https://bit.ly/9-Proxy) |
| 5,000 IPs | 5,000 residential IPs | $360 | One-off balance purchase | [ Order the 5,000-IP package](https://bit.ly/9-Proxy) |
| 15,000 IPs | 15,000 residential IPs | $720 | One-off balance purchase | [ Order the 15,000-IP package](https://bit.ly/9-Proxy) |
| 25,000 IPs | 25,000 residential IPs | $863 | One-off balance purchase | [ Order the 25,000-IP package](https://bit.ly/9-Proxy) |
| 50,000 IPs | 50,000 residential IPs | $1,438 | One-off balance purchase | [ Order the 50,000-IP package](https://bit.ly/9-Proxy) |

### Business IP packages

| Package | What you get | Price | Billing type | Get it |
| --- | --- | --- | --- | --- |
| 100,000 IPs | 100,000 residential IPs | $2,300 | One-off balance purchase | [ Order the 100,000-IP package](https://bit.ly/9-Proxy) |
| 200,000 IPs | 200,000 residential IPs | $4,140 | One-off balance purchase | [ Order the 200,000-IP package](https://bit.ly/9-Proxy) |
| 500,000 IPs | 500,000 residential IPs | $8,625 | One-off balance purchase | [ Order the 500,000-IP package](https://bit.ly/9-Proxy) |

### GB-based rotating residential packages

This is the set that matters most if you're buying specifically for rotation. Per-GB cost falls as the package grows, and the 50 GB tier ships with 5 GB extra.

| Package | Price per GB | Total price | Validity | Get it |
| --- | --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | 180 days | [ Buy 5 GB of rotating traffic](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $2.10 | $105 | 180 days | [ Buy the 55 GB rotating package](https://bit.ly/9-Proxy) |
| 100 GB | $1.50 | $150 | 180 days | [ Buy 100 GB of rotating traffic](https://bit.ly/9-Proxy) |
| 200 GB | $1.00 | $200 | 180 days | [ Buy 200 GB of rotating traffic](https://bit.ly/9-Proxy) |
| 1,000 GB | $0.80 | $800 | 180 days | [ Buy the 1 TB rotating package](https://bit.ly/9-Proxy) |
| 2,000 GB | $0.75 | $1,500 | 180 days | [ Buy the 2 TB rotating package](https://bit.ly/9-Proxy) |

### Enterprise GB packages

Four figures per package, unlimited data validity, and team features rather than a longer expiry clock.

| Package | Price per GB | Total price | Validity | Get it |
| --- | --- | --- | --- | --- |
| 3,000 GB | $0.72 | $2,160 | Unlimited | [ Order the 3 TB Enterprise package](https://bit.ly/9-Proxy) |
| 6,000 GB | $0.70 | $4,200 | Unlimited | [ Order the 6 TB Enterprise package](https://bit.ly/9-Proxy) |
| 10,000 GB | $0.68 | $6,800 | Unlimited | [ Order the 10 TB Enterprise package](https://bit.ly/9-Proxy) |

### Bundle packages

IPs and traffic in one purchase. Useful when part of your pipeline needs stable addresses and part needs volume.

| Bundle | What you get | Price | Validity | Get it |
| --- | --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | Traffic valid 180 days | [ Buy the Starter bundle](https://bit.ly/9-Proxy) |
| Popular | 1,500 IPs + 50 GB | $180 | Traffic valid 180 days | [ Buy the Popular bundle](https://bit.ly/9-Proxy) |
| Pro | 5,000 IPs + 500 GB | $720 | Traffic valid 180 days | [ Buy the Pro bundle](https://bit.ly/9-Proxy) |

Sign-up runs on an invite-code flow, and the link above carries that code into the form, so you land on the account creation page rather than a dead marketing page.

## Rotation: the two models don't rotate the same way

This trips people up when they buy a cheap rotating residential package expecting behaviour they didn't actually purchase.

On the GB-based side, rotation is built in. Rotating mode hands out a new IP automatically, sticky mode holds the same address until the session time you configured runs out. You can mix the two across different ports and endpoints. Targeting goes down to country, state, city, ZIP or ISP level, and authentication is either username/password with sub-users or an IP whitelist. Everything runs from the dashboard, no desktop software involved.

On the IP-based side, addresses don't rotate on their own. 9Proxy handles rotation through its Auto Rotation Proxy, which rotates on a custom interval across ports you select. That model requires the 9Proxy desktop app for local port forwarding, so it fits a single machine or a workstation setup better than a fleet of cloud workers.

If your whole reason for being here is high-frequency IP churn in a scraper, you're shopping in the GB-based table. Full stop.

## The limits worth knowing before you spend

Budget rotating proxies have a ceiling, and it's better to know where it sits.

- **Protection tiers matter more than price.** An independent 2026 comparison estimates 9Proxy-class budget pools at roughly 95%+ success on lightly protected targets and 85–92% on moderately protected ones, while placing heavily protected properties like Amazon, high-volume Google SERP work and LinkedIn beyond what budget pools reliably handle [3].

- **City-level targeting is thinner than the marketing suggests.** Another comparison notes limited city-level pools at this price point, which is worth testing on your own geographies before committing to a large package [3]. The official documentation lists city and ZIP targeting as available on GB plans, so the honest position is that coverage varies by location and should be verified on a small purchase first.

- **Pool size is smaller than premium providers.** 9Proxy advertises 20M+ residential IPs across 90+ countries [4]. That's a large pool, but Bright Data, Oxylabs and Decodo advertise pools in the 115M–175M range [2]. Smaller pools mean faster IP reuse on the same target.

- **The cleanliness claim is a vendor claim.** 9Proxy markets "clean" IPs with a low blacklist rate. That's their own positioning, not an independently audited metric, so treat it as something to test rather than something established [6].

None of that makes the service unusable. It means the buying decision should follow your target list, not your budget alone.

## A short checklist before you buy

1. **Test small on your actual targets.** Buy the 5 GB pack at $15, run your real workload, and measure how many requests complete. At that price, the test is cheaper than the argument.

2. **Match the billing model to the job.** Rotating scrapers with small per-request payloads belong on GB. Session-based workflows with heavy transfer belong on IP packages.

3. **Check your expiry window against your project schedule.** 180 days is generous for active work and useless for something you'll touch twice a year. In that case, Enterprise's unlimited validity is the feature you're paying for.

4. **Buy volume only when you know your rate.** The step from $3.00/GB to $0.68/GB is real, but a 10 TB package you only half consume is worse value than a 200 GB package you finish.

5. **Confirm targeting on your geographies.** Country targeting is standard. City and ZIP availability varies, so verify before scaling.

6. **Don't count on one provider for everything.** If a meaningful share of your workload is Tier 3 targets, budget pools will show their limits and you'll want a premium fallback for that slice.

## FAQ

**Is pay-as-you-go cheaper than a monthly subscription?**

Usually, for irregular workloads. 9Proxy's packages are balance-based purchases with no recurring commitment, GB traffic lasts 180 days, and unused IPs in IP packages don't expire. Subscriptions make sense when you're running steady monthly volume, not when you're running projects.

**Do GB plans charge extra for rotation?**

Rotation itself doesn't add cost. You're billed for traffic, and you can generate as many endpoints as you need. Targeting down to city, ZIP or ISP level is listed as available on the GB system rather than as a paid add-on.

**What's the real minimum spend to test rotating residential at 9Proxy?**

$15 for the 5 GB package, or $30 for the Starter bundle if you want a handful of IPs alongside the traffic. That's the lowest-cost entry point in the current pricing.

**Which plan is best for a scraper running hundreds of parallel threads?**

GB-based, without much debate. The IP-based model's app-and-port-forwarding design and per-IP usage accounting don't fit that shape of workload.

**Is 9Proxy the cheapest rotating residential proxy out there?**

Not on entry price. Its 5 GB tier at $3.00/GB sits above DataImpulse's roughly $1/GB starting point and Proxy-Cheap's $1.99/GB, and below the premium tier [1]. Its per-IP packages are where the value case is strongest, since bandwidth is unmetered, and its per-GB rate only becomes the cheapest in the market once you reach the multi-terabyte Enterprise tiers.

---

Cheap rotating residential proxies are a cost-per-completed-request problem wearing a cost-per-GB costume. Decide which billing model matches your workload first, then shop for the lowest rate within that model. If your work is rotation-heavy and traffic-light, [👉 start with a 5 GB package and test it on your own targets](https://bit.ly/9-Proxy) before buying terabyte-scale traffic you might not finish inside the validity window.
