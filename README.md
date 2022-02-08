# Motley Fool GlobalTech Developer Interview Project


## Instructions

You can install this project by doing the following:

1. Download the this repo.
2. Unzip the file.
3. Copy and paste it to your working php directory.
4. Run Apache & Mysql.
5. Open `Motley Fool GlobalTech Developer Interview Project` directory.

6. Open `DB` directory and import file:
```

 motley_fool.sql

```

7. Import `motley_fool.sql` inside your Phpmyadmin.


8. Edit `wp-config.php` file and set your Username & Password.

```php
<?php 

define( 'DB_NAME', 'motley_fool' );

/** Database username */
define( 'DB_USER', 'root' ); //Change this to your current username | By default root

/** Database password */
define( 'DB_PASSWORD', '' ); //Change this to your current password | By default ''

/** Database hostname */
define( 'DB_HOST', 'localhost' );

/** Database charset to use in creating database tables. */
define( 'DB_CHARSET', 'utf8' );

/** The database collate type. Don't change this if in doubt. */
define( 'DB_COLLATE', '' );

```

9. Project is now ready to run at:
```http

 http://localhost/MotleyFoolGlobalTech/

```
## [Optional]

Use This url apache has custom PORT_NUMBER, Just replace the `PORT_NUMBER` from the url.
```

 http://localhost:PORT_NUMBER/MotleyFoolGlobalTech/

```


## Authors / Admin Credentials[WP-ADMIN]:
```html

 Username: dpoarch
 Password: qRE$t0oyGu@ampPA1*

```