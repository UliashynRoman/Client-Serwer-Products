Project topic:

The server stores a database of products (code, name, price).

The customer enters the product code (corresponds to the bar code) and in response 
receives a pair of name and price.
Admin can add the new product.

-Program has resistance for exceptions.
-Connection rule: TCP
-Admin Password: is encrypted and decrypted by Cezar

Run on Linux
gcc -Wall Serwer.c o serwer
./serwer

gcc -Wall Klient.c o klient
./klient

Comand for Klient (admin,exit)

All products old and new are in file.txt