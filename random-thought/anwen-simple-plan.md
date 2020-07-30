# Anwen-Creator-Dweb-Platfrom Simple Plan

## As a geek user
sync filecoin daemon and create wallet (wallet-address and private_key)
read ipns(on-filecoin) articles (optional: send filecoin as gift) !!!(author will happy)
- INFO-on-chain-minimum   user-wallet-address & article-wallet-address !!!(more privacy)
- INFO-on-chain-open   user-wallet-address & article-wallet-address & ipns-address
- INFO-on-chain-public user-wallet-address & article-wallet-address & ipns-address & ipfs-address !!!(more data open)
- if user want to comment on article, user is create an article related on original one.

## As a geeker user
cache ipns(on-filecoin) articles on self-hosted ipfs-node (free)
create another wallet (for send filecoin as gift) !!!(more privacy)

## As a creater
create/update article and push it to ipns(free version)
create/update article and push it to ipns(on-filecoin) !!!(optional: author will pay for speed and storage)
metadata in article:
- ipfs of previous version (optional)
- filecoin wallet address (optional) (reader maybe send coin as gift)
- other coin wallet address (optional) (reader maybe send coin as gift)
- upstream ipns/ipfs (optional)
- related ipns/ipfs (optional)
- ipfs of current content (optional)

## As a normal user and creator
- use wallet(wallet-address and private_key) offered by sharer/retrieve-miner/publisher (donot storage too much coin in that)
- use ipns private_key offered by sharer/retrieve-miner/publisher (change to a opensource client is better)
- use publish system offered by sharer/retrieve-miner/publisher (change to a opensource client is better)


## As a sharer/retrieve-miner/publisher
- offer better service of ipns(on-filecoin) and user experience
- should never delete wallet addresses in an article
- should never change content in an article
- can append wallet address as a sharer/retrieve-miner/publisher (people may send filecoin as gift too)

## As a content-ecosystem-protector
- watch sharer/retrieve-miner/publisher and diff ipns content
- if found abuse of author's article, such as delete wallet addresses and change content, protector will open the information, and marked it as bad-ipns
- notify ipfs-node delete bad-ipns and filecoin-node stop fast retrieve of bad-ipns
