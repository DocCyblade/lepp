LEPP - Web Stack (Nginx + PostgreSQL)
=============================

The LEPP stack is an open source web platform that can be used to run
dynamic web sites and servers. It is considered by many to be a powerful
alternative to the more popular LEMP stack and includes Linux, Nginx,
PostgreSQL (instead of MariaDB) and PHP, Python and Perl.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- SSL support out of the box.
- PHP, Python and Perl support for PostgreSQL.
- `Adminer`_ administration frontend for PostgreSQL (listening on
  port 12322 - uses SSL).
- Webmin modules for configuring PHP and PostgreSQL.
- PostgreSQL listening on localhost (security)
- PostgreSQL password encryption enabled by default (security).
- The *postgres* user is trusted when connecting over local unix sockets
  (convenience).

A separate appliance is available for the `LEMP stack`_ (featuring
MariaDB instead of PostgreSQL).

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH: username **root**
-  PostgreSQL, Adminer: username **postgres**

.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org/
.. _LEMP stack: https://www.turnkeylinux.org/lemp
