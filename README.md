# Spip to Wordpress 

spip to wordpress it's a plugin for migrate spip to wordpress.

it uses for connecting to the database the basic functions of php mysql [book:mysql](http://fr2.php.net/manual/fr/book.mysql.php)

## Usage

learn constants

```php

define('SPIP_HOST', '');
define('SPIP_USER', '');
define('SPIP_PSW',  '')
define('SPIP_BASE', '');

```

check Id spip to id Wordpress Categories

```php

public $cat = array( 6 => 3 , 7 => 4 , 8=> 5 , 9=>6 , 11=> 7, 12=>8,14=>9,16=>10,17=>11, 20=>12, 21=>13,24=>14, 25=>15,26=>16);

```

finally run migration and wait
