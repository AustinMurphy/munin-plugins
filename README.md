
Munin-Plugins
=============

Postfix
-------

postfix_mailstats  tried to monitor both mail coming into a server 
and mail leaving a server.  These plugins split that task up and 
provide better detail.

* postfix_smtpd_stats - Incoming connections and accepted/rejected info
* postfix_smtp_stats - Outgoing connections

Note: The postfix_mailvolume plugin double counts the size of mail 
that has been deferred and requeued.


License Managers
----------------

* flexlm_ - Usage stats for licensed software
* rlm_ - Usage stats for licensed software

