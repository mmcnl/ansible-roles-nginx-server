## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: mmcnl.nginx_server
          vars:
            nginx_root_dir: /var/www
            ssl_cert_dir: /etc/letsencrypt/live/example.com
            ssl_cert_use_snakeoil: no

## License

MIT