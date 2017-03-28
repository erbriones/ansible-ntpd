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
