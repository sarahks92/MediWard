# MediWard V13 — clinical interaction update

React/Vite project for Vercel. Upload the contents of this folder to the GitHub repository.

Changes: interactive ECG tracing and rhythm recognition for Bed 6; natural symptom questions; emergency interventions produce scenario-specific outcomes, with mandatory reassessment before completion; optional SBAR; urgent bleeps close routine bedside screens.

**Limitations:** Conversations use scripted responses and pattern matching, not generative AI. Real AI conversations require a secure server endpoint and an API provider. Clinical algorithms are illustrative and require clinical review before educational deployment.


## V14 updates
- Bed selection is now immediate: click any bed to approach it and open the patient, avoiding blocked auto-walking paths.
- Manual keyboard and on-screen movement remain available, with wider interaction range near beds.
- Every patient now has a fictional age and two-line admission summary visible at the bedside.


## V15 changes
- Emergency assessment completes ABCDE once, with automatic nurse reassessment and clear outcome. No repeat-reassessment keyword loop.
- Effective intervention remains required; SBAR handover now requested before completing the emergency.
- Bed 8 pain questions elicit a pain score; neurovascular examination questions or actions reveal perfusion, sensation and movement findings.


V16: Bed 6 ECG → interpretation → echocardiography request → completed. Echo form accepts concise AF indications and closes the job without looping.


## V17 changes
- Hard mode routine bleeps every 22 seconds, with up to eight retained and four visible at once. Emergency timing and five-minute deadline unchanged.
- Animated sun across the ward and bedside windows, transitioning to sunset and night.
- Chloe Ting: request observations in natural language; nurse gives actual observations and advances to the X-ray request.
