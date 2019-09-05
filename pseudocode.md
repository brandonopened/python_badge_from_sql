must be able to be configured to connect to a mysql db
Reads the DB in the table salt_comment basically any new comment reads the user_id
and stores the email address for that user_id after it looks it up in the salt_user table.
it should then be able to use the badgr issuer API to award a badge for that email address, which badgr then sends an email for autoomatically
