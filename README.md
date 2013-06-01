Redmine A1 theme
================

Redmine A1 theme. Fork from http://redminecrm.com/pages/a1-theme (v1.1.1) originally by Kirill Bezrukov @ RedmineCRM. Fix for issues coloring acc. to priority.

For those suffered from the "issues coloring acc. to priority" broken in Redmine's Issues list as of Redmine version 2.3.1.stable, at least (but people do report similar issues for a long time already, like yet in Redmine 2.1.2 - http://www.redmine.org/boards/1/topics/28349?r=33781#message-33781).

The actual A1 theme is wonderful (thanks to Kirill), but seems like Redmine has changed their default enumerations (those seeded with the corresponding rake task from Redmine), specifially and at least - the actual "Issue priorities" enumeration (it's IDs have been changed), that is now looking like:
!["Issue priorities" enumeration](https://www.evernote.com/shard/s208/sh/3528c973-9ec6-4eef-83ce-c24a4a334257/1793e56c6d33bf6df008a1e2a600a99f/res/25b4de28-1c3c-4f40-841f-8fb37450a651/skitch.jpg)

So, this is how our fixed A1 theme colors the Issues listing on Redmine version 2.3.1.stable:
![our fixed A1 theme colors the Issues listing on Redmine version 2.3.1.stable](https://www.evernote.com/shard/s208/sh/103cf119-831e-46c7-9d1c-0b6f4f426fa9/cdac76a234e870f8417130eb36f4d543/res/39895e2c-89d3-4b58-8696-5c0a26c7e0f2/skitch.jpg)
