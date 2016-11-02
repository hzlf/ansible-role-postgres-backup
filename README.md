postgres backup role
====================

Ansible version of https://gist.githubusercontent.com/matthewlehner/3091458/raw/92fac0bba10b3a284ba90271d97775d698dbc854/autopgsqlbackup





Example Playbook
----------------

Minimal usage example:

    - hosts: db-servers
      roles:
        - {
            role: hzlf.postgres-backup,
          }


License
-------

GPL
