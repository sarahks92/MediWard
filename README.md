# MediWard V11 — bleeps and clinical prioritisation

Run `npm install`, `npm run build`, then `npm run dev`. Deploy the repository root to Vercel using Vite.

Changes from V10:
- First urgent bleep at 120 real seconds, one urgent patient at a time.
- In hard mode, routine bleeps every 45 seconds even when busy.
- The player can open any patient, even if an emergency is pending; a nurse warns them.
- An unanswered emergency has a five-minute real-time countdown and sends the patient to the graveyard on expiry.
- Graveyard retry reopens an emergency scenario.
- After a completed emergency, two routine jobs are required before the next emergency.

This is a training-game prototype; the fixed five-minute countdown is a gameplay mechanic, not a clinically valid survival estimate.
