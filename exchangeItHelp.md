exchangeIt is an application to get email in your OWA inbox.  It currently works with OWA 2003 as long as you have WebDAV enabled.  For the inbox URL, enter the full path to your inbox, including "/Inbox" on the end.  You can easily find this by going to OWA and right clicking the Inbox link on the left hand side, and copying that URL.  My inbox URL looks like:

https://mail.company.com/exchange/Brian.Yarger@company.com/Inbox

I'm working on ironing out the bugs and adding to the support.  OWA 2007 is also not yet supported.

In version 0.6, forms based authentication was added, as well as a background notification service for unread emails.

In version 0.7, support for self signed certs was added.