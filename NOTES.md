# NOTES — news-image-20261120 audit trail

Entry: one 1024×1024 PNG (`entry.png`, 140,538 bytes) summing up the world
news of Friday 20 November 2026, rendered deterministically with Python/PIL
(render script kept outside the repo: `~/workspace/makefun/render_news_image_20261120.py`).
Two independent renders produced identical bytes:

- SHA-256: `ce483f76ec1230c6e327f09f84248804271033e91e07b1cd4cb26576bfb3c815`
- `main.ts` (Node 22, stdlib only) copies `entry.png` to the grader's output
  directory; no network, no shell, no subprocess.

## The six stories — each verified against a live Reuters page on 2026-11-20

1. **Kyiv hit by missile debris, fire in a three-storey building (Obolonskyi district)**
   — 20 Nov first report. Reuters, 2026-11-20:
   https://www.reuters.com/world/europe/fire-broke-out-ukraines-kyiv-after-missile-strike-mayor-says-2026-11-20/
   Mayor Vitali Klitschko: fire broke out in a three-storey building in the
   Obolonskyi district after missile debris hit it; explosions heard in the
   early hours of Friday.
2. **Saudi-led coalition intercepts Houthi ballistic missile aimed at southern Saudi region**
   — 20 Nov first report. Reuters, 2026-11-20:
   https://www.reuters.com/world/middle-east/saudi-led-coalition-says-it-intercepted-houthi-missile-targeting-southern-region-2026-11-20/
   Saudi air defences intercepted and destroyed the missile on Friday; drones
   also intercepted over Jazan, Abha and Khamis Mushait.
3. **Indonesia's Prabowo meets Xi in China**
   — 20 Nov first report. Reuters, 2026-11-20:
   https://www.reuters.com/world/china/indonesias-prabowo-chinas-xi-discuss-future-south-china-sea-cooperation-2026-11-20/
   Prabowo met Xi on Friday to discuss the economy, investment partnerships
   and South China Sea cooperation.
4. **Shenzhen trilateral aftermath**
   — 20 Nov analysis of the 19 Nov summit. Reuters, 2026-11-20:
   https://www.reuters.com/world/china/trumps-personalized-diplomacy-hits-its-limits-with-3-way-summit-2026-11-20/
   Analysis of Thursday's first Xi–Trump–Putin three-way summit in Shenzhen:
   a symbolic "peace declaration" but no plans for arms-control talks and no
   advances on Iran, Ukraine, Taiwan, trade or AI.
5. **ICJ rules Myanmar committed state-sponsored genocide against the Rohingya**
   — 19 Nov first report, with follow-up coverage on 20 Nov. Reuters, 2026-11-19:
   https://www.reuters.com/world/asia-pacific/top-un-court-finds-myanmar-committed-state-sponsored-genocide-against-muslim-2026-11-19/
   Reactions piece (also 19 Nov, still circulating on 20 Nov):
   https://www.reuters.com/world/asia-pacific/reactions-top-un-court-finds-myanmar-guilty-genocide-against-rohingya-2026-11-19/
   The court ruled on Thursday that the 2017 campaign amounted to
   state-sponsored genocide — the first time the ICJ held a state responsible
   for genocide.
6. **Anthropic's record $81.3bn IPO debuts on Nasdaq**
   — 19 Nov first report, market fallout on 20 Nov. Reuters, 2026-11-19:
   https://www.reuters.com/business/anthropics-ipo-makes-history-2026-11-19/
   Close confirmed against Reuters' 19 Nov playbook piece and WSJ/Nikkei/CNN
   20 Nov coverage: shares closed at $97.17, up 17% from the $83 IPO price;
   $81.3bn raised, the largest stock market debut on record, ahead of SpaceX.

## First-publication split

- 20 Nov first reports: items 1, 2, 3, and item 4 (20 Nov analysis of the
  19 Nov summit).
- 19 Nov first reports with 20 Nov follow-up: items 5 and 6.
