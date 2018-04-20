# Nodemailer-Gmail

This code works with [Nodemailer](https://nodemailer.com/) and Gmail to send email using JavaScript in Node.js via a Gmail account.  

You will need to supply your own gmail account and password ;)

This repository was initially created to test for another project.

# Additional Considerations

- You need to enable "Allow Less Secure Apps" in your Google security settings to allow for a Gmail address to be used as the sender.  Otherwise google will reject the login at authentication.  You can find that setting here:  https://myaccount.google.com/lesssecureapps

- The "From" address must be the same Gmail address used to authenticate.  If you substitute one Gmail address to login and another in the "From" field, Google will reject it and not send the email.

- I recommend using a secondary Gmail address to send with just to be safe.  I have not encountered any issues, nor have I heard of any using this code or method.  However, historically speaking when Google has locked accounts for suspicious behavior they do so without warning and unlocking the account has not been easy according to reports on the internet.  Better to be safe than sorry.

- I belive Google restricts the amount of mail you can send "to" unique email addresses on Gmail so this would not be very useful for sending a large volume of email, but for testing and low volume notifications it works well as of April 19 2018.

# Technology
- JavaScript
- [Node.JS](nodejs.org)
- [Nodemailer](https://nodemailer.com/)
- [Gmail](http://gmail.com)
