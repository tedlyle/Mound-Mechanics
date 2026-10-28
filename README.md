# Mound Mechanics

A browser tool for coaches. Upload pitching or batting videos (separate buttons) and it:

- tracks the pitcher's body (MoveNet Thunder, running on the device)
- finds leg lift, foot strike, release and finish
- checks 15 mechanics points: balance, early drift, tempo, head stability, stride length and direction, glove at foot strike and after release, arm timing, elbow height, front-knee bracing, posture at release, arm slot, finish and direction
- scales drill reps to how far off each issue is, and checks consistency between clips
- downloads a printable practice plan (PDF) with daily checkboxes
- hitting: checks balance in the load, stride, head movement, hand drop, hips-before-shoulders sequence, front leg at contact, extension, finish balance and swing timing, with 14 hitting drills
- suggests drills for each issue
- exports an annotated MP4 with slow motion, freeze-frame callouts and a summary card
- combines every angle of the same pitcher (same pitcher name) into one report, one practice plan and one all-angles video

Videos never leave the device. Nothing is uploaded or stored.

## Filming tips

- One pitch per clip, 3 to 10 seconds long, whole body in frame, phone steady at hip height.
- A side view (1st- or 3rd-base side) measures the most. A view from behind shows falling off line.

## Files

- `index.html`: the app
- `movenet-thunder.json`, `movenet-thunder-1.bin`, `movenet-thunder-2.bin`: the body-tracking model
