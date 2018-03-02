# Information > Information Systems

As a security company we care about information and data. Our goal is to do
business with as less storage as needed. This keeps us "lean" and helps us
safeguard the information that we possess.

Some of our systems include:

## Lynis Enterprise
This is our software solution. We store here the information about systems,
collected by the client tool named Lynis. Commonly the tool collects the
following details:

* System name
* Software versions
* Hardware details
* Users and accounts

We store almost no personal data from users, except basic account details based
on full name, email address, username. The passwords are hashed and salted based
on the best practices from the Django framework. Users are responsible for
choosing a safe account, yet the system enforces secure storage. Where possible,
the database itself is stored on the same system. This limits communication
between systems.

## CISOfy ERP and CRM
Data regarding customers and partners are stored in our internal system. In this
system we limit the stored data to what is needed to do business.

## Websites
The CISOfy website is the primary page for our software solution. The use of
cookies and trackers is limited. Data is processed by reviewing and parsing the
log files.

The blog "Linux Audit" is an informational account. Normal visitors can not have
an account here. Those who add a comment, use their own authentication details
with the WordPress service, outside our control. We only store the comment,
name, website (optional), and IP address. This is standard functionality of
WordPress.

Our Linux Security Expert (LSE) project has no accounts yet. No tracking or
related cookies are used here. In the future accounts may be enabled, in that
case the cookies used would be for authentication purposes.

Overview:
* cisofy.com
* linux-audit.com
* linuxsecurity.expert
