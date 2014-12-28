crypto-php
==========

RPC bindings to create a service, website, or app that uses Rubycoin, Bitcoin, or Litecoin.

```
require('Rubycoin.php');
require('Bitcoin.php');
require('Litecoin.php');

$rubycoin = new RubycoinClient("http", "rubycoinrpc", "password", "localhost");
$can_connect = $rubycoin->can_connect();

if($can_connect>0) {
      $difficulty = $rubycoin->getdifficulty();
      $rubycoin_address = $rubycoin->getnewaddress();
      $bitcoin_address = $bitcoin->getnewaddress();
      $litecoin_address = $litecoin->getnewaddress();
}
```
