# Brief for Muse: set up the Markets In Five social profiles

**Owner:** the account owner (approves every step that needs a login, phone or payment).
**Written:** 2026-10-17 by Claude (the project's lead agent). Read this file whole before you start.
**Public copy:** https://github.com/south01/marketsinfive-brand (this brief + `assets/`), rebuilt with
`tools/brand_repo_sync.sh` after every change here. Only the brief and brand files ever go there.
**Your job:** create or finish one profile per platform for Markets In Five, all looking and reading the same, and
report what you did in your report (a reply to the owner) (template at the end). Setup only: no posts, follows, ads or
messages yet.

---

## 1. What Markets In Five is

- A free market app at **https://app.marketsinfive.com**: US market mood, movers, sectors, unusual options and
  alerts, with prices **15 minutes delayed**.
- The website **https://marketsinfive.com** (landing page, contact form, privacy and terms).
- A **live market broadcast** (a 24/5 screen of the same data, 15 minutes delayed) to be streamed on YouTube and
  Twitch.
- Planned: short daily videos ("the trading day in five beats").

It is information, not advice. It never tells anyone to buy or sell.

## 2. Identity (use exactly this everywhere)

| Item | Value |
|---|---|
| Display name | **Markets In Five** |
| Handle | **@marketsinfive**. If taken, in this order: `@marketsin5`, `@marketsinfive_`, `@marketsinfivehq`. Same handle on every platform if possible: check all platforms first, then pick the first handle free on all of them |
| Tagline | **The market, explained in five minutes.** |
| Bio link | **`https://marketsinfive.com/links?src=<platform>`** (the link page: app, website, every live channel), e.g. `?src=instagram`, `?src=tiktok`, `?src=youtube`. The `src` tag tells us which platform sends visitors. Where a platform allows more links, add `https://app.marketsinfive.com` too |
| Sign-up email | the platform's own alias, all live since 2026-10-17 and all delivered to the owner's `social@marketsinfive.com` mailbox: `youtube@`, `instagram@` (Threads uses it too), `facebook@`, `tiktok@`, `x@`, `twitch@`, `reddit@`, `bluesky@`, `stocktwits@`, `linkedin@`, `discord@` (all `@marketsinfive.com`). Use no other address. After sign-up, ask the owner to switch off the platform's email notifications (the mailbox takes 200 messages a day) |
| Category | Media / news company (Instagram, Facebook, TikTok business); Twitch: "Just Chatting" for the broadcast |
| Language / region | English; content about US markets |

Already exists: **YouTube** `@marketsinfive` (youtube.com/@marketsinfive, a Brand Account under the owner's Google
login; avatar + description set, banner still default) and **Instagram** `@marketsinfive` (no picture or bio
yet). Finish these; do not create duplicates.

To set up: **TikTok, Twitch, Facebook Page (for videos), X, Reddit, Threads, Bluesky, StockTwits, LinkedIn (company
page)**, and **claim** a Discord server name (empty, private) for the subscriber community later.

## 3. Brand assets (in this repo, `assets/`)

| Use | File |
|---|---|
| Profile picture (all platforms) | `icon-f1-1024.png` (navy square, the platform rounds or circles it) |
| X header | `banner-profile-navy.png` (1500×500) |
| YouTube banner | `cover-youtube.png` (2560×1440, logo inside the 1546×423 safe area) |
| Twitch banner | `cover-twitch.png` (1200×480) |
| Facebook cover | `cover-facebook.png` (1640×856, logo centred so the phone and desktop crops both keep it) |
| Reddit banner (profile + community) | `cover-reddit.png` (1920×384) |
| LinkedIn cover | `cover-linkedin.png` (1128×191) |
| Bluesky header | `banner-profile-navy.png` (1500×500, same as X) |
| Discord server banner | `cover-discord.png` (960×540) |
| Threads | uses the Instagram profile |
| StockTwits | avatar only (`icon-f1-1024.png`) |
| Link preview | `og-navy.png` (1200×630) |

Colours: navy `#171E38` ground, white type, mint `#9CDBA9` for the word "in", red dot `#CF5C3D`. The name is
written lower case in the logo ("markets in five") but "Markets In Five" as a display name. Do not use the older
amber/navy palette in `docs/PRODUCT.md`: it was replaced by v2.

## 4. Bios (pick the one that fits the platform's limit, do not rewrite the meaning)

**Short (≤ 80 characters: TikTok)**
> The market, explained in five minutes. Not financial advice.

**Medium (≤ 150: Instagram, X, Twitch summary, Reddit profile "About")**
> The market, explained in five minutes. US stocks, movers and unusual options, plain English. Not financial advice. Made with AI.

**Long (YouTube "About", Facebook "About", Twitch "About")**
> Markets In Five: the market, explained in five minutes.
>
> Live market screen (15 minutes delayed) and short daily videos on what moved US stocks: the overall mood, the
> biggest movers, sectors and unusual options activity, in plain English.
>
> Free app: https://app.marketsinfive.com
> Website and contact: https://marketsinfive.com
>
> Information only, not financial advice. We are not a registered adviser or dealer. Prices are delayed. Videos
> are made with the help of AI.

## 5. Rules (hard limits)

1. **Never** write or imply trading instructions: no "buy", "sell", "load up", "short this", "target", "entry",
   price predictions or promises of profit. The words "not financial advice" stay in every bio.
2. **The owner does every login, phone number, 2FA code, ID check and payment.** Never ask for, store or write down
   a password, recovery code or stream key. Ask the owner to: keep every login in a password manager, turn on 2FA
   with an authenticator app (not SMS) on each account, and add a **second owner/manager** wherever the platform
   allows it (the YouTube Brand Account, the Facebook Page, the LinkedIn page, the Discord server), so no account
   hangs on one personal login.
3. No buying followers, no follow-for-follow, no engagement groups, no ads, no DMs, no posts until the owner says go.
4. Do not claim to be a real person or a news outlet; AI is disclosed in the bio (section 4). When posting starts,
   switch on each platform's own AI-content label for AI video or voice (YouTube "altered or synthetic content",
   TikTok "AI-generated", Meta "AI info").
5. Do not link the accounts to any third-party tool (schedulers, connectors) without the owner's OK. You reach
   Instagram, Facebook and Threads natively; for the others the plan is a self-hosted **Postiz** (open source)
   that Claude sets up on a separate small server. Until then, setup only, by hand, with the owner.
6. Use only the files in `assets/`. No stock photos, no bull/bear clichés.
7. When something is unclear, stop and ask the owner. Do not guess an email, handle or category.

## 6. Steps

1. Check the handle (section 2) on all six platforms; report which are free before creating anything.
2. Owner creates the missing accounts with the platform alias email; you fill the profile: name, handle, avatar,
   banner (if the file exists), bio, link, category.
3. Instagram and Facebook: professional/business account, linked to each other in Meta Accounts Center.
4. YouTube: add the banner when it exists, the long bio, links (website + app), and turn on the channel
   watermark with `icon-f1-512.png`. Live streaming must be enabled (takes 24 hours after the request).
5. Twitch: profile picture, banner, bio, category, and enable streaming (the owner adds 2FA, which Twitch requires
   for streaming).
6. Reddit: user **u/marketsinfive** (Reddit usernames can never be changed, so check the spelling twice). Profile:
   display name, avatar, banner, the medium bio, website link, "NSFW" off. Also **create the community
   r/marketsinfive** and set it to **restricted** (anyone can view, only approved users post) so nobody else takes
   the name; no posts there yet. Reddit is the strictest platform about self-promotion: most finance communities
   (r/stocks, r/options, r/investing, r/wallstreetbets) ban links to your own app or channel and ban accounts that
   mostly post their own links. Do **not** post, comment or join communities on the brand's behalf; the owner
   decides how Reddit is used later.
7. Threads: switch on from the Instagram account (same handle and picture); medium bio.
8. Bluesky: handle **`@marketsinfive.com`** (the domain as the handle: the owner adds the DNS TXT record Bluesky
   shows; until then `@marketsinfive.bsky.social`). Header, avatar, medium bio.
9. StockTwits: `@marketsinfive`, avatar, medium bio, website link. StockTwits is for stocks talk tagged by ticker
   ($MU); no posts yet.
10. LinkedIn: a **company page** "Markets In Five" (needs the owner's personal LinkedIn as admin), industry
    "Online Audio and Video Media" or "Financial Services" (owner picks), cover, long bio, website.
11. Discord: create a server "Markets In Five", private, no channels beyond #welcome; banner if the server level
    allows it. It is only claimed for now.
12. After each profile is done, tell the owner so the link page (`site/links/index.html`, the `CHANNELS` list,
    `live: true`) shows it. Claude makes that change.
13. Write your report (a reply to the owner) (below). Mark anything missing or waiting as such.

## 7. Report template (your report (a reply to the owner))

```
| Platform | Handle | URL | Sign-up email (alias) | Avatar | Banner | Bio | Link | 2FA (owner) | Streaming on | Status / notes |
|---|---|---|---|---|---|---|---|---|---|---|
| YouTube | | | | | | | | | | |
| Instagram | | | | | | | | | — | |
| Facebook Page | | | | | | | | | | |
| TikTok | | | | | | | | | | |
| Twitch | | | | | | | | | | |
| X | | | | | | | | | — | |
| Reddit (u/ + r/) | | | | | | | | | — | |
| Threads | | | | | | | | | — | |
| Bluesky | | | | | | | | | — | |
| StockTwits | | | | | | | | | — | |
| LinkedIn page | | | | | | | | | — | |
| Discord (claimed) | | | | | | | | | — | |
```

No passwords, codes or stream keys in this file, ever.
