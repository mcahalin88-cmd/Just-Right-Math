# Just Right Math

A worksheet generator for differentiated independent practice. Pick a standard and it builds three versions of the same worksheet:

- **Support (●)**: friendlier numbers, visual models, a hint on each problem, a worked example and larger print
- **On Level (▲)**: grade-level practice of the standard
- **Stretch (■)**: multi-step problems, missing values and a closing reasoning task
  - Grade 6 Stretch sheets have six problems, each asking for a different kind of thinking: three harder applications, then **Find the mistake** (spot and fix a student's error), **Work backward** (start from the answer) and **Many answers** (more than one correct answer). Each of the last three is labeled on the sheet.
  - On every grade, a Stretch sheet uses the same story type at most twice. It ends when it runs out of new story types, with at least 6 problems.

- **Unit review**: check 2 to 4 standards from the same unit to get one sheet that covers all of them. Support groups the problems under a heading for each standard. On Level and Stretch mix them together (turn off *Mix On Level and Stretch problems* to keep them grouped). Stretch adds a Find the mistake problem and one challenge. The answer key shows which standard each answer comes from.

## What it covers

- **Standards:** New York Next Generation Mathematics Learning Standards (default) or Common Core
- **Grades 1–8:** full coverage of the New York standards, grouped by IM unit (about 160 standards in all)
  - New York–only standards include coins in grade 1 (NY-1.MD.3b), four-digit place value in grade 3 (NY-3.NBT.4), perfect squares and cubes and probability in grade 6, and box plots in grade 7
  - Standards that New York removed or moved are shown only when Common Core is selected
- **Curriculum style:** Illustrative Mathematics–style wording, names and representations, or neutral wording

## Other features

- Answer keys
- Discreet tier labels (● ▲ ■) so students can't tell which version they have
- Set codes: the same code always rebuilds the same problems
- A side-by-side view of all three versions
- No student data is collected or stored

## Using it

Open `index.html` in a web browser. It is a single file with no build step; fonts load from Google Fonts.

## Extras

Three switches in the sidebar let each teacher choose what goes on the sheet:

- **Guided example (Support)**, on by default: a box at the top of every Support sheet. *Watch me* works one problem step by step; *Your turn* gives a matching problem with the first step done and blank lines for the rest.
- **Key words**, off by default (grade 6 so far). Choosing Spanish or Arabic turns it on.
- **Cool-down**, off by default: one problem at the end that is the same on all three versions, useful as an exit ticket.

## Supports for English learners (grade 6)

Every grade 6 sheet includes:

- **Key words:** a compact list of 4–5 words for the standard. The **Word list language** menu adds the Spanish or Arabic word next to each one; English only is the default. The Support version also shows a short example for each word.
- **Sentence starters (Support only):** one line under the key words, shown when the sheet has questions that ask students to explain.
- **Easier-to-read stories (Support only):** one sentence per line, with the question in bold.

Choose a language, print, then switch languages and print again. The problems and answer key stay the same, and each sheet's footer shows its language. Translations should be checked by a bilingual colleague before use.

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
