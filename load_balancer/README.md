# load_balancer

Load balancer project: a second web server and an HAProxy load balancer in front of both.

## Files

| File | What it does |
| ---- | ------------ |
| `0-custom_http_response_header` | Installs Nginx and adds the `X-Served-By` header with the server hostname (web-01 and web-02) |
| `1-install_load_balancer` | Installs HAProxy on lb-01 and balances traffic between web-01 and web-02 with roundrobin |

## Notes

- Bash scripts start with `#!/usr/bin/env bash` and are executable.
- Services are restarted with `service`, not `systemctl`.
