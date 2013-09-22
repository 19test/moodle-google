Moodle Google
=============

Moodle Google is a collection of plugins for the integration
of Moodle with Google (or Google with Moodle - depending on
your point of view).

This work is derived from the Moodlerooms (http://development.moodlerooms.com - gmail,gaccess)
Google integration work, added to, and updated for Moodle 2.x.

The plugins consist of:

auth/gauth - Google OpenId Authentication plugin

blocks/gmail - GMail unread messages block

blocks/gaccess - Block of links to Google Apps services for your domain.

grade/export/fusion - Google Fusion tables export from grade book - has been rewritten to use the internal Moodle OAuth libs

** NEW **
repository/googledrive - OAuth based repository plugin for Google Drive - provides URLs and Files

##   INSTALL
Install Instructions:
1. Copy the blocks and auth directory to your root moodle directory.
blocks/gaccess
blocks/gdata
blocks/gmail
auth/gsaml
lib/zend
(place the zend folder in moodle's lib folder)

2. Navigate to your Moodle site and login as Admin

3. In the Site Admin Block, click on the notifications link

All Moodle Google blocks should be installed.  Please navigate to http://development.moodlerooms.com/course/view.php?id=30 to learn how to configure each block, and that authentication plugin.

Release 1.1  3 Legged OAuth is now used 
As of this moment google has stopped supporting 2 legged OAuth and
old code will not authenticate properly to the non-existant 2 leg service. 
 
