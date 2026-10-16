# Cadence

Personal nutrition and training tracker. Daily fuel targets that adapt to training, sleep, injury and weigh-ins.

- Single-file web app (`index.html`), no build step.
- Views: Today, Progress, Meals (7 days), Training, Races, Profile.
- Rules: Katch-McArdle BMR, protein 2-2.2 g/kg, carb floors per session type, no deficit after poor sleep, sickness or in race week.
- Storage: the claude.ai artifact data store (private to the owner). Falls back to browser storage when the store is unavailable.

No personal data is stored in this repository.
