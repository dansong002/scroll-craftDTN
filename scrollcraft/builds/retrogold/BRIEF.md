# Retro Gold: brief (draft, interview in progress)

## Source material (from retrogoldband.com, Bandzoogle "motiv" theme)

- **Who:** Retro Gold, pop rock cover band from Des Moines, IA.
- **Tagline in use:** "The Hottest Cover Band in Iowa!"
- **Setlist range:** hits from the 90s to present day.
- **Where they play:** Fortune 500 corporate events, weddings, festivals, private concerts across the Midwest.
- **Proof points they already claim:** professional, polished, packed dance floor, setlist tailored to the crowd, own sound gear and production crew ("concert-quality").
- **Lineup:**
  - Jacob H. (lead vocals)
  - Isaac "Izzy" R. (keys, synth, Moog, autotune vocals)
  - Daniel A. (drums, autotune vocals)
  - Sean G. (electric guitar, backing vocals)
  - Ely V. (electric guitar)
  - Holden K. (FOH and in-ear production engineer)
  - Jacob E. (FOH and in-ear production engineer)
- **Past shows:** Rendezvous on Riverview (Riverview Park, Des Moines), Music on Main Street (Town Clock Plaza, Dubuque), Winterset Cidery (Retro Gold Live, Halloween Party), plus private events. The last listed date is Oct 2023, so the Shows page is stale.
- **Media:** live and studio photo galleries; a Vimeo hero video; a "2023 Tracklist" video.
- **Links:** instagram.com/theretrogoldband, facebook.com/theretrogoldband, YouTube channel, linktr.ee/theretrogoldband.
- **Conversion:** a contact form (name, email, message). There is no booking-specific information.

## Interview answers (verbatim selections)

1. **Vibe:** Bold retro futurism.
2. **Journey:** not answered yet.
3. **Energy curve:** not answered yet.
4. **Feeling / peak:** "The live energy hit". Visitors should feel like they're missing out if they don't book.
5. **Signature seed:** "A live setlist jukebox". Scroll through decades and genres and hear what they play.
6. **Range:** Premium-minimal.
7. **One world or scenes:** "Not sure yet". The recommendation is pending.
8. **Assets:** photos and logo.

## Asset audit (38 files pulled from the live site)

- **Studio shoot (the brand, already made):** gold tinsel curtain backdrop, chrome disco balls, all-black tees, sunglasses, gold chains. Solo portraits for every player, plus two group shots holding a disco ball (one on a white ground, one with a tinsel backdrop). These are high resolution (3.5k to 4.5k px tall) and consistently graded warm.
- **Live: crowd (peak material):** a wedding tent with every hand up under purple light, and a black-and-white shot of the singer in the crowd with arms raised all around.
- **Live: band at work:** drummer under a tent, keys rig, guitarist in an AC/DC tee, a mixing desk (FOH, which proves the "own production crew" claim), and a wide outdoor stage shot.
- **Logo:** white hand-lettered "RETRO GOLD" with gold underline and sparkle marks, raster PNG on black. A vector version would be better.
- **Art direction this implies:** the chrome disco ball supplies the retro-futurism; the tinsel supplies the gold. Premium-minimal means near-black canvas, warm off-white ink, and one gold accent sampled from the tinsel. The band's existing visual identity is the brand kit, so it outranks the skill's palette defaults.

## Round two answers (verbatim selections)

- **Journey:** "Yes, build it". Curtain and logo, then the band one by one, the decade jukebox, a full-screen crowd moment, and booking.
- **Jukebox:** "Setlist only, no audio".
- **CTA:** "Check your date".
- **Form:** "Date, event type, location".

## Decisions

- **Grammar:** filmic one-shot.
  - *Why not rhythmic cutlist* (the obvious music grammar): it bans pin and parallax. The approved journey needs a layered curtain hero and a held peak, and the user chose premium-minimal over loud.
  - *Live surface* and *gallery*: the jukebox is one tool and the lineup is one rail, but neither is the whole page.
  - *Typographic poster*: wastes a strong photo shoot.
  - *Chaptered editorial*: wrong energy.
  - *Split stage*: no two-sided argument.
  - *Continuous world*: no geography, and no video assets.
- **Signature move:** a mirror ball drawn on canvas.
  - Scroll spins it through four decades and the setlist on the wall changes each quarter turn.
  - The pointer moves its key light.
  - Light flecks it throws sweep across the room.
  - The decade buttons and arrow keys drive the same dial.
- **Tell-someone sentence:** "It's the site where you spin a disco ball through their setlist."

## Feeling curve

| Act | Feeling | What causes it |
|---|---|---|
| 1 Curtain | Anticipation | A dark tinsel curtain with the sign hanging in front, which parts to show the band lit |
| 2 Band | Warmth | Faces, names and jobs, one at a time, including the two engineers |
| 3 Jukebox | Delight, recognition | Spinning the ball yourself and watching the decade (and the songs) change |
| 4 Built for your night | Calm trust | The only document-like act: tailored setlist, own production, real venues. This is the hush before the peak |
| 5 Peak | Release | Black frame, "Then the lights drop.", iris onto the crowd with every hand up, then the black-and-white singer in the crowd |
| 6 Book | Resolve | The form, held. The last screen is the action, not a fade |

**The peak:** "You scroll and suddenly you're on their dance floor with every hand in the air." It is Act 5, the largest span (4.2vh), and the act before it is the quietest.

**Authored silence:** the opening of Act 5 (a black stage with one line) is deliberate.

## Score

| Act | Device | Span | Why |
|---|---|---|---|
| Curtain | pin + three CSS-driven planes off `--sc-p` | 2.2 | A reveal is the oldest stage move there is. Depth comes from three rates: curtain fast, sign mid, band slow |
| Band | pan | 3.8 | A lineup is breadth, so it travels sideways |
| Jukebox | pin + bespoke canvas | 3.0 | The signature move needs the frame to hold while the dial turns |
| Built for your night | flow + reveal | auto | The contrast that makes the pinned acts land |
| Peak | pin + iris reveal + kinetic | 4.2 | The single iris on the page, saved for the peak |
| Book | flow | auto | The close resolves into an input, not a button island |

## Open items

- **Setlist:** `setlist.js` holds visible placeholders ("Song title", "Artist"). The real songs are needed before launch.
- **Booking email:** `RG_BOOKING_EMAIL` in `setlist.js` is empty. The form says it is not connected and points to Instagram until it is set.
- **Lineup (confirmed by the band from the group shot):**
  - On stage: Jacob H. (lead vocals), Isaac R. (keys and vocoder), Ely V. (guitar), Sean G. (guitar), Christian (bass), Daniel A. (drums).
  - Engineers: Holden K. (in-ear mix), Jacob E.
- **Band rail:** now uses each person's tinsel-shoot portrait, matched by face to the lettered group shot.
- **Christian:** has no photo yet, so he has a typographic card. Needed: a portrait (ideally from the tinsel shoot, or any 4:5 photo) and his last initial.
- **Jacob E.:** role set to "Front of house engineer"; confirm. His card uses the mixing-desk photo.
- **Hero group shot:** includes the former bassist and not Christian or Jacob E. Replace it with a current group photo when there is one.
- **Photos:** the group shot is only 1350px wide; a higher-resolution original would sharpen the hero. A vector logo would too.
- **Jukebox audio:** later, the band's own live clips only, never original studio tracks.
