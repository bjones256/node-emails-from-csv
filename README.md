# node-emails-from-csv

This is a sample project demonstrating the usage of nodemailer, handlebars and csv package to use CSV files for sending emails.
This is suitable for sending event registration confirmation emails e.t.c.
We use it for [NodeSchool Karachi](https://github.com/nodeschool/karachi) already.

## How to use

- Put your source file (CSV) under the 'files' folder
- Put your SMTP credentials in the `helpers/mailer.js`
- Add your template or use existing from the `templates` folder
- Modify the `index.js` based on your event/email to send. It contains variables that would be replaced
in the template placeholders.
- Feel free to ask questions and raise issues.