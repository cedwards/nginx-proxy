# Bastille template: nginx-proxy

This template installs and enables nginx. Configuration is minimal and requires
additional templates to populate the virtual hosts.

## usage

```shell
ishmael ~ # bastille bootstrap https://github.com/cedwards/nginx-proxy
```

## apply

```shell
ishmael ~ # bastille template TARGET cedwards/nginx-proxy
```

## virtual hosts

Virtual hosts should be placed in `/usr/local/etc/nginx/conf.d/*.conf`.
