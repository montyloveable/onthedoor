# On The Door — pilot dataset notes
Generated 6 July 2026; last weekly update 27 July 2026. Sources: council websites, ModernGov/CitizenSpace portals, licensing trade press (Poppleston Allen, Woods Whur, John Gaunt, Local Government Lawyer, Institute of Licensing), local press.

## Weekly update log
### 27 July 2026
- Link check: all 16 authorities re-checked. Environment note: direct URL fetching was provenance-restricted this run, so verification went via search-surfaced fetches. Westminster's SoLP page was fully re-fetched (updated 29 Jun; consultation live, closes 5pm 9 Aug) and every other authority's canonical page resolved via site-restricted search. No moved or dead links found — 16/16 held. Two secondary sources couldn't be directly re-fetched this run (Lambeth 2024–29 policy PDF; Hackney ModernGov decision 8179) — both unchanged-risk-low, parent pages fine.
- CAMDEN DIRECTION CHANGE (loosening → mixed): Poppleston Allen reported 24 Jul that Camden has retained its Late Night Levy with reform — extended to LATE NIGHT REFRESHMENT premises (00:00–05:00), alongside alcohol premises (00:00–06:00). Fee-free opt-out via minor variation (email licensing@camden.gov.uk) until 31 AUG 2026; then levy applies pro rata from licence anniversary; NYE-only extensions exempt. New notice + new Coming Up deadline. First direction change since launch.
- EL RINCÓN (Bristol): hearing STILL not listed as of 27 Jul (must be held by 13 Aug). MANUAL WATCH — democracy.bristol.gov.uk, sub-committee sits fortnightly Thursdays.
- Home Office closure orders consultation closes 11.59pm FRI 31 JUL — final-week framing on site + newsletter. John Gaunt coverage added as source.
- Westminster: no NTIA escalation or legal challenge found this week; consultation closes 9 Aug (13 days).
- Glasgow: Night Time Economy Commission launched 13 Jul (chair Mike Grieve, Sub Club/SNTIA) + Scotland-first NTE Manager post, £100k in 2026–27 budget. Notes + clip; overprovision unchanged, direction stays stable.
- Birmingham: promising "Digbeth CIA" Citizen Space page found — dated 2016. NEEDS VERIFICATION flag stays; CMIS manual check still needed.
- Liverpool: still the Jan 2021 policy; beware the live selective (landlord) licensing consultation — different regime, not the SoLP. Islington/Hackney: quiet.
- Trade press clips added: Camden levy (Popall 24 Jul), MVP acquires The Pipeline, Brighton — 10th community-owned venue (24 Jul), "Turn It Up" government music plan (14 Jul), Glasgow NTE Commission (13 Jul). Dropped from site clips: World Cup hours retro, Brighton CSA (Jan), Southwark SoLP (Apr), NLPF (Nov 25) — all retained in notices/history.
- Counters: 2 open consultations, 1 review this month, 0 closures this quarter (unchanged). Site notices: Hackney "now confirmed" card rotated out for the Camden levy card.
- Direction board now 4 tightening · 7 stable · 2 loosening · 3 mixed.
### 20 July 2026
- Link check: all 16 authorities' sources re-checked. Two fixes: Leeds (SoLP page moved to /licensing/statement-of-licensing-policy) and Manchester (policy PDF moved to /__data/assets/file/0019/123265/). Westminster source order updated: consultation actually lives on the Statement of Licensing Policy subpage (updated 29 Jun 2026; Commonplace docs + survey; closes 5pm 9 Aug) — added as primary source. Westminster's CIA subpage still shows only the 2023 CIA (2026 CIA is an ArcGIS storymap) — noted as an aggregation-gap exhibit, page kept as source.
- NEW NOTICE: Home Office national consultation on longer premises closure orders (s.80/s.82 ASB Crime & Policing Act 2014, powers from Crime and Policing Act 2026). Closes 31 Jul 2026. Reported by LGL 3 Jul.
- EL RINCÓN (Bristol): representations closed 16 Jul. Hearing must be held within 20 working days — by 13 Aug 2026. No listing found on democracy.bristol.gov.uk as of 20 Jul; MANUAL WATCH for the agenda.
- Hackney: policy page re-checked — still no mention of the Shoreditch CIA/Dalston SCA (15+ months after they took effect); 2023 SoLP now served via a Google Drive link.
- Liverpool: still the Jan 2021 policy, no renewal consultation live. Islington: nothing moving. Birmingham: SoLP page still lists July 2015 policy; NEEDS VERIFICATION flag retained.
- Westminster: no NTIA escalation or legal challenge found this week.
- Trade press: quiet week on the CIP beat. Clips added: IoL local-government-reorganisation guidance for licensing teams (1 Jul); World Cup licensing hours order retrospective (order extended hours 2–3 hrs for England/Scotland knockouts incl. the 19 Jul final — Popall, 22 May).
- Counters recomputed: 2 open consultations (Westminster + Home Office national), 1 review this month (El Rincón), 0 closures this quarter. Counter link now points at the closure-orders consultation (nearest deadline).
- No direction changes: board still 4 tightening · 7 stable · 3 loosening · 2 mixed.
### 13 July 2026
- Link check: all 16 authorities' primary sources checked. Two fixes: Birmingham (bare homepage → canonical SoLP page) and Liverpool (enforcement-policy page → canonical Licensing Policy Statement page). Camden's /licensing-policy page is JS-rendered (returns empty to plain fetch) but resolves and is correctly indexed — left in place.
- HACKNEY VERIFIED: Full Council decision 26 Feb 2025 published the Shoreditch CIA and designated Dalston a Special Consideration Area (not a CIA), effective 1 Apr 2025 (hackney.moderngov.co.uk decision ID 8179). The council's licensing policy page still doesn't reference it. Watch-list item resolved.
- BIRMINGHAM RETRACTED: no evidence found for the "new policy effective 1 May 2026 / Broad Street CIP carried forward" claim. Council SoLP page still lists the July 2015 policy; Poppleston Allen reported all CIPs removed under the 2020 interim policy. Notice retired; NEEDS VERIFICATION kept (check CMIS committee papers manually).
- EL RINCÓN (Bristol): review ref 26/03363/PRREV, valid 18 Jun 2026; representations close 16 Jul 2026; hearing TBC.
- Westminster: Woods Whur analysis adds detail — draft also removes Edgware Road and Queensway/Bayswater CIZs and reworks Core Hours by premises type. No NTIA escalation or legal challenge found this week.
- Liverpool/Islington: no renewal consultations live yet.
- Counters recomputed: 1 open consultation, 1 review this month (El Rincón), 0 closures this quarter (Q3).

## Files
- `councils.json` — 16 pilot authorities: policy in force, CIA/overprovision zones, direction (tightening/stable/loosening/mixed), source URLs, next review dates.
- `notices.json` — 11 live/recent notice items for the notice board + NTIA context stats for the chalkboard counters.

## The launch-issue story
Westminster's SoLP 2026 consultation is open now and closes **9 Aug 2026** — with the NTIA publicly calling it unlawful. This is the lead item: a live, contested, deadline-driven story in the highest-profile licensing authority in the country, exactly the thing solicitors need to catch.

## Direction scoreboard (map colouring)
- **Tightening (4):** Westminster, Hackney, Southwark, Leeds
- **Stable (7):** Islington, Lambeth, Manchester, Bristol, Birmingham, Newcastle, Glasgow
- **Loosening (2):** Liverpool, Edinburgh
- **Mixed (3):** Tower Hamlets (Brick Lane expanded / Bethnal Green removed), Brighton & Hove (CIZ→City Safety Area), Camden (CIAs removed / Late Night Levy extended to LNR, 27 Jul 2026)

The split itself is a finding: roughly as many pilot authorities are loosening as tightening, which cuts against the "everything is closing in" narrative — good editorial angle.

## Watch list for the weekly agent
1. **Westminster** — consultation closes 9 Aug; expect responses, NTIA escalation, possible legal challenge.
2. **Liverpool** — SoLP renewal due 2026 (last adopted Jan 2021); consultation should surface any week.
3. **Islington** — SoLP 2023–2027 expires next year; pre-consultation likely late 2026.
4. **Hackney** — VERIFY whether the Shoreditch/Dalston CIA was formally adopted; council policy page doesn't show it yet.
5. **Tower Hamlets** — CIA expires Nov 2027; review consultation likely mid-2027.
6. **Bristol** — CIA 3-year cycle means renewal by Mar 2027; plus El Rincón review hearing date to catch.

## Known gaps / verification flags
- **Birmingham**: CIA boundary detail in the 1 May 2026 policy unverified — council CMIS document links are unstable; pull the policy PDF directly.
- **Hackney**: CIA adoption status unconfirmed (flagged in both files).
- **Leeds**: full CIA only available by email request — itself evidence of the aggregation gap the product exists to fill.
- **Court listings**: no automated source found; the Pier One judgment came via trade press. As the brief predicted, this stays manual — Local Government Lawyer + Poppleston Allen/Woods Whur/John Gaunt news feeds are the practical proxy for court activity.
- Glasgow/Edinburgh run on a different statute (Licensing (Scotland) Act 2005, "overprovision") — the site copy should never call these CIPs.

## Chalkboard counters (as of 6 Jul 2026)
- Open consultations: **1** (Westminster)
- Reviews this month: **2** (El Rincón pending; Pier One decided 30 Jun)
- Closures this quarter: **1** (Corsica Studios, reopening 2027)
