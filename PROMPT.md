[PROMPT.md](https://github.com/user-attachments/files/33006385/PROMPT.md)
# Droitwich main-pool public timetable — repeat brief

Paste this whole file to Grok. Fill in the two week ranges at the bottom before you send it.

## Task
Rebuild the Droitwich Spa Leisure Centre main-pool timetable as two one-page files. Days go across the columns. Time runs down the page on one shared clock, 06:00–22:00 in 30-minute rows, so sessions line up across the week.

## Source
Open each date on:

https://www.activeintime.com/en-gb/embeddable_timetable/18424?size=small&width=300&height=1000&selected_date=YYYY-MM-DD

Read the visible session rows. Use only Main Pool (25.0m). Ignore Small Pool.

## Keep only these sessions
- General swim, including "3 lanes", "with lanes" and "half pool only"
- Lane swim / lane swimming, including "6 lanes"
- Adult saver
- Family swim

Keep them even when they overlap another session. Do not draw the other session. Note a share in the block if the source says so, for example lane swim beside junior lessons, or general swim on half the pool beside swimming club.

Drop splash hour, lessons, school swimming, swimming club, H2O, pilates, lifesaving, closed, and anything else.

## Layout
- Sunday to Saturday
- One week per file
- Colour: lane #1d4e89, general #0f766e, adult saver #6d28d9, family #157a45
- Short labels: Lane swim, General, Adult saver, Family, plus a detail such as "6 lanes", "3 lanes", "with lanes", "half pool"
- Header: "Droitwich Spa — Main Pool, public sessions"
- Subline: these four types only; other sessions left blank, including overlaps
- Footer: date range, source, and any overlap notes
- Fit each week on one A4 landscape page
- Also make the matching HTML

## File names
Include the date range:

- droitwich-main-pool-public-D-D-Mon-YYYY.pdf
- droitwich-main-pool-public-D-D-Mon-YYYY.html

Example: droitwich-main-pool-public-1-7-Nov-2026.pdf

## Dates for this run
Week 1, Sunday to Saturday: [START] to [END]
Week 2, the following Sunday to Saturday: [START] to [END]
