# MediWard V13 — clinical interaction update

React/Vite project for Vercel. Upload the contents of this folder to the GitHub repository.

Changes: interactive ECG tracing and rhythm recognition for Bed 6; natural symptom questions; emergency interventions produce scenario-specific outcomes, with mandatory reassessment before completion; optional SBAR; urgent bleeps close routine bedside screens.

**Limitations:** Conversations use scripted responses and pattern matching, not generative AI. Real AI conversations require a secure server endpoint and an API provider. Clinical algorithms are illustrative and require clinical review before educational deployment.


## V14 updates
- Bed selection is now immediate: click any bed to approach it and open the patient, avoiding blocked auto-walking paths.
- Manual keyboard and on-screen movement remain available, with wider interaction range near beds.
- Every patient now has a fictional age and two-line admission summary visible at the bedside.
