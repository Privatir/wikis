# Work Logs

## Intention
A highly-detailed record isn't required. The goal isn't to create a time tracker, but to record the process that the product and the work followed across many weeks and months, and capturing the perspectives of the people on the team.

At a minimum, record decisions made, directions taken, plans made, plans changed or re-assessed, setbacks, work preempted or missed, problems faced, realizations had, learnings, conflicts, resolutions, and generally, notes of things you want to remember or remark upon.

If you want to record details, endeavor to write the high-level points first, and then provide details.

## Tags

Tags are optional. Use them to categorize log items.

When using tags on lines, prefix the lines with the tag. Tags are delimited with square braces.

Examples:
- [setback]
- [problem]
- [realization]
- [decision]
- [plan]
- [missed]
- [direction]
- [learning]
- [conflict]
- [resolution]
- amongst others

## Order
The newest entires go at the top of the file, sorted by date descending.

## Date Format
Start each entry with the date in the format: Thu Jan 10 2013.

## Commit Messages
Commit message text should be only the date of the entry that you're submitting. Use the same date format for commit messages that you use for headers in the log itself. For example: Thu Jan 10 2013. For multiple dates, include all dates on the same line, separated by commas. Start with the most recent date first. For example: Thu Jan 10 2013, Wed Jan 9 2013.

## Updates to Previous Commits
If you have to add something you've forgotten or change previous content, add the suffix "update" to the commit message. For example: Thu Jan 10 2013 update.

## No Merge Commits
Git will, by default, insert commits when you pull (or otherwise merge) from the remote (or from any other branch). Do not add merge commits to the work log repository. To learn how to avoid merge commits, please refer to the following article: http://kernowsoul.com/blog/2012/06/20/4-ways-to-avoid-merge-commits-in-git. If you have any concerns about how to do this or if you unsure of your grasp of the subject, please ask someone on the team for help before proceeding.

## Visibility to Entire Team
Write to be read. These documents are visible to the entire team. Others on the team can benefit from reading each other's notes. You are not your only audience. Write to enable others with the awareness that you have gained in your work.

## Professional Voicing
Your audience is larger than just developers. Use precision. Don't cop out to jargon. Don't use developer slang.

## Markup Language
Use the Markdown language to write your log. More on markdown at: http://en.wikipedia.org/wiki/Markdown.