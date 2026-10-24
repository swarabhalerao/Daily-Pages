# Daily Pages

A  personal site to help with maintaining daily write-up during your daily writing commitment: one post a day, with the streak to keep you honest.

## What it does

- **Upload a post** for any date by pasting text or choosing a `.txt` / `.docx` file. A popup confirms before saving.
- **Home** shows every post as a tile, newest first, grouped by month and year.
- **Streak** shows the current streak, the longest streak and a calendar of posting days.
- **Edit or delete** any post from its page.
- **Backup** downloads all posts as one file and restores them from one.

## Where the posts live
This is currently only a static site, with data (the posts) stored only in the browser, which makes backups essential.

- Another browser, device or private window starts empty.
- Changing the site's address also starts empty.
- Clearing browser data erases the posts.

**Download a backup every week or two** from the Backup page.

## Run it

It is one file, `index.html`, with no build step. Open it in a browser.

## Notes

- Only text is imported from `.docx` files.
- Future dates are blocked.
- A date can have several posts, and several posts on one date count as one streak day.
- Built with plain HTML, CSS and JavaScript. It uses mammoth.js (for `.docx`) and Google Fonts, both loaded from the web.
