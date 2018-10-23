LogiQX Dat File Tools
=====================

Original site: http://www.logiqx.com

Updated by Barry Harris (http://www.barryharris.me.uk) on 22 February 2012


This archive contains modified source and recompiled binaries of the very useful dat file tools
written by logiqx.

These tools are assumed dormant, since the author's site hasn't been updated since 2010.

In MAME 0.145u1 the listxml format changed slightly, causing the tools to no longer work. The 
issue is that now all sets using external samples, set the sampleof flag, including the "parent 
sample" set, which is different behaviour than previous versions and the datlib (which all the 
tools are based on) couldn't handle the change.

I use MAMEDiff myself to sync the FB Alpha sets to the latest MAME release and since logiqx
released the source I decided to investigate the issue. Having identified and fixed the issue,
I decided to repackage the tools and release for others to use if they wish. My changes are small
and I take no credit for these excellent tools whatsoever, all credit stays with logiqx for these.

This repackaged archive contains the complete source, including a fix for the above described,
issue, and recompiled windows binaries for all the tools.

As well as fixing the above issue this repackage has the benefit of being compiled against a newer
zlib (1.2.6, which is current at the time of update). The tools are no longer packed with UPX, and
I have updated the dates and appended "bh" to the versions to identify these versions. I didn't
increment the version numbers, as these are not my tools.