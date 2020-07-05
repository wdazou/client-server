# Client/Server
Programme client/server qui permet de faire des requêtes et d'échanger des informations/messages entre un client et un serveur

## Installation

Il faut cloner le repository 

```bash
$ git clone https://github.com/wdazou/client-server.
$ cd client-server
```

## Usage
```bash
$ gcc Server.c -o server
$ gcc Client.c -o client
```
REMARQUE: il faut lancer le server avant le client. Il faut ouvrire sur deux terminals differents.

1er terminals

```bash
$ ./server
```
Sur le 2em terminal
```bash
$ ./client
```

NOTES: Les requêtes qu'on peut faire depuis le serveur :

* **list**: Pour lister les documents sur le serveur.
* **del** : Pour supprimer un document (del nom_du_document).

* **get** : Pour obtenir un document (get nom_du_document ).




## Resultat(output)
TERMINAL 1
```bash
$ ./server
Socket successfully created..
Socket successfully binded..
Server listening..
server acccept the client...
From client: affiche les listes sur le serveur
         To client : list
```
TERMINAL 2
```bash
$ ./client
Socket successfully created..
connected to the server..
Requete : affiche les listes sur le serveur
From Server : list
Document1       Document2`      Document3 
Requêtes : 
```

License
----



**Logiciel Libre, Oura!**
