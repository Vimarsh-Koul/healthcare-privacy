# HealthCare — Privacy Policy

_Last updated: 2026-06-29_

HealthCare is a personal medical-records application. This policy explains what data
the app accesses through the **WHOOP** integration, how it is used, and how you can
remove it. It applies to the HealthCare app and its WHOOP developer integration.

## What we access

When you choose to connect WHOOP, you are redirected to WHOOP to grant access. With
your consent, HealthCare reads the following from the WHOOP API on your behalf:

- **Profile** (`read:profile`) — your WHOOP user id, name, email, used only to label the connection.
- **Recovery** (`read:recovery`) — recovery score, HRV, resting heart rate, SpO₂, skin temperature.
- **Sleep** (`read:sleep`) — sleep duration, efficiency, performance, respiratory rate.
- **Cycles / strain** (`read:cycles`) — day strain, average heart rate, energy expenditure.
- **Workouts** (`read:workout`) — per-workout strain and heart rate.
- **Body measurement** (`read:body_measurement`) — height, weight, max heart rate (optional).

We request `offline` access so the app can refresh data without you re-authorizing each time.

## How we use it

This data is shown back to **you** inside your own HealthCare account — as current values
and trend charts on the Devices page. It is used solely to display your health history.

## How it is stored

- WHOOP OAuth tokens and the synced metrics are stored in HealthCare's own database,
  associated with your account.
- Data is **not sold, shared, or sent to any third party.** It is not used for advertising.
- HealthCare requests **read-only** scopes; it never modifies your WHOOP data.

## Retention and deletion

- You can **disconnect WHOOP** at any time from the Devices page. Disconnecting deletes the
  stored tokens and the synced WHOOP metrics for your account.
- Deleting your HealthCare account removes all associated data.

## Security

Access is protected by authenticated, per-user access controls. Secrets and tokens are
kept server-side and are never exposed to other users.

## Contact

Questions about this policy or your data: **vimarsh2001koul@gmail.com** _(replace with your contact email)_.

This is a personal/educational project. The integration uses the WHOOP API under WHOOP's
developer terms; "WHOOP" is a trademark of its respective owner.
