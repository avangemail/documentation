# Quickstart Guide 

Send email from your app (such as laravel, wordpress ...), with SMTP and API. With sign up in AvangEmail, you'll have a unique token which you can use to authenticate against our SMTP service or our HTTP API.



## Verify Domain


========= =========================================================== ==================== 
Type      Value                                                       Purpose    
========= =========================================================== ==================== 
TXT       "v=spf1 include:mailgun.org ~all"                           SPF (Required)
TXT       *Find this record in your Control Panel, Domains Tab*       DKIM (Required)
CNAME     "mailgun.org"                                               Tracking (Optional)
========= =========================================================== ====================
