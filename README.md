#WordPerfect Office for Linux Beta 1  Readme

Installation Instructions

Welcome to WordPerfect Office

About This Beta Release

General Testing Guidelines 
Known Issues 
WordPerfect Issues 
Quattro Pro Issues 
Presentation Issues 
Corel Central Issues 
Paradox Issues 
Developer Testing Guidelines
Welcome to WordPerfect Office

Welcome to the beta program for WordPerfect Office 2000  for Linux from Corel Corporation. 
At Corel we're committed to delivering the power of our  award winning, integrated 
set of business productivity applications for at work and at home to Linux users and 
we'd like to thank you for your participation in this beta program.  Check out all of the 
applications provided and we think you'll agree we prepared to deliver the best,  most 
complete, integrated productivity application suite ever available on the Linux platform.
We're obviously very excited but here's what our lawyers have to say (as per the beta 
test agreement): Corel reserves the right at any time to alter prices, features, 
specifications, capabilities, functions, release dates, general availability, 
or other characteristics of the Product. 
 

WordPerfect 9

For word-processing and page layouts WordPerfect 9  for Linux delivers the power and control that 
has made WordPerfect famous and widely used throughout the Windows environment. Check out 
these exciting new features :
Corel RealTime Preview lets you preview a formatting change before you apply it to a document.
The Autoscroll tool on the WordPerfect toolbar lets you scroll through a document quickly, without using the arrow keys or scroll bars while the back and forward arrows allow you to move between cursor insertion points.
WordPerfect provides a separate print preview option so that users can experiment with real time preview, adjust the final output while viewing facing pages and to lay out your documents quickly.
SpeedLinks let you create Internet links to another part of the same document or to another

document on the World Wide Web.
Powerful table capabilities including skewed columns or rows.
Browse by button located at the bottom of the scroll bar allows you to quickly navigate to the next table or graphic in your documents.

The same  file format as the Windows versions WordPerfect
File format capabilities for many of the most popular file formats for both text and graphics.
Quattro Pro 9

Quattro Pro for Linux lets you create professional spreadsheet based documents to help you 
manage data. We believe that  Quattro Pro will  be the most powerful spreadsheet program available for Linux. Check out these features:
Corel RealTime Preview lets you preview a formatting change before you apply it to a document.
Formatting features for borders, fills, page breaks and the quick format brush on the application bar.
File format capabilities for many of the most popular file formats for spreadsheets.
 Each notebook can now

contain over 18,000 spreadsheets, each containing one million rows and 18,000 columns.
Dynamic Cross Tab Reports feature, you can summarize large amounts of data into a cross-tabulated table, called a Cross Tab Report.
Improved Internet capabilities including automatic conversion of formatted text to live hyperlinks, HTML and XML output.
Plus the consistent look and feel of WordPerfect  and comparable features such as autoscroll and real time preview.
Presentations 9

Corel Presentations for Linux is a graphics presentation program that lets you create high quality 
slide shows and drawings, which can include text, data charts, organization charts, and 
graphic objects.  Use Corel Presentations to produce professional looking project proposals, interactive 
demonstrations, multimedia presentations, flyers, signs, banners, and more. Check out these features:
File format capabilities allow exporting of Microsoft Powerpoint files for those desperate times when you're not with your friends.
Corel RealTime Preview lets you preview a formatting change before you apply it to a document.
Image tools to edit images and bitmaps
Internet Publisher to allow publishing of your slide shows to the Internet in HTML format.
90 New Masters have been developed based on corporate and environmental themes for choice and professional output.
Paradox 9

Paradox for Linux is a powerful and easy-to-use relational database program that helps you organize, 
track and retrieve information. You can also create sophisticated forms, charts and reports 
to display your information.  If you have unixODBC installed on your system, Paradox will be able to use it to access SQL databases.  unixODBC is not included due to packaging and licensing issues, but is under review for inclusion is subsequent releases.  Check out these features:
Visual database designer accelerates building and review of database structure.
Samples show advanced features in forms and reporting.
Experts guide users through common tasks
Compatibility features such as publish reports to WordPerfect (.WPD), Rich Text Format (.RTF), and Microsoft Word

(.DOC) and store JPEG images in a table
Spell checking for tables and forms
Quick design when table is open from the tools menu, Quick forms, Quick Report, Quick Chart and Quick Crosstab.
Performance, even in this debug non optimized beta build Paradox is amazing everyone with it's performance.
Corel Central

CorelCENTRAL for Linux includes CorelCENTRAL Calendar CorelCENTRAL Memos and CorelCENTRAL 
Address Book to help you effectively manage your time, tasks, appointments, and personal information. 
You can use CorelCENTRAL to plan your everyday schedule, write reminders to yourself, organize 
reference information, and manage all your business contact information.  Check out these features:
Address Book allows you to store contact numbers and addresses
Memos help you create reminders and lists for future reference
Schedule and track events using the Calendar feature
Card Files allow you to store information in user customized groups
Installation Instructions

The entire installation requires approximately 467Mb at this point in time. This can be reduced to 366 Mb by not installing  the help files package. 
 
For Corel Linux Users

Corel Linux users can use the Corel Update program to install the software. The instructions are: 
Open the Corel Update program 
Go to Options / Set file sources 
Select the Corel Linux Distribution CD check box OK 
OK to main menu and select the Update Profile 
A non-free category should appear in the available software tab 
Select wpo2000install package in the non-free category 
Select the update button on the tool bar
Once this procedure is completed any user with usr/bin on the path will be able to run application as outlined in the General Testing Guidelines section of this document. 
 

For Debian Linux Users

Debian users may install the Debian packages using methods familiar to them. For example the following commands would install the appropriate packages from a CD mounted at /mnt/amnt/cdrom1/
dpkg -i /mnt/amnt/cdrom1/dists/slink/main/binary-i386/libwine-wpo2000_2000.01.05.04.45-1_i386.deb 
dpkg -i /mnt/amnt/cdrom1/dists/slink/main/binary-i386/wine-wpo2000_2000.01.05.04.45-1_i386.deb 
dpkg -i /mnt/amnt/cdrom1/dists/slink/non-free/binary-i386/bitstream-fonts_1.0-1_i386.deb 
dpkg -i /mnt/amnt/cdrom1/dists/slink/non-free/binary-i386/corel-icons_1.0-12_i386.deb 
dpkg -i /mnt/amnt/cdrom1/dists/slink/non-free/binary-i386/fonttastic_1.0-2_i386.deb 
dpkg -i /mnt/amnt/cdrom1/dists/slink/non-free/binary-i386/wpo2000install_2000.01.05.04.45-1_i386.deb 
dpkg -i /mnt/amnt/cdrom1/dists/slink/non-free/binary-i386/wpo2000_2000.01.05.04.45-1_i386.deb 
dpkg -i /mnt/amnt/cdrom1/dists/slink/non-free/binary-i386/wpofiles_2000.01.05.04.45-1_i386.deb 
dpkg -i /mnt/amnt/cdrom1/dists/slink/non-free/binary-i386/wpohelpfiles_1.0-9_all.deb 
dpkg -i /mnt/amnt/cdrom1/dists/slink/non-free/binary-i386/wpoprograms_2000.01.05.04.45-1_i386.deb 
dpkg -i /mnt/amnt/cdrom1/dists/slink/non-free/binary-i386/wposystem_2000.01.05.04.45-1_i386.deb

Note that Debian package version numbers indicated in the file names may differ than those actually provided in the release.

For Redhat Linux Users

Redhat packages are included on the CD. Redhat users may install the RPM packages using methods familiar to them. For example the following commands would install the appropriate packages from a CD mounted at /mnt/amnt/cdrom1/
rpm -Uvh /mnt/amnt/cdrom1/dists/redhat/i386/*.rpm

Note that these packages have been converted from the Debian packages using a version of Alien that has been patched to 
handle spaces in file and directory names.  The default Alien conversion will fail without this patch.  The patch can be found 
below, and should be applied to /usr/lib/alien/Torpm.pm from Alien 6.18 ( the latest alien won't work, even with this patch).

--- Torpm.pm.orig       Tue Nov 23 08:25:45 1999 
+++ Torpm.pm    Tue Nov 23 08:25:58 1999 
@@ -54,7 +54,7 @@ 
                                $filelist.="%config $fn\n"; 
                        } 
                        else { # normal file 
-                               $filelist.="$fn\n"; 
+                               $filelist.="\"$fn\"\n"; 
                        } 
                } 
        } 
Alien can be retrieved from it's official home page at http://kitenet.net/programs/alien/

Redhat and localhost configuration

Localhost is not properly configured on some Redhat systems. We will not be using local host in future releases but for this beta release users  may need to manually set the fonttastic font server path with by executing the following command while logged in as superuser:
xset fp+ tcp/120.0.0.1:7102/all

Redhat and Printing

Printing may not work on some Redhat installations. We are aware of this issue and apologize for any inconvienience caused by this limitation.
General Testing Guidelines

Do Not Run As Root

Users should not be logged in as Root when testing the WordPerfect Office 2000 applications.  It has been acknowledged that the applications may not be as stable when run by users logged in as root and although we do consider these bugs and we would like these issues brought to our attention,  we encourage users to only log in as root for system administration. 
 
Application Launching

The applications can be  launched via icons that are created in the application starter menu on the KDE desktop. Note that if icons do not appear or are not applicable to your installation you can run the applications using the following commands at an x-windows console. 
 
Script 	Application
wordperfect	WordPerfect 9
quattropro	Quattro Pro 9
presentations	Presentations 9
paradox	Paradox 9
cccalendar	Corel Central 9 Calendar 
ccmemos	Corel Central 9 Memos
ccaddressbook	Corel Central 9 Address Book
setupWPO2000 --force 	Forces reset of configuration files for Corel WordPerfect Office 2000 applications
Note that setupWPO2000 --force does reset all configuration entries therefore user setting and preferences will be lost after this command has been executed. The setupWPO2000 is invoked automatically the first time the applications are launched and in general is only required to force a reset of the user settings.

If an application does not launch it is possible that an error has occurred in the font server technology being provided. The font server runs as a component of X-Windows and as such may require a restart of X-Windows to properly re-initialize. For more information on the font server please see the Bitstream Fontserver section that follows. 
 

Killing Applications

It is possible that an application error may occur in the WINE process and in order to exit the application or restart applications it will be necessary to kill all WINE processes. Before doing this any application which is making use of WINE other than the offending application should be exited by the user. The user may then execute the following command from a console: 
killall -9 wine 
 
Packages

All software technology provided is under development including the Debian Packages and Redhat Package Manager files provided.  Please  log any problems encountered including problems encountered with these packages.
On-line Help

Accessing the online help requires a Java enabled browser.  The current content for online help is actually the Windows version of the help content and therefore contains references to Windows environment that may not be applicable to WordPerfect Office for Linux. Please do not report these occurrences as bugs.
BitStream Font Server

This beta includes a beta  copy of the BitStream FontTastic font server which runs as a component of X-Windows. Normally if an error occurs in the fonts server it should be able to be stopped and restarted using the commands documented in this section. As a last resort the user may have to shutdown and restart X-Windows to properly re-initialize the fontserver. Symptoms of the fontserver having to be restarted include  applications not being able to be launched and fonts not appearing in applications and fonts behaving very erratically in applications (i.e. a new line for each character or characters overlapping). The following commands run as root may be helpful if users  encountering suspected font server problems: 
 
Commands	Result
xset fp+ tcp/120.0.0.1:7102/all	Set your font path 
killall fontfs 	Kills the fontserver related processes currently running
/usr/sbin/fonttastic	Manually starts the font server application. Note: this runs in background therefore users should not expect a console response when launching the fontserver.
On Linux systems that are not Debian based you will need to manually start the font server by running the script /usr/sbin/fonttastic. 
 

Bug Logging

When logging bugs please try to include all of the steps required to reproduce the  problem you encounter but no more. Frequently lengthy bug reports are submitted where only the last 1 or 2 steps are required to reproduce the problem. Determining the minimum number of steps to reproduce a bug is always appreciated by the entire development staff.
Known Issues

System Font

The system font that appears in most dialogs is an approximate match to the final font we intend to use. Some dialogs may have text strings that are truncated or wrap inappropriately in the dialogs. Please do not log bugs against these issues.
Removable Media

Removable media types such as floppy disks and CD-ROM are polled by the WordPerfect Office applications when the applications are 
launched. If present when the applications are launched these devices are indicated as icons in the file open and save dialogs. If a CD-ROM or 
floppy is mounted while the application is running it will not be accessible from the icon's in these dialogs but  can be accessed directly by 
browsing or typing in the mounting  points directly.
Slow Startup Times

The applications may be very slow to initialize the first time they are launched. This is due to application and template initialization. If users continue to experience long delays on applications launching it may be caused by processes that automount drives. The user can determine if this is occurring by launching the applications from a console and observing the time required for the "could not stat" messages to appear for each drive. These devices should be mounted before the applications are launched or automount daemons should be disabled to avoid the slow launch times.
Performance

This beta release of WordPerfect 2000 Office for Linux has not be optimized for performance. Please do not log bug against performance unless there is a specific operation that is significantly slower relative to the general performance you are experiencing.
Printing

The printing implementation is not complete and may have some obvious problems. The print file sizes have not been optimized and fonts may be downloaded multiple times for a single document. The result is that printing may not be reliable especially when  printing to non-postscript printers. Please limit the number of bugs you report on printing to ones that will summarize the overall status (i.e. numerous bugs logged against a specific font not printing because the same font appears in multiple documents is not an efficient use of beta testers or developers time).
Some testers have reported that the applications only print if the printer is installed after the printer installation. This problem has not been tracked down and should be logged as a bug when encountered by users.

The  PrimaSans BT font cannot currently be printed due to file size limitation with our current printing libraries. Printing has not been optimized and may generate large print files, this is particularly noticeable when documents being printed have many font changes applied within the document.

Keyboard Shortcut Conflicts

In some cases  WordPerfect Office 2000 keyboard shortcuts conflict with the standard keyboard shortcuts for commonly used Desktops. Since keyboard customization is not an option in this beta users can either customize the shortcuts for their desktop or invoke the commands via menus and dialogs in the applications.  The known keyboard shortcut conflicts between  the KDE desktop environment included with Corel Linux and WordPerfect Office 2000 for Linux include the following keystrokes: 
 
alt-esc	alt-F2	ctrl-F4
ctrl-esc	alt-F3	ctrl-F5
alt-tab	alt-F4	ctrl-F6
alt-shift-tab	ctrl-F1	ctrl-F7
ctrl-tab	ctrl-F2	ctrl-F8
ctrl-shift-tab	ctrl-F3	ctrl-alt-escape
Please do log bugs for any conflicting keyboard shortcut in your standard desktop environment  that is not noted in this document. When logging the bug please include the Desktop you are using, the function of the shortcut in the desktop and what application and application functionality the keyboard shortcut is conflicting with. 
 

WordPerfect 9

The following features are not ready for testing in WordPerfect:
Templates
Macros/Perfect Script
Page Setup
Envelopes
Symbols (bullets and quotes)
Equation editing
Known Issues

Symbols are not hooked up to the font engine therefore items generated using symbols (i.e. bullets, typographical quotes, equations) will not appear correctly.
The style drop-down list on the Property bars are not working correctly (you can apply styles via the menus however)
Shapes are being rendered with a white background instead of a transparent one.
List of Fonts: When scrolling down the list, the last font can not be seen.  The list does not get pushed up to display the last font
No initial default font size displayed on the drop-down
Italicizing and bolding in some cases corrupts display of text
Color issue: incorrect colors being displayed
All Style Editor dialogs have their menus cut off but you can still access them by clicking where the menus would be.
Print Dialog is being rendered incorrectly (i.e. it is not big enough to display all of the functions.)
Customization dialogues for toolbars, property bars, and menus are incorrectly sized, resulting in some of the buttons to be off the visible dialog box and some functionality will not appear.
Refresh problem when adding Header and Footer
Only one target appears in drop down window of Cross-Refs bar
Comment 'bubble' outline remains on screen after comment has been closed.
Please note that WordPerfect symbols (bullets, quotes etc) only work when the BitStream FontTastic font server is enabled. See General Testing Guidelines section for further details.
Closing WordPerfect while in equation editing mode will cause WordPerfect to hang and setupWPO2000 --force command may be required to re-initialize the application.
There are known display issues with some fonts when you apply attributes such as bold, underline or italics.
Quattro Pro 9

The following features are not ready for testing in Quattro Pro:
PerfectScript
External Data area (Expert, Database Desktop, Table Query, Table Link)
Known issues

Files with VBA code can be opened, but the code is lost when the file is saved.
Running multiple applications results in Quattro Pro running slower.
Notebook write-protect permission can be over-written, if this occurs it will corrupt the file.  Modification of write-protected files can occur if a user without write permission to the Quattro Pro file has write permissions to the  folder the files reside in.
Quattro Pro does not recognize the default floppy drive unless mounted manually through the console.
Quattro Pro experiences unpredictable behavior when the File Manager is open.
When trying to open a Shared Notebook, a dialog appears warning that any saving of the file in Linux will result in the file no longer being shared and the change history being deleted.
Refresh problems with Toolbars.
A registry check and a protocol procedure during the first launch, resulting in a slower startup.  Templates are also slow on first initialization.
Quattro Pro files created in the Windows release can be imported and opened in the Linux release.  Quattro Pro files created in the Linux release can be imported  but not opened in a Window's release.
Macros which include functionality that is in the ?Not ready for testing? section, will cause unpredictable results.
Alternate menus are incorrect (Excel, Lotus).
Using Tools-Consolidate - being logged in as root can cause application crash  when typing file names.
Presentations 9

The following Corel Presentations 9 features are not ready for testing:
Page Setup
Show on the Go
Scrapbook
Symbols
Trace Text
Macros/Perfect Script
Known Issues

Bullets - bullets do not appear in the bullet properties dialog, the slide show and while playing slide show
Grids - there is a problem when you turn off grids, it will not refresh properly and grid lines will not disappear
Filters - the following Import/Export filters are not currently working, CorelDRAW (*.CDR, *.CMX, *.CDT, *.PAT), Microsoft PowerPoint (*.PPT), Compuserve bitmap (*.GIF), Kodak (*.PCD), and Freelance(*.PRS)
Internet Publisher - the Show Me feature is not currently working
Internet Publisher - since the GIF filter is not currently working, you can not create a web page using this graphic type.
Settings - user can not create custom toolbars unless they are a root user
Toolbars - Floating toolbars disappear behind the application window.  To view the floating toolbar again minimize then maximize the application window.
Working in 256 color mode is not supported.
Paradox 9

If you have unixODBC installed on your system, Paradox will be able to use it to access SQL databases.  UnixODBC is not included due to packaging and licensing issues, but is under review for inclusion is subsequent releases. Please post inquires to the beta news group if you are having any problems using unixODBC with Paradox.
The following features are not ready for testing in Paradox 9:

Active X Controls and Windows Controls
Dynamic Publishing to HTML
OLE related features
MS-Access features
Setup Considerations

To launch Paradox from the command line type "paradox" (no quotes).
To launch the BDE Administrator program from the command line type "bdeadmin" (no quotes).
The idapi.cfg is by default installed into your home directory under the directory .wpo2000
Known Issues

Paradox printing and form/report design works better if the default fonts in the Preferences is set to "Courier SWC"
Project Viewer has been altered for Linux version
Alias drop down-list not completely functional must use the keyboards up/down arrows
MAPI, OLE, DDE Object Pal methods and procedures will compile correctly, however, they do not function
Frameworks has been removed
Limited printing capability
New methods created with the OPAL editor are missing parameters after the key word "method"
Printing the sample report "customer.rsl" and tables, will sometimes hang Paradox.
Inserting tableframe in a form causes Paradox to freeze
Design Tools - Rectangle and ellipse causes Paradox to freeze when Object Explorer is opened
Corel Central 9

The following features are not ready for testing in Corel Central:
Printing
Event Alarms
Palm Pilot Synchronization
Known Issues

Cannot access Help via F1 key
Cannot launch "Corel on the Web" Web Links
Developer Testing Guidelines

Wine Developers

WINE Source

At this time, the source code for WINE is not included.  Corel does  plan to include the modified WINE source code in subsequent betas, as well as making it available from our web site.
WINE Contributors

In the Help about box of each application please notice the list of credits to the people who have contributed to the WINE project.

WINE Debug Information

When experiencing a repeatable crash the WINE debug information can be captured and submitted with the bug report. See the application launching script (/usr/lib/corel/bin/wpolauncher)  for information on setting the required environment variable to export debug messages. 
  
 
