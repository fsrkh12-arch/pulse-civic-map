# PULSE — Civic Map

PULSE is an exploratory prototype for helping residents visualize and describe local concerns in Baku, such as road hazards, damaged infrastructure, crowd conditions, and community events. It explores how a map and a city feed might make those signals easier to understand.

## Prototype status

The map starts with illustrative reports. Visitors can filter and search, select reports, add a report, and try a location pin or device-location option. New reports and confirmations exist only in the current page session and reset on reload; they are not shared with other users. Profile names are stored locally in the current browser. The insights and routing views are demonstrations, not live municipal data or dispatch tools.

PULSE is not deployed by, partnered with, endorsed by, or integrated with a government agency. It does not contact departments or emergency services. SIMA verification is presented as a possible future integration; government FIN codes are not collected or stored. A real public deployment would need an authorized operating model, privacy and security safeguards, and reliable data handling.

## Run locally

Serve the `dist/` directory with a static web server. For example, with Python installed:

```sh
cd dist
python -m http.server 8000
```

Open `http://localhost:8000`. The interface uses HTML, CSS, JavaScript, and Leaflet for the interactive map. Device location requires browser permission and a supported secure context.

This repository is private; reviewers need an accessible demo or appropriate repository access to inspect it.
