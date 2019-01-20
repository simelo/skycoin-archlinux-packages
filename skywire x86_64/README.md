Install this package in archlinux with pacman

GO envs need not be changed

To run skywire-mamager:

`skywire-manager -web-dir ~/go/src/github.com/skycoin/skywire/static/skywire-manager`

or

`nohup skywire-manager -web-dir ~/go/src/github.com/skycoin/skywire/static/skywire-manager > /dev/null 2>&1 &sleep 3`


To run skywire-node:

`skywire-node -connect-manager -manager-address 127.0.0.1:5998 -manager-web 127.0.0.1:8000 -discovery-address discovery.skycoin.net:5999-034b1cd4ebad163e457fb805b3ba43779958bba49f2c5e1e8b062482904bacdb68 -address :5000 -web-port :6001`

or

`nohup skywire-node -connect-manager -manager-address 127.0.0.1:5998 -manager-web 127.0.0.1:8000 -discovery-address discovery.skycoin.net:5999-034b1cd4ebad163e457fb805b3ba43779958bba49f2c5e1e8b062482904bacdb68 -address :5000 -web-port :6001 > /dev/null 2>&1 &sleep 3`
