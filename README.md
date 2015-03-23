Seafile for Yunohost
============

Seafile is an open Source Cloud Storage application.

Official website: <http://seafile.com/>

Requirements
------------

Functionnal instance of [Yunohost](https://yunohost.org/#/)

Installation
------------

Through the administration web interface:

Applications -> Install and copy the repo url in "Install custom app"

`https://github.com/CotzaDev/seafile_ynh`

From command line:

`sudo yunohost app install https://github.com/CotzaDev/seafile_ynh`

Upgrade
-------

From command line:

`sudo yunohost app upgrade https://github.com/CotzaDev/seafile_ynh`

Remove
------

Through the administration web interface:

Applications -> Seafile -> Remove

From command line:

`sudo yunohost app remove seafile`

Infos
-----

Seafile server v4.0.6

Available for x64, x86 and arm (Raspberry) architecture but only tested for x64 (feedback are welcome)

TODO
-----

 - Auto login/logout
