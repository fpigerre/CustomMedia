CustomMedia
===========

A custom media centre that improves on other popular media centres.


How To
------

Init an xbmc module : `git submodule update --init`

Apply Patches : `./applyPatches.sh`

### Create patch for server ###

`cd CustomMedia\CustomMedia`

Add your file for commit : `git add <file>`

Commit : `git commit -m <msg>`

`cd ..`

Create Patch `./rebuildPatches.sh`




Compilation
-----------

'Make' is used to build CustomMedia.

* Install ['Make'](http://www.gnu.org/software/make/)
* Clone CustomMedia
* ```cd CustomMedia\CustomMedia```
* Build the project using ```make```