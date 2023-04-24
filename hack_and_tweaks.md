# Hacks and Tweaks
- [Hacks and Tweaks](#hacks-and-tweaks)
  - [Git](#git)
  - [Ilias](#ilias)
  - [TMS](#tms)
  - [Bash](#bash)
  - [MySql](#mysql)
  - [PHP](#php)
  - [Salt](#salt)


## Git

Cleans all untracked files. Dryrun with -n
```bash
git clean -d -f
```

Show all stashed files
```bash
git stash list
```

Clears the stash
```bash
git stash clear
```

## Ilias

## TMS

## Bash

## MySql

## PHP

## Salt

Refresh pillar data for a minion
```bash
salt '*' saltutil.refresh_pillar
```
