god-sensor
==========

FreeBSD monitor process with god

Install God
-------------------
Pre-req: ruby rubygems
`sudo gem install god`

http://godrb.com/

Service Wrapper
--------------------
Start God
`/usr/local/etc/rc.d/god start`

Unloading *without* killing everything
`/usr/local/etc/rc.d/god unload`

(Note: `/usr/local/etc/rc.d/god stop` kills everyone and everything.. you know dooms-day)

Setting Up FreeBSD rc.conf
--------------------
`god_enable=”YES”` is set in /etc/rc.conf 

God Configurations
------------------
/usr/local/etc/god.conf includes all project god files in `/usr/local/etc/god/*.conf`.

Updated with new conf?
------------------
`/usr/local/bin/god load /usr/local/etc/god/service.conf`
