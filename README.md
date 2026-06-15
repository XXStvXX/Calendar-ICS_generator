# UTSC Summer Course Calendar ICS Generator

A lightweight, browser-based tool for building a complete UTSC Summer 2026 course calendar and downloading it as an `.ics` file. Everything runs locally in the browser; no account, backend, or data upload is required.

## Live Demo

https://xxstvxx.github.io/Calendar-ICS_generator/

## Highlights

- Build one calendar per course to avoid mixing course codes.
- Add assignments, projects, presentations, exams, tutorials, and other course items.
- Include grade weight, notes, room/location, and useful links in event descriptions.
- Create all-day or timed events.
- Paste flexible date formats, including newline-separated, comma-separated, or glued dates.
- Generate recurring weekdays within UTSC Summer 2026 first, second, or full sessions.
- Review Summer 2026 academic dates directly in the app.
- Download a standards-compatible `.ics` calendar instantly.

## Usage

1. Review the Summer 2026 academic dates shown in the app.
2. Enter and lock the course name, course code, and session.
3. Add an item name and any optional details.
4. Choose all-day or timed event settings.
5. Paste dates or select recurring weekdays for the chosen session.
6. Add the item to the course calendar and repeat as needed.
7. Download the completed `.ics` file and import it into your calendar app.

## Supported Paste Formats

Examples:

```text
2026-05-12
2026/05/12
20260512
12 May 2026
May 12 2026
2026-05-122026-05-19
```

The parser supports common separators and configurable YMD, DMY, or MDY ordering.

## Academic Session Codes

- `fss`: first sub-session
- `sss`: second sub-session
- `fs`: full session
- `rw`: reading week
- `fss_fp`, `sss_fp`, `fs_fp`: final periods

Recurring weekday generation is scoped to the UTSC Summer 2026 `fss`, `sss`, and `fs` sessions.

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- GitHub Pages

## Privacy

No calendar data is stored or sent anywhere. All processing and file generation happen locally in the browser.

## License

MIT License. See [LICENSE](LICENSE).
