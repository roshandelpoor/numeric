# numeric
change number english to persian for ui view


**get package by**

composer require roshandelpoor/numeric_change_persian



**example call function in class**


<?php

require_once __DIR__.'/vendor/autoload.php';

use numericpersian\numericpersian;

$obj = new numericpersian();

echo $obj->enToFa("123456");
