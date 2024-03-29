注意
====
这是一个更改过的supervisor-4.2.5应用，添加了路由配置字段！

::

 在inet_http_server下配置base_path字段
 [inet_http_server]        ; inet (TCP) server disabled by default
 port=*:9001               ; ip_address:port specifier, *:port for all iface
 username=******           ; default is no username (open server)
 password=******           ; default is no password (open server)
 base_path=/path/          ; (default is /)

Supervisor
==========

Supervisor is a client/server system that allows its users to
control a number of processes on UNIX-like operating systems.

Supported Platforms
-------------------

Supervisor has been tested and is known to run on Linux (Ubuntu), Mac OS X
(10.4, 10.5, 10.6), and Solaris (10 for Intel) and FreeBSD 6.1.  It will
likely work fine on most UNIX systems.

Supervisor will not run at all under any version of Windows.

Supervisor is intended to work on Python 3 version 3.4 or later
and on Python 2 version 2.7.

Documentation
-------------

You can view the current Supervisor documentation online `in HTML format
<http://supervisord.org/>`_ .  This is where you should go for detailed
installation and configuration documentation.

Reporting Bugs and Viewing the Source Repository
------------------------------------------------

Please report bugs in the `GitHub issue tracker
<https://github.com/Supervisor/supervisor/issues>`_.

You can view the source repository for supervisor via
`https://github.com/Supervisor/supervisor
<https://github.com/Supervisor/supervisor>`_.

Contributing
------------

We'll review contributions from the community in
`pull requests <https://help.github.com/articles/using-pull-requests>`_
on GitHub.
