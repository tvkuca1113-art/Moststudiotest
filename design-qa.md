# Design QA — MOST Studio test

Status: passed for test preview, 2026-09-22.

Scope: independent Moststudiotest repository. Original site and repository were not modified.

Reference: user-selected dark forest concept, stone arch, lime accents and Hrast/Lipa panels. Compared the 1122 × 1402 reference side by side with the browser capture normalized to 1122 px width and cropped to the same visible height. Screenshots retained in session QA evidence.

Surfaces inspected: desktop hero and project section, full page, mobile hero at 390 × 844 (375 px content viewport), mobile menu, project dialog, contact message preview, and German language state.

First pass findings and corrections:
- P2: desktop headline and project heading undersized. Increased responsive type scales.
- P2: scene positioned too high. Adjusted vertical placement.
- P2: mobile arch crowded the primary button. Moved the scene below the copy and increased hero height.

Final visual pass: headline, primary button and artwork are readable and separated; forest/lime/cream palette, stone scene, serif project previews and page hierarchy match the selected direction. No blocking P0–P2 findings remain. P3: generated stone scene and demo preview imagery are approximate recreations, not pixel-identical copies of the reference.

Functional checks passed: anchor navigation; mobile menu opening, navigation and closing; project dialog; reveal third project; BS/DE switch; contact message preview and clipboard confirmation. Contact does not send messages. Existing demo links open separately. No broken images were found. No terminal.local application warnings or errors were reported by browser log inspection. Mobile document width matched its viewport without horizontal overflow.

Limits: mobile layout was inspected in a responsive browser frame, not a physical device. Hero panels are illustrative artwork. Existing full demos were not rebuilt in this visual test.
