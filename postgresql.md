### Listen on all addresses

/etc/postgresql/[version]/main/postgresql.conf

`listen_addresses = '*'`

### Bind to 0.0.0.0

/etc/postgresql/[version]/main/pg_hab.conf

```
#TYPE   DATABASE  USER  CIDR-ADDRESS  METHOD
host    all       all   0.0.0.0/0     md5
```
