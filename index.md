---
layout: default
title: Ohio & Michigan NPS Road Trip — Itinerary, Nov 23–25, 2026
---

# Ohio & Michigan NPS Road Trip {#top}

**Road-trip itinerary · Mon Nov 23 – Wed Nov 25, 2026 · Lombard / Chicago → Cuyahoga Valley → West Bloomfield → home for Thanksgiving**
Five NPS sites from the map, one full ranger-planned day in Cuyahoga Valley, and a night at his aunt's in West Bloomfield on the way back. One passport stamp is actually collectable this trip — Cuyahoga Valley (see [Know before you go](#know-before-you-go) for why the other three are exterior-only this week, and why River Raisin was dropped).

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
- [Day 1 — Mon Nov 23: Lombard → Cleveland → Fairlawn](#day-1)
- [Day 2 — Tue Nov 24: the ranger's Cuyahoga day, then West Bloomfield](#day-2)
- [Day 3 — Wed Nov 25: straight home](#day-3)
- [Stamp checklist](#stamp-checklist)
- [Know before you go](#know-before-you-go)
- [Packing checklist](#packing-checklist)

## Bookings {#bookings}

### 🚗 Rental car — BOOKED: Enterprise, Lombard
[Enterprise Rent-A-Car, Lombard on Google Maps](https://www.google.com/maps/search/?api=1&query=Enterprise+Rent-A-Car+920+E+Roosevelt+Rd+Lombard+IL) — 920 E Roosevelt Rd, Lombard, IL 60148 · (630) 916-7700. It's also on the trip map below (Day 1 pin 1; the return is Day 3 pin 1).
- Pickup **Mon Nov 23, 2026 @ 9:00 AM**
- Return **Wed Nov 25, 2026 @ 6:00 PM**, same location
- Acura Integra or similar, unlimited mileage
- **$143.42 total**
- Confirmation number is in the email, not on this public page
- **⚠️ The Lombard branch closes at 6:00 PM on Wednesday** — the return is right at closing. Day 3 is timed to land in Lombard by ~1:00–2:00 PM CT, hours ahead of closing; if the day runs late, the after-hours key-drop is the fallback, and photo-documenting the drop (odometer + fuel dash photo, exterior walk-around) is the proof of condition and time.

### 🏨 Hotel — BOOKED: Fairfield Inn & Suites Akron Fairlawn, Mon Nov 23
Only Monday night is a hotel night — Tuesday night is at his aunt's in West Bloomfield. Booked by Rajashree via Hotels.com (forwarded Nov 15, 2026):
- **[Fairfield Inn & Suites Akron Fairlawn](https://www.google.com/maps/search/?api=1&query=Fairfield+Inn+Suites+Akron+Fairlawn+208+Springside+Dr+Akron+OH)** — 208 Springside Dr, Akron, OH 44333 · (330) 665-0641. It's on the trip map below (Day 1 pin 3).
- Check-in **Mon Nov 23, 3:00 PM** · check-out **Tue Nov 24, 12:00 PM**
- Room, 2 Queen Beds (Mobility Accessible, Bathtub) · **2 adults**
- **$111.68 total** ($96.90 + $14.78 taxes), paid Nov 16, 2026
- **Non-refundable** — unlike the $57.60 refundable Motel 6 Richfield option priced Nov 14, this one can't be cancelled for a refund. (Confirmation number is in the email, not on this public page.)
- Fairlawn is on the Akron side, southwest of the park — ~14 mins to Beaver Marsh for Tuesday's 7:24 AM sunrise start (6 mi).

### 🏠 Tuesday night — aunt's, West Bloomfield, MI
Overnight at his aunt's in West Bloomfield, MI on **Tue Nov 24** (address kept off this public page — the map pin is the township, not the house). Wednesday morning is the drive straight home from there — River Raisin was dropped from the plan.

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

Every stop on one map: 🔵 **Day 1** (Mon, the drive east + Rocky River Nature Center in Cleveland + the booked hotel + the two closed sites' status pins) · 🟠 **Day 2** (Tue, the ranger's Cuyahoga day + the night drive to West Bloomfield) · 🟢 **Day 3** (Wed, the drive home). Pins are numbered in visit order — tap a pin for the stop and a Google Maps link. **Filter by day:** use the layer checkboxes on the map (top right — on a phone, tap the layers icon). [Open the map full-screen](map.html) for easier browsing on a phone.

<iframe src="map.html" width="100%" style="border:1px solid #ccc; border-radius:8px; height:82vh; min-height:620px;" loading="lazy" title="Ohio and Michigan road trip map — stops color-coded by day"></iframe>

## Day 1 — Mon Nov 23: Lombard → Cleveland → Fairlawn {#day-1}

*Drive east to Cleveland for the afternoon, then the hotel — the park day is Tuesday.*

- **9:00 AM CT — Pickup: [Enterprise, Lombard](https://www.google.com/maps/search/?api=1&query=Enterprise+Rent-A-Car+920+E+Roosevelt+Rd+Lombard+IL)** (920 E Roosevelt Rd). Fuel, coffee, on the road by ~9:15.
- **~9:15 AM CT — The drive east:** I-355 / I-88 to the Ohio Turnpike (I-80) east, then I-480 W to Cleveland's west side. Lombard → Fairlawn is **375 mi / 5 hrs 42 mins (Google Maps, via I-80 E)**, and Ohio is on Eastern Time — you lose an hour on the clock.
- **~3:30 PM ET — [Rocky River Nature Center](https://www.google.com/maps/search/?api=1&query=Rocky+River+Nature+Center+24000+Valley+Pkwy+North+Olmsted+OH) | Cleveland Metroparks** (24000 Valley Pkwy, North Olmsted). Open daily 9:30 AM–5:00 PM, free entry — ~1.5 hrs before close: wildlife exhibits and the Dunkleosteus, the deck over the 360-million-year-old shale cliff, and the Fort Hill Stairs. The reservation's trails stay open till 11 PM if you want a short walk after the center closes.
- **Evening — dinner in Cleveland with Lakshmi (to confirm).** Call Monday afternoon to confirm — reminder set for ~2:42 PM CT. Options: Amba (Indian, vegan shareables), Prosperity Social Club (Tremont), Aladdin's Eatery (Cleveland Heights).
- **Late evening — Fairlawn.** Check in at the Fairfield Inn & Suites Akron Fairlawn (see Bookings) after Cleveland — the room is held, check-in is from 3:00 PM. Tuesday starts before sunrise. The two other closed sites, Garfield and Perry's Victory, are on the map as status pins (Day 1 pins 4–6) — see [Know before you go](#know-before-you-go) before improvising a detour to either.

## Day 2 — Tue Nov 24: the ranger's Cuyahoga day, then West Bloomfield {#day-2}

*The Park Ranger's list in the ranger's order, bookended by sunrise and sunset — with three hikes folded into the gaps (Furnace Run, Blue Hen Falls, Deep Lock Quarry), ~9.1 mi of hiking in all. Daylight in Peninsula: sunrise 7:24 AM, sunset 5:00 PM ET.*

- **~7:10 AM — [Beaver Marsh](https://www.google.com/maps/search/?api=1&query=Beaver+Marsh+Ira+Trailhead+Cuyahoga+Valley) at sunrise (7:24 AM).** Ira Trailhead, ~0.6 mi flat boardwalk / Towpath walk ([AllTrails](https://www.alltrails.com/trail/us/ohio/beaver-marsh--2)). Dawn is when the marsh is most alive — herons, muskrats, beavers. From the Fairfield Inn in Fairlawn this is ~14 mins (6 mi).
- **~8:05 AM — [Everett Covered Bridge](https://www.google.com/maps/search/?api=1&query=Everett+Covered+Bridge+2370+Everett+Rd+Peninsula+OH) + the Furnace Run Loop** (2370 Everett Rd, Peninsula). Summit County's only remaining covered bridge, over Furnace Run — and from the same lot, hike the **Furnace Run Loop (1.9 mi, 246 ft, ~45–60 mins)** ([AllTrails](https://www.alltrails.com/trail/us/ohio/furnace-run)) along the creek instead of just photographing the bridge. It sits just south of Beaver Marsh, and Boston Mill is ~10 mins from the lot.
- **9:30 AM — [Boston Mill Visitor Center](https://www.google.com/maps/search/?api=1&query=Boston+Mill+Visitor+Center+Cuyahoga+Valley)** (6947 Riverview Rd) — **at opening, for the Cuyahoga Valley passport stamp.** Open daily 9:30 AM–5 PM (the stamp desk runs all day, so a late start here costs nothing). Grab the park newspaper / map while you're there.
- **~9:45 AM — [Blue Hen Falls](https://www.google.com/maps/search/?api=1&query=Blue+Hen+Falls+Cuyahoga+Valley+National+Park)** — a 15-ft falls on Spring Creek, **2.5 mi round trip from Boston Mill via the Buckeye Trail (~488 ft)** ([AllTrails](https://www.alltrails.com/trail/us/ohio/blue-hen-falls-via-buckeye-trail-boston-mill)), done by ~11:15. It was in the original best-hikes set; the old midday gap is what makes room for it.
- **~11:30 AM — [Brandywine Falls](https://www.google.com/maps/search/?api=1&query=Brandywine+Falls+Cuyahoga+Valley+National+Park)** — the 60-ft falls, boardwalk overlooks plus the **Brandywine Gorge Loop (1.5 mi, ~1 hr)** ([AllTrails](https://www.alltrails.com/trail/us/ohio/brandywine-gorge-trail)), done by ~12:30.
- **~12:45 PM — [Peninsula village](https://www.google.com/maps/search/?api=1&query=Peninsula+OH+village)** for lunch (~45 mins): a preserved 19th-century canal town inside the park — **Lock 29** and the Towpath, the Peninsula Depot, **Trail Mix Peninsula** (the Conservancy's park store, 1600 W Mill St), the G.A.R. Hall and Bronson Church exteriors on Main St. Lunch: Fisher's Café & Pub or the Winking Lizard Tavern, both open from 11 AM.
- **~2:00 PM — [Deep Lock Quarry](https://www.google.com/maps/search/?api=1&query=Deep+Lock+Quarry+Metro+Park+Peninsula+OH)** (5779 Riverview Rd, Peninsula — Summit Metro Parks, ~5 mins from the village). The **Quarry Trail (~1.4 mi)** ([AllTrails](https://www.alltrails.com/trail/us/ohio/deep-lock-quarry-trail)): quarry walls, discarded millstones and Lock 28 of the Ohio & Erie Canal. The one non-NPS stop of the day — and the day's flex stop: if anything has run long, this is the one to drop; it's last and closest to the Ledges.
- **~3:30 PM — [Ledges Trail](https://www.google.com/maps/search/?api=1&query=Ledges+Trailhead+Cuyahoga+Valley+National+Park)** (405 Truxell Rd) — start the **2.2 mi loop** ([AllTrails](https://www.alltrails.com/trail/us/ohio/cuyahoga-valley-ledges-trail)) in late afternoon and time **Ledges Overlook for sunset at 5:00 PM**: a west-facing rocky clearing, one of the best sunset views in the park. **Bring a headlamp** — the Ledges area closes at dusk and the walk back to the car will be in twilight.
- **~5:45–6:00 PM — Drive to West Bloomfield, MI.** Ledges → West Bloomfield is **195 mi / 2 hrs 58 mins (Google Maps, via the Ohio Turnpike / I-75 / I-275)**. Arrive at his aunt's ~8:45–9:00 PM ET. Night there.

## Day 3 — Wed Nov 25: straight home {#day-3}

*Straight home in time for Thanksgiving — and for the 6:00 PM Lombard return. River Raisin was dropped from the plan, so there's no Monroe detour and no second stamp this trip.*

- **~9:00 AM — Leave West Bloomfield for home.** West Bloomfield → Lombard is **291 mi / ~4 hrs 10 mins–5 hrs 20 mins typical (Google Maps, via I-94 W / I-294 N)** — Thanksgiving Eve traffic is the wide range — and you gain the hour back crossing into Central Time, so Lombard is **~12:10–1:20 PM CT**; with a fuel / food stop, plan on **~1:00–2:00 PM CT**.
- **By 6:00 PM CT — Return: Enterprise, Lombard.** The branch closes at 6:00 PM, so the timed arrival above is the plan, not the after-hours key-drop. If traffic eats the buffer and the key-drop becomes necessary, photo-document the drop (dash, walk-around, car in its spot).
- **Evening — home for Thanksgiving.** 🦃

## Stamp checklist {#stamp-checklist}

- [ ] **Cuyahoga Valley National Park** — Boston Mill Visitor Center, Tue ~9:30 AM (the one stamp that anchors the trip)
- [ ] ~~River Raisin National Battlefield Park~~ — **dropped from the plan**: the Wednesday Monroe detour was cut, so no stamp this trip
- [ ] ~~First Ladies NHS~~ — **not available this trip**: closed Mon–Wed in the Nov–Apr season (Thu–Sat only); no stop this trip
- [ ] ~~James A. Garfield NHS~~ — **not available this trip**: closed Mon–Wed in the Nov–Apr season (Fri–Sun only)
- [ ] ~~Perry's Victory & International Peace Memorial~~ — **not available this trip**: the visitor center's last 2026 day was Oct 26; it reopens in May

## Know before you go {#know-before-you-go}

- **Only 2 of the 5 sites are actually open Mon–Wed this week.** Cuyahoga Valley (Boston Mill, daily 9:30 AM–5 PM, closed Thanksgiving Day) and River Raisin (daily ~10 AM–5 PM) are fully open. The other three are closed or done for the season — see the stamp checklist. A spring **Fri–Sun** trip is when Garfield (Fri–Sun), First Ladies (Thu–Sat) and Perry's Victory (visitor center from May) are all open at once.
- **Perry's Victory, if you're tempted anyway:** the grounds are open, but the memorial plaza / rotunda / observation deck are closed all of 2026–27 for the Upper Plaza Rehabilitation, and getting there means the **Miller Ferry from Catawba** (runs Nov 2–25 on a reduced schedule, last mainland departure ~5:00 PM; the Jet Express ended Oct 25). It does not fit this trip's clock — that's a deliberate skip, not an oversight.
- **The train is out.** The Cuyahoga Valley Scenic Railroad's daytime National Park Scenic excursions ended Oct 31. The only Tuesday service is the North Pole Adventure — a 90-minute Santa ride built for kids and families (5:00 PM and 7:55 PM from Rockside, right when you're at the Ledges for sunset and then driving to Michigan). Skipped on purpose.
- **Sunrise / sunset, Tue Nov 24 (Peninsula, OH):** 7:24 AM / 5:00 PM ET — 9 hrs 36 mins of daylight. The ranger's bookends use both edges of it, and the day is now full (~9.1 mi of hiking with Furnace Run, Blue Hen and Deep Lock Quarry folded in) — the flex is Deep Lock Quarry: it's the drop if the morning runs long, and the Ledges start time doesn't move.
- **Brandywine Falls and the Ledges close dusk–dawn.** The sunset plan works because you're walking out at dusk, not starting after it — headlamp in the pack.
- **Towpath note:** the Boston Trailhead → Lock 29 Towpath closure ran Aug 24–Nov 20, 2026, so it's over before this trip — the Towpath is whole again for the Beaver Marsh and Peninsula walks.
- **Time zones:** Ohio and Michigan are Eastern; home is Central. Monday's drive "loses" an hour, Wednesday's drive home gains it back — the Day 3 timing already accounts for it.
- **Wednesday is Thanksgiving Eve** — the busiest driving afternoon of the year. The plan now lands in Lombard by ~1:00–2:00 PM CT, leaving a ~4 hr buffer into the 6:00 PM return — that buffer is there for exactly that traffic.

## Packing checklist {#packing-checklist}

- [ ] Passport To Your National Parks Collector's Edition book (Cuyahoga stamp)
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

[↑ Back to top](#top)

<a href="#top" title="Back to top" style="position:fixed; right:16px; bottom:16px; z-index:99; background:#1d6fb8; color:#fff; padding:10px 16px; border-radius:24px; text-decoration:none; font-size:14px; font-weight:600; box-shadow:0 2px 6px rgba(0,0,0,.3);">↑ Top</a>

<script>
document.addEventListener('DOMContentLoaded', function () {
  document.querySelectorAll('a[href]').forEach(function (a) {
    var h = a.getAttribute('href');
    if (h && h.charAt(0) !== '#') { a.setAttribute('target', '_blank'); a.setAttribute('rel', 'noopener'); }
  });
});
</script>
