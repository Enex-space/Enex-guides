# (do we need to call it Enecuum extension or ENEX.SPACE extension or what could be a proper name thereof? Also, are other browser extensions planned for the time being?)



## Installing Enecuum Browser Extension

- go to app.enex.space
- click Connect (top right); the following window appears (screenshot about here) 
- 
- Connect to a wallet (ENQ wallet - intended to be clickable?) -> Get Enecuum browser extension
- Click **Get Enecuum browser extension**. You will be taken to the Chrome Web Store (screenshot).  
 
Click **Install** to proceed. 

Once the installation is complete, click (icon) right of Chrome address bar to access the Extensions menu and click **Enecuum**. A pop-up window will open, asking you to set up a password. 

Enter the password twice and click **Save**. You will be taken to the _Welcome to Enecuum_ window. 

At this point, you can either create a new wallet by generating a new mnemonic phrase (to do so, click **Generate**) OR log into your existing wallet with its mnemonic phrase (to do so, click **Login**).  

### Creating a Wallet

In the _Welcome to Enecuum_ window, click **Generate**. The following will appear (screenshot): 


If you do not like the mnemonic phrase that was generated, click **Back** to go back to the start view and then **Generate** to generate a new mnemonic phrase. 

If you like the mnemonic phrase that was generated, click **Next** to continue with the creation of your new wallet. 

**VERY IMPORTANT**: If you decide to proceed with the generated mnemonic phrase, **back the mnemonic phrase up** before clicking **Next**. You will not be able to recover your mnemonic phrase once the wallet is created.  

For the next step, you'd better keep the mnemonic phrase at hand

After you've clicked **Next**, you will be asked twice to pick the word at the correct place in the mnemonic phrase (e.g. #7), for example:

Having successfully completed that, you will see the contents of your wallet (empty as of now). This will be covered in the following section (reference). 

Upon creation, the network you invoked the wallet's creation from is default, but the wallet is not connected to it. 

To connect your newly created wallet to a network, go back to app.enex.space, click **Connect** and click **ENQ Wallet** in the window that appears:

**Enecuum Extension** will request access to your account address: 

Click **Allow** to proceed further. Your wallet is now connected to the network. 

### Logging into an Existing Wallet

To log into an existing wallet, open Enecuum extension, enter the mnemonic phrase for the wallet and click **Login**.

You will be taken straight to the wallet view. 

## Working with Enecuum Extension (once logged in)

Window once logged in (screenshots)

_Elements_

> Header: Network name
> Account properties
> > Connection Status (Connected 1 / Not Connected)
> > Account name ("account 1? can you change the account's name?")
> > ("21575" (some number) and weird time stamp I can make no sense of - to be clarified)
> Token info (~ currently selected token) 
> > token name
> > token balance
> > token balance value in USD
> Actions
> > Copy = copy wallet public key
> > Send = send tokens to another wallet
> Assets (overview of the tokens held in the wallet, see further)
> Activity (activity log for the wallet, see further)

### Assets 

This section lists the tokens held in the wallet as follows (screenshot):

> token logo 
> token ticker - short name (check with API?)
> token balance of the wallet
> token balance value in USD

### Activity 

Activity log (add screenshot) 

### Sending Tokens

- click **Send**, the following window appears:

fill in the recipient wallet and the sum and click Send. No further confirmations needed.

screenshot with info 

To send another token, select it first by clicking on it in **Assets**, then proceed in the same way.

### Accounts



- add seed phrase (check terms)
- generate seed phrase
- connect ledger --> A ledger is the Enecuum hardware wallet solution. This functionality is being developed now. 


- working with private keys
- - adding a new private key

### Networks

Enecuum extension supports working with multiple networks. When you install Enecuum for the first time (see above), there's only one network available. 

- add network



- switch network
- 
click Select on the network's bar in the extension; the window will be redrawn, showing the new network in the header.

- delete network

click X, no confirmation is requested

### DApps 

This section allows to work with apps running on the Enecuum network. 

DApps thus far:

- Enex (same as the "big" / desktop ENEX, corresponds to the mobile app view)
- Wallet - same as Explorer Wallet interface
- Faucet - add BIT tokens (is it going to go to production?)
- Save - ???

### Set Password

When you've first launched the extension, it will ask you to set a password

(requirements for a password, checks?) 

Enter the password twice and click **Save**. 

### (e.) Window - ???

### Popup Window - ???

### Logout (and be taken back to the beginning)

Click cogwheel icon in the extension -> Log out. 

All of your data, including the private key and the access password for the extension, will be deleted. You're back to square 1. 
