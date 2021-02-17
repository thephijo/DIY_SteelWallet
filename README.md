# DIY_SteelWallet
An open DIY steel wallet device for securely storing Bitcoin and other cryptocurrency seeds

# Introduction to steel wallets, seeds and Bitcoin wallet backups

Parts of the following information were taken from the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Bitcoin_Wiki:About) and partly adapted for this description.
According to the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Storing_bitcoins#Cold_storage_wallets) there is a best practice when it comes to storage of Bitcoin. There are good and [bad wallet ideas](https://en.bitcoin.it/wiki/Storing_bitcoins#Bad_wallet_ideas) The best way to store bitcoin is to either use a hardware wallet, a multisignature wallet or a cold storage wallet. One should have the wallet create a seed phrase,
 write the Seedphrase down on paper and store it in a safe place (or several safe places, as backups). This is where a steel wallet can come into play:
 
A [seed phrase, seed recovery phrase or backup seed phrase](https://en.bitcoin.it/wiki/Seed_phrase) is a list of words which store all the information needed to recover Bitcoin funds on-chain. BIP39 is the most common standard used for seed phrases today. Anybody  who is in posession of the phrase can transfer the bitcoins, so it must be kept safe like jewels or cash. For example, it must not be typed into any website. A password can be used to create a two-factor seed phrase where both "something you have" plus "something you know" is required to unlock the bitcoins. This also allows the backup to be split between two different locations, so that if only one location (the seed or password) has been compromised, the Bitcoins cannot be accessed immediately, as long as the second part (the password or seed) is still secure and unknown to the attacker.

Most people write down Seeds and phrases on paper but they can be stored in many other ways such as memorizing, engraving or stamping on metal. There are also [Methods that are not recommended](https://en.bitcoin.it/wiki/Seed_phrase#Methods_that_are_not_recommended). Seed phrases can however be stamped or engraved into metal which is significantly more durable than paper. Metal backups are recommended if the threat model involves fire, water, extremes of temperature or physical stress. Those metal devices are often refered to as steel wallets.

[Jameson Lopp](https://jlopp.github.io/metal-bitcoin-storage-reviews/) provides an overview over some of the commercially available devices, which he has tested and evaluated. Commercially available devices cost between $20 and over $300, depending on the features, quality and finish. 
Depending on whether only a seed or a seed plus password is used, two wallets are necessary for a complete backup. If two or three backups are to be kept in different locations, a plurality of wallets is required accordingly. As a student, I see a problem at this point: the whole business of storing bitcoin securely is going to be an expensive endeavor. 
I would like to provide a solution to this problem: A DIY Steel wallet, which is as robust as possible, featurerich, easy to make yourself and inexpensive, even if several wallets are needed.
