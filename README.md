# alu-system_engineering-devops

## SSH project

This project is about servers and SSH. It uses an RSA key pair to connect to a remote server without a password.

### Files (in the `ssh` directory)

| File | What it does |
| ---- | ------------ |
| `0-use_a_private_key` | Connects to the server as `ubuntu` using the private key `~/.ssh/school` |
| `1-create_ssh_key_pair` | Creates a 4096-bit RSA key pair named `school` with a passphrase |
| `2-ssh_config` | SSH client configuration: uses the `school` key and refuses password login |

### Notes

- Bash scripts start with `#!/usr/bin/env bash` and are executable.
- The private key is never stored in this repository.
- Task 3 was done on the server: the given public key was added to `~/.ssh/authorized_keys` of the user `ubuntu`.

## Author

Ruzigana Irakiza Junior Raul (rruzigana-hub), African Leadership University
