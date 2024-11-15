# ReminderApp (Reminder) - User manual

<html lang="en">

With ReminderApp (Reminder), no more forgetting!    
Rest assured, this program is there to remind you of everything that is important thanks to reminders such as (eg: take your medication, don't forget an appointment or someone's visit, with the baby-minder, domestic help, nurse, etc.).    
Even birthday reminders!    
We've all experienced this embarrassing moment at least once in our lives: forgetting a loved one's birthday! It must be said that it is not always easy to remember the birthday dates of all the people you are used to knowing (especially when you come from a large family or are part of a large group of friends).    
You enter the birthday dates of the whole family and the program will remind you of them every year with an alarm, including reminders of a anniversariy!    
This program also contains an address book and much more to discover!    

To learn more and configure this program Please read this documentation in its entirety. Thanks.    

Note: In this document, specific terminology has been adopted for users who use IT aids for blind people.    

# User Guide

* Author: [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Last modified: November 2024

## Table of contents

* [1.\ Introduction](#toc1)
* [2.\ Setting up the program](#toc2)
* [3.\ The menus](#toc3)
* [4.\ Additional information for the main window for the option "Reminder for the selected day:"](#toc4)
* [5.\ How does the Address book work?](#toc5)
* [6.\ How to open the program from the system tray?](#toc6)


---


# 1.\ Introduction <a name="toc1"></a>
This program which is a combination of an agenda and an address book developed by myself, I called it ReminderApp (internal name) but in reality the program window and in the status bar system appear with the name "Reminder".    

The ReminderApp program is portable and can be configured to minimize and run automatically when Windows starts.    

This program is very intuitive and does not require much explanation, however I will give you some guidelines to follow.    

# 2.\ Setting up the program <a name="toc2"></a>
If you obtained the ReminderApp.zip file, extract it for example in the path:    
`C:\Program Files\ReminderApp`    

You can also extract it to the root of disk `C:\`, example:    

`C:\ReminderApp`    

or you can place it wherever you want.    

Once extracted, this file contains the following elements:    

* The "Doc" folder which contains the program guide files for the current language in use (is available).    
* The "locale" folder which contains the translation files of the language interface available for the program.    
* The "Sounds" folder which contains the alarm sound files, you can add them directly to this folder as long as they are in "wav" format, and their duration is less than 2 seconds, ReminderApp will automatically load the names and sort them inserting them into the   "Set notifications" settings option, which means if you add alarms, the number of alarms you set may change and you will have to reset it in the Settings Menu Submenu Alt+s then in the dialog box "Set notifications" under the list drop-down called: Use alarm: followed by the name of the alarm.    
There is also a "Samples" folder inside the "Sounds" folder, these sounds are used by the program.    
* The "ReminderApp.exe" file (executable file to start the program at any time).    
* The ReminderApp.ico file (the ICO file format is managed by the Microsoft Windows operating system, this format is also widely used for favicons. This icon is visible in the taskbar as soon as the program is minimized and is removed when the program is closed application).    

# Warning

The ReminderApp.zip file, once extracted, will contain its executable called ReminderApp.exe, which will be declared false positive by your antivirus when running it for the first time!    

This happens with Windows Defender antivirus for example.    

How do I allow Windows Defender Antivirus to run the program anyway?    

To allow the program to still run with Windows Defender, you must click on "Additional information". A "Run anyway" button then appears, simply click on it to start running the program on Windows.    

This needs to be done every time the new ReminderApp.exe executable file is installed in the ReminderApp folder.    

# 3.\ The menus <a name="toc3"></a>
In the main window of the program at startup we will find the following five menus with their respective commands.    

# File Menu Submenu Alt+ f

In this first menu we will have the following options:    

* Export address book contacts... Ctrl+Shift+e    
Press Enter, a dialog box appears as name:    
`Export contacts`    
Select the location and export name of your list, in the edit field:    
`File name`    
Then indicating txt or json in the document type.    
`Type :  Text files (*.txt)`    
Down arrow to find:    
`JSON files (*.json)`    
Finally save your file by pressing the button:    
`Save`    
If everything went well, the following message will appear:    
`Note! Contacts exported successfully!`    
* Import contacts into your address book... Ctrl+Shift+i    
Press Enter, a dialog box appears as name:    
`Select a file to import`    
`File name`    
Then indicating txt or json in the document type.    
`File Types: JSON Files (*.json)`    
Down arrow to find:    
File types: Text files (*.txt)    
Select the previously exported txt or json file, then open it by pressing the button:    
`Open`    
If everything went well, the following message will appear:    
`Note! Import completed successfully!`    
Press the `OK` button, A new dialog box appears with the name:    
`Choose how to proceed`    
`By choosing Yes, the contacts will be overwritten.`    
`By choosing No, they will only be added to existing ones.`    
Press either the Yes or No button depending on your choice.    
FOR YOUR INFORMATION    
`JSON files in the case of this program are structured as a list of data, for example: ["...", "...", "..."] and are more convenient for the program to manage, while text files they are structured with a new line marker, for example line\nline\nline etc which are more human readable`.    
* Exit  Alt+f4    
This option closes the program until the next reboot via the executable file (ReminderApp.exe), unless you have configured it when Windows starts.    

# Edit Menu Submenu Alt+ e

In this second menu we will have the following options:    

* Add reminder... Ctrl+n    
* Edit reminder... F2    
* Move reminder... Ctrl+F2    
* Delete reminder... Del    
* Additional reminder notes (submenu) with 3 items:    
* Add... Ctrl+Shift+1    
* Edit Ctrl+Shift+2    
* Delete Ctrl+Shift+3    
If you add a note to a reminder, it will be saved in ReminderApp_config /ReminderApp_notes folder.    
Notes have a unique number in the file name, e.g. "Notes_xxxx.txt", the program is therefore able to find and manage them.    
Note: In the dialog, when adding an Anniversary or Birthday, you can also select a tune and play/stop it via a combo box and button.    
The melodies are stored in the Sounds, Samples, Melodies folder and are in .wav format.    
You can add more as long as they are of the same format and of short duration.    
If there are multiple anniversaries/birthdays on the same day, these will be grouped into a single notification, therefore the first melody on the list will be used.    
Continuing with the Edit menu:    
* Delete past appointments... Ctrl+Shift+a    
* Eliminate past medicines... Ctrl+Shift+m    
* Address book... F4    
A dialog box will open for the options just described, follow the instructions on the screen.    
* Set to current date Ctrl+Shift+h    
It will reset the date selector to the current date.    
* Stop current notification Ctrl+Shift+F1    

#  View Menu Submenu Alt+ v

In this third menu we will have the following options:    

* See birthdays F5    
* See appointments F6    
* See recurring appointments Shift+F6    
* See repeat reminder Ctrl+F6    
* See anniversaries F7    
* See medicines F8    
* See recurring medicines Shift+F8    
Press Enter on the desired option to display it in a list.    
Press the applications key or shift+f10 to display the available options.    
Press Tab and then click the Close button or press the Escape or Enter key to close this dialog box and then return to the main program window.    
Note:    
When you create/edit a reminder, you will also notice 2 recurring types: (Recurring appointment and Recurring medicine)    
These two types of reminders can be set with recurrence: (Daily, Weekly, Yearly), depending on the week for Weekly, choice of day and choice of month will be activated for Yearly.    
You can set from 5 to 60 minutes, you will be notified in time and you will have the opportunity to, I don't know, change, get ready, and when the warning expires the real alarm will go off.    
Recurring reminders are smart, they move to the next equivalent date when they expire. For example, a recurring daily reminder, you will always find it the next day too, and so on.    
I haven't provided the ability to delete recurring reminders (for obvious reasons), but you can view them via the "View" menu.    
If you want to remove one, just activate Show the first "Date" column in the lists, excluding appointments and medications from the View menu.    
Next, select the type of recurring reminder you want to delete from the "View" menu and note its entry date, visible in the first column on the left.    
Finally, set this date in the main selector so you can see it and proceed with the deletion.    
Continuing with the View menu:    
* Show the first "Date" column in displayed lists, (Excluding appointments and medications) (unchecked by default)    
Seeing these dates is useful for easily finding reminders to change or delete them by setting the date from the main selector.    

# Settings Menu Submenu Alt+ s

In this fourth menu we will have the following options:    

* Set notifications Ctrl+Shift+n    
Press enter, a dialog box appears, move with "Tab" and "Shift+Tab" to move between controls, up and down arrows to change the parameter value.    
`Number of repetitions: 3`    
`Interval between repetitions (seconds): 8`    
`Use alarm: Alarm 01`    
`Enables reading of hours in 24-hour format`    
This is a checkbox to choose whether to set the format to 24 hours or 12 hours, the default is 24 hours.    
Press the spacebar to set the 12-hour format.    
`Enable date reading in European format`    
This is a checkbox to choose to set the date format to US or European, the default is European.    
Press the spacebar to set the US format.    
This dialog also contains these checkboxes:    
* Minimize the program on startup (unchecked by default)    
If you choose to minimize the program at startup, the program will hide in the taskbar so as not to bother you, you should see its icon, certainly in the hidden icons, you will be able to interact with the context menu whenever you want. but the program will continue to monitor any reminders of the day.    
If you want the icon to always be seen in the taskbar, you can do so, once hidden, by setting from Windows settings, customizations, Taskbar, show all applications, and activating ReminderApp.    
* Autorun when Windows starts (unchecked by default)    
Choosing this option will allow the program to start automatically when Windows starts.    
* Show reminder preview at startup if the program is minimized (checked by default)    
When the program minimizes to the system tray at startup, it opens a preview of the day's reminders.    
Once the configuration is complete, press Enter or the "OK" button to validate the changes. To cancel the changes press Escape or the "Cancel" button.    
Continuing with the Settings menu:    
* Set hotkey combination Ctrl+Shift+K    
The hotkey combinations to prevent the current notification from triggering an alarm and to show the reminder (even when it is not in the foreground) are designed to work outside of the ReminderApp GUI.    
This means that in case of conflicts with other applications, you will be able to customize them individually.    
If you create a combination that is already in use in the program you will be warned by an error sound and it will not be accepted.    
If your new combination is valid it will appear in the title bar, you can then click the "Use this combination" button and it will be used until you decide to change it again.    
* Set language Ctrl+Shift+L    
When you press Enter on this item, a dialog box will open where there are some languages, which will be enabled if the translation is available in the local folder).    
You can choose the interface language by selecting among the languages currently available displayed in this dialog.    
A dialog box appears informing you that the language has been changed and then that the program must be restarted for these changes to take effect.    

# Help Menu Submenu Alt+ h

In this fifth and final menu we will have the following options:    

* Program information... F1    
When you press Enter on this item, a dialog box will open where the program information will be displayed in a read-only editing document in your respective language if available.    
Use the NVDA+b or Insert+b keys of the screen reader in the documentation to read this information again.    
Once done, press Tab and then click OK button or press Enter or Escape key to close this dialog box and then return to the main program window.    
* User manual... Shift+F1    
When you press Enter on this item, a window will open displaying the program help in a read-only editing html document in the default browser in your respective language if available, otherwise you will receive a warning message.    
Press Alt+F4 to close it.    
* Key shortcuts... F9    
When you press Enter on this item, a dialog box will open in which the program's keyboard shortcuts will be displayed in a read-only editing list, use the arrow keys to move through the list.    
Press Tab and then click the Close button or press the Escape or Enter key to close this dialog box and then return to the main program window.    

# 4.\ Additional information for the main window for the option "Reminder for the selected day:" <a name="toc4"></a>
When you change the date in the main window selector, if the selected date matches a reminder, a sonar sound will sound.    
However, the focus may shift to the list if a reminder has previously been selected.    
To avoid this inconvenience, you can deselect the reminder before proceeding, or enter the date directly following the order day, month, year or month, day, year, depending on the system language settings (and not those of the program ).    
In the selector you can navigate using the horizontal arrows.    
For users of screen readers such as NVDA, it is important to note that the latter does not speak the current position in the selector. We recommend pressing a vertical arrow: NVDA will communicate the date you set and provide updates as soon as you type a full day, month, or year.    
Sonar solves the problem of setting the initial date, instead of moving the focus to the list of reminders when there is one on that date, you hear the sound that notifies you and you can play with your date without problem :)    

# 5.\ How does the Address book work? <a name="toc5"></a>
Access to:    
`Edit Menu Submenu Alt+ e`    
then:    
`Address book... F4`    
When you press Enter on this option, a dialog box opens with the name:    
`Address book`    
This dialog box will contain the list of your contacts if you have added one, otherwise this list is empty.    
When you open the context menu in this dialog box by pressing the applications key located next to the right control key on most keyboards. On a keyboard without an applications key, press shift+f10 instead.    
Please note that some options are unavailable in the contact list depending on the context. You can press Enter on the option you want, so here are the options:    

* Add contact... Ctrl+N    
* Edit contact... F2    
* Delete contact... Del    
* Find contact... Ctrl+F3    
A dialog box will open for the menu options just described, follow the on-screen instructions.    
* Find next F3    
* Find previous Shift+F3    
Both of these options are based on the contact name you typed in the "Find contact" dialog box, so the search is performed with the next or previous match of the same name found in the address book list.    
* Send email to contact... Ctrl+e    
A dialog box will open for this option, follow the on-screen instructions.    

Please note that you can send an email to the contact if the contact's email has been entered in the edit field separated by a space at the beginning (and if necessary at the end), when editing the name of contact, for example. Otherwise, if there is no email in this edit box, this option will not be available to send it.    

If you have not set a default email program, the system will automatically display a dialog box allowing you to select the application to use to send the email.    

# 6.\ How to open the program from the system tray? <a name="toc6"></a>

* Access the system tray by pressing Windows+b, Down arrow to the "Reminder" icon, and open the context menu by pressing the applications key located next to the right control key on most keyboards. On a keyboard without an applications key, press shift+f10 instead.    
* Right-click on the  "Reminder" icon located in the Windows system tray.    

When the context menu comes up, You can use the arrow keys to navigate the menu, and the enter key to activate any of the items listed below.    

* ShowReminder    
Pressing the Enter key on this option will display the program.    
* Stop current notification    
Pressing Enter key on this option The current notification will be stopped.    
* Address book...    
Pressing the Enter key on this option opens the "Address book" dialog box.    
* Exit from Reminder    
Pressing the Enter key on this option will exit the program.    

---

Thank you for reading this documentation!    

I wish you good use of the program ReminderApp (Reminder) 😉    
I would like to sincerely thank [Rémy Ruiz](mailto:remyruiz@gmail.com) for writing this documentation and translation of ReminderApp into French, English, Italian and Spanish and for his feedback and suggestions.    
