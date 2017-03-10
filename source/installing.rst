
**********
Installing
**********

Installing Android Studio
=========================

So the first thing you need to do is install Android Studio.
Android Studo is an Integrated Development Environment (IDE) for the programming language Java.
It checks your code for bugs in realtime. Programming without it would mean that you would only be aware of bugs after compiling it.

#. Download the Android Studio Installer

	The first few steps are pretty simple, but I'll go through them anyway.
	Go to https://developer.android.com/studio/index.html and download the installer. The page should look like this:

#. Run the installer

	 Choose the IntelliJ theme. Then the photos I have will look the same as what you're looking at.
	 Don't install the emulator, you won't need it.

#. Install the correct SDKs
And SDK is a System Development Kit. It gives you the tools to work with a certain system. So like, if Java is the tool box, and SDK is like the kit with the drill and drill bits.
	3.1 Open the Standalone SDK Manager
Android Studio has many SDKs you can install. They corrospond with the different Android operating systems. FTC has limits on which phones they allow, and by extension, which operating systems they allow. So you don't have to install the SDKs for every Android operating system. The different SDKs are grouped by what are called APIs, or Application Programming Interfaces. These are numbered, which makes them a good way to differentiate SDK packages.
For FTC you need the entire API 19 package, the entire API 21 package, and a few select packets from API 23 and 24. 
So check them all and click install. Then go get lunch, this will take a while.
Next we'll go over the installation of the FTC package itself.

Installing the FTC Packet
==========================

The FTC packet allows you to program FTC opmodes in Android Studio.
It comes as a Gradle project you have to import. This is tricky, everything has to be just-so.

#. Download the FTC Packet

	 Go to https://github.com/ftctechnh/ftc_app. You can also google "FTC Android Studio Packet" and that will turn it up as well.
	 It should look like this:

	 So click on "Clone or download," then clock on "Download ZIP." Note where you download it to.
	 Navigate to the zip file and extract it.


	 It'll look like this:

	 Click the Extract button. Once that's done return to Android Studio.

#. Import the FTC Packet to Android Studio

	 In Android Studio, you should be looking at a window like this:

	 If you aren't, you're looking at a project already. Go to the top left corner and click File,
	 then Close Project in the dropdown menu. Then click Import Project(Eclipse ADT, Grade, etc.).
	 Find the extracted FTC folder and click open. Beware: There is a second identical folder nested just beneath it.
	 DON'T SELECT IT. Select the topmost folder named ftc_app_master. Then click import. It will look like this:

	 It will do that for a while, and then Android Studio should open fullscreen.
	 Don't click anything yet, though, because it's still working in the background. Look at the bottom of the screen:

	 You might get an error that looks like this:

	 Click the link and wait for it to finish. You may have to do this multiple times.
	 Once it's done and you haven't gotten any errors, look over at the left side of your screen.
	 There will be tabs on the side. One of them is labelled Project. Click on it. You should get a pop-out.
	 Expand the FtcRobotController, copying the image below.

	 What you're looking for is the little blue C icons. Congratulations! Android Studio is now succesfully installed on you computer.

	 Now, there are two folders in the Project tree, FtcRobotController and TeamCode.
	 FtcRobotController is where all the samples are, and TeamCode is where your code will go.
	 You can only load programs from the TeamCode folder onto the phones.
	 Most of the programs have very minimal documentation, so they are very hard to understand.
	 Because of that, some sample programs have been included with this manual to help you along.
