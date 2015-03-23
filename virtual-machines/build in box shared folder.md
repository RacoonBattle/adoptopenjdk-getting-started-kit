# Sharing host folder with guest VM

This section describes how to access the Java source code that is inside a VM, from your IDE running on the host computer. This way you can edit in your favourite IDE and environment, then switch to the VM when you are ready to build.

As tested on *Mac OSX 10.10* running *VirtualBox 4.3.20* with the Ubuntu_12.04_OpenJDK_dev_1 VM.

We tried using VirtualBox shared folders, but the Open JDK build environment has problems running in a shared folder, particularly concerning C++ precompiled headers. It would be nice to get this working at some stage, and only fire up the VM when you want to build, but for now we can leave the VM running and access its files from the host computer via Samba, as detailed below. 

TODO MB complete this bit...

See [this article](http://www.howtogeek.com/howto/ubuntu/share-ubuntu-home-directories-using-samba/) or [this one]( http://superuser.com/questions/241825/share-virtualbox-folders-in-reverse-guest-host) for more details.
