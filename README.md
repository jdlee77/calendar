# Year Planner

A free, single-page year-at-a-glance calendar you can fill in, shade, and print at any size, from Letter paper to a 4 × 8 ft wall banner.

**Open it:** https://jdlee77.github.io/calendar/

No sign-up and no server. Everything you add stays in your own browser.

## What it does

- **Year at a glance.** All 12 months, with a box for every day. Event titles appear in the boxes. Use the arrows or the year menu to go to any year.
- **Day view.** Click any day for an hour-by-hour schedule. Add, edit, and delete events with a title, start and end times or all day, a type, and notes.
- **Event types.** Name your own types (Team meeting, Client meeting, Deadline, and so on) and pick a color for each. Optionally shade days on the year view by type. Days with several types split into bands.
- **Holidays you control.** Start from US federal, Oregon state, Canada, UK (England and Wales), or Australia holidays, or from an empty list. Turn any holiday on or off, edit it, or add your own. Rules include a fixed date, "3rd Monday of January", "Monday on or before May 24", Easter-based dates, and one-time closures. Choose how weekend holidays are observed. Set the holiday shade and its name in the key.
- **Printable, clickable PDFs:**
  - **Presets:** Wall calendar (one page), Full planner (year, 12 month pages, and a page for every day with an hourly schedule, top priorities, and notes), or Year + event days. You can also build your own mix and pick a month range.
  - **Paper sizes:** Letter, Legal, Tabloid, Super B, A4, A3, A3+, ANSI C/D/E, Arch C/D/E1/E, A2, A1, A0, 2A0, posters up to 48 × 96 in, or any custom size up to 200 in.
  - **Links:** day boxes jump to that day's page. Every page links back to the year, the month, and the next and previous day. A bookmark sidebar lists each month and day.
  - **Text that scales:** text grows with the print. The export panel shows how big the text will print and how far away it can be read.
  - **Options:** standard, narrow, or binder-edge margins, black and white, and four text sizes.
- **Outlook import and export:**
  - **Import:** read `.ics` calendar files or Outlook `.csv` exports. Repeating meetings are filled in, including weekly, nth weekday, last weekday of the month, and yearly patterns, with skipped and moved occurrences. Time zones are converted, and Outlook categories map to event types. You get a preview before importing, duplicates are skipped, and you can undo the last import.
  - **Export:** `.ics` for new Outlook, Outlook on the web, and Outlook for Windows or Mac, or Outlook's `.csv` layout for Outlook for Windows (classic). Event types become Outlook categories.
- **Light and dark mode**, and it works on phones.

## Your data

Events and settings are saved in your browser's local storage on the device you use. They aren't uploaded anywhere. Clearing your browser's site data erases them. To back up your calendar or move it to another device, use **Import & export → Export to Outlook**, then import that file on the other device.

## Run it yourself

It's one HTML file with no build step:

1. Download `index.html`.
2. Open it in a browser, or host it on any static web host.

It loads [jsPDF](https://github.com/parallax/jsPDF) from cdnjs for PDF export and the Inter and Archivo fonts from Google Fonts.

## Publish your own copy on GitHub Pages

1. Fork this repository.
2. In your fork, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Pick the `main` branch and the `/ (root)` folder, then save.
5. Your copy will be live at `https://<your-username>.github.io/calendar/` within a minute or two.

## License

[MIT](LICENSE). You can use, copy, change, and share this tool freely, including for commercial use, as long as you keep the copyright and license notice.
