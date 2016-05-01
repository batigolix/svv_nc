
````
(reverse-i-search)`svv': ../vendor/drush/drush/drush si standard --db-url=mysql://root:root@localhost/svv1
```

````
../vendor/drush/drush/drush @svv8.val migrate-upgrade --legacy-db-url=mysql://root:root@localhost/svv --legacy-root=http://svv.val --configure-only
````

(reverse-i-search)`svv': drush rsync @svv.a2h:%files/ @svv.val:%files


(reverse-i-search)`svv': composer create-project drupal-composer/drupal-project:8.x-dev svv --stability dev --no-interaction
