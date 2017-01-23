# Rough Edges
## of open source

^
Speaker notes look like this. [Rendered PDF of talk](rough-edges.pdf).
I used DeckSet to present. I wish I could export to html.

---

You know

---

You got to

---

![fit](sandpaper-buying-guide-hero.jpg)

---

# I'm Francis
# 🚀

![](francis nuka cola.jpg)

---

# I'm Francis
# @reconbot

![](francis nuka cola.jpg)

---

I've been programming for at least 11 or 12

---

weeks

---

I compulsively patch projects I use

![inline](commit-history.png)

^
graph made with Isometric Contributions
https://chrome.google.com/webstore/detail/isometric-contributions/mjoedlfflcchnleknnceiplgaeoegien

---

## I Think it Makes life better

---

![fit](firstpr.png)

^
So how did I start?
Just learned about XSS

---

![fit](first pr github.png)

---

![fit](first pr nomerge.png)

---

Not even merged

---

- Best feeling in the world
- You always know something someone else doesn't
- Fixing your bugs for other people is great

---

![fit](all issues.png)

---

![fit](all commits.png)

---

![autoplay loop](shocked.mp4)


---

# How did this start?

---

![fit](button.gif)

---

![fit](first issue.png)

^debounce was unhelpful not like EE

---

![fit](first rejection.png)


^
submitted a failing test showing what I meant
Described electrical debouncing
wrote my own and walked away

---

6 months, 16 comments, 3 issues and 2 prs

---

![fit](solved.png)

---

- Somethings will be hard and you wont know why
- You get a lot done when you don't care who gets credit
- Build it yourself with failing tests or small examples

---

## node serialport
## (part 1)
![fit](RS-232_full_serial_port.png)

---

![fit](serialport-unit-tests.png)

^ it kept breaking johnny-five and I wanted it to stop
"Cant test this because it's hardware."

---

- followed up with dozens of small tests
- fixed bugs I found while trying to test
- given commit access(!)

^ too afraid to merge anything though

---

![fit](docs-bugs.png)

^ first merge of my own work

---

documentation bug reports help a lot

---

Getting eyes on your work isn't showing off

---

## NPM

^ When does `install` get called? What are the default values? Hidden behavior!? what?

---
![inline fit](npm-docs-1.png)
### https://github.com/npm/npm/blob/master/CHANGELOG.md
![inline fit](npm-docs-2.png)

^ encourages you to read the source
talk to maintainers

---

- Read the source for reality
- Tests help define behavior as much as find bugs
- Docs always drift

^ Always read the source

---

![](always-read-the-source.jpg)


---

# File Bug Reports

---

![75%](file bug reports.png)

---

## New Tools

![](terraform.png)

---

![fit](Confused Cat - Imgur.gif)

^
wanted a docker cloud thing to host some community sites I like, docs are inconsistent and wrong a few places. I didn't write it down and I all I can say is read the source if you get lost and immediately open an issue.

---

# New Job

![fit](bustle.png)

---

![fit](shep issues.png)

opened 8 of the last 10 issues on shep

^ 7 but I convinced someone else to open the 8th
^ half are pull requests

---

You only get beginners eyes once

---

Always file bug reports

---

![fit](slack-header.jpg)


# New project

^ http://1amstudios.com/2016/11/27/c64-slack-client/ runs slack and serialport!

---

## node serialport
## (part 2)
![fit](RS-232_full_serial_port.png)

^
serialport was crashing on me so I went to see if I could fix it
open issues unanswered for 10 months
I'm now the maintainer so watch out

---

![fit](serialport-pulse.png)

---

## oldest open issue
![fit](oldest open issue.png)

^ jquery.transit animation library
https://github.com/rstacruz/jquery.transit/issues/40

---

## oldest open issue

![fit](firmata-issue-1.png)

^
I made a midi parser to better understand firmata and found a bug
crashes web midi and a few other things
https://github.com/firmata/protocol/issues/1

---

- Ask questions (Respectfully)
- Help others with what you know and do triage
- If you're confused then so are others

---

# Work on tools you use

^
Shep isn't the most polished tool for lambda but it will be the best tool if you have similar needs to bustle

---

# Things I Want in Shep

- Custom builders `code => zip`

- Deterministic deploy artifacts `sha => deploy`

- Centralized Configuration for Lambda (not `shep`?)

---

# Nice first contributions

- Run Linters
- Delete stuff that's weird
- Ask questions

^
All this stuff makes for a more approachable and maintainable project

---

#Why?

^ asking you to do stuff for no reason is crazy

---

It's personal

^
I can only tell you why I do it
It teaches me new things
I get to learn about new problems
It's changed my carer
It gives me chance to work with people around the world
It's why I'm here today

---

# Projects that would love to see you

- Node-Serialport (talking to hardware of all kinds)
- Johnny-Five (JQuery for robots)
- PouchDB (JS document database)
- Shep (Manage your __lamb__da functions)

---

### http://yourfirstpr.github.io/

---

![](reconbot-2015.png)

I am Francis
@reconbot
@bustlelabs

https://github.com/reconbot/rough-edges
