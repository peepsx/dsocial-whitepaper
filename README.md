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

### Blockchain-Based Application Execution
The code related to a lot of dSocial's functionality is located on the Arisen blockchain within various smart contracts stored under the [@peeps](https://explorer.arisen.network/accounts/peeps) account. This is due to the fact that some functionality is related to specific [on-chain actions](#on-chain-actions) that require user authentication via PeepsID and the data that derives from these actions must be stored on-chain alongside the account that is executing the action.

When dSocial calls for a specific action to be executed on Arisen, a specific private key related to a specific permission-level is required to sign a transaction that derives these on-chain actions. Just like the login process, this is handled via the PeepsID application, where a user simply verifies a pin code or biometric data, the transaction related to the action is signed, subsequently broadcasted to the Arisen network and the data that derives from the action is stored across all peers on Arisen's network within dSocial's on-chain multi-index database. Data within dSocial's on-chain multi-index database can be retrieved from any Arisen blockchain node, via Arisen's RPC API, at any time. dSocial keeps a constantly updating list of Arisen nodes, so that API requests to these nodes can be properly load balanced for absolute redundancy and for performance purposes as well.

Specific functions within dSocial's application that are executed on the Arisen blockchain, include:
- Posting
- Commenting
- Interacting with a post or comment (reacting to a post, for example, liking a post)
- Reposting a post
- Upvoting a post or comment 
- Messaging a user
- Favorite posts
- Pinning a post
- Following a user or unfollowing a user
- Blocking a user
- Updating a profile image or profile header image
- Hiding a post from public view
- Deactivating a profile

By using a blockchain like Arisen as a way of carrying out these actions, we're able to insure that:
a) hackers cannot impersonate users or carry out unauthorized actions.
b) data associated with these actions is stored immutably across potentially thousands of blockchain nodes across the world (and soon, space...).
c) dSocial can retrieve data from any of these nodes easily without there being a single point of failure or any bottlenecks.
d) the code behind specific dSocial features is openly stored on the blockchain, where anyone can see it and where every single executed action can also be seen and verified via the blockchain's ledger. This creates trust amongst the users of dSocial and insures dSocial remains censorship-resistant.
e) accounts that take part in the distribution of illegal content (pornography) or illegal activity can be frozen and removed from the network by a 15/21 vote of Arisen's elected governance (more on this in [Decentralized Reporting System](#decentralized-reporting-system).

### Blockchain-Based Data Storage
It was pointed out in the previous section that the data that derives from [on-chain actions](#on-chain-actions) are stored on the blockchain as well. dSocial uses an on-chain multi-index database, which allows dSocial to easily store and retrieve data at anytime, rather than a central database that can be attacked by rogue actors.

Typical data that is stored on-chain, includes:
- Data related to 140 character posts.
- Data related to 140 character comments (replies).
- Every interaction (like, etc.)related to a post_id.
- Data related to 140 character messages.
- Data related to an upvote (RIX amount, user upvoting, post_id or comment_id being upvoted).
- Data related to a favorite post (post_id and the user initiating the [favorite](#favorite) action).
- Follower data related to a particular account.
- dWeb-based discovery keys of dDrives that contain a profile image or header image for a particular account (more on this in [Off-Chain Distributed Media Storage](#off-chain-distributed-media-storage).).
- dWeb-based discovery keys of dDrives, which contain the media (images, videos, audio, etc.) attached to a post (more on this in [Off-Chain Distributed Media Storage](#off-chain-distributed-media-storage).).
- Data representing the post_id(s) that dSocial should no longer retrieve from the blockchain.
- Data representing accounts that should be "blacklisted" or "deactivated" and ignored by the dSocial application.

### Off-Chain Distributed Media Storage
Essentially, dSocial utilizes a blockchain for:
- Executing portions of an application that requires trust, authentication, storing data that needs to be retrieved at a later time by dSocial users or for some sort of economic functionality within dSocial that involves a blockchain-based currency (i.e. RIX or LIKE). 
- Accounts, account authentication, validation of digital signatures and account permissions.

Although, dSocial cannot rely on a blockchain for everything, especially large pieces of data. For this reason, dSocial was integrated with the dWeb protocol. The [dWeb protocol](https://dwebs.io) has given birth to several components and sub-protocols that make up the other half of the decentralized web's software development framework that we used to develop dSocial. dWeb's protocol is designed to operate over a Kademilia DHT-based network and is simply responsible for sharing a folder full of files with a network of participants (like a Torrent network). It's what we're doing with those files that has helped form the decentralized web and a truly decentralized social network like dSocial. 

#### The dWeb DHT
While a lot of data created by dSocial users is stored on-chain, large pieces of data (images, videos, audio files, etc.) are stored and distributed off-chain. In order to do this, dSocial utilizes many of dWeb's off-chain, peer-to-peer services, as well as various DHT-based networks. dSocial uses multiple DHT-based networks, which provides true off-chain redundancy to dSocial in the nearly impossible event that one of these key-value stores were to go offline (i.e. millions of users, all at once, decide to leave the network and all of its data behind). Just as BitTorrent and other DHT-based networks will never go offline, neither will dWeb's DHT-based network. In effect, the more users who use apps on the dWeb, the more and more redundant the network becomes, since data is shared amongst all of the computers that are using these applications, while these peers and their network location is stored in a key/value format across multiple DHTs.

In short, if the dWeb was only made up of two apps, App(A) and App(B) and App(A) has 1,000 users, while App(B) had only 500 users, the data from both dApps is redundantly available across 1,500 computers and the information needed to locate these computers is located across multiple DHT-based networks which could be made up of millions of computers around the world. All of these computers would have to stop using these respective applications, all at one, before new users join in and create replicas of the data from one of the remaining nodes on the network, to effectively take the network down. At the very same time, all of the DHT-based networks where this peer information is stored would also have to die, to where peers for a particular dataset, could not possibly be located.

#### Introducing The dDrive
When a user posts to dSocial, while including specific media files (can be multiple files per-post), dSocial actually takes those files and moves them into a folder named after the ```post_id``` of a given post on the end-user's local machine. This folder is typically a sub-folder within a folder called "dsocial-drives". Each sub-folder related to a post is essentially an instance of a [dDrive](https://github.com/dwebjs/ddrive), which is a virtual distributed file system. Before one can understand how post media is shared efficiently off-chain, they would have to understand how a dDrive works. 


**A dDrive works just like a torrent, minus a few key points:**
a. dDrives can be found and accessed publicly by users other than the creator, only if it is announced and broadcasted to the dWeb network. Otherwise, the dDrive is only accessible from the creator's machine.

b. dDrives feature true content integrity, which means that the protocol is designed to verify that the data received, is the data that belongs to the dDrive being requested. Like blockchain-based authentication, this is made possible using public key cryptography. This is important in a distributed system, as this mechanism will catch incorrect data sent by bad peers. This also allows for reproducibility as well, allowing the dSocial application to refer to a specific version of a dDrive (a version of a file within a dDrive).

c. All messages in the dWeb protocol are encrypted and signed by the dDrive's public key while in transport. This means unless you know the discovery key (e.g. unless the dWeb link was shared with you [dweb://8e1c718...]) then you will not be able to discover or communicate with any member of the flock (group of peers seeding a dDrive). Anyone with the public key of a dDrive, can verify that messages such as entries in the dDrive's stream, were created by the holder of the private key. 

Every dDrive has a corresponding private key which is kept on the end-user's device and is never shared for any reason. dWeb's protocol never exposes a dDrive's public or private key over the network. During the discovery phrase, a "BLAKE2B" hash of the public key is generated which becomes the dDrive's "discovery" aka "revelation" key. This means the original key is impossible to discover, since only a one-way cryptographic hash function of the key is announced to the network. In simple terms, a hash function is "any function that can be used to map data of an arbitrary size, to data of a fixed size per [WOOD17]. Simply put, a cryptographic hash function is a one-way hash function that maps data of an arbitrary size to a fixed-size string of "bits". 

The "one-way" nature means that it is computationally infeasible to recreate the input data, if one only knows the output hash (in this case the dDrive's public key). The only way to determine a possible input is to conduct a "brute-force" search, checking each candidate for a matching output. Given that the search space is virtually infinite, it is easy to understand the practical impossibility of the task. dWeb's protocol, rather than an authentication system, provides a "capability system". In other words, anyone with a dWeb link (the discovery key) is currently able to discover a dDrive and access the files within it. If a user doesn't want a dDrive to be accessed, they shouldn't share the discovery key, although, it is important to understand that unless a post is marked "private", dDrive discovery keys are publicly streamed over the dSocial application, where the public key can be accessed in order to verify a dDrive's integrity. 

A dDrive's storage, content integrity and networking protocols are implemented in a module known as a [dDatabase](https://github.com/dwebjs/ddatabase). A dDatabase is agnostic to the format of the input data and operates on any stream of binary data. A dDrive is simply a module on top of a dDatabase. A dDatabase is basically a binary representation of the files within a dDrive, essentially forming a distributed file system that can be shared amongst peers [RICE19B]. "dDatabase Registers" are the most important part of the dWeb specification. dWeb's protocol uses two registers simply known as "content" and "metadata". Registers are binary "append-only" streams whose contents are cryptographically hashed and signed and therefore can be verified by anyone with access to the public key of the dDrive's creator. They are an implementation known as a "register", an "off-chain" digital ledger that can truly be trusted. The "content" register contains the binary representation of the files within a dDrive and the "metadata" register contains the metadata about the files including name, size, last modified time, etc.

dWeb's specification is designed so that both registers are replicated when syncing with another peer. When files are added to a dDrive, each files gets split up into a number of chunks and the chunks are then arranged into a Merkle tree, which is used later for version control and replication processes. This means when syncing files with peers, they don't need to have access to an end-user's computer to receive the files, nor will they ever have access to the end-user's computer. Peers simply share a dDatabase (binary representation of files), between each other and when the receiving peer receives a dDatabase, it is then converted into usable files. Simply put, the binary of picture.jpg file is represented in a binary format in a dDatabase, but a dWeb-integrated system like dSocial is able to convert this binary into the actual picture1.jpg file or in other words, into its original state as it's found on the dDrive creator's computer.

#### How Media Is Shared Amongst Users Without Central Servers
As soon as a peer acquires the first piece of data from a dataset (dDatabase) they can become a partial mirror (seeder) of the dDrive. If another peer (a dSocial user) contacts them for that particular piece, they can choose whether or not they want to share it.

dSocial when it comes to off-chain media storage, utilizes three methods for peer and dDrive discovery:
a. On-Chain dDNS - Used for resolving dWeb keys to specific addresses 
b. Multicast DNS - Useful for peer discovery on local networks
c. Kademilia Mainline Distributed Hash Table (DHT) - Eliminates central points of failure and keeps the decentralized web's off-chain storage network running in the event dWeb's on-chain dDNS records are unreachable. Multiple DHT-based networks are used for absolute redundancy, insuring dDrive records are forever accessible

**The posting and discovery process for off-chain media on dSocial is as follows:**
1. A dSocial user creates a post with two pictures (picture1.jpg and picture2.jpg) and a video (video1.mp4) that says "Here is proof Hillary colluded with Russia.". 
2. dSocial moves the two pictures and video into a folder (dsocial-drives/<post-id>) along with generated thumbnails of images and video and then creates a local instance of a dDrive.
3. dSocial announces a key/value pair of the dDrive discovery key to multiple DHT-based networks, along with the value of the user's peer address and stores the same key/value via dWeb's on-chain dDNS system (on the Arisen blockchain). 

NOTE: It is important to note that at the moment this takes place, these files are accessible via dweb://<ddrive-discovery-key> from any dWeb-ready client like [dBrowser](https://dbrowser.com) or [dWebCLI](https://github.com/dwebjs/cli).

4. dSocial attempts to execute the [post](#post) [on-chain-action](#on-chain-action) by first authenticating the user executing the action, along with their given permission level via PeepsID and subsequently, Arisen's network. Once authenticated, the [post](#post) action is executed and signed by the user's permission level specific keys, where the ```post_data``` is then stored in dSocial's multi-index on-chain database under the ```posts``` multi-index table, along with the generated 32-byte ```post_id```, the ```post_user``` and the ```post_media```, which is simply the discovery key of the dDrive where a post's media can be found.

5. The post can now be found within the dSocial application. dSocial is able to show the media from within a dDrive since dSocial is highly integrated with [@dwebjs/core](https://github.com/dwebjs/core). The video can be streamed within dSocial's built-in video player as well, which is specially designed to stream dDrive-based videos and other media files.

#### Parallel and File-Specific dDrive Downloads
As a user scrolls through their feed or through a user's profile, they're are certainly going to come into contact with multiple off-chain media sources (multiple dDrives). For performance purposes, dSocial is designed so that multiple dDrives can be streamed or downloaded in parallel. As a feed is loaded, whether on the feed page, search feed page or a user's profile page, only eight posts are shown at a time. This means at most, the media held within eight dDrives is downloaded or streamed at a given time. It is important to note, that dSocial is designed to only download the pre-generated thumbnails of much larger media files within these dDrives, instead of downloading or streaming all of the files within all of the dDrives in order to increase performance. If a user wants to view the actual media (non-thumbnail version), or stream a video, they simply click the image thumbnail or video thumbnail within the post and it can be streamed or downloaded to the dSocial application.

**For each dDrive that is discovered via dWeb's on-chain dDNS system or via a DHT-based network, the following takes place:**

1. dSocial forms a list of the potential peers that have the data of a dDrive being requested and attempts to connect with them to exchange a dDatabase. 

**NOTE:** Since dWeb's protocol is transport agnostic, dSocial is able to utilize both the UDP and TCP protocols when connecting to specific peers of a dDrive. Whichever creates a connection first (UDP or TCP), dWeb's protocol is designed to abort the other. If none connect, dSocial will try again until it believes the dDrive's source is offline or unavailable and stops trying to connect to the source(s). Sources dSocial is able to successfully connect with, end up in a list of "good-sources", so that if an internet connection goes down, dSocial can use that list to reconnect to known good sources again, quickly, once the internet connection is active once again. If dSocial receives many potential data sources for a dDrive, it picks several at random to connect with and keeps the rest around for future cases where more sources are needed.

2. Once dSocial has successfully connected to a remote source or remote sources, a "duplex binary connection" between the sources and the local instance of the dSocial application fetching the dDrive, is opened. dSocial then layers on the dDatabase protocol, a message-based replication protocol, which allows two peers to communicate over a state-less channel, where both are able to request and exchange data from each other. dSocial opens a separate channel for each peer of a dDrive, so that pieces of a dDrive can be fetched in parallel from multiple peers, ultimately allowing the thumbnail-based contents (images, videos, etc) of a dDrive to appear instantly in a user's feed. 

#### dDrive Access Capabilities
A dDrive has the following "access capabilities":
- Support large file hierarchies (millions of files in a single dDrive).
- Support efficient traversal of a dDrive file system's hierarchy.
- Store all changes to files.
- List all changes made to a single file. 
- View the state of all files relative to any point in time.
- Subscribe to changes of a dDrive (live), one of its files or a file under a specific path.
- Efficiently access any byte range of any version of a file.

#### The Network That Will Never Die
Simply put, dDrive and dDatabase's protocol brings to life a truly distributed file system which enables applications like dSocial and their users to share large datasets like videos, images and other media files efficiently across a massive peer-to-peer network. A network, that one could easily come to the conclusion, is virtually impossible to take offline. In fact, if one million users are using dSocial, it is safe to say that one million nodes will store dDrive discovery keys and the location of one million peers who possess potentially billions of fragments (that make up millions of files), related to millions of dDrives. Over the past decade, extensive work has been done to various DHT protocols. In academia, researchers have proposed numerous variants of DHT and improvements, which manage the resources in many kinds of structures which in-turn has provided an abundance of choices for the construction of a distributed system. At Peeps we have worked with many platforms that have brought DHT from theory to practice, where practical problems such as load balancing [CORA20, HAZE20], multiple replicas [LAKS10, IBM20], consistency [BAMB20, DECA07, SHI09], latency [LAKS10, SHI09] and security [CODE20, GNUN20] were solved. In DHT, the server is not  needed any more and allows dSocial to operate in a fully decentralized way, since the users of dSocial are responsible for the distribution of all of its off-chain media. 

Kademilia-based DHT structures are the most popular DHT structure-type and is the structure used by dWeb's specification, as well as dSocial's application. Kademilia is also used by services like [Overnet](https://overnet.org), [BitTorrent](https://bittorrent.com), [eMule](https://emule.org) and other peer-to-peer services. Centralized applications such as Facebook and Skype use various DHT platforms for critical portions of their centralized applications as well. In fact, Facebook originally designed the Cassandra project [LAKS10] which is an open-source DHT-based structure, much like Kademilia. Companies like Cisco, IBM and Amazon have also released proprietary DHT-based protocols that are used as internal tools for many of their critical services. In short, dSocial uses battletested protocols and DHT structures so that it can provide off-chain storage that is much more trustworthy and efficient than centralized alternatives. It also allows dSocial to operate in a fully decentralized way.

### Off-Chain Application Distribution
In a decentralized application, smart contracts are used to store the business logic (program code) and the related state of the application. You can think of a smart contract replacing the server-side (aka "backend") component in a regular application. This is an over-simplification of course. One of the main differences is that any computation executed in a smart contract is very expensive and consequently smart contract-based executions should be kept to a minimum. It is therefore important to identify which aspects of an application needs a trusted and decentralized execution platform.

#### How dSocial's Application Is Distributed
- dSocial's application is being written in ReactJS and React-Native which means its a JavaScript application, which also means it can run completely from any web browser.

**NOTE:** Aside from compiling the web version, this same codebase is also used to compile dSocial's desktop version (Windows, Linux, MacOS and [PeerOS](https://github.com/peepsx/peeros-whitepaper)) and dSocial's mobile version (iOS and Android). 

- Much of the application code is not related to [on-chain actions](#on-chain-actions) which means it is not stored on-chain, instead dSocial's web-based application files are instead stored in a dDrive.

- Web browsers like [dBrowser](https://dbrowser.com) are made to view a dDrive that contains a website or web application's files via a dDrive's discovery key, which can be thought of as a dWeb URL, which takes on a format like:
```dweb://867fdc4389b1b2dbb5c3ec259378788477120dsa8...```

- dBrowser is also compatible with [dNames](https://dnames.network), which is a decentralized domain name register where developers can soon register decentralized top-level domains (dTLDs) like .dcom, .dnet, .dorg, etc.. Developers can create DNS records for these dTLDs that point directly to a dDrive. Decentralized domains are made possible by the Arisen blockchain, which are essentially account names, in front of bidded-on account suffixes (*.dcom). dSocial, when launched, can easily be accessed via dBrowser via its own dTLD:
```dweb://dsocial.dcom```

- When a user logs into dSocial, they login with the PeepsID application as discussed in [Cross-Platform UAL](#cross-platform-ual). This does not require any executions on Arisen, since dSocial simply uses the [ArisenJS](#) library to access Arisen's open and distributed API to authenticate the user with Arisen's network (although sometimes a ```verify``` action is used). All API actions work this way and gladly, dSocial's application for the most part queries Arisen's API for a majority of the data dSocial requires for user requests (posts, dDrive discovery keys, comment data, upvotes, follower information and more as explained in [Blockchain-Based Data Storage](#blockchain-based-data-storage)). Thankfully dSocial does all of this from the end-user's device from within an application or a dWeb-ready web application via dBrowser. This is data that was stored on-chain from previous executed [on-chain actions](#on-chain-actions), so no further executions are needed, only a simple query to [Arisen's RPC-based API](https://docs.arisen.network). 

- When a user posts, comments or upvotes a post, it's important that users trust that these actions came from a specific account and so specific actions like [post](#post) were created. These actions require the input of data (as explained in [Off-Chain Distributed Media Storage](#off-chain-distributed-media-storage)), which is then stored on Arisen's blockchain so that this data can be retrieved by dSocial's application at anytime. The ```post``` action must be signed by the @account initiating the action, proving ownership of the data and that a specific account did in-fact submit it. These actions on Arisen may make up 200 lines of code and are specifically written to work with Arisen's internal APIs. Therefore, they are not full-fledged programs. It is better to view Arisen-powered programs (smart contracts) as simply "actions" or "functions" of a much larger application, because nine times out of ten, they are.

- Simply put, 97% of dSocial's functionality takes place on a user's computer and the other 3% which requires authentication and/or distributed storage, take place on Arisen's blockchain or via dWeb's peer-to-peer file storage network.  Keep in mind that these actions are executed via ArisenJS, which packages actions into transactions that are in-turn broadcasted to Arisen's world computer (the Arisen Virtual Machine), which then stores the data that derives from the action, in dSocial's on-chain multi-index database, which dSocial can query for data at anytime. 

**Since dSocial's application is 100% distributed across multiple peer-to-peer networks, it is safe to say that:**
1. It is far less likely dSocial can be DDOS'd or suffer from DOS-style attacks when compared to centralized social networks like Gab, since hackers can identify central points of failure on those centralized networks, whereas on dSocial, there are no central points of attack for hackers to exploit.

2. Domain registrars or rogue governments cannot seize the ```dsocial.dcom``` domain name since it is a decentralized top-level domain name that is not administered by anyone. Only the elected Arisen governance can vote to remove records from a dTLD in extreme circumstances where illegal activity is taking place (more on this in [Decentralized Reporting System](#decentralized-reporting-system)).

3. The web version of dSocial cannot be seized since it's distributed in a dDrive amongst the user's of dSocial's web version.

4. dSocial's application will always be available since it operates with 100% uptime, more than any centralized application can possibly claim, since dSocial is not reliant on centralized networks of any sort. 

#### Offline Application Usage
dSocial users have the option to locally download dSocial's entire on-chain database and can also fully download all of the dDrive's fetched during their usage of the application so that dSocial can be used while a user operates without an internet connection. dSocial also allows a user to commit pre-executions of [on-chain actions](#on-chain-actions), where transactions are signed by PeepsID, dDrives are created and then placed in a queue for broadcast to their respective networks when a user's device comes back online. As a side note, this data can be cleared at easily at anytime from dSocial's [Settings](#settings).

### Decentralized Reporting System
How do members, users and developers of dSocial protect themselves from potentially illegal or otherwise morally unacceptable behavior from developers or rogue users without some sort of centralization? This is the question that advocates of centralized applications will certainly ask. The answer isn't a simple one, but at Peeps, we have worked hard developing a system called [dReport](https://github.com/peepsx/dreport-whitepaper) that helps provide protection to the decentralized applications we're building, where through the self-policing of the community, the limited and checked authority of the elected Arisen governance and dSocial's built-in AI-powered algorithms, we're able to eliminate the threat of illegal content without centralizing anything.

#### About Arisen's Elected Governance (Block Producers)
- Arisen's blockchain is a multicomputer system, currently made up of at least 21 different networks of computers, maintained by 21 "elected" block producers.
- Arisen utilizes the DPOS (Delegated Proof Of Stake) decentralized consensus algorithm, which has been proven to meet the demanding performance requirements of applications that run on a blockchain like Arisen.
- Those who hold Arisen's native cryptographic and decentralized currency known as RISE (RIX), may vote on various things that other users on the network put up for vote. Holders may also vote for block producers.
- Block producers run the Arisen software, which ultimately is used to make sure that blocks and the transactions within them are cryptographically verified. You could say a block producer on Arisen, is responsible at the very minimum for what a miner on the Bitcoin network is responsible for - propagating transactions to other computers on the network for verification and verifying a block, which simply consists of transactions.
- Blocks are created every 0.5 seconds on Arisen's network. 
- A transaction found on the Arisen network is far more complex than the transactions found on the Bitcoin network. This is because the Bitcoin network is only for peer-to-peer payments and is not capable or designed for compiling, storing and executing programs (smart contracts).
- A transaction on Arisen's network is made up of one or more executed "actions" like the [on-chain actions](#on-chain-actions) described in this paper. Each action is an instruction to be executed in a program stored on Arisen's network (a smart contract). A transaction can also be made up of multiple actions that are linked together.
- Blocks are produced in rounds of 126 (6 blocks each, times 21 producers). 
- At the start of each round, 21 unique block producers are chosen by preference of votes casted by token holders (RIX holders).
- The selected producers are scheduled in an order agreed upon by 15 or more producers.
- Once 15 producers have signed a block, it is deemed irreversible.
- Arisen is built so that the power originates with RIX-holders, who delegate that power to the block producers. The BPs are given limited and checked authority to freeze accounts, update defective applications and propose hard-forking changes of the underlying protocol.
- The election of BPs is an embedded feature of Arisen's network.
- Before any change can be made to the blockchain, these BPs must approve it.
- If BPs refuse to make changes desired by RIX holders, then they can be voted out.
- If the block producers make changes without permission of the token holders, then all other non-producing full-node validators (like dSocial's nodes on the network) will reject the change. 
- BPs have the ability to stop illicit applications and remove them from the network. 15/21 BPs must agree to do this.
- BPs have the ability to freeze accounts to recover stolen funds through a 15/21 vote. Abuse of this power will result in BPs being voted out and an account will be unfrozen.

#### About dSocial's Reporting System
In truth, potentially illegal or otherwise morally unacceptable behavior is going to happen via decentralized applications like dSocial, just as it happens via centralized applications like Facebook. The difference in how these issues are resolved is that centralized companies who have central control over centralized applications, can delete illicit content and freeze accounts, while decentralized applications are governed by a governance elected by the users of the network, as explained in the previous section. The most important difference is that when a centralized company abuses their power, a user has no recourse. With decentralized applications, users police their own communities and elect a 21 member governance to carry out their needs. If a BP or group of BPs abuse their power, they're voted out the next round. Bad people exist all over the world and they always find a place to nest and carry out their dirty deeds. Thanks to the underlying foundation dSocial is built upon, dSocial was able to develop dReport as a way for the community to report illicit activity for other community members to vote on for removal. Once a report hits a voting threshold, it is automatically sent to BPs for review via Arisen's referendum system. Emergency reports on the other hand, can be sent to BPs for immediate review. Those who abuse the emergency reporting system could have their access to dReport "blacklisted" by BPs.

#### Morally Unacceptable Behavior vs. Illegal Activity
Morally unacceptable behavior like hateful comments fall under Arisen's network constitution as "un-bannable behavior", while illegal activity like users selling drugs, is considering "ban-able behavior". While I do not agree with hateful comments, it is a user's right to make them and dSocial's software, as well as Arisen's network by-design will never interfere with that right. BPs are not prohibited to ban accounts for morally unacceptable behavior and if they did, users of the network would simply elect new BPs and reverse this action. Illegal activity on the other hand will not be tolerated and shouldn't be.

#### The Reporting Process
Every single post or comment can be reported via the "Report" button, which can be found via any post or comment in the dSocial application. Reports must be marked by their importance (General or Emergency) and their category (Illegal Pornography or Other Criminal Activity). Emergency reports must have 140 character descriptions before they can be submitted. Reports are immediately posted to the ```arisen.forum``` contract and appear for vote in the dReport dashboard, where users can vote on or follow the status of reports from all applications that use dReport's system for reports. BPs on the network can auto-sign reports that reach a certain amount of public votes, so that BPs are not bogged down with too many reports. Most BPs will certainly take advantage of this option by simply voting with those who elected them.

The decentralized reporting system insures that:
- The community can police itself
- Free speech cannot be censored
- Illegal activity and content can be quickly removed
- Users of the network determine what is accessible and what is not.

### Decentralized Network Addressing
As discussed in [Off-Chain Media Storage](#off-chain-media-storage) dSocial's web application and website do not utilize an IP address or centralized network addressing, instead it utilizes a dWeb address like:

```dweb://867fdc4389...```
and can also be accessed via the 
```dweb://dsocial.dcom``` decentralized domain name.

User profiles are accessible like so:
```dweb://867fdc4389.../@username/```
and
```dweb://dsocial.dcom/@username/```

Posts are accessible like so:
```dweb://867fdc4389.../@username/america-first/```
```dweb://dsocial.dcom/@username/america-first/```

**NOTE:** In order to access these addresses, end-users must use a dWeb-enabled web browser like dBrowser. dSocial apps for desktop and mobile do not use decentralized network addressing externally. dSocial's dWeb version of its application is the only version of the platform that uses decentralized network addressing, since dSocial is both web and app-based.

### The dSocial dTLD
dSocial has its own dTLD known as ```.follow```. Users can easily point their profile to a custom ```.follow``` domain like:

```dweb://donaldjtrump.follow```

.follow domains are free courtesy of Peeps and can be registered inside the dSocial application.

### Built-In Decentralized Cryptocurrency Bank
dSocial allows users to earn through the upvotes of their posts. For example, you can upvote your friend's post with 1 RIX, which ultimately sends that 1RIX from @youracount to @yourfriendsaccount. dSocial has a built-in cryptocurrency bank known as dWallet which can be managed within dSocial or via the separate [dWallet App](https://arisen.network/dwallet/). dWallet is integrated with PeepsID, where users can easily login and manage assets like RIX or other currencies that are earned via Peeps applications or other Arisen-powered applications. In the coming weeks, you will be able to manage Bitcoin, Litecoin, Ethereum, EOS and other currencies via dWallet as well, in the integrated version, as well as in dWallet's applications for MacOS, Windows, Linux, iOS and Android.

## On-Chain Actions
As explained in [The Decentralized Application](#the-decentralized-application) many of dSocial's most important functions are executed on the Arisen blockchain. This section is meant to cover those actions, what they do, as well as each action's optional and required parameters.

### post
The ```post``` action is used to create a post on dSocial and store its data in the ```posts``` table. Its primary index is ```id```.

#### ```post``` Parameters
- ```id``` - This is the unique id for the post. This must be 32 bytes and cannot exist in the ```posts``` or ```comments``` table.
- ```author``` - The author of the post.
- ```media``` - The discovery key of a dDrive. The dDrive must be discoverable, in other words, it must be announced on the network.
- ```content``` - The post content. Limited to 140 characters.


### comment 
The ```comment``` action is used to comment on a specific post on dSocial and stores its data in the ```comments``` table. Its primary index is ```id```.

#### ```comment``` Parameters
- ```id``` - The unique id for a comment. This must be 32 bytes and cannot exist in the ```comments``` or ```posts``` table. 
- ```author``` - The author of a comment.
- ```media``` - The discovery key of a dDrive. The dDrive must be discoverable, in other words, it must be announced on the network.
- ```content``` - The comment content, limited to 140 characters.


### interact
The ```interact``` action is used to interact with a specific post or comment on dSocial and stores its data in the ```interactions``` table.

#### ```interact``` Parameters
- ```id``` - The unique id of an interaction.
- ```type``` - The reaction type (like, love, hate, angry, shocked, sad, excited, etc.)
- ```content_id``` - The post or comment id the interaction belongs to. The id must exist in the ```posts``` or ```comments``` table.
- ```user``` - The user interacting with a post or comment.


### repost 
The ```repost``` action is used when a user wants to repost an already existent post to their own feed. It stores its data in the ```reposts``` table and its primary index is ```post_id```. 

#### ```repost``` Parameters
- ```reposter``` - The account name of the user reposting.
- ```post_id``` - The post_id of the post being reposted.


### upvote
The ```upvote``` action is used when a user wants to upvote another post or comment with a specific amount, in a specific currency. The upvote action is typically executed in parallel with the ```transfer``` action from the ```arisen.token``` contract, specifically for the purpose of transferring RIX, since the ```upvote``` action is only used for storing data related to upvotes. The ```upvote``` action stores data within the ```upvotes``` table and its primary index is ```content_id```.

#### ```upvote``` Parameters
- ```content_id``` - The unique post or comment identifier being upvoted.
- ```voter``` - The account who is upvoting a post.
- ```quantity``` - The quantity and asset being transferred.
- ```memo``` - The memo related to the upvote. Limited to 140 characters.


### message
The ```message``` action has been moved to the ```dmessenger``` contract, outside of the scope of the ```dsocial``` contract being discussed. More on dMessenger in [The dMessenger Application](#the-dmessenger-application).


### favorite
The ```favorite``` action is used to favorite a specific post_id. The ```favorite``` action stores data within the ```favorites``` table and the ```post_id``` is the primary index.

#### ```favorite``` Parameters

- ```post_id``` - The unique ID of the post a user wants to favorite.
- ```account``` - The account "favoriting" a post.


### pin
The ```pin``` action is used to pin a post to the top of a profile page. The ```pin``` action stores data within the ```pins``` table. Only one pin can exist, per account. If a pin already exists for an account, the new entry will overwrite the old entry. The primary index for ```pins``` is ```account```.

#### ```pin``` Parameters
- ```post_id``` - The unique id of the post being pinned.
- ```account``` - The account pinning a post.


### hide
The ```hide``` action is used to hide a post from a dSocial page. Only the creator of a post can view hidden posts. The ```hide``` action uses the ```hidden_posts``` table. The ```hide``` action can be ran against an already hidden post, to modify its status in order to make the post publicly available again.

**NOTE:** Post data can still be found on the blockchain by those who really want to find it. If you want to delete a post, you should use the [delete](#delete) action.

#### ```hide``` Parameters
- ```post_id``` - The unique id of the post to be hidden.
- ```account``` - The account name who is hiding the post.
- ```status``` - Boolean of whether a post is actually hidden (True = hidden).


### follow
The ```follow``` action is used by one account that wants to subscribe to the posts of another account. The follow action stores data in the ```followers``` table. The [unfollow](#unfollow) action also modifies data in the ```followers``` table. There are multiple indexes in the ```followers``` table (```follower``` and ```following```).


#### ```follow``` Parameters
- ```follower``` - The account initiating the follow action.
- ```following``` - The account the follower wants to follow. 

- ```status``` (auto) - The Boolean of the follow status (False=unfollow and True=follow). When running the  ```follow``` action, this is always true. 

### unfollow
The ```unfollow``` action is used by one account that wants to unsubscribe to the posts of an account it was previously subscribed to. The ```unfollow``` action modifies data in the ```followers``` table.

#### ```unfollow``` Parameters
- ```follower``` - The account initiating the unfollow action.
- ```following``` - The account the follower wants to unfollow.
- ```status``` (auto) - The Boolean of the follow status (False=unfollow and True=follow). When running the ```unfollow``` action, this is always false.

### media
This has been deprecated and merged into both the [post](#post) and [comment](#comment) actions.

### block
The ```block``` action is used by a user who wants to notify dSocial of their requests to block a specific account. 

**NOTE:** This is not permanent, since the [unblock](#unblock) action can be subsequently used to modify the result of this action. Data from the ```block``` action is stored in the ```block_status``` table.

#### ```block``` Parameters
- ```account``` - The account initiating the block action.
- ```blocked``` - The account being blocked.
- ```status``` (auto) - The Boolean of the block status (True=blocked, False=unblocked). When running the ```block``` action, this is always true.



### unblock
The ```unblock``` action is used by a user who wants to notify dSocial of their request to unblock a specific account. 

**NOTE:** This is not permanent, since the [block](#block) action can be subsequently used to modify the result of this action. The ```unblock``` action modifies data within the ```block_status``` table.

#### ```unblock``` Parameters
- ```account``` - The account initiating the unblock action.
- ```blocked``` - The account being blocked.
- ```status``` (auto) - The Boolean of the block status (True=blocked, False=unblocked). When running the ```unblock``` action, this is always false.



### system
The ```system``` action has been deprecated. The [block](#block), [unblock](#unblock), [deactivate](#deactivate), [pimage](#pimage), [himage](#himage) and [pdata](#pdata) actions are now in the their own top-level actions.


### delete
The ```delete``` action is used to delete the content pertaining to a specific ```post_id``` or ```comment_id```. This action does not store data, rather, it erases the row matching the unique ```delete_id``` in either the ```posts``` or ```comments``` tables. 

#### ```delete``` Parameters
- ```delete_id``` - The unique id of the post or comment being erased.


### deactivate
The ```deactivate``` action is used to notify dSocial that a profile should be blacklisted by the dSocial application. This means that an account will NOT be found through dSocial's application and if a profile is accessed directly (by link or search), it will show as "deactivated". Data from the ```deactivate``` action is stored in the ```profile_status``` table. 

**NOTE:** This action is only temporary and the results of this action can be modified through the [activate](#activate) action.

#### ```deactivate``` Parameters
- ```account``` - The account being deactivated.
- ```status``` (auto) - The Boolean of a dSocial account's status (True=activate, False=deactivate). When running the ```deactivate``` action, this is always false.


### activate
The ```activate``` action is used to notify dSocial that a profile should be removed from the blacklist and re-activated. The ```activate``` action modifies the data within the ```profile_status``` table. NOTE: This action is only temporary and the result of this action can be modified through the [deactivate](#deactivate) action.

#### ```activate``` Parameters
- ```account``` - The account being activated.
- ```status``` (auto) - The Boolean of a dSocial account's status (True=activate, False=deactivate). When running the ```activate``` action, this is always true.


### pimage
The ```pimage``` action is used to add or modify an account's main profile image. The ```pimage``` action stores and modifies data in the ```profile_images``` table. If a profile image already exists, running this action will replace the data for a specified account, since ```account``` is the primary_index in the ```profile_images``` table.

#### ```pimage``` Parameters
- ```account``` - The account adding or modifying a profile image.
- ```media``` - The discovery key of a dDrive where the profile image is located.
- ```file_name``` - The name of the image in the dDrive. File must exist in a dDrive.


### himage
The ```himage``` action is used to add or modify an account's profile header background image. The ```himage``` action stores and modifies data in the ```header_images``` table. If a header image for an account already exists, running this action will replace the data for a specified account, since ```account``` is the primary_index in the ```header_images``` table.

##### ```himages``` Parameters
- ```account``` - The account adding or modifying a header background image.
- ```media``` - The discovery key of the dDrive where the profile image is located.
- ```file_name``` - The file name of the image in the dDrive. File must exist in dDrive.


### pdata
The ```pdata``` action is used to add or modify an account's profile data. The ```pdata``` action stores and modifies data in the ```profile_data``` table. The primary index in the ```profile_data``` table is ```account```.

#### ```pdata``` Parameters
- ```account``` - The account associated with the profile data being submitted. (required)
- ```name``` - The display name for a profile. (required)
- ```url``` - An external URL. (required - even if empty)
- ```bio``` - The description for a profile. Limited to 140 characters. (required - even if empty)
- ```location``` - The location of the profile. (required)

## Application Layout
This section briefly describes some of the "components" and "views" of the dSocial application. dSocial's application layout is the same (responsive) across all devices so that the user experience is seamless when switching between desktop and mobile devices. dSocial is written in ReactJS and uses React-Native, as well as Electron so that a single code base can be deployed across multiple platforms (Web, MacOS, Windows, Linux, iOS and Android). dSocial is a SPA (single page application) made up of many components that are combined to make up more complex components. These components are explained in the sub-sections that follow.

### Account Creation & Login
As discussed in [Cross-Platform UAL](#cross-platform-ual), the UAL used by dSocial is the most important element of the application itself. Before an end-user can actually use dSocial, the application itself requires that an end-user downloads the PeepsID app so that the cryptographic keys (for various permission levels, that are generated during both the login and signup processes) are securely stored within the PeepsID application. This insures that all keys that generated during the login and signup processes, are securely stored within the PeepsID app. This also insures that end-users can securely use these keys to sign the transactions related to any of the [on-chain actions](#on-chain-actions) they end up initiating while using dSocial.

#### No-Show Policy (NSP)
dSocial uses a "no-show policy" (NSP) (not to be confused with network service provider) for private keys, meaning private keys within the dSocial application are never shown to the end-user for any reason. Instead, private keys are managed within PeepsID and securely stored on an offline subnet (similar to an air-gapped environment). 

Here is a pseudo representation of how dSocial and PeepsID use what is known as a "Secure Key Vault" or "SKV":
```
Arisen Network  <-syncing->  dSocial  <-PeepsID->  |SKV| <-> Transaction Signing
```

#### PeepsID-Integrated
As was explained in previous sections, dSocial is highly integrated with the PeepsID application for user and action authentication. When a user initiates [on-chain actions](#on-chain-actions) via dSocial, dSocial uses the PeepsID application to sign the transaction these actions are neatly packaged within so that an end-user's private keys are never exposed or exploited in any way. This process is the crown jewel of consumer-friendly decentralized applications.

PeepsID is designed to operate on MacOS, Windows, Linux, Google Chrome, iOS and Android.

**NOTE:** ***PeepsID and its UAL will soon be utilized by the world's first decentralized operating system, [PeerOS](https://github.com/peepsx/peeros-whitepaper).***

#### Secure SKV Communications
PeepsID stores a user's permission-level based cryptographic keys in a [Secure Key Vault](#secure-key-vault) or "SKV" which is located on an offline subnet within the user's device. dSocial and PeepsID use a decentralized messaging protocol known as "dMemo" for inter-process communications between the dSocial and PeepsID applications.  This is for the secure transport of unsigned and signed transactions between the application environment and the SKV. 

**The process for achieving secure transaction signing and transport to and from the SKV is as follows:**
1. The end-user executes an [on-chain action](#on-chain-actions) (ex. the user creates a new post on dSocial, which executes the [post](#post) action.

2. dSocial packages the action or a set of actions into a single unsigned transaction, using the dMemo protocol, dSocial sends a ```SIGOTC``` (open transaction channel) signal to PeepsID to open a ```transaction channel``` and sends the unsigned transaction to PeepsID, along with the account and the account's permission level.

3. If the account and permission level's keys are managed by PeepsID, PeepsID sends the ```SIGSOK``` (signing is ok) signal and dSocial switches to the PeepsID application where a user is asked to verify a pin number or their static biometrics. The resulting serialized data from this input, along with the unsigned transaction, account and permission levels are sent over a separate dMemo channel to the SKV. 

4. The SKV receives both the serialized input data, the account name and the permission level, along with the unsigned transaction. Before closing the communication channel with PeepsID, the SKV sends the ```SIGDRE``` (data received) signal back to PeepsID and then the ```SIGCLOSE``` (close channel) signal, to signal that it has received the data and is closing the communication channel.

5. The SKV decrypts the required private key related to the given account and associated permission-level via its offline subnet and temporarily stores it in a portion of random-access memory (RAM) that is only accessible by the offline subnet where the SDK operates.

6. The SKV then signs the transaction, serializes it and subsequently removes the exposed private keys from RAM. 

7. The SKV then sends PeepsID the ```SIGOTC``` signal, signaling its intent to open a transaction channel.

8. PeepsID accepts the SKV's request to open a ```transaction channel```. (PeepsID by design always accepts SIGOTC-based requests from the SKV). 

9. PeepsID sends the signed transaction back to dSocial over their open ```transaction channel```. 

10. dSocial broadcasts the transaction to the Arisen network, where the action is executed and data is stored in the ```dsocial``` on-chain database.

11. dSocial sends PeepsID the ```SIGTXBR``` (transaction broadcasted) signal, signaling that the transaction was successfully broadcasted and then sends the ```SIGCLOSE``` signal to close their ```transaction channel```. 

12. dSocial then queries the Arisen network for the new data and it is displayed to the user.

This process takes a matter of 1-2 seconds and the end-user never sees any of these background processes.

**NOTE:** For more on the dMemo protocol, please read the [dMemo Whitepaper](https://github.com/peepsx/dmemo-whitepaper).

#### Initial Login Actions
When a user initially signs into dSocial for the first time, many on-chain actions are linked together and executed, including:
- [activate](#activate) - Sets the user's profile activation status to ```true```.
- [follow](#follow) - Follows the @peeps, @jared and @dsocial profiles.
- transfer (via the ```arisen.token``` contract) - Sends the new user 1000 LIKE tokens and 10 RIX tokens from the @peeps account, so that the new user can post to dSocial and upvote others immediately.
- The necessary RAM, CPU and NET resources are reserved on Arisen for the new user so that they can utilize all of dSocial's features.

#### Onboarding
When a new user successfully signs into dSocial for the first time and the [Initial Login Actions](#initial-login-actions) have taken place, they are taken through an onboarding process.

##### Step 1: Add Profile Data
The user is asked to enter specific profile information, including the following:
- Profile Display Name (can be anything and is different than the account username) (required)
- Profile Description (profile description - limited to 140 characters) (optional)
- Profile URL (URL to a website or other profile. Also limited to 140 characters) (optional)
- Profile Location (user types in a city, state or country) (required - even if user selects "Global").
- Profile Color (user selects an RGB-based hex code from a color wheel for their profile's color scheme.)

This data is used as parameters for the [pdata](#pdata) action. dSocial places this unsigned transaction in a queue so that PeepsID can sign all of the transactions that derive from its onboarding process at once, so that the end-user only has to verify their identity with PeepsID one time.

##### Step 2: Add Profile Image
The user is asked to choose a profile image and it is replicated on their local computer in the ```dsocial-drives/profileimage/``` folder. dSocial converts the local instance of the folder into a dDrive and announces the dDrive to dWeb's dDNS and DHT networks.

This data is used as a parameter for the [pimage](#pimage) action. dSocial places this unsigned transaction in the ```onboarding transaction queue``` and the onboarding process continues to Step 3.

##### Step 3: Upload Header Image
Similar to Step 2, the user is asked to choose a header image and it is replicated on their local computer in the ```dsocial-drives/headerimage/``` folder. dSocial converts this local instance of the folder into a dDrive and announces the dDrive to dWeb's dDNS and DHT networks.

This data is used as parameters for the [himage](#himage) action. dSocial places this unsigned transaction in the ```onboarding transaction queue``` and the onboarding process continues to Step 4.

##### Step 4:  Follow Popular Voices
Step 4 shows the new user, a list of popular users on dSocial (those with the highest follower count) allowing a user to choose who they they want to follow out of the list. For each follow, a [follow](#follow) action is generated. All of them are packaged into a single unsigned transaction and placed into the ```onboarding transaction queue``` and the onboarding process continues to Step 5.

##### Step 5: Create First Post
A user is asked to create their first post which creates a [post](#post) action. This is packaged into a single unsigned transaction and placed into the ```onboarding transaction queue```. 

##### The Onboarding Transaction Queue
All transactions from the onboarding process are concurrently sent to PeepsID, signed in the SKV and sent back to dSocial as signed transactions, where dSocial subsequently broadcasts them to the Arisen network. After broadcast, the user is taken to the home screen.

### Feed
The ```Feed``` top-level component, also considered as the "home screen" for dSocial, is made up of a large component hierarchy. That component hierarchy is somewhat discussed in the sub-sections that follow, as well as some of dSocial's special functionality found throughout the ```Feed``` component. The dSocial post feed is made up of many instances of [The Post Component](#the-post-component) as well as desktop-based components for [Trending Topics](#trending-topics-component), [Profile Management Component](#profile-management-component), the [Earnings Breakdown Component](#earnings-breakdown-component) and the [New Post Component](#new-post-component). On mobile devices, these components are tabs at the bottom of the screen and available across all feed-based views. A feed only loads 8 posts at a time. To load more posts, the end-user must click the "Show More Posts" button which queries the Arisen blockchain for 8 more posts. Similarly, only 8 comments are loaded on a per-post basis and will only load more when the "Show More Comments" button is clicked , which retrieves 8 more comments for a particular post from the Arisen blockchain.

#### The Post Component
All posts are displayed in a "card"-like structure ***(See Bootstrap cards)***, within the [Feed](#feed), [Profile Page](#profile-page) and [Search](#search) top-level components. The post component is the same for every post and functions alongside many sub-components, so that feed-based data is consistent across all feed-based components, which of course, consists of a bunch of posts. 

A pseudo-representation of the post component:

```
===========================================================
| (Post Account)                                         (Post Time) (Post Menu) |
|                                                                                                    
| (Post Content)                                                                                       
|                                                                                                     
|
|
|
| (Post State)
| (Post Footer)
| (Post Repost) (Post Interaction) (Post Comment) (Post Upvote)        |
============================================================
```

##### Post Content Component
The post content component is responsible for displaying post data and post media for a given post. This data is retrieved from the ```dsocial``` multi-index database on Arisen's network and the media associated with the retrieved dDrive discovery key, is subsequently retrieved from the peers who are distributing it (a dDrive's flock). This component organizes thumbnail-based media in a masonry-style structure under the actual post content.

##### Post Time Component
The post time component is responsible for retrieving the time related to when the post data was initially created and stored on the Arisen network via Arisen's API and displaying the time with [The Post Component](#the-post-component).

##### Post Account Component
The post account component is responsible for displaying the profile name, account username and profile image at the top left of [The Post Component](#the-post-component). The profile name, account username and the dDrive discovery key of the profile image are retrieved from Arisen's network and the profile image is retrieved from the dDrive's flock.

##### Post Stats Component
The post stats component displays the number of:
- interactions
- comments
- reposts
- upvotes (In RIX)

These statistics are displayed below the [Post Content Component](#post-content-component) within [The Post Component](#the-post-component). All of this data is retrieved via Arisen's network for a given ```post_id```.

##### Post Footer Component
The post footer component, contains four buttons that each in-turn initiate the display of one of four separate sub-components:
- Repost - displays the [Post Repost Component](#post-repost-component)
- Interact - displays the [Post Interaction Component](#post-interaction-component)
- Comment - displays the [Post Comment Component](#post-comment-component)
- Upvote - displays the [Post Upvote Component](#post-upvote-component)

Each button also has a ```label``` that displays the amount of reposts, interactions, comments and upvotes (in RIX).

##### Post Menu Component
A hamburger-style menu at the top right of [The Post Component](#the-post-component) that features the following options:
- Block User - Initiates the [block](#block) action.
- Favorite Post - Initiates the [favorite](#favorite) action.
- Report Post - Displays the [Post Report Component](#post-report-component).
- Unfollow User - Initiates the [unfollow](#unfollow) action.
- Message @username - Opens the dMessenger application and starts a new conversation with @username.

##### Post Favorite Component
The post favorite component is a star icon to the right of the [Post Menu Component](#post-menu-component) that when clicked initiates the [favorite](#favorite) action for a given post.

##### Post Upvote Component
The post upvote component is a small component that is located within an in-app popup module which allows a user to upvote a specific post with a specific amount of RIX or LIKE tokens. A user must have the upvote amount in their account, as well as the needed permissions to transfer the coins (arisen.token requires the active permission).

The [upvote](#upvote) action first initiates the ```transfer``` action via the ```arisen.token```  contract and then runs the actual [upvote](#upvote) action, if the transfer was successful. The user only has to verify once via PeepsID for both actions, since one notifies the other of a successful execution via the on_notify() function and since both are packaged within a single transaction.

##### Post Interaction Component
The post interaction component allows a user to "react" to a post using the [interact](#interact) action.

The following reactions are included with dSocial, as emojis:
- like
- love
- hate
- angry
- shocked
- sad
- excited

All reactions are emoji-based and their counts, along with each emoji icon, are displayed within a post, via the [Post Stats Component](#post-stats-component).

##### Post Comment Component
The post comment component expands from the bottom of [The Post Component](#the-post-component) and displays all comments ordered by popularity and upvote averages. Each comment, like each post, is an instance of [The Post Component](#the-post-component). This means a user can upvote, interact, comment, repost, favorite and report comments, just as they do with posts.

#####  Post Repost Component
The post repost component is displayed in a popup module basically asking a user if they really want to repost a specific post. The "Yes, Repost" button within the popup initiates the [repost](#repost) action. dSocial feeds are designed to showcase reposted posts immediately, as if it came from the original user. The only difference between the original post and the reposted version is that [The Post Component](#the-post-component) displays "Reposted by @account" at the top of [The Post Component](#the-post-component).

#### Trending Topics Component
The trending topics component is designed to display dSocial's trending topics globally by default, but also includes a built-in location search for fetching trending topics by location. dSocial's applications use a local location database to help auto-complete location searches and a [Trending Search Algorithm](#trending-search-algorithm) for determining trending terms and #hashtags on a per-location basis, as well as where they rank in the ```trending graph```.

##### Trending Search Algorithm
Trending topics are determined on a per-location basis using an algorithm that searches all posts on the network that contain the same #hashtags or a constant string of text and categorically keeps count of each instance on a per-location basis.

For example, if there is a post by two users that use the hashtag #LockHerUp, where one user's profile location is Dallas, TX and the other user's profile is in Oklahoma City, OK then the #hashtag would have the following per-location counts:

```
Global - 2
United States - 2
Texas - 1
Oklahoma - 1
Dallas, TX - 1
Oklahoma City, OK - 1
```

Notice that since Dallas is in Texas and Oklahoma City is in Oklahoma, the locations of Texas and Oklahoma each have a count of 1 and since both are in the United States, the United States location has a count of 2. The ```Global``` location is the default location for all profiles and its count for a term is incremented for all instances of a term, regardless of location.

Although, the ranking of terms in the top trending terms for a locality is not entirely dependant upon the amount of times terms are mentioned by users in a particular locality. The ```Trending Search Algorithm``` weighs many factors:

- The average time frame between the previous two instances of a term being posted (resets every 30 minutes) [60%]
- The popularity of users who have posted the term within the last 24 hours [10%]
- The amount of times the term is found in reposts within the last 24 hours [10%]
- The total amount of RIX earned by posters of the term within the past two hours [5%]
- Total number of instances (count) [15%]

A term with the lowest average time frame between multiple posted instances and the highest total amount of upvoted RIX (totaled amongst all posts), will rank higher than a term that is found to have a higher count, with more reposts and more reposts from the network's most popular users. This algorithm insures that terms found to be quickly gathering traction on the network, on a per-location basis, can rank ahead of older terms with a higher post count.

#### Earnings Breakdown Component
The earnings breakdown component shows a daily and a weekly breakdown of a user's earnings in RIX and LIKE. It also has a button that says "View Wallet" which takes a user to the [Wallet Component](#wallet). On desktop devices the earnings breakdown component is on the left sidebar under the [Account Management Component](#account-management-component) and above the [Trending Topics Component](#trending-topics-component). On mobile devices, it's located in a tab at the bottom of the screen.

#### Latest, Popular and Custom Feed Filter Components
dSocial by default allows users using the ```Feed``` and ```Search Feed``` views, to organize posts by those posted most recently (latest) and those that have the greatest popularity (popular). Users can also create their own custom filters by selecting a variety  of factors or terms they prefer to see over others. Instead of centralized networks determining what a user sees, users can make that determination for themselves by simply creating custom filters for their dSocial home feed.

#### Account Management Component
The account management component is found at the top of the left sidebar above the [Earnings Breakdown Component](#earnings-breakdown-component). The account management component shows:
- profile image
- profile name
- @username
- post, following and follower counts
- an "Edit Profile" button that links directly to the user's profile

#### New Post Component
When a user clicks the "New Post" button, a popup module is opened which contains the new post component. The new post component is simply a text box, with a character counter that only allows users to type 140 characters, as well as a media icon for selecting media to be placed within a dDrive. Under the text box, is a button that says "Post", which initiates the [post](#post) action.

#### Post Report Component
Each post has a "Report Post" link, found within the [Post Menu Component](#post-menu-component) which when clicked, opens a popup module that contains the post report component. The post report component is essentially a form where a user can make a report about a specific post, as explained earlier in this paper in the [Decentralized Reporting System](#decentralized-reporting-system) section.

The form contains the following:
- (pre-selected post_id or comment_id)
- (pre-selected @username of who created the post or comment)
- Report Type (General or Emergency)
- Report Category (Illegal Pornography or Other Criminal Activity)
- ([IF] Emergency) Text box for a max 140 character description about why an issue is an emergency.
