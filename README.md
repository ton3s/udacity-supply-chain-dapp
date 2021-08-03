# Udacity Supply Chain Dapp

### Libraries

```
# dotenv
Used to load environment variables from a .env file

# truffle-assertions
Helper library to assist with checking for events

# truffle-hdwallet-provider
HD Wallet-enabled Web3 provider. Use it to sign transactions for addresses
```

### Versions

```
# Truffle version
v5.3.12

# Node version
v12.22.1

# web3 version
v1.2.1
```

### Contract Details

```
Deploying 'FarmerRole'
----------------------
> transaction hash:    0x1d085405a37a8145bcbe0374871bfcd35059cd7cbc038e17fd28fdd4d8b5800e
> contract address:    0xfE9728E7d68723B32887B5A8B662232b10dc4756
> account:             0x85C2A38b0251fbe7E5bDBb43f34212c0E32e9D3B

Deploying 'DistributorRole'
---------------------------
> transaction hash:    0x087362a1c5cee9e43f02f200930d7ffc54c3be3aa34335601fcad35c090fde3a
> contract address:    0x4d79c3bF517C5c41c40DE8e673fea66c5589BD17
> account:             0x85C2A38b0251fbe7E5bDBb43f34212c0E32e9D3B

Deploying 'RetailerRole'
------------------------
> transaction hash:    0x2cfd49e72a179b65aeafa2b07512bd49fb1ed194b1607ae24f0934ff50053f24
> contract address:    0xB7974792e30155b1E46AFbDDdbCcc69AC236B6c6
> account:             0x85C2A38b0251fbe7E5bDBb43f34212c0E32e9D3B

Deploying 'ConsumerRole'
------------------------
> transaction hash:    0xa467ab39fe5eddf354e97b8c9c4e7e7e4baa1a1fae904110fc03f48cc9bdf0c7
> contract address:    0xA0db8C08842c79B9F5aAE9E5AE49CcE625047b34
> account:             0x85C2A38b0251fbe7E5bDBb43f34212c0E32e9D3B

Deploying 'SupplyChain'
-----------------------
> transaction hash:    0xa301d6cc9c84c2bc4b394a4b319dc4efcec2164d984016893ee6e949ec23ccf5
> contract address:    0xbaC23F1dFfe7f625BBffdDC8c26a10b91bBf4CFC
> account:             0x85C2A38b0251fbe7E5bDBb43f34212c0E32e9D3B
```

### Setup

#### Smart Contracts

```
# Configure a .env file with the following:
INFURA_ID=<Infura-Id>
BLOCKCHAIN_PRIVATE_KEY=<Private key of the metamask wallet address>

# Compile and build the smart contracts
truffle migrate
```

#### Web app

```
npm install
npm run dev
```

### UML

#### Activity Diagram

![Activity Diagram](https://i.imgur.com/GBn0WDr.png)

#### Sequence Diagram

![Sequence Diagram](https://i.imgur.com/7EWzRSv.png)

#### State Diagram

![State Diagram](https://i.imgur.com/6JfZs3Q.png)

#### Class Diagram

![Class Diagram](https://i.imgur.com/czWUijg.png)
