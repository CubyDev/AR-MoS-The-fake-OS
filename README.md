Welcome to the Official repository of AR-MoS :D

Thanks for entering this repository where basically I created a project that.. Technically is kinda useless.

What is AR-MoS?

AR-MoS is a fake operating system That is a parody of MS-DOS

AR-MoS stands for:
Android Memory operating System

How it works?

AR-MoS works on Termux Well that wouldn't make any sense why the hell you running a shell, inside of a shell?

But However AR-MoS is currently very Lightweight since AR-MoS is currently in development

Installation

Before downloading the latest version of AR-MoS, the requirements are:

- An Android phone (OBVIOUSLY)
- Termux
- A ZIP file of the latest AR-MoS version
- A bit of patience :)

I realized something.

Why the hell do you need a tutorial for a setup installation?

Then I realized that you probably didn't know how to install MS-DOS or Windows either. 😭

So here we are.

Step 1: Extract the ZIP file

Extract the ZIP file using ZArchiver, RAR, or another file manager.

But please, do not extract the ZIP file from Termux.

Please. 😭

Step 2: Open Termux

Open Termux.

Remember to install the Termux:API app from F-Droid.

Then type:

cd /storage/emulated/0/

However, you need to check where the AR-MoS folder is located using your file manager.

After you find the AR-MoS folder, search for the "DISK01" folder.

If "setup.sh" is inside it, run:

bash setup.sh

Step 3: Provide the disk files

In older versions of AR-MoS, you had to replace the floppy disks.

Not literally. 😭

The setup needed "Disk02.sh" to create a system file, so you had to provide the exact directory where "Disk02.sh" was located.

For example:

/storage/emulated/0/Download/AR-MoS_v.X/Disk02/

You then had to do the same thing with "Disk03.sh".

AR-MoS v0.4

The process is similar, but instead of using the old disk scripts, you need to provide the location of the ".tar.gz" file.

For example:

/storage/emulated/0/Download/AR-MoS_v0.4/Disk2/

Enter that location when the setup asks for it.

Simple explanation

After the v0.3 update, you now have to search for where the ".tar.gz" file is located.

The setup needs to copy the files inside the ".tar.gz" archive.

But please remember:

Do not extract the ".tar.gz" file.

Please. 😭

Step 4: Check the installation

Now check:

~/build

You should find a folder called:

ARMOS

If you find it, congratulations!

AR-MoS has been installed in Termux.

Step 5: Start AR-MoS

The command used to start AR-MoS depends on the version.

AR-MoS v0.1 FBE

In the first beta version, you used:

./login.sh

This was AR-MoS v0.1 FBE, also known as First Beta Edition.

AR-MoS v0.2 to v0.3

From v0.2 up until v0.3, you used:

bash login.sh

AR-MoS v0.4

For v0.4, you use:

bash ar.sh

This starts AR-MoS.

Notice

If you are installing AR-MoS v0.4, follow the v0.4 instructions.

The older version instructions are only included here for historical reference.
