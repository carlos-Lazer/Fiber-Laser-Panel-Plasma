# Plasma Panel Wafer — Interactive Operator Checklist

An offline-capable, interactive checklist derived from the supplied Plasma Panel Wafer Etching production SOP.

## Open the interactive guide

Once GitHub Pages is enabled, open:

https://carlos-lazer.github.io/Fiber-Laser-Panel-Plasma/

To enable it: **Settings → Pages → Build and deployment → Deploy from a branch → main → / (root) → Save**.

GitHub’s file viewer displays HTML source. Use the Pages website to operate the checkboxes, or download `index.html` and open it in a browser.

## Features

- 167 checkboxes, section navigation, and progress tracking
- Operator, wafer and lot details, plus run notes
- Browser-local saved progress, printable record and JSON export
- Original SOP photos and critical machine rules

Checkmarks record operator confirmation; they do not control or verify the machine. Export or print each run record. Browser storage is local to the browser and device.

## Source review required

Section 14 orders profile loading differently from the global Start Run rule. The checklist preserves the original sequence and flags this discrepancy for the procedure owner to resolve before production use. Section 17 gives no numeric Count limits. Conditional repeat-pass actions may remain unchecked when not needed; document the reason in run notes.

## Bottom wafer rotation update

After rotating the Bottom Wafer 180°, repeat Wobble Left and Wobble Right before the second-orientation Horizontal and Vertical sensors. Do not Home between the left and right wobble profiles. Home after completing the right-side wobble, then continue with the sensor procedures. Bottom STM remains once after the second-orientation sensors. This revision starts a fresh browser checklist so earlier completion marks do not carry into the changed process.
