How to install panel pterodactyl :

Go to Codespace in the Code, Codespace, Create New
$ sudo su
$ pkg update
$ pkg upgrade
$ docker-compose up -d

How to add user and password

Just like before, go to Codespace ( In your project )
COPY THIS ;
docker-compose run --rm panel php artisan p:user:make
Now add your gmail
add your username
and add your password

How to go to the panel

In the your Codespace, press the " ports " menu
and press the top website ( with port 80 )
and finally press the one like the world browser logo
Enter the username and password that you just said

and VOILA, you can enjoy the free ADMIN PANEL Pterodactyl for free
