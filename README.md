# Nodemailer-Gmail

This code works with [Nodemailer](https://nodemailer.com/) and Gmail to send email from JavaScript in Node.js via a Gmail account.  You will need to supply your own gmail account and password ;)

# Additional Considerations
- You need to enable "Allow Less Secure Apps" in your Google security settings to allow for a Gmail address to be used as the sender.  Otherwise google will reject the login at authentication.  See https://myaccount.google.com/lesssecureapps

- I belive Google restricts the amount of mail you can send "to" unique email addresses on Gmail so this would not be very useful for sending a large volume of email, but for testing and low volume notifications it works well as of April 19 2018.

# Technology
JavaScript
[Node.JS](nodejs.org)
[Nodemailer](https://nodemailer.com/)
[Gmail](http://gmail.com)
