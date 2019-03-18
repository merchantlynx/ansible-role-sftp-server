SFTP Server
=========

This role configures an SFTP server on top of OpenSSH, but with segregated credentials / port / access.

Requirements
------------

OpenSSH Server

Role Variables
--------------

    sftp_group: "sftp-users"
    sftp_users: []
    deleted_sftp_users: []

    sftp_chroot_directory: "/var/sftp_data"

    sftp_extra_config: ""

License
-------

MIT

Author Information
------------------

Brian O'Reilly / Merchant Lynx Services
