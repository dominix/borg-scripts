# borg-scripts
my scripts to handle borg backups

- cp `etc/borg` to `/etc/borg`
- cp `bin/*` to `/usr/bin`
- edit `/etc/borg/config` 
- edit `/etc/borg/passphrase`
- `borg-init`
- ln -s `/usr/bin/borg-backup` `/etc/cron.daily`

more docu at https://borgbackup.readthedocs.io

