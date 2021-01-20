# makigai 🐚 
A minimalist anki alternative written in POSIX shell. No dependencies (besides GNU core utils+bc or macOS builtin utils), no database, no media, only front/back cards supported. Uses a tab-separated file as its "database." This tsv file is intended to be tracked in git for syncing and keeping track of history. Currently using the SuperMemo-2 algorithm. Designed to be portable and run on any POSIX compliant shell with echo, date, awk, shuf, and read installed.

## Features
* Select between multiple decks
* Filter review queue by tag
* Total recall mode (ignore due dates and consider all cards)
* No reschedule mode (don't update db with new due date)
* Both import and review functionality can read from stdin (useful when using in scripts)

## Planned features
* Review ahead by *n* days
* Better stats/reports
