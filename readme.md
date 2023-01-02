Set trusted domains manually in nextcloud with
```
docker exec --user www-data Nextcloud php occ config:system:set trusted_domains 2 --value=$URL
```

Read trusted domains manually in nextcloud with
```
docker exec --user www-data Nextcloud php occ config:system:get trusted_domains
```
