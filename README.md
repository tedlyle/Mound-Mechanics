# Mound Mechanics

A browser tool for coaches. Upload a pitching video and it:

- tracks the pitcher's body (MoveNet Thunder, running on the device)
- finds leg lift, foot strike, release and finish
- checks balance, glove position, arm timing, stride, finish and direction
- suggests drills for each issue
- exports an annotated MP4 with slow motion, freeze-frame callouts and a summary card

Videos never leave the device. Nothing is uploaded or stored.

## Filming tips

- One pitch per clip, 3 to 10 seconds long, whole body in frame, phone steady at hip height.
- A side view (1st- or 3rd-base side) measures the most. A view from behind shows falling off line.

## Files

- `index.html`: the app
- `movenet-thunder.json`, `movenet-thunder-1.bin`, `movenet-thunder-2.bin`: the body-tracking model
