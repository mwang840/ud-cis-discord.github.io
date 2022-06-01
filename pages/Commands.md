---
waltz:
  title: Commands
  resource: page
  published: false
layout: page
title: Commands
permalink: pages/commands
---
Here is a list of all of the commands available for Sage, with the format `s;command [arguments]`.
<br>
Note, `[argument]` denotes an optional argument while `<argument>` denotes a required argument. Brackets should be omitted when running commands.
### General Commands

**assign**

- Description: Use this command to assign a role to yourself! 
Use the argument 'list' to see a list of all self-assignable roles.

- Usage: `s;assign [Role|list]`

- Aliases: `role`


**check**

- Description: Displays the users current message count. 
If the word 'here' is used as an argument, the message count will be 
sent in the same channel that the command was used in (rather than the user's dms).

- Usage: `s;check [here]`

- Aliases: `count`


**submit**

- Description: Submit a profile picture to the pfp contest.

- Usage: `s;submit [more information]`

- More info: Exactly one file must be attached when running this command.
### Configuration Commands

**enroll**

- Description: Enroll yourself in a course.

- Usage: `s;enroll <course>`

- Aliases: `unenroll`

- More info: If you use this command on a course you are already enrolled in, you will be unenrolled.
### Fun Commands

**8ball**

- Description: Ask the 8ball a question and you shall get an answer.

- Usage: `s;8ball [question]`

- More info: This command requires you to put a question mark at the end of your question.


**doubt**

- Description: Press x to doubt

- Usage: `s;doubt `

- Aliases: `x`

- More info: This command must be used by replying to a message.


**f**

- Description: Press F to pay respects

- Usage: `s;f `

- Aliases: `respect`


**poll**

- Description: Have Sage create a poll for you

- Usage: `s;poll <timespan>|<question>|<choices...>`

- Aliases: `vote`

- More info: You can have two to ten choices.


**rockpaperscissors**

- Description: The ultimate battle of human vs program. Can you best Sage in a round of rock paper scissors?

- Usage: `s;rockpaperscissors <rock|paper|scissors>`

- Aliases: `rps`


**xkcd**

- Description: Find a comic from xkcd.

- Usage: `s;xkcd [latest | comicNumber]`

- Aliases: `x`

- More info: If given no paramaters, sends a random comic. You can also specify a comic by its number or get the latest comic with `latest`.
### Info Commands

**discordstatus**

- Description: Check Discord's current status.

- Usage: `s;discordstatus `

- Aliases: `ds`
, `discstatus`
, `discordstats`


**feedback**

- Description: Provide feedback or bug reports about Sage.

- Usage: `s;feedback <suggestion>`

- Aliases: `suggest`


**help**

- Description: Provides info about all Sage commands

- Usage: `s;help [command]`

- Aliases: `commands`
, `man`
, `h`

- More info: If given no arguments, a list of all commands you have access to will be sent to your DMs


**info**

- Description: Provides information about Sage.

- Usage: `s;info `


**leaderboard**

- Description: Gives the top 10 users in the guild

- Usage: `s;leaderboard [page number]`

- Aliases: `rank`
, `leader`

- More info: Enter a page number to look further down the leaderboard


**ping**

- Description: Runs a connection test to Discord

- Usage: `s;ping `


**serverinfo**

- Description: Provides information about the UDCIS discord server.

- Usage: `s;serverinfo `

- Aliases: `serverstats`


**stats**

- Description: Displays info about Sage's current status

- Usage: `s;stats `
### Partial Visibality Question Commands

**anonymous**

- Description: Send an anonymous question in your classes general channel.

- Usage: `s;anonymous [course] <question>`

- Aliases: `anon`

- More info: Sage will automatically determine your course if you are only enrolled in one!


**private**

- Description: Send a question to all course staff privately.

- Usage: `s;private [course] <question>`

- More info: Sage will automatically determine your course if you are only enrolled in one!


**reply**

- Description: Reply to a question you previously asked with Sage.

- Usage: `s;reply <questionID> <response>`

More info related to the question tagging system can also be found on [this page](https://ud-cis-discord.github.io/pages/Question%20Tagging).
### Reminders Commands

**cancelreminder**

- Description: Cancel any pending reminders you may have.

- Usage: `s;cancelreminder <reminder number>`

- Aliases: `cr`
, `removereminder`

- More info: You can only cancel one reminder at a time


**remind**

- Description: Have Sage give you a reminder.

- Usage: `s;remind <reminder> | <duration> | [repeat]`

- More info: Reminders can be set to repeat daily or weekly.


**viewreminders**

- Description: See your upcoming reminders.

- Usage: `s;viewreminders `

- Aliases: `showremind`
, `showreminders`
, `sr`
, `viewremind`
, `vr`

- More info: Don't worry, private reminders will be hidden if you use this command publicly.
### Settings Commands

**togglelevelpings**

- Description: Toggles whether or not you will receive notifications from Sage on a level up.

- Usage: `s;togglelevelpings `

- Aliases: `levelpings`
, `lp`


**togglepii**

- Description: Toggles whether or not your personally identifiable information will be sent by instructors over Discord.

- Usage: `s;togglepii `

- Aliases: `pii`
### Staff Commands
All of the staff-only commands can be found on [this page](https://ud-cis-discord.github.io/staff_pages/staff%20commands).