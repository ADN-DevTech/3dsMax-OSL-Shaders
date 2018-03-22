# 3dsMax-OSL-Shaders

This is the repo to hold shared OSL shaders for 3ds Max 2019 and beyond. 
Note that 3ds Max 2019 is the first version to support this standard.

All shaders in this repository are under the Apache 2.0 License - see [LICENSE.txt](LICENSE.txt)

For developer documentation, read [The OSL Map and You.pdf](The%20OSL%20Map%20and%20You%20V1.pdf), 
and for more user-facing information - as well as documentation for the 101 shaders shipping with 
3ds Max - read [OSL shaders in 3ds Max 2019.pdf](OSL%20shaders%20in%203ds%20Max%202019.pdf).

## Layout of the repository

### 3ds Max Shipping

The shaders shipping with the current version of max, and updates to them. 
The intent of this folder is that it should be safe to replace your 3dsmax\OSL 
folder with the content from here. It should only contain safe (compatible)
updates to the shaders shipping together with max.

### Non-shipping shaders

Non-shipping are under the OSL directory, with a few sub-folders. They are all
under a main "OSL" folder. This allows you to add the folder checked out from
GitHub as a plugin folder.

Go to *Customize* -> *Configure System Paths* -> *3rd Party Plug-Ins* and add 
the checked out folder as a plugin path. 3ds Max will find the "OSL" subdirectory
and automatically load everything in it at startup, and populate the material 
browser.

#### OSL\ADN-Experimental

Contains shaders in flux and in development that may change completely tomorrow. 
Use these with caution, and its probably safest to use them in unlinked mode, because
if you download a new version in the future, the behavior may have changed enough such
that your old scenes no longer work.

#### OSL\ADN-Stable

These are shaders that are mature enough and stable enough that the intent is that
the shaders interface and behaviour won't substantially change in the future. It may
gain parameters, but defaults should be compatible with the previous version. These 
shaders are candidates to be included in the shipping set in the next version.

#### OSL\ADN-User Submitted

These are shaders submitted by users. 

If you want to contribute, read the [how to submit](HOW-TO-SUBMIT.md) documentation for details.
