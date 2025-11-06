# Réponses

## Packet n°4 

Packet requête POST avec un username ("Groot") et un mot de passe "Je_sappelle_Groot" -> voir bloc code txt en dessous avec les objets

```yml
----
# Packet 3 from /home/thibault/Downloads/introduction_basic.pcapng
- 4
- 0.000249722
- 127.0.0.1
- 127.0.0.1
- HTTP/JSON
- 257
- POST /signin HTTP/1.1 , JSON (application/json)
```


```txt
JavaScript Object Notation: application/json
    Object
        Member: username
            [Path with value: /username:Groot]
            [Member with value: username:Groot]
            String value: Groot
            Key: username
            [Path: /username]
        Member: password
            [Path with value: /password:Je_sappelle_Groot]
            [Member with value: password:Je_sappelle_Groot]
            String value: Je_sappelle_Groot
            Key: password
            [Path: /password]
```

## Packet n°10

Packet réponse HTTP OK à la requête faite disant que le user ou mot de passe est pas bon

```txt
JavaScript Object Notation: application/json
    Object
        Member: error
            [Path with value: /error:login or password does not match]
            [Member with value: error:login or password does not match]
            String value: login or password does not match
            Key: error
            [Path: /error]
```
