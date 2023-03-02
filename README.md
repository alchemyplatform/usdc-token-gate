# Build a $USDC Token-Gated dApp

Today, **Create Web3 Dapp** and the **Alchemy SDK** will help you build a minimally-featured web3 version of [Stripe](https://stripe.com/)! 💸

If you follow along with the steps below, you will have a full-fledged web3 payments processor. You'll be able to use this to token-gate parts of your dApp and only allow users to see secrets if they have fulfilled some condition - in this case, like sending a certain amount of $USDC to a merchant!

**You can get some Goerli $USDC at https://usdcfaucet.com/**

You'll also see how easy it is to boostrap a dApp using [Create Web3 Dapp](alchemy.com/create-web3-dapp?a=e57fe2174f) as well as how to use Alchemy's Enhanced APIs, via the [Alchemy SDK](alchemy.com/sdk?a=cc7506720d), to superpower your dApp and perform near-instant blockchain data scraping.

## What Will the $USDC Token-gated dApp Do?

For this simplistic guide, you will set it up so that you end up with a very simple application that verifies whether a user has sent **1 $USDC** (on Goerli!) to a designated Ethereum address (also on Goerli!). If the user has indeed *ever* sent $1 USDC to this address, they will unlock a secret secret! If the user has **not** sent the required payment, the verification will fail and they will be prompted to send $1 USDC to the designated merchant's address.

#### Your Goal: Follow this guide set up and EXPAND on this basic infrastructure! 🏁

Can you think of more use cases for a web3 Stripe-like processor? There are so many things you can be creative with, here's a few: 

- How much $USDC the user has to pay and to whom
- What the secret is? (ie, the Krabby Patty Secret Formuler or the location of a super awesome party, a private key, an API key, etc)
- The demo app will check if a user has EVER sent $1 USDC to the merchant - but maybe you can create something that acts more like a subscription?
- Maybe you can also check whether a user owns a certain NFT in order to see the secret? (you can do this with the Alchemy SDK!)

**Build these out and win the ETH Denver Hackathon bounties!!!** Ready to build this dApp using Create Web3 Dapp and the Alchemy SDK? Let's jump in! ⬇️

## Step 1. Bootstrap dApp using Create Web3 Dapp 🏗️

1. Open a terminal and run: **`npx create-web3-dapp@latest`**
2. Name your project! To follow this guide, name it **`usdc-token-gate-dapp`**
3. Select **`Create a default full-stack dapp`**
4. **Choose your chain!** To follow this guide, select **`Ethereum`**.
5. **Choose your network!** To follow this guide, select **`Testnet`**
6. **Choose your blockchain development environment!** To follow this guide, select **`Skip`** - we won't be deploying any smart contracts!
7. **Do you already have an Alchemy account?** Select either **`Yes`** or **`No`** and you will be automatically taken to Alchemy.com to either sign up for an account or log in.
8. **Insert your Alchemy API Key:** Once you log in to your Alchemy account, select `View Key` in the top-right corner and copy-paste your API Key into the command line.

And boom! After a short installation, you are now set up with a basic web3 dApp template! 💥 

## Step 2: Start Your Application! 🏃‍♂️

1. In the same terminal where you just finished Step 1, run `cd usdc-token-gate-dapp` (or whatever you named your app in Step 1.2!)
2. Once you are in your project directory, run `npm run dev` and your local application will be ready at http://localhost:3000

## Step 3: Add $USDC Token Gate Functionality 🪙

1. **Edit the `index.jsx` file**. For your main dApp logic, go to **http://bit.ly/3J7rtwr** and copy-paste the entire file into your project's `index.jsx` (yep, just copy and overwrite the whole thing!) - and remember to save the file!

> You'll notice your dApp start to change! 👀

2. **Edit the `Home.module.css` file**. For your dApp styling, go to **https://bit.ly/3YfBZGc** and copy-paste the entire file into your project's `Home.module.css`.

> Does your app look slightly better? 👀

3. **In the `/api` folder of your project, create a file called `authUser.js`**. For your dApp server-side logic, go to **http://bit.ly/3y2V7gb** and copy-paste the entire file into your project's newly-created `authUser.js` file.

And you are done! Your dApp should now have basic token-gate functionality! NICE. 🔥

## Step 4: Customize This Dapp and Win the Hackathon! 🏆

There are so many things you can do with this functionality, here are some challenges for you to work on:

- deploy your dApp using [Vercel](https://vercel.com/) (hint: it's really easy!) This will allow you to share your actual production-level dApp to others!
- can you create an NFT-gate? So that only users owning a specific NFT can see the secret?
- The UX could use some work... think you can make it a little more intuitive for users to use this dApp?
- The styling could also use a lift! Calling all artists!
- Can you think of a better secret to reveal than just the location of a party?

Come to the Alchemy x Circle booth and ask questions or show us how you've expanded on this use case!
