# qtum-dapp-documentation

[Last Update: 13th September 2018]

High-level (non technical) documentation about diadem network project

Table of content:  

- [qtum-dapp-documentation](#qtum-dapp-documentation)
  - [What is Diadem Network?](#what-is-diadem-network)
  - [What is Diadem Network composed of?](#what-is-diadem-network-composed-of)
  - [Future improvement ideas](#future-improvement-ideas)
  - [Roadmap](#roadmap)

## What is Diadem Network?

Diadem Network leverages blockchain technology from [Qtum](https://qtum.org) and [Facebook](https://www.facebook.com/) to connect users achieving great things with people wanting to support them  

Actions you can do on Diadem Network:  

- CREATE YOUR ACHIEVEMENT (1max per user): Post a link to an achievement you already posted on facebook
- UPDATE YOUR ACHIEVEMENT: Your achievement evolved? No problem! Available only if you have an achievement created
- CONFIRM achievement(s): Confirm other user(s) achievement(s)
- SUPPORT achievement(s): Send QTUM token to achievers to show them some love
- DEPOSIT for achievement(s): Deposit QTUM tokens which will not be sent until the facebook user YOU chose confirms the achievement
- WITHDRAW your tokens: QTUM Tokens you own in your hot wallet can be withdrawn any time you want

General information about usage:  

- Facebook Login is required to perform most actions
- A hot wallet is used to manage QTUM transactions
- You need to send token to Diadem Hot wallet to be able to Support and Deposit. [Check official QTUM user guide here](https://docs.qtum.site)
- Create, Update and Confirm are free
- Support, Deposit and Withdraw need QTUM tokens. For this, you must send some to your hot wallet

## What is Diadem Network composed of?

- [Client](https://github.com/DiademNetwork/qtum-dapp-client)
- [Server](https://github.com/DiademNetwork/qtum-dapp-backend)
- [Watchers](https://github.com/DiademNetwork/qtum-dapp-watcher)
- [Contracts](https://github.com/DiademNetwork/qtum-smart-contracts)

## Future improvement ideas

- Internationalize platform, so anyone in the world can participate
- Add other types of achievements (self-goal-achievement, group achievement, one-time/running achievement...) and their custom rules
- Add categories for achievements (art, society, education, ecology...)
- Add filters (by date, by category, by confirmations count....) for achievements on platform.
- Add search function to find achievement(s) (search by title, creator...)
- Make it possible to choose a group of witnesses for deposit, with configurable rules (all must confirm / half must confirm ?)
- Integrate Diadem Network with other social networks (Twitter, Google+, Medium...)
- Improve fee management in hot wallet (so users can chose fees they are willing to spend, to make blockchain confirmations faster)
- Add possibility to report an achievement (for example if someone post something non-ethical)
- Or add administrator users to filter achievements at creation time ? => To be discussed
- Add possibility to delete his achievement(s)
- Make it possible to create more than one achievement per user
- Integrate with Qrypto (or equivalent) if user prefer to use it instead of DM Hot wallet

## Roadmap

- September 2018: Release of mainnet version for QTUM Hackathon
- TBD