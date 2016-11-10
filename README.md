# otrs-slack-notification.sh
It's a shell script to send slack notifications from OTRS

The script's 3 notification types:

- New Ticket
- Note/Actualization 
- Ticket has been closed. 

### Instructions

#### You need

hostdb = The Database IP or hostname.

userdb = A user with RO privileges to OTRS database.

password = password for userdb.

db = OTRS database name.

Incoming webhooks for slack: 
https://slack.com/apps/A0F7XDUAZ-incoming-webhooks

