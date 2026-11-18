# web_server

Web server project: transfer files with scp, install and configure Nginx on `web-01`.

## Files

| File | What it does |
| ---- | ------------ |
| `0-transfer_file` | Transfers a file to a server with scp (4 parameters, strict host key checking off) |
| `1-install_nginx_web_server` | Installs Nginx and serves a page containing `Holberton School` on port 80 |
| `2-setup_a_domain_name` | The domain name pointing to `web-01` |
| `3-redirection` | Nginx setup with a 301 redirect from `/redirect_me` |
| `4-not_found_page_404` | Nginx setup with a custom 404 page containing `Ceci n'est pas une page` |
| `5-design_a_beautiful_404_page.html` | A designed 404 page that still contains `Ceci n'est pas une page` |

## Notes

- Bash scripts start with `#!/usr/bin/env bash` and are executable.
- Nginx is restarted with `service`, not `systemctl`.
