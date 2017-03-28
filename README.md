ansible-ntpd
============

Install and configure ntpd with specific ntp servers.

Example Playbook
----------------

    - hosts: web
      roles:
         - role: erbriones.ntpd
           ntp_servers:
            - time.localhost

License
-------

The MIT License. See the [LICENSE file](https://github.com/erbriones/ansible-ntpd/blob/master/LICENSE).
