# New Zealand South Island itinerary · 2026–27

A responsive, standalone family itinerary for 23 December 2026 to 2 January 2027: four adults and a one-year-old baby.

The page begins with a numbered route overview and illustrated map, followed by destination photos, all eleven daily schedules, overnight suggestions, a booking checklist and publishing guidance. The layout uses a consistent dark theme. All three Wānaka stops on 28 December are included; Coronet Peak is intentionally omitted.

## View locally

Open `index.html` in your browser. There are no dependencies or build steps. Photos, styling, the route illustration and JavaScript are embedded in the HTML. External map and booking links require internet access.

For a local server:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Edit

`index.html` is the source of truth. Edit its HTML for itinerary details, its `<style>` block for the design and its final `<script>` block for the personal checklist. Checklist state is stored only in the visitor’s browser and is not shared between travellers.

Keep image credits and licence links in the footer when reusing the embedded photos. The route illustration is schematic and must not be used for navigation. The full credit list is in the page’s Photo credits disclosure.

## GitHub Pages

Publish from `main` and `/ (root)` under **Settings → Pages → Build and deployment → Deploy from a branch**. The `.nojekyll` file serves this as a static page without Jekyll processing. Future pushes to `main` will publish updates automatically after Pages is enabled.

Expected site address: https://vitorsei.github.io/nz-trip-itinerary-2026/

## Travel planning

The itinerary contains two hotel nights and eight campervan nights. Accommodation suggestions are not confirmed reservations. Confirm the 1 January campervan return, infant restraint compatibility in the exact vehicle, holiday campground bookings, road conditions and trail accessibility before travel. Drive times are approximate planning estimates.
