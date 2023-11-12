# road_to_web3_week5


## My IPFS Hashes for the smart contract:

    string[] bullUrisIpfs = [
        "https://ipfs.io/ipfs/bafybeifaczyxnmxrc7banc3lw4674c6y3km4slddjnff6fdwhxufeh3zjm/gamer_bull.json",
        "https://ipfs.io/ipfs/QmRJVFeMrtYS2CUVUM2cHJpBV5aX2xurpnsfZxLTTQbiD3/party_bull.json",
        "https://ipfs.io/ipfs/QmdcURmN1kEEtKgnbkVJJ8hrmsSWHpZvLkRgsKKoiWvW9g/simple_bull.json"
    ];
    string[] bearUrisIpfs = [
        "https://ipfs.io/ipfs/Qmdx9Hx7FCDZGExyjLR6vYcnutUR8KhBZBnZfAPHiUommN/beanie_bear.json",
        "https://ipfs.io/ipfs/QmTVLyTSuiKGUEmb88BgXG3qNC8YgpHZiFbjHrXKH3QHEu/coolio_bear.json",
        "https://ipfs.io/ipfs/QmbKhBXVWmwrYsTPFYfroR2N7NAekAMxHUVg2CWks7i9qj/simple_bear.json"
    ];

### Deployed first part of tutorial to Rinkeby:

Deployed to first test the mockdata and see how it works

Mockdata: 0x16b1F19213FC922A67d3C50D32D9949080E4500E
Bear&Bull:  0xFbB69Fb33A74d9797903C4a02357bCe7c556A4e4

https://rinkeby.etherscan.io/address/0xFbB69Fb33A74d9797903C4a02357bCe7c556A4e4

npx hardhat verify --network rinkeby 0xFbB69Fb33A74d9797903C4a02357bCe7c556A4e4 30 0x16b1F19213FC922A67d3C50D32D9949080E4500E

Successfully verified contract BullBear on Etherscan.
https://rinkeby.etherscan.io/address/0xFbB69Fb33A74d9797903C4a02357bCe7c556A4e4#code

then changed to use ETH/USD price feed:

ETH/USD:  0x8A753747A1Fa494EC906cE90E9f37563A8AF630e

https://rinkeby.etherscan.io/address/0x8A753747A1Fa494EC906cE90E9f37563A8AF630e#readContract

Then registered an upkeep with LINK
[now cancelled due to lack of funds, oops]

#### VRF assignment

Deployed via Remix to Rinkeby

BearBull: 0x8E3F4C8Fd59fE4C81BCf05F19408C3893b0088A3

Approve subscription:

https://rinkeby.etherscan.io/tx/0x7cc8643e94c57648d3cd84040b4ce93155b750c4b4e9e02fdb7927cd490855e6


Add funds:

https://rinkeby.etherscan.io/tx/0x0a0a261edc4560b73415bd61b3c8066a9eb6dc6feff438dbc9ba7d5bbb58f9b5

Add consumer:

https://rinkeby.etherscan.io/tx/0x72a61e8c7536607b04ae61c472f33912e6dace41d931d8da9c890903695827a7

Consumer added and funded:

https://vrf.chain.link/rinkeby/9915


Created custom upkeep:

https://rinkeby.etherscan.io/tx/0x9636ea46c9b35e4f825d6c21b6ce2b135630d4d907665abfdddafa11a139e21f


Upkeep set:
https://keepers.chain.link/rinkeby/3548


NFT Changed to coolio_bear which is randomly selected!

https://testnet.rarible.com/token/0x8e3f4c8fd59fe4c81bcf05f19408c3893b0088a3:0?tab=overview



















