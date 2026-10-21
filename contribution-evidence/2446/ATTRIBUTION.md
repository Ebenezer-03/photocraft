# Object Selection regression captures

These images were rendered directly by PhotoCraft's egui test harness with a synthetic red disc on white. They contain no image from the original bug report.

The gesture starts with a small rectangle selected at the upper left. Shift is held at mouse-down over the disc and released before mouse-up. Before the fix, the old rectangle is lost. After the fix, the rectangle remains selected and the disc is added.

| Path       | Title                        | Author       | Source                                             | License           |
|------------|------------------------------|--------------|----------------------------------------------------|-------------------|
| before.png | Object Selection before fix  | Ebenezer-03  | PhotoCraft egui regression harness, synthetic scene  | MIT OR Apache-2.0 |
| after.png  | Object Selection after fix   | Ebenezer-03  | PhotoCraft egui regression harness, synthetic scene  | MIT OR Apache-2.0 |

Test: `object_selection_keeps_the_mode_from_the_mouse_press`.
Related report: https://github.com/storytold/artcraft/issues/2446
