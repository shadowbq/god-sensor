god-sensor
==========

FreeBSD monitor process with god


Setting Up FreeBSD rc.conf
--------------------
`god_enable=”YES”` is set in /etc/rc.conf 

God Configurations
------------------
/usr/local/etc/god.conf includes all project god files in `/usr/local/etc/god/*.conf`.

Updated with new conf?
------------------
`/usr/local/bin/god load /usr/local/etc/god/service.conf`
