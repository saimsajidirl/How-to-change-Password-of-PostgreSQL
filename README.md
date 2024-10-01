# How-to-change-Password-of-PostgreSQL


#Open the Command Prompt or PowerShell as an administrator.


#Switch to the PostgreSQL installation directory. The default path is usually something like:


cd C:\Program Files\PostgreSQL\16\bin

#Replace <version> with your installed PostgreSQL version.

#Start the PostgreSQL command line interface:


psql -U postgres




#You may need to provide the password if prompted.

#type this after confirming your password:

\password postgres

#Enter and confirm your new password.


#Exit the prompt:


\q
