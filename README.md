Ansible Role: Docker-Compose
============================

This role builds and applies composes for Docker. Rather than have the same rough framework repeated in app specific roles, this was made to be generic and keep things DRY.

If you need to sign into a registry, set these variables:

```yaml
registry_protocol: https # or http
registry_server: registry.example.com
registry_username: username
registry_password: password
```