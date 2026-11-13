# MediWard 🩺

A retro-inspired interactive medical ward game prototype, with 10 patients, day/night shift, diverse characters, a Meddy assistant, clinical tasks, ABCDE emergencies, bleeps, SBAR handovers, achievements and easy/hard modes.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL displayed in the terminal.

## Deploy to Vercel

1. Create a new GitHub repository and upload **all the contents of this folder** (not just the ZIP).
2. In Vercel select **Add New → Project**, import the GitHub repository.
3. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
4. Select **Deploy**.

## Notes

- This is a playable **first prototype**, not a validated clinical training product.
- It uses a locally rendered, stylised ward rather than a full tile-engine game. You can move your character using WASD or arrow keys and click beds to interact.
- The blue Meddy uses the central brand colour `#2764D9`. This is an approximation of the M in the supplied document; replace the `BLUE`/CSS colour if you have the exact original brand hex code.
- Emergency investigation text uses a limited keyword matcher, not an AI clinician. SBAR is checked for length, not clinical correctness.
- The patient graveyard is a deliberately playful failure/retry mechanic; it does not represent real-world consequences of routine task errors.
- No backend, login, database, external API, or ongoing AI fee is needed for this prototype.
- Clinical content is simplified and must be checked against current local UK guidelines before use for education or assessment.

## Future upgrades

Add a tile-based walkable map, richer multi-stage scenarios, prescribing forms with drug/allergy/renal checks, proper CPR/choking minigames, persistent saves, a scenario authoring interface, and validated clinical scoring.
