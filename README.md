# Bass Coach

A practice coach for double bass scales that runs in the phone's browser.

- Records the exercise with the phone camera (1080p, 30 fps, microphone processing off).
- Listens to every note's tuning and matches it to the selected scale or arpeggio.
- Tracks the left hand, bow arm and posture with MediaPipe Hands and Pose, and links tuning misses to hand frame, shifts and bow arm.
- Writes a short coach's note with a practice plan.

Everything runs on the device. Recordings and sessions stay on the phone.

Hand and pose tracking: MediaPipe (Apache 2.0), files in `mp/`.
