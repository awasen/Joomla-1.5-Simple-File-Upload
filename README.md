Joomla-1.5-Simple-File-Upload
=============================

Joomla 1.5 Extension Module - Simple File Upload

This is a very easy to use, yet powerful, upload file(s) module for Joomla. It can be as simple as just adding the directory to upload to, or you can chose to use any of the below listed functions.

Version 1.3.5 is tested and verified on Joomla 2.5! (2012-01-14)
Use download for 1.6/1.7!

!!!Security Release 2012-01-02!!!
JED found an exploit in the code where they managed to upload a file named "file.php5". Unfortunately I had not added php5 to the blocked extensions list but now (version 1.3.5) it is added along with .php6 and an extra check to see if ".php" exists in the file-name!
Please make sure to update to version 1.3.5 as soon as possible!

UPDATE 2010-01-04: To be even more on the safe side I have now added code to inspect GIF comments. There is a new option called "Block PHP GIF comments" in the settings which is default set to "Yes" which will read any GIF comment and block the upload if the comment contains any PHP code!
!!!Security Release!!!


It includes the following key features:
- Multiple modules on the same page with different settings
- "Add Note" to uploaded files
- Image re-size
- Automated thumbnail creation for images
- Image compress for JPEG and PNG
- Now supports both "User Named Directory" and "User Defined Directory"! (see below)
- CAPTCHA
- List files in upload directory in pop-up (FancyBox)
- Multiple files upload
- Notification e-mail
- And more...

More features:
- Integrated Ajax in Joomla framework
- "Blacklist" of extensions (threat-protection)
- Multi select file browser for FireFox 3.6+ versions
- Info popup-box now contains the link (URL)
- URL attached in e-mail notice
- Redirect option after uploading
- User Named Directory: You can set a root path for User Named Directories, e.g. "/home/users/" and then select which users should have the option to use the directory. 
- User Defined Directory: You can select from the list of users and add custom directory paths for the user.
- Multiple choice of upload paths added. If a users has "User Named Directory" and/or "User Defined Directory" the user will get a pop-up box asking for the directory to upload to.
- List files option from upload directory in "pop-up"
- Form Fields can now be collected into the same file. A few JED Image Galleries are using a parameter file for labels/description of images.
- Multiple languages.

Joomla 3.0 is now supported!

Update 2012-11-28: User Named Directories and User Defined Directories is now also supported in the Joomla 3.0 version!
