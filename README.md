# 3dsMax-OSL-Shaders

This will be the repo to hold shared OSL shaders for 3ds Max. Note that 3ds Max neptune (currently in beta only) is the only version to support this standard.

## Layout of the repository

### 3ds Max Shipping

The shaders shipping with the current version of max, and updates to them. 
The intent of this folder is that it should be safe to replace your 3dsmax\OSL 
folder with the content from here. It should only contain safe (compatible)
updates to the shaders shipping together with max.

Non-shipping are under the OSL directory, with a few main subfolders:

### OSL\ADN-Experimental

Contains shaders in flux and in development that may change completely tomorrow. 
Use these with caution, and its probably safest to use them in unlinked mode, because
if you download a new version in the future, the behavior may have changed enough such
that your old scenes no longer work.

### OSL\ADN-Stable

These are shaders that are mature anough and stable enough that the intent is that
the shaders interface and behaviour won't substantially change in the future. It may
gain parameters, but defaults should be compatible with the previous version. These 
shaders are candidates to be included in the shipping set in the next version.

### OSL\ADN-User Submitted

These are shaders submitted by users. Please only upload shaders you've written yourself
or where you can be certain the license is explicitly permissive. This is a sharing site
and OSL files will be flying left and right.

Each user builds their own subdirectory under this to place their shaders. Some may later
be promoted to other folders.


## To submit your own work to this repository

Standard GitHub workflow: 

* Fork the repository on GitHub
* Clone your fork to your local computer
* Work in your local repo in the "OSL\User Submitted" folder, and push changes to a branch on your forked repository
* When ready, submit a pull request
* ADN-DevTech will check out your submission and merge it into this repository