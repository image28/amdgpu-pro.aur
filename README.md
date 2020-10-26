# AMDGPU-PRO.AUR
 
<B>Current version:</b> <I>20.40</I><BR>
<B>Current status:</b> <I>Package builds, tested, working with a few
kinks. It overwrites your /lib symbolic link to /usr/lib (temporarilly I removed
symbolic link then moved the files before re-adding, will add a fix tomorrow.
Other than that I had to remove all stale install files etc, with the exception of
a few symbolic links I had previously setup. </I>

<B>Changes</B>
<UL><LI>Removed all the meta packages</LI>
<LI>Merged meta packages into one, easier to maintain</LI></UL>

<B>TODO</B>
<UL><LI>Fix /lib symbolic link issue</LI>
<LI>Test with a clean build system</LI>
<LI>Add all the correct provides</LI>
<LI>Check all licences and technicallities are correct</LI><LI>Fixes for current kernel ( only LTS kernel works with the DKMS module, much like the Xeon Phi DKMS )</LI></UL>

