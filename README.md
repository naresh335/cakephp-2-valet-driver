# CakePHP 2.x Valet Driver

Add CakePHP 2 support to Laravel Valet in two steps:

1. Add an identifier file to your app root

`touch ~/Sites/your_app/.cake2`

This is what the driver looks for to determine if the app is running Cake 2.x.

2. Copy the CakePHP 2.x valet driver into your Valet Drivers directory

`cp Cakephp2ValetDriver.php ~/.valet/Drivers`
