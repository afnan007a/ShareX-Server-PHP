# ShareX-Server-PHP
ShareX file/image hosting made in php

## ✨ Features

- just an image hosting script lol
- thats it!

## 💁‍♀️ How to use

- download the `index.php` file and upload it to your webserver
- create a directory named `images` in the root directory
- edit the variables below, inside the `index.php` file:

 `$your_domain_url = 'https://yourdomainhere.com/';`
 
 `$file_directory = "images/";`
 
 `$lenght_of_file_name = 12;`
 
 `$$secret_key = "secretkey";`
 
 - now its time to edit the ShareX destination
 - for that first headover to `destination` tab in sharex then `custom uploader settings`
 - now create a new uploader then change the `request url` to yourdomain with the index.php file
 - example: `https://yourdomain.com/index.php`
 - next create a new variable under the body section and name it `secret_key` and in the value section add your secret key
 - example `abcd1234`
 - now scroll down and you will see `file form name` type `images` inside it
 - if you did everything correctly, your server will be up and running properly

