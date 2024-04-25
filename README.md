# Wordpress site - local testing - Pro-Dosa

* docker-compose up
  * Run a Wordpress + mysql + nginx setup to run a local wordpress site.
  * Can be used to restore a backup and explore/fix it on local machine.

## Setup

1. Set db credentials in .env
1. Optional: Update WP and MySql versions in docker-compose.yml
1. Create a dir ./html (Will contain the WordPress files)
1. in terminal run $ docker compose up
1. open http://localhost/wp-admin/

## WordPress notes

### Backups

* Add WP plugin "backup-backup" or backup the generated content in ./html folder.
