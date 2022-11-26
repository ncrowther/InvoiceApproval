# MidcountiesExpenseBot
Contains RPA bot source for Midcounties Coop  RPA bot.

## Setup Instructions:

1. Open readOutlookFolders.wal in RPA Studio

2. Fix paths to point to your local folder

3. Set outlookUser and outlookPwd variables to your outlook credentials

4. In outlook, create folders as follows:
 
     ![Outlook Folders](/assets/images/outlookfolders.jpg)

5: Create invoice emails with the appropriate attachements and move to the correct folder for the expense type

6. run

7. If all goes well the invoices are extracted from outlook and processed with OCR to get key data.  The output is in the /ifs folder

Outlook Error diagnosis:

[USER DIR]\AppData\Local\IBM Robotic Process Automation\imap.log

