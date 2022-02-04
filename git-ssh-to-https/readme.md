# Git SSH to HTTPS

Sets up the global git config to replace any ssh clone URLs with HTTPS URLs. This must be used after the checkout code action.

```yaml
- name: Checkout Code
  uses: actions/checkout@v2

- uses: bpx-network/actions/git-ssh-to-https@main
```
