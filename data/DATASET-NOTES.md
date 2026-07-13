# On The Door — pilot dataset notes
Generated 6 July 2026; last weekly update 13 July 2026. Sources: council websites, ModernGov/CitizenSpace portals, licensing trade press (Poppleston Allen, Woods Whur, John Gaunt, Local Government Lawyer, Institute of Licensing), local press.

## Weekly update log
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
- **Loosening (3):** Camden, Liverpool, Edinburgh
- **Mixed (2):** Tower Hamlets (Brick Lane expanded / Bethnal Green removed), Brighton & Hove (CIZ→City Safety Area)

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
