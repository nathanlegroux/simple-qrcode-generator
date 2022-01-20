- ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) `Note : this code use a google api !`


## Generate QR code with $_GET request named "url"


```php

<?php if (isset($_GET["url"])){
	
$url = $_GET["url"]; ?>

<img src="https://chart.googleapis.com/chart?chs=150x150&cht=qr&chl=<?php echo $url ?>">

<?php } else { 

echo 'error';

 } ?>


```

## Generate QR code with $_GET request named "url" with weight and height

```php

<?php if (isset($_GET["url"])){
	
$wh = '150x150';
$url = $_GET["url"]; ?>

<img src="https://chart.googleapis.com/chart?chs=<?php echo $wh ?>&cht=qr&chl=<?php echo $url ?>">

<?php } else { 

echo 'error';

 } ?>
```

## Generate QR code with $_POST request named "url"

// Encrypt 

```php
<?php if (isset($_POST["url"])){
	
$url = $_POST["url"]; ?>

<img src="https://chart.googleapis.com/chart?chs=150x150&cht=qr&chl=<?php echo $url ?>">

<?php } else { 

echo 'error';

 } ?>
 
```

## Generate QR code with $_POST request named "url" with weight and height

```php
<?php if (isset($_POST["url"])){
	
$wh = '150x150';
$url = $_POST["url"]; ?>

<img src="https://chart.googleapis.com/chart?chs=<?php echo $wh ?>&cht=qr&chl=<?php echo $url ?>">

<?php } else { 

echo 'error';

 } ?>
```


