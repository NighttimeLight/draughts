## Multi threaded english draughts game
* multiple matches on single server
* IPv4 connection 
* ncurses

## How to:
* first run server
* then you can connect with clients

or just run basicApp to play two players in one window

## Compilation:
* server

    g++ server.cpp -o server.out -Wall -Wextra -pthread

* client

  g++ client.cpp -o client.out -Wall -Wextra -lncurses

* serverless

  g++ basicapp.cpp -Wall -Wextra -lncurses

