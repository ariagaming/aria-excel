# Aria in Excel

Because of the delays in the real character sheet, we're moving to a temporary solution using Excel. I hope to change this soon 
to something more powerful and web-based.

## How to use this Document

You clone the repo, make a copy of the character sheet, create your character and commit the changes.

If you really want to keep things neat and clean, create a branch and do the same.

## For Kobayashi

Excel is a spreadsheet. This means that you can break everything by chaning or removing functions. For example:
when you have a function like:

```
=SUM([XP])
```

And this shows `0` and you think to yourself, well....I have 13 XP, let's just change that; you break the fucking sheet!
Don't do that! (Looking at you Ernie).

## Not of the named values

Almost everything important has been named in the workbook. This means that you can rip out the Character Sheet page
and write/design your own. If you look at the names defined in the sheet you might figure out what you have to play
around with.

Some things are double like `STAMINA` and `FEAT_STAMINA` this is because of a changing naming convention, a sucky design
and a fear of breaking things. This should be resolved but seeing how I'm rebuilding the original website this has a
very low priority.

