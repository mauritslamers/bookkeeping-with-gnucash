---
layout: page
title: Saving 
permalink: /saving_gnucash_file/
parent: Setup
nav_order: 5
---

## Saving the administration
We created the accounts, tax rates and entered the company info.
The next step is saving. By default GnuCash will store this info in multiple files in order to be able to
revert to an earlier version. it is advisable to create a separate folder for the GnuCash administration. 

## Retaining old versions
Every time GnuCash saves the changes, it will create a new file with a (slightly) different file name.
This is very practicle when you want to revert to an earlier version if you made some kind of error, or 
deleted something coincidentally. 
By default these files are retained for 30 days. The settings for the retaining period and automatic saving can be found
in the GnuCash settings. See [GnuCash Settings](({{ site.baseurl}}/setup/gnucash_settings) how to find this dialog.

![Tabblad algemeen van de programmavoorkeuren]({{ site.baseurl}}/assets/gnucash_general_settings.png)

## Backups
It is crucial to have a backup of the administration. Make sure that you make a backup of the folder in which you save your GnuCash administration.
You can do this in many ways, such as creating a zip of that folder and mail it to yourself, or copying the folder to a special USB stick or external disk drive.
Use automated backup solutions such as Time Machine (macOS), Windows Backup (Windows) or Deja Dup (Linux). 

Another solution we want to mention is saving the administration to a cloud service. 
You can think of online services such as Google Drive, Microsoft OneDrive, Apple iCloud Drive, Dropbox, or self-hosted solutions as NextCloud or a NAS in the company network.
Using a cloud solution brings the advantage that you can open the same administration on any computer which has GnuCash installed and has access to the cloud location, as long as you don't open it on multiple computers at the same time. You need to also verify that the GnuCash settings are the same as not all settings are transferred.

Be aware however that your administration likely contains sensitive personal data, such as names, addresses and telephone numbers.
As a consequence, it is likely that in the EU your administration is subject to the GDPR (General Data Protection Regulation) or any local implementation of these rules (such as the AVG in the Netherlands). Whatever solution you choose, make sure your data is protected according to these rules!

Be also aware that strictly speaking a cloud storage is _not_ a backup. Make sure you make additional backups.

## Ready for use
Your accounting program is now ready for use. Read the other parts of this manual to find out how to create and post invoices and bills, do the VAT declaration etc.
