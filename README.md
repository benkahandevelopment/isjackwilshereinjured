# is.jackwilshereinjured.com

So after a discussion with a colleague, we decided the best way to ascertain exactly whether or not Jack Wilshere was, at any moment in time, ruled to the sidelines with injury was to create a website with a sole purpose of distributing said information.

Hence, <a href="https://is.jackwilshereinjured.com/" target="_blank">`is.jackwilshereinjured.com`</a> was born.

## credits

<a href="http://stackoverflow.com/users/1241793/ben-pearl-kahan">
<img src="http://stackoverflow.com/users/flair/1241793.png" width="208" height="58" alt="profile for Ben Pearl Kahan at Stack Overflow, Q&amp;A for professional and enthusiast programmers" title="profile for Ben Pearl Kahan at Stack Overflow, Q&amp;A for professional and enthusiast programmers">
</a>

<i>Built with love by Ben Kahan - <a href="https://www.bkdev.co.uk/">BKDev</a></i>

## versions

### v1.2

* Modified `fork` GitHub button to no longer show count because nobody forks me :(
* Added "Super Users"
 * Entirely for development purposes
 * Added PHP array of whitelisted IPs in the Globals section
 * Added pleasant but commented-out message for Super Users in `<head>`
 * Show debug information by default for these users

### v1.1

* Removed ShareThis.com bullshit buttons
* Added Facebook/Twitter native share/tweet buttons
* Moved deferred JS to end of `<body>` tag

### v1.0

Features include:

* Self-made API (read: cURL request) once a day to `physioroom.com` to check whether Wilshere is on "the list" and to parse the data to find out how long he's staying there
* NoDB system (read: a `.txt` file with today's date) created to prevent multiple cURL requests per day
* Full design and implementation, including:
 * Finding <i>just the right</i> image of Wilshere in agony, optimising it and crediting
 * Adding share buttons to the footer
 * Editing lovely `.svg` curly things above and below the header
 * Colours
* Sharing meta for Twitter, Facebook etc.

## other people's stuff used

* <a href="https://jquery.com/">`jQuery`</a>
