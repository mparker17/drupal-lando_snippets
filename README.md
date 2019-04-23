# drupal-lando_snippets

Snippets to use in `.lando.yml` or `.lando.local.yml` files.

Use these to construct lando configurations.

Don't forget to ignore the local Lando overrides file...

```
echo '/.lando.local.yml' | tee -a .gitignore
```

If you don't want to commit lando files at all...

```
echo '/.lando.yml' | tee -a .git/info/exclude
echo '/.lando.local.yml' | tee -a .git/info/exclude
```
