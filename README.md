# OGXTC Cheer V28 — Reliable music start

Changes:
- The supplied `rally_background_music.mp3` is preloaded and playback is attempted when the front page loads.
- When audible autoplay is rejected, a tasteful **♫ TAP TO BEGIN** button appears over the bag without blocking the zipper.
- First touch on the gold zipper calls `audio.play()` directly in the `pointerdown` handler. Keyboard zipper interaction is also supported.
- The fallback disappears when music starts; the user can still pause/resume with the music controls. Explicit manual pause is respected.
- The mini-game navigation button now says **INVITATION** (no 'SKIP TO').
- All V27 bag images, mini-game, awards, 30% pop-out, pull-up invitation, event details and WhatsApp RSVP remain.

Important: Android and iOS browser autoplay policies cannot be bypassed. Guest interaction is the reliable fallback.

Publish all five files to the root of https://github.com/balloonaire/welcome-2027-pickleball.
