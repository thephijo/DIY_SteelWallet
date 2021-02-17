# DIY_SteelWallet
An open DIY steel wallet device for securely storing Bitcoin and other cryptocurrency seeds
Important: Decide for yourself if you trust your skills and the device you made: I do not give any warranty and reject any liability.

# Introduction to steel wallets, seeds and Bitcoin wallet backups

Parts of the following information were taken from the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Bitcoin_Wiki:About) and partly adapted for this description.
According to the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Storing_bitcoins#Cold_storage_wallets) there is a best practice when it comes to storage of Bitcoin. There are good and [bad wallet ideas](https://en.bitcoin.it/wiki/Storing_bitcoins#Bad_wallet_ideas) The best way to store bitcoin is to either use a hardware wallet, a multisignature wallet or a cold storage wallet. One should have the wallet create a seed phrase,
 write the Seedphrase down on paper and store it in a safe place (or several safe places, as backups). This is where a steel wallet can come into play:
 
A [seed phrase, seed recovery phrase or backup seed phrase](https://en.bitcoin.it/wiki/Seed_phrase) is a list of words which store all the information needed to recover Bitcoin funds on-chain. BIP39 is the most common standard used for seed phrases today. Anybody  who is in posession of the phrase can transfer the bitcoins, so it must be kept safe like jewels or cash. For example, it must not be typed into any website. A password can be used to create a two-factor seed phrase where both "something you have" plus "something you know" is required to unlock the bitcoins. This also allows the backup to be split between two different locations, so that if only one location (the seed or password) has been compromised, the Bitcoins cannot be accessed immediately, as long as the second part (the password or seed) is still secure and unknown to the attacker.

Most people write down Seeds and phrases on paper but they can be stored in many other ways such as memorizing, engraving or stamping on metal. There are also [Methods that are not recommended](https://en.bitcoin.it/wiki/Seed_phrase#Methods_that_are_not_recommended). Seed phrases can however be stamped or engraved into metal which is significantly more durable than paper. Metal backups are recommended if the threat model involves fire, water, extremes of temperature or physical stress. Those metal devices are often refered to as steel wallets.

[Jameson Lopp](https://jlopp.github.io/metal-bitcoin-storage-reviews/) provides an overview over some of the commercially available devices, which he has tested and evaluated. Commercially available devices cost between $20 and over $300, depending on the features, quality and finish. 
Depending on whether only a seed or a seed plus password is used, two wallets are necessary for a complete backup. If two or three backups are to be kept in different locations, a plurality of wallets is required accordingly. As a student, I see a problem at this point: the whole business of storing bitcoin securely is going to be an expensive endeavor. 
I would like to provide a solution to this problem: A DIY Steel wallet, which is as robust as possible, featurerich, easy to make yourself and inexpensive, even if several wallets are needed.

# Features of DIY_SteelWallet
+ resistant to heat, corrosion and mechanical damage
+ metal plate visibility protection through 3d printed case
+ integrated tamper proof seal to enable the detection of a potential security risk
+ cheap and easy production

# Tools and materials required

Some Tools and materials are required for the DIY_SteelWallet that are listed in the following paragraph:

Tools:
+ A 3d printer or access to a 3d printer: for making the case
+ A drill with metal drills (1.5 or 2mm): For attaching the metal plate, case and tamper proof seal
+ Letter Metal Stamps (60 * 6 * 1.5mm work very well): For engraving the seed into the metal plate
+ A hammer
+ A sturdy surface to hammer onto
+ Personal protective equipment (for your safety!)

Material:
+ Sufficient ammount of filament for the 3d printer
+ Metal plate max. 50 * 70 * 2mm (a thinner metal plate will also work; See below for material choice)
+ tamper proof seals (preferably from [HIMEN: "AWS-06x7"](https://www.amazon.fr/plastique-métallique-HIMEN-numérotés-consécutivement/dp/B07VDYRMH5/))
The case is designed so that the HIMEN AWS-06x7 fit perfectly. Other seals can also be used maybe with another variant of the case if required (different drills might be required then).

Optional
+ A metal saw to saw the metal plates
+ Additional stick on tamper proof seals

# Material for the steel plate

The case only serves to avert curious glances from the metal plate. Together with the tamper proof seal, tampering attempts or attempts to read the seed can be detected. The resistance of the backup is ensured by the metal plate. Its material must be selected with great care.

I recommend the materials titanium and stainless steel. For my two prototypes I chose:
+ titanium (grade 2) plates 
+ stainless steel (material number 1.4571 or also AISI 316 or V4A (X6CrNiMoTi17-12-2))

Both materials are fairly resistant to mechanical damage and both choices are very corosion resistant. V4A is a bit harder to work with generally but both might be good for the intended purpose. Titanium is a bit more on the expensive side though.
Rusting materials or materials that are not resistant to corrosion may be less suitable for the application (e.g. cast iron or mild steel). 
I personally do not see corosion as very important in my threat model. An exception might be if the steel wallet is to be stored in a swimming pool or in the sea. However, I consider a fire in an apartment to be a realistic danger, in which extinguishing water can also play a role.

In order to be able to assess the fire behavior of building components such as columns, ceilings or walls, certain standard characteristics of the fire progression have been agreed upon, with which uniform tests are possible. What is good enough for buildings should also be sufficient for bitcoins, which is why I use the relevant standards as a guide. The uniform temperature-time curve (ETK) was developed and prescribes the temperature and fire progression in which the fire behavior of a component is to be recorded and classified. Important fire tests that I know of are DIN 4102-2 or DIN EN 1363-1. 
After skimming the standardized fires, some temperatures and times stand out: In a standardized fire, the temperature according to the unit temperature-time curve is about 842 °C after 30 minutes, about 1,006 °C after 90 minutes and about 1,110 °C after 180 minutes. Leaving the times aside, it can be stated that temperatures up to 1110 °C can obviously be reached and they are possibly an upper limit in residential buildings. So for our wallet roughly 1110 °C should be the lower limit that the material can endure for a longer time period.

Aluminum has a melting point of approx. 660 ° C and is therefore to be regarded as unsuitable. 
Even if [Jameson Lopp has had good experiences with copper](https://jlopp.github.io/metal-bitcoin-storage-reviews/reviews/safe-seed/), the melting point (1083 °C) appears to be too low to guarantee sufficient protection against long-term heat and fire.
The melting point of titanium (1668 °C; roughly 1000 °C more than aluminium!) and stainless steel (1460 °C) appear to be much more suitable. 

