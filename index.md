---
layout: default
title: Ohio & Michigan NPS Road Trip — Itinerary, Nov 23–25, 2026
---

# Ohio & Michigan NPS Road Trip {#top}

**Road-trip itinerary · Mon Nov 23 – Wed Nov 25, 2026 · Lombard / Chicago → Cuyahoga Valley → West Bloomfield → River Raisin → home for Thanksgiving**
Five NPS sites from the map, one full ranger-planned day in Cuyahoga Valley, and a night at his aunt's in West Bloomfield on the way back. Two passport stamps are actually collectable this trip — Cuyahoga Valley and River Raisin (see [Know before you go](#know-before-you-go) for why the other three are exterior-only this week).

<style>
.trip-fig { margin: 14px 0; }
.trip-fig img { width: 100%; height: auto; border-radius: 10px; display: block; }
.trip-fig figcaption { font-size: 0.85em; color: #606c71; text-align: center; margin-top: 5px; }
.hero-fig img { max-height: 420px; object-fit: cover; }
</style>

<figure class="trip-fig hero-fig"><img src="https://commons.wikimedia.org/wiki/Special:FilePath/Brandywine%20Falls%20(14367071241).jpg?width=1280" alt="Brandywine Falls, Cuyahoga Valley National Park — the late-morning stop on the ranger's list." loading="lazy"><figcaption>Brandywine Falls, Cuyahoga Valley National Park — late morning on Tuesday's ranger list.</figcaption></figure>

## Contents {#contents}

- [Bookings](#bookings)
- [Weather in the valley — live forecast](#weather)
- [Trip map — color-coded by day](#trip-map)
- [Day 1 — Mon Nov 23: Lombard → Cuyahoga Valley](#day-1)
- [Day 2 — Tue Nov 24: the ranger's Cuyahoga day, then West Bloomfield](#day-2)
- [Day 3 — Wed Nov 25: River Raisin, then home](#day-3)
- [Stamp checklist](#stamp-checklist)
- [Know before you go](#know-before-you-go)
- [Packing checklist](#packing-checklist)

## Bookings {#bookings}

### 🚗 Rental car — BOOKED: Enterprise, Lombard
[Enterprise Rent-A-Car, Lombard on Google Maps](https://www.google.com/maps/search/?api=1&query=Enterprise+Rent-A-Car+920+E+Roosevelt+Rd+Lombard+IL) — 920 E Roosevelt Rd, Lombard, IL 60148 · (630) 916-7700. It's also on the trip map below (Day 1 pin 1; the return is Day 3 pin 2).
- Pickup **Mon Nov 23, 2026 @ 9:00 AM**
- Return **Wed Nov 25, 2026 @ 6:00 PM**, same location
- Acura Integra or similar, unlimited mileage
- **$143.42 total**
- Confirmation number is in the email, not on this public page
- **⚠️ The Lombard branch closes at 6:00 PM on Wednesday** — the return is right at closing. Day 3 is timed to land in Lombard by ~4:00–4:30 PM CT with buffer; if the day runs late, the after-hours key-drop is the fallback, and photo-documenting the drop (odometer + fuel dash photo, exterior walk-around) is the proof of condition and time.

### 🏨 Hotel — TO BOOK: one night near the park, Mon Nov 23
Only Monday night is a hotel night — Tuesday night is at his aunt's in West Bloomfield. Two checked options (Expedia, checked Nov 10, 2026; both prices were quoted for 2 nights, so a Mon-only stay is roughly half):
- **Motel 6 Richfield** — 5171 Brecksville Rd, Richfield · **$103.68 / 2 nights (~$52/night)**, refundable at that price · 6.6/10 (961 reviews) · no breakfast. Closest budget cluster to Beaver Marsh (~10 mins) — best for Tuesday's 7:24 AM sunrise start.
- **Econo Lodge Cleveland Southeast – Kent (Streetsboro)** — 9789 State Route 14, Streetsboro · **$125.37 / 2 nights (~$63/night)**, refundable rate $132.31 / 2 nights · 7.8/10 (1,001 reviews) · no breakfast. East side — closer to the Ledges, ~25–30 mins to Beaver Marsh.
- Better-room fallback if wanted: Hampton Inn Stow, $271.38 / 2 nights, breakfast included, 8.8/10.

### 🏠 Tuesday night — aunt's, West Bloomfield, MI
Overnight at his aunt's in West Bloomfield, MI on **Tue Nov 24** (address kept off this public page — the map pin is the township, not the house). Wednesday morning runs south from there to River Raisin before the drive home.

## Weather in the valley — live forecast {#weather}

Live forecast for Peninsula, OH, powered by [Open-Meteo](https://open-meteo.com).
Backup: the [National Weather Service forecast for Peninsula](https://forecast.weather.gov/MapClick.php?lat=41.2408&lon=-81.5516).

<div id="wx" class="wx-row"><p>Loading the latest forecast…</p></div>
<p id="wx-note" class="wx-note"></p>

<style>
.wx-row { display: flex; gap: 10px; flex-wrap: wrap; margin: 10px 0 4px; }
.wx-card { flex: 1 1 100px; max-width: 128px; border: 1px solid #d6dee3; border-radius: 10px; padding: 10px 6px; text-align: center; background: #f7faf9; }
.wx-card.trip { border: 2px solid #2e5a3c; background: #eef6f0; }
.wx-d { font-weight: 700; font-size: 13px; }
.wx-i { font-size: 26px; line-height: 1.25; }
.wx-t { font-size: 14px; font-weight: 600; }
.wx-c { font-size: 12px; color: #606c71; }
.wx-p { font-size: 12px; color: #1d6fb8; }
.wx-note { font-size: 12px; color: #606c71; margin-top: 0; }
</style>

<script>
(function () {
  var el = document.getElementById("wx");
  var note = document.getElementById("wx-note");
  var TRIP = { "2026-11-23": 1, "2026-11-24": 1, "2026-11-25": 1 };
  function wmo(c) {
    if (c === 0) return ["☀️", "Clear"];
    if (c === 1 || c === 2) return ["🌤️", "Partly cloudy"];
    if (c === 3) return ["☁️", "Overcast"];
    if (c === 45 || c === 48) return ["🌫️", "Fog"];
    if (c === 51 || c === 53 || c === 55) return ["🌦️", "Drizzle"];
    if (c === 56 || c === 57) return ["🌦️", "Freezing drizzle"];
    if (c === 61 || c === 63 || c === 65) return ["🌧️", "Rain"];
    if (c === 66 || c === 67) return ["🌧️", "Freezing rain"];
    if (c === 71 || c === 73 || c === 75 || c === 77) return ["🌨️", "Snow"];
    if (c === 80 || c === 81 || c === 82) return ["🌦️", "Showers"];
    if (c === 85 || c === 86) return ["🌨️", "Snow showers"];
    if (c === 95) return ["⛈️", "Thunderstorm"];
    if (c === 96 || c === 99) return ["⛈️", "Thunderstorm, hail"];
    return ["🌡️", ""];
  }
  function dayName(iso) {
    var p = iso.split("-");
    var d = new Date(p[0], p[1] - 1, p[2]);
    var days = ["Sun", "Mon", "Tue", "Wed", "Thu", "Fri", "Sat"];
    var mons = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];
    return days[d.getDay()] + " " + mons[d.getMonth()] + " " + d.getDate();
  }
  fetch("https://api.open-meteo.com/v1/forecast?latitude=41.2408&longitude=-81.5516&daily=weather_code,temperature_2m_max,temperature_2m_min,precipitation_probability_max&temperature_unit=fahrenheit&timezone=America%2FNew_York&forecast_days=16")
    .then(function (r) { return r.json(); })
    .then(function (d) {
      var t = d.daily.time, html = "", seen = 0;
      for (var i = 0; i < t.length; i++) {
        var w = wmo(d.daily.weather_code[i]);
        var isTrip = TRIP[t[i]] ? " trip" : "";
        if (TRIP[t[i]]) seen++;
        var pp = d.daily.precipitation_probability_max[i];
        html += '<div class="wx-card' + isTrip + '"><div class="wx-d">' + dayName(t[i]) + (TRIP[t[i]] ? " · TRIP" : "") + '</div><div class="wx-i">' + w[0] + '</div><div class="wx-t">' + Math.round(d.daily.temperature_2m_max[i]) + "° / " + Math.round(d.daily.temperature_2m_min[i]) + '°F</div><div class="wx-c">' + w[1] + '</div><div class="wx-p">' + (pp === null || pp === undefined ? "" : "💧 " + pp + "%") + "</div></div>";
      }
      el.innerHTML = html;
      note.textContent = seen === 0
        ? "Showing the current forecast window. Your trip (Nov 23–25) is not in it yet — check back during trip week and those days will be highlighted here."
        : "Your trip days are in this forecast — the green cards are the ones that matter. Tuesday Nov 24 is the outdoor day to dress for: sunrise at Beaver Marsh through sunset at the Ledges.";
    })
    .catch(function () {
      el.innerHTML = '<p>Could not load the live forecast right now — use the <a href="https://forecast.weather.gov/MapClick.php?lat=41.2408&lon=-81.5516">National Weather Service forecast for Peninsula</a> instead.</p>';
    });
})();
</script>

## Trip map — color-coded by day {#trip-map}

Every stop on one map: 🔵 **Day 1** (Mon, the drive east + hotel options + the two closed sites' status pins) · 🟠 **Day 2** (Tue, the ranger's Cuyahoga day + the night drive to West Bloomfield) · 🟢 **Day 3** (Wed, River Raisin + the drive home). Pins are numbered in visit order — tap a pin for the stop and a Google Maps link. **Filter by day:** use the layer checkboxes on the map (top right — on a phone, tap the layers icon). [Open the map full-screen](map.html) for easier browsing on a phone.

<iframe src="map.html" width="100%" style="border:1px solid #ccc; border-radius:8px; height:82vh; min-height:620px;" loading="lazy" title="Ohio and Michigan road trip map — stops color-coded by day"></iframe>

## Day 1 — Mon Nov 23: Lombard → Cuyahoga Valley {#day-1}

*Driving only, by design — the park day is Tuesday.*

- **9:00 AM CT — Pickup: [Enterprise, Lombard](https://www.google.com/maps/search/?api=1&query=Enterprise+Rent-A-Car+920+E+Roosevelt+Rd+Lombard+IL)** (920 E Roosevelt Rd). Fuel, coffee, on the road by ~9:15.
- **~9:15 AM CT — The drive east:** I-355 / I-88 to the Ohio Turnpike (I-80) east. Lombard → the Peninsula / Richfield area is **~351 mi / ~5 hrs 45 mins (estimate)**, and Ohio is on Eastern Time — you lose an hour on the clock.
- **~4:00–4:30 PM ET — Arrive in the valley.** Check in at the hotel (Richfield or Streetsboro — see Bookings).
- **Optional detour — [First Ladies National Historic Site, Canton](https://www.google.com/maps/search/?api=1&query=First+Ladies+National+Historic+Site+Canton+OH)** (Saxton–McKinley House, 205 S Market Ave). Canton is ~35–40 mins south of the park, so this is +~1 hr on the day. **The site is closed Mondays** (Nov–Apr it's Thu–Sat only), so this would be an exterior / photo stop only — no museum, no house tour, no stamp. Only if the drive is running early and the light holds.
- **Evening — early night.** Nothing planned after check-in: Tuesday starts before sunrise. The two other closed sites, Garfield and Perry's Victory, are on the map as status pins (Day 1 pins 5–7) — see [Know before you go](#know-before-you-go) before improvising a detour to either.

## Day 2 — Tue Nov 24: the ranger's Cuyahoga day, then West Bloomfield {#day-2}

*The whole day is the Park Ranger's list, in the ranger's order — bookended by sunrise and sunset. Daylight in Peninsula: sunrise 7:24 AM, sunset 5:00 PM ET.*

- **~7:10 AM — [Beaver Marsh](https://www.google.com/maps/search/?api=1&query=Beaver+Marsh+Ira+Trailhead+Cuyahoga+Valley) at sunrise (7:24 AM).** Ira Trailhead, ~0.6 mi flat boardwalk / Towpath walk. Dawn is when the marsh is most alive — herons, muskrats, beavers. From the Richfield hotels this is ~10 mins; from Streetsboro ~25–30 mins.
- **~8:15 AM — [Everett Covered Bridge](https://www.google.com/maps/search/?api=1&query=Everett+Covered+Bridge+2370+Everett+Rd+Peninsula+OH)** (2370 Everett Rd, Peninsula). A short walk from the lot to Summit County's only remaining covered bridge, over Furnace Run. It sits just south of Beaver Marsh, so it pairs with the sunrise stop before the visitor center opens.
- **9:30 AM — [Boston Mill Visitor Center](https://www.google.com/maps/search/?api=1&query=Boston+Mill+Visitor+Center+Cuyahoga+Valley)** (6947 Riverview Rd) — **at opening, for the Cuyahoga Valley passport stamp.** Open daily 9:30 AM–5 PM. Grab the park newspaper / map while you're there.
- **~10:30 AM — [Brandywine Falls](https://www.google.com/maps/search/?api=1&query=Brandywine+Falls+Cuyahoga+Valley+National+Park)** — the 60-ft falls, boardwalk overlooks plus the **Brandywine Gorge Loop (1.5 mi, ~1 hr)** if you want the full loop.
- **Midday — [Peninsula village](https://www.google.com/maps/search/?api=1&query=Peninsula+OH+village)** for lunch and a stretch: a preserved 19th-century canal town inside the park — **Lock 29** and the Towpath, the Peninsula Depot, **Trail Mix Peninsula** (the Conservancy's park store, 1600 W Mill St), the G.A.R. Hall and Bronson Church exteriors on Main St. Lunch: Fisher's Café & Pub or the Winking Lizard Tavern, both open from 11 AM. This stop is also the day's buffer — if the morning runs long, it absorbs it.
- **Optional, only if you're well ahead of schedule — Blue Hen Falls** (3 mi round trip from Boston Mill via the Buckeye Trail). It was in the original best-hikes set; the ranger's five come first, and it only fits if it doesn't eat into the Ledges start time below.
- **~3:30 PM — [Ledges Trail](https://www.google.com/maps/search/?api=1&query=Ledges+Trailhead+Cuyahoga+Valley+National+Park)** (405 Truxell Rd) — start the **2.2 mi loop** in late afternoon and time **Ledges Overlook for sunset at 5:00 PM**: a west-facing rocky clearing, one of the best sunset views in the park. **Bring a headlamp** — the Ledges area closes at dusk and the walk back to the car will be in twilight.
- **~5:45–6:00 PM — Drive to West Bloomfield, MI.** Valley → West Bloomfield is ~2 hrs 45 mins (estimate) via the Ohio Turnpike / I-75. Arrive at his aunt's ~8:30–9:00 PM ET. Night there.

## Day 3 — Wed Nov 25: River Raisin, then home {#day-3}

*One stamp stop, then a straight run home in time for Thanksgiving — and for the 6:00 PM Lombard return.*

- **~8:30–9:00 AM — Leave West Bloomfield** and drive ~1 hr south to Monroe, MI.
- **~10:00 AM — [River Raisin National Battlefield Park](https://www.google.com/maps/search/?api=1&query=River+Raisin+National+Battlefield+Park+Monroe+MI)** (333 N Dixie Hwy, Monroe). Visitor center open daily (~10 AM–5 PM in winter) — **passport stamp here**, plus the War of 1812 battlefield story ("Remember the Raisin"). Budget ~1–1.5 hrs.
- **~11:30 AM ET — Leave Monroe for home.** Monroe → Lombard is ~285 mi / ~4 hrs 30 mins (estimate), and you gain the hour back crossing into Central Time — that puts Lombard at ~3:00–3:30 PM CT before stops; with a fuel / food stop, plan on **~4:00–4:30 PM CT**.
- **By 6:00 PM CT — Return: Enterprise, Lombard.** The branch closes at 6:00 PM, so the timed arrival above is the plan, not the after-hours key-drop. If traffic eats the buffer and the key-drop becomes necessary, photo-document the drop (dash, walk-around, car in its spot).
- **Evening — home for Thanksgiving.** 🦃

## Stamp checklist {#stamp-checklist}

- [ ] **Cuyahoga Valley National Park** — Boston Mill Visitor Center, Tue ~9:30 AM (the one stamp that anchors the trip)
- [ ] **River Raisin National Battlefield Park** — Visitor Center, Monroe, Wed ~10:00 AM
- [ ] ~~First Ladies NHS~~ — **not available this trip**: closed Mon–Wed in the Nov–Apr season (Thu–Sat only); exterior only if detoured to on Monday
- [ ] ~~James A. Garfield NHS~~ — **not available this trip**: closed Mon–Wed in the Nov–Apr season (Fri–Sun only)
- [ ] ~~Perry's Victory & International Peace Memorial~~ — **not available this trip**: the visitor center's last 2026 day was Oct 26; it reopens in May

## Know before you go {#know-before-you-go}

- **Only 2 of the 5 sites are actually open Mon–Wed this week.** Cuyahoga Valley (Boston Mill, daily 9:30 AM–5 PM, closed Thanksgiving Day) and River Raisin (daily ~10 AM–5 PM) are fully open. The other three are closed or done for the season — see the stamp checklist. A spring **Fri–Sun** trip is when Garfield (Fri–Sun), First Ladies (Thu–Sat) and Perry's Victory (visitor center from May) are all open at once.
- **Perry's Victory, if you're tempted anyway:** the grounds are open, but the memorial plaza / rotunda / observation deck are closed all of 2026–27 for the Upper Plaza Rehabilitation, and getting there means the **Miller Ferry from Catawba** (runs Nov 2–25 on a reduced schedule, last mainland departure ~5:00 PM; the Jet Express ended Oct 25). It does not fit this trip's clock — that's a deliberate skip, not an oversight.
- **The train is out.** The Cuyahoga Valley Scenic Railroad's daytime National Park Scenic excursions ended Oct 31. The only Tuesday service is the North Pole Adventure — a 90-minute Santa ride built for kids and families (5:00 PM and 7:55 PM from Rockside, right when you're at the Ledges for sunset and then driving to Michigan). Skipped on purpose.
- **Sunrise / sunset, Tue Nov 24 (Peninsula, OH):** 7:24 AM / 5:00 PM ET — 9 hrs 36 mins of daylight. The ranger's bookends use both edges of it, so keep the midday Peninsula stop loose.
- **Brandywine Falls and the Ledges close dusk–dawn.** The sunset plan works because you're walking out at dusk, not starting after it — headlamp in the pack.
- **Towpath note:** the Boston Trailhead → Lock 29 Towpath closure ran Aug 24–Nov 20, 2026, so it's over before this trip — the Towpath is whole again for the Beaver Marsh and Peninsula walks.
- **Time zones:** Ohio and Michigan are Eastern; home is Central. Monday's drive "loses" an hour, Wednesday's drive home gains it back — the Day 3 timing already accounts for it.
- **Wednesday is Thanksgiving Eve** — the busiest driving afternoon of the year. The plan's ~1.5–2 hr buffer into the 6:00 PM Lombard return is there for exactly that; don't spend it in Monroe.

## Packing checklist {#packing-checklist}

- [ ] Passport To Your National Parks Collector's Edition book (Cuyahoga + River Raisin stamps)
- [ ] Hiking boots (Hoka Transport GTX / Merrell high-ankle) — Ledges rock can be slick in late November
- [ ] Headlamp — the walk out from Ledges Overlook after sunset
- [ ] Layers for a 7 AM marsh sunrise and a 5 PM overlook sunset (late-November Ohio: expect 30s–40s °F, estimate)
- [ ] Rain shell — gorge trails and boardwalks stay damp
- [ ] Binoculars, if handy — Beaver Marsh at dawn
- [ ] Phone charger + car mount for the three long drive legs
- [ ] Snacks / water for Monday's ~6 hr drive and Wednesday's run home
- [ ] Something for his aunt — Tuesday night is at her house

---

Part of [Hari Pages](https://harikrishnad1997.github.io/hari-pages/) — all of Harikrishna Dev's GitHub Pages sites in one place.
