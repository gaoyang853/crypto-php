crypto-php
==========

### Example Usage
```
$bitcoin = new BitcoinClient("http", "bitcoinrpc", "password", "localhost");
$litecoin = new LitecoinClient("http", "litecoinrpc", "password", "localhost");
$rubycoin = new RubycoinClient("http", "rubycoinrpc", "password", "localhost");

$bitcoin_address = $bitcoin->getnewaddress();
$litecoin_address = $litecoin->getnewaddress();
$rubycoin_address = $rubycoin->getnewaddress();
```
