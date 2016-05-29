||****************************Streamlined Grading System Release 1.0 by Innovators*****************************||

===========================================Software Requirement==================================================

Operation System: 	Windows XP or later versions with Latest Updates
Pre-installed Software:	Adobe Reader with Latest Updates
			Microsoft .NET Framework
			Qt 5.4

===========================================Hardware Requirement==================================================

Processor:		1 Gigahertz (GHz) or faster
RAM:			1 Gigabyte (GB)
Hard Disk Space:	50 Megabyte (MB)
Graphics Card:		Microsoft DirectX 9 Graphics Device with WDDM Driver

===========================================Installation==========================================================

1.Before Installation
	a. 	SGS application is required to be run on SFU CSIL workstations to
		access the SFU Local (cypress) database.
	b.	Make sure the workstation has the required software installed and
		has met the minimum hardware requirements.
2.Installation
	a.	Download the ‘SGSr10.exe’ installation package. (Also available in the misc folder)
	b.	Follow the on-screen instructions provided in the installation wizard.
	c.	To launch the program, execute the ‘SGSr10.exe’ file located
		inside the application directory which was selected in Step b.

===========================================Technical Installation for UAT========================================

1.	Extract SGS archive file ‘SGS_G07_RELEASE1.0.zip’ to a folder destination of your choice.

2.	Launch pre-installed software ‘Qt Creator’ on your computer.

3.	Select ‘Open Project’ inside the ‘Qt Creator’ application.

4.	Open project file ‘SGSr10.pro’ located inside the ‘src’ folder in the extracted package created in Step 1.
	e.g. SGS_G07_RELEASE1.0\src

5.	Select “Configure Project” after the project file in Step 4 is chosen.

6.	Select “Release” as the deploy mode.

7.	Generate the project executable file by selecting “Run” or press “Ctrl + R” on the keyboard.

8.	SGS application is installed in the same folder as your extracted package in Step 1.

9.	In order to launch the SGS application, the required library files need to be copied to the application release folder.
	To do this, copy all (.dll) library files located inside the ‘lib’ folder in the extracted package created in Step 1
	and paste them into the ‘release’ folder located inside the application folder ‘build-SGSr10-Desktop_Qt_5_4_1_MinGW_32bit-Release’.
	e.g. SGS_G07_RELEASE1.0\build-SGSr10-Desktop_Qt_5_4_1_MinGW_32bit-Release\release

10.	SGS application is launched and ready to use.

=================================================================================================================