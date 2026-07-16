# Communicator

**A free communication app for people who cannot speak.**

Open it in a browser, allow the camera, and movements become spoken words:
turn your head right to say *"Yes"*, left for *"No"*, hold up one finger for
*"I'm hungry"*, a long blink for *"I love you"* — fourteen movements in total,
every phrase customisable.

**▶ Use it now: https://ecksquad.github.io/communicator/**

No install. No account. No cost. Everything — including the camera video —
is processed on your own device and never leaves it.

## Who it's for

It was built for a friend who cannot speak or sign, so a handful of reliable
movements — head turns, blinks, an open mouth, simple hand poses — are enough
to say the things that matter most. It may help people living with ALS/MND,
cerebral palsy, stroke, autism, or anyone who needs a voice while their hands
can't manage a keyboard or a picture board.

## What it can do

- **14 movements** — head turns / nods, long blink, raised eyebrows, open
  mouth, and hand gestures (1 finger, 2 fingers, open palm, fist, thumbs
  up/down, 🤟)
- **Any phrase on any movement** — a caregiver can change every text in
  Settings
- **Your own voice** — record a phrase once and the app plays *your recording*
  instead of the synthetic voice
- **7 languages** — English, Svenska, Українська, Español, Deutsch, Français,
  Polski — with male or female voice
- **Tuned for real bodies** — hold times, cooldowns and sensitivity sliders so
  involuntary movements don't trigger phrases
- **Private by design** — the camera feed is analysed on-device
  (Google MediaPipe running locally in the browser); nothing is uploaded

## Tips

- Works best on a tablet or computer with the face well lit
- Add it to the home screen and it opens like a normal app
- Settings (⚙) lets you disable movements the user can't make and tune the
  ones they can

## For developers

A single `index.html` — MediaPipe Tasks Vision (FaceLandmarker +
GestureRecognizer), Web Speech API for TTS, MediaRecorder + IndexedDB for
own-voice recordings, localStorage for configuration. MIT licensed — use it,
translate it, build on it.

## Contact

Questions, feedback, feature requests or success stories: **ecksquad@gmail.com**
(or open an issue here). Hearing what works and what doesn't is what improves the app.

If this app helped someone you love communicate, you can support future
development at the [donation page](https://ecksquad.github.io/communicator2/donate.html) ❤️
