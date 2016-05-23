composer create-project drupal-composer/drupal-project:8.x-dev svv --stability dev --no-interaction

composer install

````
../vendor/drush/drush/drush si standard --db-url=mysql://root:root@localhost/svv1
```

drush @svv8.val en sebas

drush rsync @svv.a2h:%files/ @svv8.val:%files


chmod a+w sites/default/settings.php

http://www.jeffgeerling.com/blog/2016/migrate-custom-json-feed-drupal-8-migrate-source-json

drush cim --y;drush cr;drush migrate-status
drush @svv8.val cim --y;drush @svv8.val cr;drush @svv8.val ms;

drush mi books --update

drush @svv8.val sqlq "update node__body set body_format ='full_html';"
drush @svv8.val sqlq "update node_revision__body set body_format ='full_html';"

install steps from http://bourbon.io/
valencia:sebas boris$ sass --watch stylesheets/sass:stylesheets

design
colors
http://www.colorcombos.com/color-schemes/43/ColorCombo43.html
https://wordpress.org/themes/twentysixteen/
https://www.google.com/fonts#QuickUsePlace:quickUse/Family:Montserrat