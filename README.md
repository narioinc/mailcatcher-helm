# mailcatcher-helm
Helm charts to deploy a simple Mailcatcher fake SMTP server inside a k8s cluster.

This is to support dev team run the wonderful tool called Mailcatcher which enables them to test 
email scenarios that use SMTP

The Services that come up as follows
1) mailcatcher - UI to see the emails that have been sent to the SMTP endpoint - Port 1080
2) postfix - exposes the SMTP endpoint on 1025 for SMTP clients to connect and send mail


Thanks to the Mailcatcher team for the wonderful tool
https://github.com/sj26/mailcatcher 