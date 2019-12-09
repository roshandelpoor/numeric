# numeric
change number english to persian for ui view

#call function in class

example :

<?php

require_once __DIR__.'/vendor/autoload.php';

use numericpersian\numericpersian;

$obj = new numericpersian();

echo $obj->enToFa("123456");
