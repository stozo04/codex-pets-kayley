# Curly look mechanics

The standard contact sheet preserves the approved adult character and outfit. The
feet and lower torso anchor remain fixed. No walking, hand gestures or new props.

Ocean-blue eyes lead attention, then the head and neck turn naturally. Eyelids and
brows respond to gaze while facial proportions stay fixed. The upper torso follows
very slightly; curls follow the head while remaining attached to the same side.
Earrings follow the ears and the pendant stays centered on the shirt.

Cardinals use screen coordinates:

- 000 up: face stays horizontally centered; chin lifts, eyes look upward and lids
  open upward. The nose points visibly upward. This must differ clearly from neutral.
- 090 screen-right: head turns about 40 degrees toward the screen-right edge.
  Nose tip and both irises shift toward screen-right relative to the facial center;
  the far cheek and eye are partially occluded, while the body stays anchored.
- 180 down: face stays horizontally centered; chin lowers and eyes look downward,
  with lowered lids and more visible upper hair. Preserve recognizable face shape.
- 270 screen-left: oppose 090 with about a 40-degree screen-left head turn. Nose tip
  and irises lie screen-left of facial center; the opposite cheek becomes visible.
  Keep the anatomical hair part, jewelry and lower-body placement consistent.

Intermediates trace one clockwise gaze circle. Each 22.5-degree step combines smooth
head yaw and pitch between adjacent cardinals. No body rotation, affine tilting,
skull stretching, mirrored cells, jumping scale, or pupils outside the eyes.
The 157.5-to-180 and 337.5-to-000 boundaries must remain gradual. Hands stay down.

Use the canonical base for identity, the approved standard sheet for display scale,
and approved cardinal anchors for all direction meanings. All backgrounds are
magenta #FF00FF before deterministic transparency extraction.
