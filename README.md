# Ostler Trips app

The logbook, replay and trip sharing.

Part of [Ostler](https://github.com/openostler/ostler), an open, local-first,
smart-home-like ecosystem for your car. Ostler is built like a phone OS: the
platform repo is the bare system, and every feature is an app or pack in its
own repo, installed from the Store.

Status: empty. This project follows UX first: design, then UI against
recorded fixtures, then wiring. Nothing is built here until the app's design
brief is approved. The briefs live in
`openostler/ostler/references/design/2026-10/brief/`.

Licence: AGPL-3.0-or-later. Contributions are
accepted under the project CLA.

## What this repo holds

- **Owner in the brief:** `app:trips`.
- **Contents:** trip timeline, trip detail, analysis, replay controls and the share sheet (the recorder, store and export stay in the OS); widgets: last trip, recording, this month, Rewind shortcut.
- **Design brief:** [50-vehicle-f-trips](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/50-vehicle-f-trips.md), [50-vehicle-g-share-places](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/50-vehicle-g-share-places.md), [50-vehicle-h-recordings](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/50-vehicle-h-recordings.md), [50-vehicle-l-apps](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/50-vehicle-l-apps.md) (index: [99-index](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/99-index-a.md)).
- **Spec:** [trip-sharing](https://github.com/openostler/ostler/blob/main/specs/2026-10-07-trip-sharing-design.md).
- **Code that moves here later** ([ADR-0046](https://github.com/openostler/ostler/blob/main/decisions/adr-0046-empty-os-every-app-an-add-on.md)): `ui/src/destinations/LogsDestination.tsx`, the Logs and Analysis screens and `ui/src/components/replay/` (map engine files stay in the OS). It moves only after this app's designs are approved ([ADR-0045](https://github.com/openostler/ostler/blob/main/decisions/adr-0045-ux-first.md)).
