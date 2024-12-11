MSP Test
======

This is a test repository I'm using to try and debug why buildbot is not picking up on release tags. 

If you have stumbled across this, it's basically the source code to [bstone](https://github.com/bibendovsky/bstone) because I know that builds properly. The only changes I'll be making are to this readme and to make tag versions. 

### Commit #1

Initial commit to get things rolling. No tags yet. 

### Commit #2 (TAG: v1.0 VERSION: 1.0)

The buildbot thing I'm trying to do fails if there's no tags so I'm going to call this one 1.0 with a tag of v1.0

### Commit #3

New commit with no tag, seeing what buildbot picks up. 

### Commit #4 (TAG: v1.1 VERSION: 1.1)

Commmit #3 did not trigger a build so I'm tagging this one with 1.1 to see if it gets picked up. 

### Commit #4 (TAG: v1.2 VERSION: 1.2)

Commmit #4 did get commits 3 and 4 picked up as changes (which commit 3 did not do by itself) but did not trigger a build. I've tweaked the change filter for the single branch scheduler so I'm seeing if this being tagged as 1.2 changes anything with that tweak. 