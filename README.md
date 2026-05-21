# Zero to One — Founder Network

A backlink swap for founders in the [Zero to One](https://discord.gg/k5cNhKFUv2) Discord.

Everyone adds the same **Founder Network** section to their own site and links to it from their footer. That gives every member a real backlink from every other member's site, which helps Google discover and trust all of our sites.

---

## How to join (3 steps)

**1. Copy the HTML.** Open [`founder-network.html`](founder-network.html), copy the whole block.

**2. Put it on a page** on your site (e.g. `yoursite.com/founder-network`) and **link to that page from your footer.**

**3. Post in `#backlinks`** with two links: your site, and your live founder-network page. Once it's verified, you get added to the list above and everyone else adds you too.

That's it. Restyle the CSS to match your site if you want, just keep the `<a href>` links intact.

---

## Why it has to be real HTML

For the backlinks to count, Google has to actually see the links:

- ✅ Real HTML in your page source (what the snippet gives you).
- ❌ Loaded in an `<iframe>` — the link equity doesn't pass to anyone.
- ❌ Fetched with JavaScript at runtime — Google often won't see it.
- ❌ Marked `rel="nofollow"` or `rel="sponsored"` — tells Google to ignore the link.

If you can view-source on your page and see the `<a href="https://...">` links, you're good.

---

## When new members join

The list in [`founder-network.html`](founder-network.html) is the source of truth. When someone new is added:

1. The maintainer adds their row to this file.
2. A heads-up goes out in `#backlinks`.
3. Everyone copies the updated block (or just adds the new `<tr>` row) to their page when they get a chance.

No need to ping every time someone joins — watch this repo or check `#backlinks` for the weekly update.
