
````
(reverse-i-search)`svv': ../vendor/drush/drush/drush si standard --db-url=mysql://root:root@localhost/svv1
```

````
../vendor/drush/drush/drush @svv8.val migrate-upgrade --legacy-db-url=mysql://root:root@localhost/svv --legacy-root=http://svv.val --configure-only
````

(reverse-i-search)`svv': drush rsync @svv.a2h:%files/ @svv.val:%files


(reverse-i-search)`svv': composer create-project drupal-composer/drupal-project:8.x-dev svv --stability dev --no-interaction

chmod a+w sites/default/settings.php

http://www.jeffgeerling.com/blog/2016/migrate-custom-json-feed-drupal-8-migrate-source-json

drush cim --y;drush cr;drush migrate-status
valencia:web boris$ drush mi books --update

valencia:web boris$ drush sqlq "update node__body set body_format ='full_html';"

valencia:web boris$ drush sqlq "update node_revision__body set body_format ='full_html';"

install steps from http://bourbon.io/
valencia:sebas boris$ sass --watch stylesheets/sass:stylesheets

design
colors
http://www.colorcombos.com/color-schemes/43/ColorCombo43.html
https://wordpress.org/themes/twentysixteen/
https://www.google.com/fonts#QuickUsePlace:quickUse/Family:Montserrat