mono 3.12.0
mod_mono 2.10.2

Getting Started with OpenShift and Mono
=========
---

####You will need:
  - [MonoDevelop 4][1]
  - [GIT][2]
  - [OpenShift account][3]

####Geting Started:
Sign into your OpenShift account and click the Create Application tab.
You then want to scroll to the VERY bottom and look for the text box that says: "URL to a cartridge defination"
Paste https://raw.github.com/samasama/openshift_mono_cart/master/metadata/manifest.yml into the text box and click "Next"
Give a name to your application, we will be using "mono" as the name through out rest of this.
Once you have chosen a name click "Create Application" at the bottom.

After it has finished he creation process go ahead and start up MonoDevelop.

Insite MonoDevelop click on the menu item labeled "Version Control" then click on "Checkout"
Under the "Type" drop down box choose "Git".

Paste your git url you got at the end of the application creation wizard into the Url:// text box. 
Chose a directory that does not exist for the "Target directory". Click on "OK". If you have git properly set up and your ssh key added to your OpenShift account you should see "Solution checked out".

Once that has finished click on "File" then "Open". Navigate to where you checked out your code and open OpenShift.csproj(Feel free to rename this.)

You should now be able to press F8 (Windows/Linux) or CMD+B (OS X) to build the solution. Congratulations you are now ready to create your website! 

To push your changes up to OpenShift click on "Version Control" and click on "Commit Solution"
Write a short commit message and press "Commit". Click back on "Version Control" and press "Push Changes" then click the button labeled "Push Changes". After a bit your new site will be up.

[1]: http://www.monodevelop.com/
[2]: http://git-scm.com/
[3]: http://www.openshift.com/
