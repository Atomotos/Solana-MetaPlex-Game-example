<h1 align="center">SOLHunt - Play.Win.Earn</h1>

<p align="center">
  <a href="/">
    <img src="./screenshots/7.png" alt="Logo" width="480" height="240">
  </a>
  <h6>Built at Solana Ignition Hackathon 2021</h6>
  <img src="./screenshots/12.svg" alt="Logo" width="120" height="120">
  </p>

  <p>Play SOLHunt game online at <a href="https://solhunt.surge.sh">here</a></p>
  <p>Visit SOLHunt store at <a href="https://solbros.github.io/solhunt-store">here</a></p>
  
  <p align="center"><a href="https://www.youtube.com/watch?v=SISGTRfX3LE">Watch Demo Video on YouTube</a></p>

# ARCHITECTURE

![image](./screenshots/flow.jpg)

# FEATURES

SOLHunt is a lightweight pixel Play To Earn dungeon game built on the Solana Blockchain, built with Phaser. Our motivation is to enable users to own what you earn

**GAME DATA IS STORED ON-CHAIN WHICH MEANS THAT THE USER CAN'T COLLECT TREASURE (SPL TOKENS) PREVIOUSLY COLLECTED**

- 🎮 Secure authentication with phantom wallet
- 🎮 In Game Store
- 🎮 NFT rewards as Level Passes
- 🎮 $DUN(SOLHunt) Token Rewards as Loot (SPL token)
- 🎮 Auto save game progress on chain
- 🎮 Metaplex Game storefront for buying game characters and using them as game assets as NFT. Every character is Rare and has unique abilities.
- 🎮 Decentralised storage powered by ARWEAVE
- 🎮 Swap $SOL for $DUN(game token), on serum DEX swap (ALPHA) in game to deposit token in escrow to play (COMING SOON)
- 🎮 SOLHunt DAO to reward game-artists assets through voting on Solana using $DUN token.

<p>
 <img src="./screenshots/8.png" alt="Logo" width="480" height="240">
 <img src="./screenshots/11.png" alt="Logo" width="460" height="220">
</p>

![image](./screenshots/9.png)

## Quick Start

This app requires the following dependancies. Before continuing, download and install them:

- [Node.js](https://nodejs.org/en/download/) Node.js 10 or higher is required.
- [Anchor](https://project-serum.github.io/anchor/getting-started/installation.html#install-solana) Install version v0.13.2
- [Solana Tool Suite](https://docs.solana.com/cli/install-solana-cli-tools)

## Update Environment Variables

Add candy machine config to .env

```
cp .env.example .env
```

For this demo we have added our env variables, Feel free to update them.

## Running the program locally

```
cd program
npm run build // This will build the program
npm run deploy // This will deploy the program to the local solana network and copy idls generated to the client app.
```

## Running the app locally

### Install dependencies

```
cd client
npm install
```

### Create a mint authority

```
npm run initialize
```

### Start the development server

```
npm start
```

view game at [http://localhost:3000/](http://localhost:3000/)

### Gameplay

![image](./screenshots/1.png)

![image](./screenshots/2.png)

![image](./screenshots/3.png)

![image](./screenshots/4.png)

![image](./screenshots/5.png)

![image](./screenshots/6.png)
![image](./screenshots/10.png)

```

```
