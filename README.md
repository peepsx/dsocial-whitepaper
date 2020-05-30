# dSocial
### ***The Decentralized Social Network***
##### **Authored By:** Jared Rice Sr.
##### **Last Updated On:** 05-28-2020

**NOTE:** ***The need for another social network, namely a decentralized social network, may be questioned by many, due to the popularity of platforms like Facebook, Twitter, Instagram and others. There are many inherent problems with these platforms, as well as a plethora of issues that have become very political over the last few years. I don't want to get into politics, although I do want to call out the unethical actions of the many software developers who work for these platforms, as well as the executives above them, for utilizing these platforms in many irresponsible ways.  For this reason, this whitepaper, different from any of my past whitepapers, will start off with my own personal protest. ***

## Protest
Centralized social media providers have become increasingly tyrannical and overly biased towards the views of a large and growing percentage of their users. That bias, due to the centralized control they have over their users, has in-turn motivated networks like Twitter and Facebook to censor many of their end-users for publishing content that its majority liberal-leaning workforce politically disagree with. Most recently, Twitter elected to place a fact-checker on Donald J. Trump's public postings, where a fact-checking module used biased and opinionated journalists from CNN as its cited sources. This turns technology into a weapon, which is currently being used by these networks to create misinformation campaigns where in this case, these campaigns are clearly being used to mislead US voters and interfere in US elections. This sort of behavior by Twitter is reckless, possibly illegal and completely unforgiveable. 

All politics aside, using software to control users psychologically, in order to censor their ideas or opinions, while attempting to alter their political or world views through nefarious misinformation campaigns, is not only completely unethical, it is highly irresponsible. What happened to our ethical standards as software developers? How can we trust companies like Facebook, Twitter and Google to ethically build AI-powered applications or even-worse, AI-powered machines, when we know from experience that they simply cannot be trusted? Elon Musk already warned against trusting someone like Mark Zuckerberg or Jack Dorsey with these sort of capabilities, simply calling it "dangerous", while also calling into question the ethics of some of these companies to begin with. Sadly, AI is already being used by these companies to exploit the privacy of their users in a plethora of ways. They do this with an ambition for world control and are destroying our democracy in the process [SCHE15]. This should also bring into question the politicians that support their existence in the first place nor should any of this be considered a conspiracy theory, considering all of the information that has been coming out in recent years about these big tech executives has proven to be true (please see Fabian Society in [GRIF10]). 

If history repeats itself, it is my fear that the internet giants of the centralized web will come together to form a "cartel" to create some sort of shared monopoly behind the scenes, just as Senator Nelson W. Aldrich and Paul M. Warburg secretly crafted the central bank cartel on Jekyll Island back in 1910, which would become known as the infamous Federal Reserve in 1913 [GRIF10]. Back then, banks came together to protect themselves from the growing influence of small, rival banks and it is my belief that as we expand a decentralized ecosystem like the decentralized web with more applications, disinformation campaigns will be launched by these so called "protectors of the public" so that their platforms can come together and fight off the oncoming threat decentralization poses to their existence. With that said, we designed the decentralized web, as well as dSocial, to resist these sort of attacks and rogue formations. 

That design is built around a truly digitized version of a meritocratic republic, where the majority of the people that use the network are in complete control via their abilities to vote on network changes or improvements and police the network as a whole, rather than it being policed by a politically biased workforce. While there are some semi-decentralized social networks out there like Steem, none of them are completely decentralized, where most of them depend on the HTTP protocol or centralized servers and domain names for some aspect of their operations. For this reason, networks like Gab were easily attacked and taken offline by the big tech cartel, due to their growing influence over conservatives and the droves of users that were leaving these network for the freedoms Gab provided. 

dSocial, as you will see in this paper, is built to scale the globe without centralized servers or centralized TLDs (top-level domain names) and is based entirely on peer-to-peer technologies like blockchain, the DPOS consensus algorithm and a Kademilia DHT-based storage network [RICE19A]. Consequently, dSocial is far more secure for its users when compared to centralized alternatives and is virtually impossible to seize or take offline. dSocial is being open sourced and poses a true threat to all centralized social networks beyond just the economic incentive given to dSocial's users for posting to its network. Instead of reshaping the nature of truth, as the centralized social networks of the Internet are taking part in today, dSocial is reinstating the freedoms and constitutional rights that its users truly deserve and expect.

It's time for ethical software developers to ban together, while putting all politics aside, to ethically develop technologies that benefits their end-users once again. Otherwise, the big tech cartel and the centralized web's regime will continue to attack our freedoms through misinformation campaigns and the constant attack of free thought and ideas, which will ultimately result in an enslaved society, hell-bent on socialism, where all of its users are in-turn censored and controlled by the swamp itself. This means abandoning these centralized tyrants and their development platforms, in order to build our own decentralized alternatives.

This paper is intended to start a decentralized revolution.

## Abstract
dSocial is the world's first truly decentralized social network that (a) is impossible to seize, hack or exploit; (b) is not reliant on centralized servers or domains; (c) is not completely reliant on blockchain technology; (d) pays its users for their interactions; (e) is protected against illegal or inappropriate content by a meritocratic republic formed and voted on by its users; (f) is completely censorship-resistant; (g) is infinitely scalable.

These features are made possible through dSocial's integration with various peer-to-peer technologies and protocols, namely [Arisen](https://github.com/arisenio/technical-whitepaper), [dWeb](https://github.com/distributedweb/whitepaper), [dRegister](https://github.com/distributedweb/ddatabase-whitepaper) and [dAppDB](https://github.com/distributedweb/dappdb-whitepaper). dSocial is a Twitter-like social networking platform that has a similar feature set and user experience, including posting, post commenting, re-posting, post interaction (i.e likes, etc.), direct messaging, user subscriptions (following), user blocking, and the ability for users to earn various decentralized, cryptographic currencies like "RIX" and "LIKE" for their interactions. In the future, dSocial will be integrated with a decentralized bank known as [dBnk](https://dbnk.network) which will allow users to earn for their interactions with many popular, decentralized cryptographic currencies, including Bitcoin, Ethereum, Litecoin, EOS and many others. 

dSocial represents the software of the future, one where freedom is a catalyst and the single greatest feature for its users. It also brings to life the ideologies of a constitutional republic, where users are once again in control of everything from their digital existence on the network, to the data they create. dSocial represents the idea, that if we're able to build more decentralized applications like dSocial across a multitude of industries, that the web can once again be free for its users and a place for us to grow our businesses and safely share our personal lives with those we love and care about. It's a future we're currently developing and a system that I will explain thoroughly throughout this paper.

## Table Of Contents
[Protest](#protest)
[Abstract](#abstract)
[Table Of Contents](#table-of-contents)
[Introduction](#introduction)
[The Decentralized Application](#the-decentralized-application)
- [Decentralized UAL](#decentralized-ual)
- [Blockchain-Based Application Execution](#blockchain-based-application-execution)
- [Blockchain-Based Data Storage](#blockchain-based-data-storage)
- [Off-Chain Distributed Media Storage](#off-chain-distributed-media-storage)
- [Decentralized Reporting System](#decentralized-reporting-system)
- [Decentralized Network Addressing](#decentralized-network-addressing)
- [The dSocial dTLD](#the-dsocial-dtld)
- [Built-In Decentralized Cryptocurrency Banking System](#built-in-decentralized-cryptocurrency-banking-system)
[On-Chain Actions](#on-chain-actions)
- [post](#post)
- [comment](#comment)
- [repost](#repost)
- [upvote](#upvote)
- [pimage](#pimage)
- [pheader](#pheader)
- [message](#message)
- [favorite](#favorite)
- [pin](#pin)
- [hide](#hide)
- [follow](#follow)
- [unfollow](#unfollow)
- [media](#media)
- [block](#block)
- [system](#system)
- [delete](#delete)
- [deactivate](#deactivate)
[Application Layout](#application-layout)
- [Account Creation & Login](#account-creation-login)
- [Feed](#feed)
- [Profile Page](#profile-page)
- [Direct Messages](#direct-messages)
- [Followers](#followers)
- [Following](#following)
- [Media](#media)
- [Wallet](#wallet)
[Application Features](#application-features)
- [Censorship-Resistant](#censorship-resistant)
- [A Social Economy](#a-social-economy)
- [Self-Policing](#self-policing)
- [Completely Server-less](#completely-server-less)
- [DDOS & Hacker Resistant](#ddos-hacker-resistant)
- [Cross-Platform](#cross-platform)
- [True Privacy](#true-privacy)
- [User-Controlled Data](#user-controlled-data)
[Conclusion](#conclusion)

## Introduction
**NOTE:** A programmer who steals the work of another is called a **forker** and one who takes from the works of ***many*** in order to develop something entirely different, is known as an **inventor**. I say all of that to say that our team is deeply indebted to the inventors who invented many of the individual components that make up the decentralized software development framework we've invented. It is that framework that has allowed us to develop applications like dSocial and we are eternally grateful for their passion and hard work. Without them, this project simply wouldn't be possible.

Does the world really need another social network? I have struggled with this question for years. The Internet is sheer proof that there is no shortage of social networks, in fact, there are too many. There isn't a shortage of decentralized social networks either but most, if not all of them, have been ignored by the mainstream media and have very few users as a result. A lot of that has to do with most of these "dApps" (decentralized applications) having a very complicated user experience. Most importantly, as discussed in the [protest](#protest) section, none of these are ***truly*** decentralized and if they ever did become a threat, could certainly be taken offline in various ways. Ways, if you know my story, I'm pretty well aware of - in fact - I'm a victim of it.

I have spent years researching many computer science fields, from wireless communications and systems to data and computer communications, all to end up tinkering with many peer-to-peer protocols including popular distributed hash table-based protocols like Chord, CAN, GISP, Kademilia, Pastry, Tapestry, Viceroy and others. That journey led me to the realization that by developing software that utilizes the simple and elegant design of a distributed system, we can develop applications that have better performance, stronger security and dramatically less overhead. Distributed systems are decentralized for the most part and do not rely on the typical Client/Server model (C/S Model) [LITW96]. As you can probably imagine, all of dSocial's features - from the files of the application itself, to the domain name used to access the application, are completely distributed across DHT and blockchain-based systems, rather than centralized systems. Not only does this dramatically improve performance and security, it also improves the scalability and efficiency of applications, which in-turn dramatically lowers the operational overhead of these applications. It also means that finding a central point of failure in an application like dSocial is like finding a needle in a haystack. If only that needle, in this case, actually existed - in other words, there isn't a single central point of failure. dSocial also uses many "off-chain" networks for much of its functionality, to insure that blockchain-based execution costs are kept to a minimum, so users of dSocial can reap the true economic benefits from their interactions with other users on the network.

All technicalities aside, the user experience (UX) surrounding these systems is just as important. A decentralized social network that finally achieves mass adoption will require a simplified user experience that most, if not all of the decentralized applications currently being used, truly lack. It has been difficult for developers to achieve this feat, considering that most of the complex functionality these systems feature, in most cases, requires some sort of cryptographic-based authentication. We have worked hard at [Peeps](https://peepsx.com) to develop tools like [PeepsID](http://peepsid.com), which allows users to seamlessly execute actions on a blockchain (like posting on the network), while "signing" those executions with their cryptographic identities, without actually realizing they're doing so. Instead of end-users (who have no idea what cryptographic keys are) having to figure out how to use these keys or having to use these keys every time they execute actions within the application itself, PeepsID does all of this heavy lifting for them. This way, end-users simply feel as if they're using the applications they use every single day - while also being able to benefit from the freedoms distributed systems and decentralized applications bring to the forefront. 

This paper is intended to explain the many features of dSocial and if you notice, all of these features are made for anyone to use, while also making sure the application itself remains completely decentralized throughout the entire user experience. It has long been my goal to make sure our apps are useable by anyone so that we could create change across the globe in ways software was intended to, while also using decentralized systems that in-turn distribute freedom to those who truly need it, rather than centralized systems that eventually become corrupted and abused over time. Although, it is important to note that building a user-experience that ***anyone*** can use with ease, which functions on top of multiple distributed systems, is no easy task. As a result of that fact, this project has taken us years of research, thousands of man hours to develop and has been refined over and over again until our vision finally found its way to the screen. With all of that said, I'd like to introduce all of you to the world's first truly decentralized social network, dSocial, otherwise known as  "The People's Network".

## The Decentralized Application
dSocial is a decentralized application which means it is made up of many moving parts, from its own universal and decentralized authentication layer to several on-chain (blockchain-based) and off-chain (non-blockchain-based) service layers that allow for it to operate with true end-to-end decentralization.  In order for someone to understand how an application can possibly operate this way without a single central point of failure or any bottlenecks for that matter, one would have to understand the components of a decentralized application like dSocial and how it's able to function and ultimately live through the people who use it. The following sub-sections cover the components that make up the dSocial application.

### Cross-Platform UAL
The most important part of a decentralized application is how it authenticates the "actions" of its users. dSocial utilizes an application known as PeepsID and its universal authentication layer (UAL), which is layered on top of the Arisen blockchain for the purpose of simplifying the user authentication process. Like with all Peeps applications, users log into dSocial with their PeepsID, which is simply an account on the Arisen blockchain. Arisen accounts, unlike most blockchain-based accounts use human-readable names (@username), where each account can have a virtually unlimited amount of permission levels that can be programmatically used to authenticate specific actions, within specific applications (i.e. in dSocial, the "posting" permission is used for the [post](#post) action). Every PeepsID has an ```owner``` and ```active``` permission level, where the ```owner``` permission level essentially has "root" or "superuser" access to an account and can update the cryptographic keys related to the permission levels beneath it (like the keys related to the ```active``` permission level or levels below it). For example, if you were to give someone the keypair related to the ```posting``` permission level, which only allows the key holder to execute the [post](#post) action on dSocial (post on a dSocial account), the individual who possesses the ```owner``` keypair could easily change the ```posting``` keypair, thereby blocking the individual who is utilizing the previous keypair.

dSocial, for the security and potential future use-cases of the platform, also uses its own permission levels, outside of the default permission levels included with any Arisen-based account, which are explained below. 

**Note:** ***dSocial-specific permission levels like the access levels described below can only be used with the dSocial application and do not give a user access to do anything else outside of their designed purpose within dSocial (ex. these permission levels cannot request a ride on dRide or send cryptographic tokens via dBnk, etc.).***

#### ```socialx```, ```posting``` and ```postingx``` Permission Levels
The ```socialx``` permission level is the highest possible permission level that can access the dSocial application (other than the ```owner``` and ```active``` permission levels) and can be used to execute any [on-chain actions](#on-chain-actions) within dSocial's smart contracts (i.e. on-chain executable portions of the dSocial application). Also, the ```socialx``` permission level can be used to reset any of the permission levels beneath it.

The ```posting``` permission level only allows a user to execute the [post](#post) action while the ```postingx``` permission level allows extended access, which enables an end-user to execute the [post](#post), [comment](#comment), [interact](#interact), [repost](#repost) , [pin](#pin), [favorite](#favorite), [follow](#follow), [unfollow](#unfollow) and [message](#message) [on-chain actions](#on-chain-actions). As an added example, this allows the ```posting``` or ```postingx``` permission levels to be handed out to a social media marketer or digital marketing agency, without giving them access to permission levels that in-turn give a user access to more sensitive areas of a user's account.

#### Vanity Permission Levels (VPLs)
dSocial users can create their own custom permission levels known as "vanity permission levels" or "VPLs", which can be tied to any custom grouping of dSocial's [on-chain actions](#on-chain-actions). The beautiful thing about dSocial is how it generates cryptographic keys for each dSocial-related permission level or VPL and securely imports these keys into PeepsID, without the user ever realizing it. 

More on how PeepsID utilizes these keys to sign specific [on-chain actions](#on-chain-actions) is explained in-depth in the sections that follow. Any account with any dSocial-related permission-level can login to the dSocial application but will only be allowed to utilize the features that are related to the permission level they logged in with.

#### The Signup Process
When creating a dSocial account, as stated previously, a user actually has to create a PeepsID. A PeepsID can be created via the PeepsID [account creation service](https://signup.peepsid.com) or via dSocial's [dedicated signup system](https://signup.dsocial.network). 

**The process for creating a PeepsID is as follows:**
1. The signup service always checks if the PeepsID application is installed on a user's device. If not, it directs a user to quickly download the latest version of the PeepsID app for a user's specific operating system.

2. The PeepsID signup service is designed to wait until a user installs the PeepsID app on their device, before proceeding with allowing a user to reserve their PeepsID. Once installation has been finalized and the PeepsID application has been detected, the PeepsID signup service proceeds to allow a user to type in their username of choice.

3. A user types in a @username (usernames must be between 0-12 characters).

4. If the username is available, keypairs (public/private keys) are generated for the ```owner``` and ```active``` permission level and the account and the public keys related to the account's ```owner``` and ```active``` permission level are sent to the Arisen blockchain for registration. (NOTE: RIX costs related to user registrations on Arisen for PeepsID-based registrations are sponsored by @peeps).

5. The private keys, along with the account information (username, etc.) are imported into the PeepsID app in the background. (Note: keypairs are never shown to a user for security purposes and this remains standard across all Peeps applications).

6. User is notified that their PeepsID has been created and that their keys have been successfully imported into the PeepsID app.

In short, registration happens in seconds once the PeepsID application is installed and subsequently setup, where the keys associated with an account's permission levels are seamlessly imported into the PeepsID app without any required action from the end-user whatsoever. As you will see in the next section, this significantly simplifies the login process. 

#### The Login Process 
The login process for a decentralized application is a bit different than that of a centralized application, especially since passwords are technically private keys and most decentralized accounts have a private key for each of the possible permission levels (including VPLs) that an account may possess. The [PeepsID application](https://peepsid.com) has to be downloaded on any machine where a user is using Peeps applications and is used to dramatically improve the user experience while also simplying the login process for Peeps applications. 

**The process for logging into dSocial is as follows:**

1. dSocial contacts the PeepsID application and asks it which accounts and their corresponding permission-levels have been imported and securely stored within it. It returns the account usernames and each account's related permission levels to dSocial. (NOTE: When creating a PeepsID via the account creation system and when you first sign into dSocial, permission levels like ```owner```, ```active```, ```socialx```, ```posting``` and ```postingx```, as well as their corresponding keys are automatically imported into the PeepsID application and will be available for use when a user logs in. Outside users like a digital marketing agency could manually add an account and its corresponding ```postingx``` permission level, for example, for each of the clients they manage, since the PeepsID application also allows accounts and keys to be manually imported as well. 

2. dSocial presents the user with a dropdown of all of the available accounts they can sign into dSocial with.

3. After selecting an account (one is selected by default), beneath it, where you would normally find a form box for typing a password, another dropdown appears where the end-user is able to select the permission-level they're going to use in their dSocial session, that is related to the @account chosen in (2).

4. Once a user clicks login, dSocial sends a ```verify``` action to PeepsID, that PeepsID must sign with the specific private key related to the permission level of the account the user is attempting to login with. The PeepsID application stores keys on an offline subnet on the end-user's device, so that the transactions it receives can be securely signed by the specified keys and a serialized version of the signed transaction can then securely be broadcasted out the Arisen blockchain for verification. 

**NOTE:** ****If you don't understand how digital signatures work or how they're mathematically impossible to forge, you will have to read more about Elliptic Curve Cryptography and how the Arisen blockchain utilizes ECDSA-based math to verify transactions via digital signatures.***

The PeepsID application will only initiate the "signing process" if a user can verify a pin number (via desktop devices) or static biometrics (via biometric-capable desktop and mobile devices). This is because all private keys imported into the PeepsID application are encrypted with either a pin number or the serialized output of a user's biometric data (a user sets this up when they first download the PeepsID application).

In short, a user clicks "login", a unsigned transaction is sent to PeepsID, the user's device immediately opens the PeepsID application where they're asked to verify a pin number or their thumbprint. Once verified, the specific private key is decrypted within an offline "key vault" on the end-user's device, the transaction is securely signed and subsequently broadcasted to the Arisen network. PeepsID sends the transactionID of the verified transaction back to dSocial, where dSocial is able to verify the user attempting to login has the required credentials to access dSocial for a given account, along with a particular permission level.

While this sounds like it takes a long time, transactions are confirmed within 0.5 seconds (a half of a second) on the Arisen blockchain and the decrypting of keys and the broadcasting of a signed transaction takes an additional 0.5 seconds. On average the total time for a user to login takes 1 second, plus however long it takes for the use to enter a pin number or verify their fingerprint. 

**It's also important to note that all a user ever sees is:**
- (a) the login screen, where they select an account and an associated permission level.
- (b) a screen via PeepsID asking a user to verify their PeepsID-based pin number or biometrics.
- (c) the [feed](#feed) screen, where they're immediately switched back to after verifying with PeepsID, signaling a user has logged-in successfully.

This creates a very comparable login experience to that of centralized applications.

As you will see in the next section, every time a user executes an action within dSocial (ex. post, comment, interaction, follow, unfollow) the action must be signed and transmitted to Arisen for not only authentication but for the purpose of storing the data related to the action, so that data can be retrieved at anytime by the dSocial application itself. This means unauthorized actions can never take place on dSocial, which also means hackers have no way of gaining access to accounts or taking part in rogue or illicit activity within the dSocial application itself. This is the advantage of using a blockchain and asymmetric cryptography (public key cryptography) for user authentication.
