mono 3.12.0
mod_mono 2.10.2

Getting Started with OpenShift and Mono
=========
---

####You will need:
  - [VisualStudio][1]
  - [GIT][2]
  - [OpenShift account][3]

####Geting Started:
Sign into your OpenShift account and click the Create Application tab.
You then want to scroll to the VERY bottom and look for the text box that says: "URL to a cartridge defination"
Paste https://raw.github.com/samasama/openshift_mono_cart/master/metadata/manifest.yml into the text box and click "Next"
Give a name to your application, we will be using "mono" as the name through out rest of this.
Once you have chosen a name click "Create Application" at the bottom.

After it has finished he creation process use git to clone the repo created.
Open the cloned solution using VisualStudio and start development.
Commit your changes using git to reflect on you application.

[1]: http://www.visualstudio.com/
[2]: http://git-scm.com/
[3]: http://www.openshift.com/
