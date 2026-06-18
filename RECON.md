# RECON · Limelight Cuts

## Verified facts (used in the build)
- **Business:** Limelight Cuts (barbershop). On Instagram the wordmark reads "LIME LIGHT CUTS ✂️💈🔪".
- **Address:** 175 Main Street, City of Orange, NJ 07050. Confirmed via the public directory listing (bippermedia store page title "Limelight Cuts at 175 Main St, City of Orange NJ 07050") and search results.
- **Phone:** (973) 905-0309 (from the assignment facts). PIN = last 6 digits = **050309** (confirmed: 9050309 -> 050309). Could not independently re-confirm the number from a public listing, so it is used as given; flagged below.
- **Rating:** 4.6 stars on Google (from assignment facts; consistent with the "highly recommended, skilled barbers, affordable" tenor of the public review snippets). Total review count not available, so no count is shown.
- **Named barber:** "Luis" appears repeatedly in public review snippets ("Luis has been cutting my hair and my son's...", praised as skilled, comfortable, fair price). Used in the Chairs section and paraphrased (not quoted verbatim) in the review band.
- **Services / prices:** Public snippets mention precision cuts, styles, shaves, beard work and a typical price band of about $30 to $40. The menu uses honest "starts at" pricing in that range (fade $30+, cut and beard $40+, lineup $20+, kids' $25+, hot towel shave $30+, design "Ask") with a visible disclaimer to confirm the total in chair. Not a published price sheet, so it is framed as starting prices, not exact.

## NO existing website — confirmed
Searched the open web. Limelight Cuts has **no dedicated website**. Its only web presence is:
- Instagram **@_limelightcuts** (exact-name match, verified as this business -> shown on the site).
- A Facebook page listed as "Limelight barber shop | Orange NJ" (slightly different name; NOT shown, since I could not prove it is exactly this business vs a same-name neighbor).
- Third-party directory aggregator pages (bippermedia, barberhead, booksy listings, yellowpages). These are aggregators, not an owned site.
This is a genuine BWYW candidate: real, well-reviewed, zero owned web presence.

## Hours — genuinely unavailable
No public source published this shop's hours (the directory page is an SEO shell with no hours; IG/FB bios were not machine-readable). Per the brief, I did **not invent** posted hours. The Visit section and the Chairs note both say plainly "Call for today's hours." The live **Open now / Closed** pill and the chair-availability chips compute against a clearly-labeled **typical neighborhood barbershop week** (Mon-Thu 9 AM to 7 PM, Fri 9 AM to 8 PM, Sat 8 AM to 8 PM, Sun 10 AM to 4 PM, America/New_York) so the interaction is live and useful, while the copy stays honest that the real hours come by phone. All times render 12-hour.

## Upsell intel (one line, for admin)
Owner has an active Instagram (@_limelightcuts) but no booking platform and no website. Easy upsells: a Booksy/Squire online-booking link wired into the "Call to hold a chair" CTA, and turning the IG feed into a live gallery. Capture real shop hours and a real price sheet on the first visit to replace the typical-week fallback.

## Art-direction notes
- **Kit honored exactly:** accent #D4A574 gold, base #15161A charcoal, Cabinet Grotesk display + Satoshi body (Fontshare), layout archetype = **fixed left-rail nav + full-height hero panel**, mood = modern-lux barbershop.
- **Signature interaction (mine alone):** a **fresh-fade before/after drag slider** (grown-out cut reveals a sharp finished cut, mouse + touch + keyboard, with a one-time auto-nudge when it scrolls into view) PLUS **chair-availability time chips** (Early chair / Midday / After work, marked "Chairs now / Usually open / Filled up" by current NY time) and a **live Open now / Closed pill** in the rail, the hero, and the mobile bar.
- **Distance from GQ Cutz (burned barber build):** deliberately avoided the magazine-cover editorial frame and the sand/copper luxe palette that GQ Cutz burned. This is a dark left-rail "shop instrument" layout, not a magazine spread.
- **No-repeat imagery:** every photo appears once; none collide with any ID in `.orchestrator/used_images.json`.

## Images used (Pexels, direct source URLs, all verified live, content-checked)
- **4969842** — vintage red leather barber chair, empty studio (HERO). https://images.pexels.com/photos/4969842/pexels-photo-4969842.jpeg
- **2076930** — barber mid-cut shaping hair (before-state of the fade slider). https://images.pexels.com/photos/2076930/pexels-photo-2076930.jpeg
- **1453005** — barber finishing a sharp lineup with a razor (after-state of the fade slider). https://images.pexels.com/photos/1453005/pexels-photo-1453005.jpeg
- **1570807** — tattooed barber combing/shaping hair (gallery tall). https://images.pexels.com/photos/1570807/pexels-photo-1570807.jpeg
- **1813272** — busy shop, two clients at the chairs (gallery wide). https://images.pexels.com/photos/1813272/pexels-photo-1813272.jpeg
- **1319460** — vintage barber scissors on a wooden wall (gallery detail). https://images.pexels.com/photos/1319460/pexels-photo-1319460.jpeg
- **3998429** — side view, beard trim with scissors (gallery). https://images.pexels.com/photos/3998429/pexels-photo-3998429.jpeg
- **3998415** — barber trimming a bearded man in a classic shop (gallery wide). https://images.pexels.com/photos/3998415/pexels-photo-3998415.jpeg

Pexels image IDs for the central ledger: **4969842, 2076930, 1453005, 1570807, 1813272, 1319460, 3998429, 3998415**. Videos: none.

## Self-verification done
- Rendered in headless Chrome at 1280px (desktop) and 375px (mobile): no overflow, left rail on desktop, collapsed top bar with ~46px gold call icon on mobile.
- Em dashes: only the allowed attribution prefix on the review line ("— Paraphrased from a Google review"). No em or en dashes in body copy.
- 12-hour time everywhere (verified the fmt12 logic: noon = 12 PM, midnight = 12 AM, 7 PM, 8 AM).
- Live status pill + 3 chair chips generate in the DOM with no page JS errors.
- Google Maps keyless embed uses the Ramos `output=embed` pattern centered on 175 Main St (renders in a real browser; the headless grey box is the known sandbox artifact).
