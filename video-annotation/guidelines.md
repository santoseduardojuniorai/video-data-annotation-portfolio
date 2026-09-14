# Video Annotation Guidelines

## Objective

The objective of this exercise is to identify visible objects and human actions
in a short video. Each annotation records the start time, end time, label,
description, and confidence level.

## Scope

This exercise focuses only on actions that are clearly visible in the video.
No assumptions are made about events outside the camera frame.

## Labels

### person_picks_object

Use this label when a person lifts an object from a visible surface or location.

### person_places_object

Use this label when a person puts an object onto a visible surface or location.

### person_moves_object

Use this label when a person changes the location of an object without clearly
picking it up and placing it down as separate events.

### person_opens_object

Use this label when a person opens a visible object, such as a book, box, door,
or container.

### person_closes_object

Use this label when a person closes a visible object, such as a book, box, door,
or container.

### person_writes

Use this label when a person writes on paper or another visible writing surface.

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
