# notes

Keep notes throughout the date of things you want to talk about at standup

## Scripts

### `./log-note {MESSAGE}`

Log a note. Will be stored in `.notes` directory, in a file with todays date in 'YYYY-mm-dd' format.

### `./open-notes [FROM_DATE] [TO_DATE]`

Open notes in `vim` in a given date range. If no arguments given defaults to yesterday to today.

Eg.

`./open-notes 2019-09-26 2019-09-28`

Will open notes files for 26, 27, and 28
