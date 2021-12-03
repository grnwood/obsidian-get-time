## Joes GetTime Plugin

This is a sample plugin for Obsidian (https://obsidian.md).

I needed to recreate my system for tracking buckets of time on any daily note page.  The Tracker plugin and other advanced solutions were just too much.

I would keep my buckets ongoing, say on a daily note, throughout the day.  Often I'd like to see where I am at with my day by summary.

The format is really simple, a one liner:

bucket,description,minutes

I would then select over the lines and Ctrl/CMD-P: Get time (or map to hotkey):

```
kjus,tickets and qa of jobs,75
doonta,daily standup,30
cushe,redesign estiamtes,45
cushs,support scrum,30
doonta,functional qqs,30
doonta,chat with matt on address,15
doonta,powerreviewqs meeting,45
doonta,powerreviews tsd and tickets,60
kjus,dev status meeting,30
cushs,ug pdp pages blank tshooting,60
int,email and timesheets,60
```
Will then summarize each unique bucket and spit back out the original input plus the summarization:

```
8 hours (480 minutes), buckets:
   | kjus	1.75
   | doonta	3
   | cushe	0.75
   | cushs	1.5
   | int	1
```

