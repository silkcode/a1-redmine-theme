Redmine A1 theme
================

Redmine A1 theme. Fork from http://redminecrm.com/pages/a1-theme (v1.1.1) originally by Kirill Bezrukov @ RedmineCRM:
* Fix for issues coloring acc. to priority;
* Private issues made explicitly red bold;

For those suffered from the "issues coloring acc. to priority" broken in Redmine's Issues list as of Redmine version 2.3.1.stable, at least (but people do report similar issues for a long time already, like yet in Redmine 2.1.2 - http://www.redmine.org/boards/1/topics/28349?r=33781#message-33781).

The actual A1 theme is wonderful (thanks to Kirill), but seems like Redmine has changed their default enumerations (those seeded with the corresponding rake task from Redmine), specifially and at least - the actual "Issue priorities" enumeration (it's IDs have been changed), that is now looking like:
!["Issue priorities" enumeration](https://dl.dropboxusercontent.com/u/16588359/silkcode_a1-redmine-theme_fixed/issue_priorities.jpg)

So, this is how our fixed A1 theme colors the Issues listing on Redmine version 2.3.1.stable:
![our fixed A1 theme colors the Issues listing on Redmine version 2.3.1.stable](https://dl.dropboxusercontent.com/u/16588359/silkcode_a1-redmine-theme_fixed/coloring.jpg)

[03.06.2013] UPDATE:
* Private issues made explicitly red bold;
