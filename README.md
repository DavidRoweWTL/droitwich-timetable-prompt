[README.md](https://github.com/user-attachments/files/33006050/README.md)
# Droitwich main-pool timetable prompt

A reusable brief for asking [Grok](https://grok.x.ai) to turn the Droitwich Spa Leisure Centre swimming timetable into one page per week.

The leisure-centre site shows one day at a time. This prompt tells Grok to read the main pool, keep only the sessions a casual swimmer can turn up for, and lay seven days across one aligned clock.

It does not contain timetable data. Each run reads the live page, so the files can change when the centre changes the programme.

## What you get

Two files per week, Sunday to Saturday:

- a one-page A4 landscape PDF
- the same grid as HTML

Only these main-pool sessions are drawn:

- General swim, including 3 lanes, with lanes, and half pool
- Lane swim / lane swimming, including 6 lanes
- Adult saver
- Family swim

Splash hour, lessons, school swimming, club, H2O, pilates, lifesaving and closed periods are left blank. A session is still shown if it shares the pool with something else, with a short note in the block.

## Use it

1. Open [Grok](https://grok.x.ai).
2. Paste the whole of [PROMPT.md](PROMPT.md).
3. Replace the two week ranges at the bottom with the Sundays and Saturdays you want.
4. Download the PDF and HTML it returns.

Example file name: `droitwich-main-pool-public-1-7-Nov-2026.pdf`

## Adapt it

The source URL is the Active In Time embed for Droitwich Spa Leisure Centre, timetable `18424`. To point it at another centre, replace that URL and the pool name in `PROMPT.md`. Session names differ between centres, so change the keep-list to match what that timetable actually calls a public swim.

## Credit

The prompt was written with Grok, built by xAI, to direct Grok. Grok does the reading and the page layout on each run. The timetable itself belongs to the leisure centre and is published through Active In Time.

## License

The prompt text in this repository is MIT licensed. See [LICENSE](LICENSE). That license does not cover timetable data, the Active In Time site, or files generated from them.

## Example

[example/droitwich-main-pool-public-4-10-Oct-2026.html](examples/droitwich-main-pool-public-4-10-Oct-2026.html) is one page made from the prompt for Sunday 4 October to Saturday 10 October 2026. It is a snapshot, not a live timetable. Download it and open it in a browser. GitHub will show the source, not the grid.
