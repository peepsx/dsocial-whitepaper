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
