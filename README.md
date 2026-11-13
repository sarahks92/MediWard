# MediWard V2

A Vite + React educational ward game prototype.

## Deploy
Upload **the contents of this folder** to the root of your GitHub repository, replacing the existing files. Vercel framework: Vite; build: `npm run build`; output: `dist`.

## New in V2
- Multiple interactive free-text steps per task and emergency (no multiple-choice questions).
- Nurse priority warnings for less urgent bleeps, animated walking nurses, clickable nurse station.
- Graveyard retry and emergency history.
- Fishbone and other achievement outcomes.
- Speech-to-text SBAR using browser Web Speech API where supported.
- Animated bleep alert and generated audible bleep (browser audio may require initial interaction).

## Limitations
This is a prototype, not clinically validated software. Free-text actions use a lightweight keyword matcher and do not provide AI conversation or clinically reliable grading. The relative dialogue is scripted, not AI. Speech transcription requires a compatible browser and microphone permission; Safari support varies. This version does not include a catheter insertion animation or an interactive prescribing chart. Full production build was not locally verified because npm installation was unavailable in the execution environment.


V3 changes: Meddy Reg animated at bedside with tailored hints, expanded free-text synonyms, meaningful incorrect-action feedback, capped hard-mode bleeps, patient zoom, contextual nurse dialogue, and hidden priority labels.
