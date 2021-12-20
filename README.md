# eea.mailarchive.rules
Rules to create mail archive from mail to roles

These rules are run whenever a new email reaches the zeionet mailbox and writes it (if it passes the contained filters) into two mailbox files (`mail` and `rolesmail` folders) that are afterwards processed by the Products.MailArchive product and shown in https://www.eionet.europa.eu/rolemails.
