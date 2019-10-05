# notes

Keep notes throughout the date of things you want to talk about at standup

## Scripts

### `./scripts/log-note {MESSAGE}`

Log a note. Will be stored in `.notes` directory, in a file with todays date in 'YYYY-mm-dd' format.

### `./scripts/open-notes [FROM_DATE] [TO_DATE]`

Open notes in `vim` in a given date range. If no arguments given defaults to yesterday to today.

Eg.

`./scripts/open-notes 2019-09-26 2019-09-28`

Will open notes files for 26, 27, and 28

## Installing

1. Clone this repository somewhere

`git clone https://github.com/awocallaghan/notes.git`

2. Set up aliases:

```
alias log-note=/path/to/notes/scripts/log-note
alias open-notes=/path/to/notes/scripts/open-notes
```

Replace `/path/to/notes/` to where ever you checked out the repo

3. Run the 2 scripts using your aliases to log notes and open them
