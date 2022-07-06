# PS-Set-LinkedMaster Multi-domain
Set Linked Master account with multiple domain selection and credential saving options

This allows you to have multiple domains to select from, and has the "-UseCredFiles" switch which attempts to use saved credential XML files, or create them if they don't exist in the "-XMLLoc" folder (~\creds\ by defualt)

I had to make a few changes to sanitize this and I've had to use a slightly older version than what I use in production, but I welcome any feedback on this. I know there are some assumptions made here that won't necessarily be true in all environments, any help spotting and correcting those would be appriciated.

I've tried to mark the lines that will need updated for this to work as-is, but please let me know if I've missed any. 
