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

## Second edition — user-requested visual improvement

Source visual truth: /workspace/scratch/134ade74ad7a/generated_images/exec-2c5a373a-8d8b-46ed-9cd9-d3bcb6ab8c47.png.
Browser implementation: /workspace/scratch/most-test-qa/revision-final.jpg and revision-final-page.jpg.
Combined comparison: /workspace/scratch/most-test-qa/revision-comparison-final.jpg.
Viewport: desktop browser 1348 CSS content width, 1363 capture width; mobile 390 × 844 browser frame with 375 px content area. Reference 1122 × 1402; desktop capture normalized to 1122 px width and cropped to the same 1402 px region. BS home, default project state.

Intentional revision after rejection: retained architectural hero direction, strengthened CTA, replaced two small project cards with selectable full-width projects and desktop/mobile preview controls. Added service strip, clearer lower-page hierarchy and a studio wordmark. These are requested design improvements, not strict copies of the reference's lower section.

Comparison history:
- P2 first revision: shortening desktop hero cropped arch at top and put panel behind heading. Restored proportional height and vertical asset offset. Final combined comparison shows separated heading, artwork and header controls.
- P2 first mobile revision: button crowded arch. Increased scene start to 475px; final mobile capture shows clear separation.
- P2 mobile project tabs: third option required horizontal scrolling. Switched to three compact equal columns, keeping all options visible. Retested selection of Meridijan.
- Development syntax error in added keyboard handler was fixed before final build and verification. Fresh application console inspection returned no warnings/errors for terminal.local.

Required surfaces:
- Typography: Inter headings and interface; Playfair for warm project previews; sans-serif business preview. Checked BS and DE hero wrapping, mobile headings and tab labels.
- Layout: inspected desktop full-page capture and focused mobile hero/project states. Primary buttons and project selectors stay visible. Mobile preview control narrows the rendered concept.
- Color: retained forest, lime and cream; distinct warm, pale green and dark green project presentations. Selected controls have visible contrast.
- Images: retained optimized generated architectural scene and existing WebP photos; no missing assets observed. Generated scene remains an approximation of the selected reference.
- Copy: Bosnian and German UI; concepts clearly labelled; no invented clients or results. Existing full demos still open separately.

Interactions verified: project tab changes (Lipa and Meridijan), desktop/mobile preview toggle, opening and closing project dialog, BS/DE switch, anchor navigation. Prior contact and mobile navigation checks remain applicable; those behaviors were not rewritten. Build and four Sites packaging/runtime tests passed. Physical-device testing was not performed.

Final result: passed
