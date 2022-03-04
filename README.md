# TwisteRServer

Multiplayer game-server for TwisteRTanks.

## Some reference about status codes
```
-127 - Unknown error.

-4X - Permission denied.
-40 - Permission denied. Invalid key

-3  - Invalid packet.

-2X - Connection is corrupted.
-21 - Connection is corrupted. Invalid key
-20 - Connection is corrupted. Invalid id


-1 - Error. Maximum connected clients to server
 0 - Succes
```

## TODO:
* Replace all generic typehints
* Map generation
* Chat (~70% done)
* ~~API~~
* ~~Python API wrapper lib~~
* GUI client.
* Base docs
* Async