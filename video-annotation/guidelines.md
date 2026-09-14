# Video Annotation Guidelines

## Objective

The objective of this exercise is to identify visible objects and human actions
in a short video. Each annotation records the start time, end time, label,
description, and confidence level.

## Scope

This exercise focuses only on actions that are clearly visible in the video.
No assumptions are made about events outside the camera frame.

## Labels

### child_holds_toy

Use this label when a child visibly holds a toy.

### child_moves_toy_backward

Use this label when a child moves a toy backward across a visible surface.

### child_moves_toy_forward

Use this label when a child moves a toy forward across a visible surface.

### adult_reads_book

Use this label when an adult visibly looks at an open book for the purpose of reading.

### adult_looks_at_child

Use this label when an adult turns or directs their gaze toward the child.

### adult_smiles

Use this label when an adult visibly smiles.

### camera_focuses_on_adult

Use this label when the camera focus or framing shifts to the adult.

### camera_focuses_on_toy

Use this label when the camera focus or framing shifts to the toy.

## Timestamp Rules

1. The start time is the moment when the visible action begins.
2. The end time is the moment when the visible action ends.
3. Timestamps are recorded in the format `MM:SS`.
4. Do not create annotations for actions that are not clearly visible.
5. Do not guess an action when an object or hand is hidden from view.

## Confidence Levels

- **High:** The object and action are clearly visible.
- **Medium:** The action is mostly visible, but some details are uncertain.
- **Low:** The action is difficult to identify because of occlusion, camera
  movement, poor lighting, or an unclear view.

## Quality Rules

1. Use one label for one clear action.
2. Use neutral and factual descriptions.
3. Do not describe emotions, intentions, or assumptions.
4. Review all timestamps before finalizing the table.
5. Use the same labels consistently throughout the exercise.
