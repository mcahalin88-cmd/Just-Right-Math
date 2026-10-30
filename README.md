# Just Right Math

A worksheet generator for differentiated independent practice. Pick a standard and it builds three versions of the same worksheet:

- **Support (●)**: friendlier numbers, visual models, a hint on each problem, a worked example and larger print
- **On Level (▲)**: grade-level practice of the standard
- **Stretch (■)**: multi-step problems, missing values and a closing reasoning task

## What it covers

- **Standards:** New York Next Generation Mathematics Learning Standards (default) or Common Core
- **Grades 1–8:** full coverage of the New York standards, grouped by IM unit (about 160 standards in all)
  - New York–only standards include coins in grade 1 (NY-1.MD.3b), four-digit place value in grade 3 (NY-3.NBT.4), perfect squares and cubes and probability in grade 6, and box plots in grade 7
  - Standards that New York removed or moved are shown only when Common Core is selected
- **Curriculum style:** an Illustrative Mathematics–style layout with a warm-up routine, practice and a cool-down, or neutral wording

## Other features

- Answer keys
- Discreet tier labels (● ▲ ■) so students can't tell which version they have
- Set codes: the same code always rebuilds the same problems
- A side-by-side view of all three versions
- No student data is collected or stored

## Using it

Open `index.html` in a web browser. It is a single file with no build step; fonts load from Google Fonts.

## Printing

When the page is opened directly (for example, hosted on Netlify), two print buttons appear in the sidebar. Both follow the tab you are on:

- **Print this view** prints the sheet or sheets on screen.
- **Print sheet** prints the worksheet for the tab you are on (Support, On Level or Stretch), or all three on the All three tab, with no answers.
- **Print key** prints a condensed answer key for the same tab: the warm-up, every practice answer, the reasoning task and the cool-down on one page. On the All three tab, the three versions sit side by side. To print the full sheet with answers written in, turn on **Show answer key** and use the browser's print command.

To save a PDF, choose "Save as PDF" in the browser's print dialog. The buttons are hidden when the page is shown inside a viewer that cannot print.

## Reporting problems

On the hosted site, **Report a problem with this sheet** (below the print buttons) opens a short form. It records the standard, tier, set code and settings automatically, plus what is wrong, the problem number and details. Reports are collected by Netlify Forms. The form asks people not to include student information.

## Hosting

The site deploys as-is: on Netlify, import this repository with no build command and the repository root as the publish directory. Every push to `main` then updates the site.

To receive problem reports, turn on form detection in Netlify (**Site configuration → Forms → Enable form detection**), deploy again, and add an email notification under **Forms → Form notifications**.

## Notes

The layout follows the IM lesson structure (warm-up, practice, cool-down). Just Right Math is not affiliated with or endorsed by Illustrative Mathematics.
