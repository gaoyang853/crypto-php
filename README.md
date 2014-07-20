crypto-php
==========

```
require('Rubycoin.php');
require('Bitcoin.php');
require('Litecoin.php');

$rubycoin = new RubycoinClient("http", "rubycoinrpc", "password", "localhost");
$bitcoin = new BitcoinClient("http", "bitcoinrpc", "password", "localhost");
$litecoin = new LitecoinClient("http", "litecoinrpc", "password", "localhost");

$rubycoin_address = $rubycoin->getnewaddress();
$bitcoin_address = $bitcoin->getnewaddress();
$litecoin_address = $litecoin->getnewaddress();
```
