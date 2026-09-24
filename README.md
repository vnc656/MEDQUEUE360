# MEDQUEUE 360

A deployment-ready, interactive MVP for hospital wait-time optimization. Open `index.html` in a browser, or deploy the folder directly to Vercel, Netlify, or GitHub Pages.

## Demo flow

1. Start in **Admin overview** to establish the hospital problem and live prediction model.
2. Open **Patient portal** to show token GM-047, position, alerts, and estimate.
3. In **Doctor dashboard**, use **Complete & call next patient**. Every patient-facing prediction recalculates.
4. Return to Admin. Use **Assign Doctor 3** on the congestion alert to demonstrate smart queue rebalancing.

The prediction uses a transparent hybrid queue model: priority-adjusted patients ahead × consultation time ÷ available doctors. It recalculates dynamically as the queue changes.

## Expanded MVP capabilities

- Five live department queues: General Medicine, Cardiology, Orthopedics, Pediatrics, and Dermatology.
- Patient live tracking, queue-change alerts, current-token display, prediction explanations, and arrival wayfinding.
- Dedicated staff console for registration, department routing, priority assignment, patient movement, arrival/no-show status, and token cancellation.
- Cross-portal updates for emergency arrivals, doctor capacity changes, and completed consultations.
