# Hacks and Tweaks

## Table of Contents
1. [Git](#git)
2. [Ilias](#ilias)
3. [TMS](#tms)
4. [Bash](#bash)
5. [MySql](#mysql)
6. [PHP](#php)
7. [Salt](#salt)

## Git <a header="git"></a>

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

## Ilias <a header="ilias"></a>

## TMS <a header="tms"></a>

## Bash <a header="bash"></a>

## MySql <a header="mysql"></a>

## PHP <a header="php"></a>

## Salt <a header="salt"></a>

Refresh pillar data for a minion
```bash
salt '*' saltutil.refresh_pillar
```
