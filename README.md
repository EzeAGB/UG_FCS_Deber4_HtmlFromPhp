# HTML from PHP

This is a project that shows a way of generating, dynamically, new HTML from a PHP file.

## Requirements:
- Apache2 server.
- Git (Optional).

## Usage (Linux):
Clone the repository (git clone "repo_url") and paste all the downloaded files on "var/www/html".
Then go to "localhost" on any installed web-browser. After that, you should see text at the top and a bird image below it.

## Troubleshooting:
At first you might see a blank page. First check if the Apache server is running, you can do it by using the following command:
```
sudo services Apache2 status.
```
If the Apache2 service is not running. Try executing it by using this command:
```
sudo service apache2 start
```
If still not working try the following command, or restart your computer (yes, old reliable).
```
sudo service apache2 restart
```
Is now running correctly? Congratulations! Otherwise, just search for support (PHP module might not be enabled nor configured correctly).

## Author:
- Name: Ezequiel García Bat.
- EMail: e2016garbat@protonmail.com
- Carnet: 24003175

## Disclaimer 🤗:
No birds were harmed. This image was generated with **Leonardo AI**. Don't try to fed a bird with milk, you might kill them. 🦜☠️
