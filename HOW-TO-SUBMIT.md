# How to submit OSL shaders to this repository

If you want to contribute to this repository, you are very welcome to do so! 

Please only upload shaders you've written yourself or that is based on code that itself
has a sufficiently permissive license. 

We require all files in this repository to be licensed under the Apache 2.0 license, which is
a very permissive open-source license. You keep the copyright to your original files, but give
a license to anyone to use them for any reason, including use in a commercial product (in case we
like your shader so much we want to put it into a future 3ds Max version.)

## What you need to do:

### Add a license header to your file

If not there, add to the header of your file that it is under the Apache 2.0 license by adding 
this line or something equivalent:

	// License: Apache 2.0 License
	//   https://github.com/ADN-DevTech/3dsMax-OSL-Shaders/blob/master/LICENSE.txt

### To submit your own work to this repository

First, each person wanting to contribute to this repo must you first sign a Contributor Licence Agreement,
scan it and email to us. This is a one-time thing per person, and exists for both your and our protection.

* For individuals: [3dsMax OSL Shaders - Ind Contrib Agmt.pdf](https://github.com/ADN-DevTech/3dsMax-OSL-Shaders/raw/master/3dsMax%20OSL%20Shaders%20-%20Ind%20Contrib%20Agmt.pdf)
* For corporations: [3dsMax OSL Shaders - Corp Contrib Agmt.pdf](https://github.com/ADN-DevTech/3dsMax-OSL-Shaders/raw/master/3dsMax%20OSL%20Shaders%20-%20Corp%20Contrib%20Agmt.pdf)

Once that is done, simply follow a standard GitHub workflow: 

* Fork the repository on GitHub
* Clone your fork to your local computer
* Work in your local repo in the "OSL\ADN-User Submitted" folder
* Put all your files in a subdirectory to this directory that has your name/nickname or company name. 
* Push changes to a branch on your forked repository
* Rinse, repeat and iterate until you are happy and feel ready to contribute
* Submit a pull request from the branch on your repository to the 3dsMAX-OSL-Shaders repository
* ADN-DevTech will check out your submission and merge it into this repository
* For questions, email 3dsMaxOSLShaders@Autodesk.com

### Best Practices

We suggest that if your shader may need documentation or a "demo", to add files with the same basic filename as your shader that describes it. For example something like this:

	WooHoo.osl          The shader itself
	WooHoo.jpg          Example rendering, or screenshot containing example rendering and setup
	WooHoo_Setup.jpg    Screenshot from SME showing an intended use case 

One could also consider having PDF or TXT files with written documentation, and if necessary, a scene. However the ideal is that the shader is self-documenting enough with metadata and tooltips so this won't be necessary. But an example image showing what the shader does is always welcome!


	
