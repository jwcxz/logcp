logcp - Bulk Copy with Manual Interface
=======================================

This script looks at some number of most-recently-modified files in a source
directory and copies them to a destination allowing the user to direct the
objects to manually-defined deestination directories as they pass through.

I find this useful for handling stuff like log files and backups.

Syntax: `logcp [num]` where `num` can optionally be how far back to go back in
the recent files to import.  At this point, an editor will open up with the
opportunity to say where the folder will go according to the screenshot below.

Configure the variables in `example.cfg` first and save that file as
`~/.logcp.cfg`.


![screenshot](https://raw.github.com/jwcxz/vim-logcp/master/logcpmap.png)
