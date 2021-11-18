# Create a Multi Sig for receiving the fund

In order to distribute the 1st batch reward and manage the rest of the fund in a decentralized way, I would like to set up a multi-sig wallet with the main implementor in the bouty, which is Pascal from Beacon and Anton from Fearless/Nova Wallet.

The multi-sig wallet is a 3/4 wallet, where:

Hanwen: FvokLqZ9DqT67pukJWWWbEi5kvCkjyCoTvhw4RwUJFgpQXn

Hanwen Backup:DaXGiHoePTkBAcWUEViyjvvYQrC3g2jrfkQfDnT2TWxe5py

Pascal: GRfviCuQxbQeT6hU3gQ6fD8UvcQfyLWj7yg2DQAEhSw6QSK

Anton: Day71GSJAxUUiFic8bVaWoAczR3Ue3jNonBZthVHp2BKzyJ


To use a multi-sig account for using the fund, we need Fearless Wallet team and Beacon team to do the followings.

1. Open Polkadot.js app and select Kusama network
2. Enter the Address Book under Account tab, click `Add Contact` on the top right corner and add the above address into your address book
3. Back to accounts list, and click `+ Multisig` on the top right corner
4. Select the above address, and enter the threshold of **3**, you may enter any readable name you like.
5. If the correct multi-sig wallet is created, you will see the multi-sig account appear in you account list, and there is a red icon appear on the left of its name.
6. Click red icon and see `view pending approvals`, this is a test tx, you don't need to actually sign it. In the future once we distribute the bounty value, we will be use this function.

For more about Multi Signature Account, please refer to the [Example on Polkadot.js](https://wiki.polkadot.network/docs/learn-accounts#generating-addresses-of-multi-signature-accounts)

