# PULSE — Civic Map

PULSE began with a question: how can residents make local concerns visible to public agencies that cannot observe every issue across Baku? The project explores a clearer channel for reporting problems such as road hazards, damaged infrastructure, crowd conditions, and community events.

The long-term idea is to use AI to categorize reports, assess urgency and the number of people reporting an issue, and help route relevant details to the appropriate public agency. We are currently pitching the concept to government stakeholders. These capabilities are proposed, not implemented in the current prototype; prioritization would need careful validation and human oversight.

## Open the prototype

[Open the PULSE prototype on GitHub Pages](https://fsrkh12-arch.github.io/pulse-civic-map/).

## Prototype status

The map starts with illustrative reports. Visitors can filter and search, select reports, add a report, and try a location pin or device-location option. New reports and confirmations exist only in the current page session and reset on reload; they are not shared with other users. Profile names are stored locally in the current browser. The insights and routing views are demonstrations, not live municipal data or dispatch tools.

PULSE is not deployed by, partnered with, endorsed by, or integrated with a government agency. It does not contact departments or emergency services. A possible future integration is [SİMA](https://sima.az/?lang=en), an Azerbaijani digital solutions platform whose SİMA İmza service provides digital signatures and identity verification for online services. Any such integration would require authorization, appropriate privacy safeguards, and an agreed technical arrangement; it is not implemented. The prototype does not collect or store government FIN codes. A real public deployment would need an authorized operating model, privacy and security safeguards, and reliable data handling.

## Run locally

Serve the `dist/` directory with a static web server. For example, with Python installed:

```sh
cd dist
python -m http.server 8000
```

Open `http://localhost:8000`. The interface uses HTML, CSS, JavaScript, and Leaflet for the interactive map. Device location requires browser permission and a supported secure context.

This repository is private; reviewers need an accessible demo or appropriate repository access to inspect it.
