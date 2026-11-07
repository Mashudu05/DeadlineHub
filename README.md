# DeadlineHub

A shared assignment deadline tracker for students. Built as the prototype for the **Human Computer Interaction (HCIN6222)** Portfolio of Evidence.

## What it is

DeadlineHub lets a student record every assignment deadline once, see what is due next, and (optionally) compare deadlines with classmates in the same module.

## How to run it

1. Download or clone this repository.
2. Open `index.html` in a modern browser (Chrome, Edge or Firefox). No installation or server is needed.
3. On the sign-in screen, enter any student number with 8 to 10 digits (for example `12345678`) and a display name, then click **Sign in**.

The prototype uses sample data held in memory, so any changes reset when the page is refreshed.

## What you can try

- **Dashboard:** deadlines sorted by urgency, with a countdown, an icon and a text label on each one
- **Add / edit deadline:** one short form with a date picker and validation
- **Delete:** needs a confirmation step
- **Mark as done:** tick the "Done" checkbox, and the item moves to History
- **Stressful states:** an overdue deadline with a hint, and a "Busy week" note when 3 or more deadlines are near
- **Filter chips and List / Calendar toggle**
- **Class board:** opt in per module, comments, and "This was helpful" reactions (display name only)
- **History:** everything you have completed
- **Keyboard use:** Tab through every control, with a visible focus outline and a "Skip to main content" link

## Design focus

The prototype demonstrates usability goals, desirable user experience aspects, design principles, interaction types, social interaction, emotional interaction and WCAG 2.0. The full explanation, with screenshots, is in the research report.

## Files

| File | Description |
| --- | --- |
| `index.html` | The prototype (HTML, CSS and JavaScript in a single file) |
| `HCIN6222_Final_POE_DeadlineHub_Report.docx` | Updated research report with screenshots |
| `README.md` | This file |

## Technology

HTML, CSS and plain JavaScript. The Atkinson Hyperlegible typeface loads from Google Fonts. If you are offline, the browser uses a standard sans-serif font instead.

## Limitations

- No server, database or real sign-in; the data is sample data only
- Drag-and-drop reordering was planned in Part 1 but is not included
- No comment moderation tools
- No formal accessibility audit or screen reader testing yet
