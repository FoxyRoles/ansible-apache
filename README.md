# ansible-apache

Setups Apache2 from [ondrej/apache2](https://launchpad.net/~ondrej/+archive/ubuntu/apache2) PPA

PPA follows latest Apache2 packages as maintained by the Debian Apache2 team with couple of compatibility patches on top.

It also includes some widely used Apache 2 modules.

### Example playbook
```yaml
---
- hosts: myserver
  roles:
    - role: sunfoxcz.apache
```

## Mandatory variables

## Optinal variables (with their default values)

 * apache_mpm: event
 * apache_user: web
 * apache_group: web
 * apache_uid: 1001
 * apache_gid: 1001

## License

Licensed under MIT license. See [LICENSE](LICENSE.md) for details.
