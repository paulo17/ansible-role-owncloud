# Ansible Role: ownCloud

Installs ownCloud for Debian 8 and Mysql

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    owncloud_database_db: owncloud

The name of the database to create.

    owncloud_database_username: owncloud

The database user name.

    owncloud_database_password: s3cr1t

The database password.

    owncloud_http_domain: cloud.yourdomain.com

The owncloud http domain.

## Example Playbook (using default config)

    - hosts: owncloud
      roles:
        - paulboiseau.owncloud

## License

MIT / BSD