crypto-php
==========

PHP library for developing applications with Rubycoin, Bitcoin, or Litecoin.

```
require('Rubycoin.php');
require('Bitcoin.php');
require('Litecoin.php');

$rubycoin = new RubycoinClient("http", "rubycoinrpc", "password", "localhost");
$bitcoin = new BitcoinClient("http", "bitcoinrpc", "password", "localhost");
$litecoin = new LitecoinClient("http", "litecoinrpc", "password", "localhost");

$can_connect = $rubycoin->can_connect();

if($can_connect>0) {
      $difficulty = $rubycoin->getdifficulty();
      $rubycoin_address = $rubycoin->getnewaddress();
      $bitcoin_address = $bitcoin->getnewaddress();
      $litecoin_address = $litecoin->getnewaddress();
}
```
