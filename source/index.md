---
title: ShadowCore API

language_tabs:
  - shell
  - json
  - java
  - javascript

toc_footers:
  - <a href='http://aboutshadow.com/'>Shadow public website</a>
  - <a href='http://github.com/tripit/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

On the 19th of July 2014, Shadow emerged as an innovative and unique open source project with a mission to create the first truly anonymous and decentralized cryptocurrency. Back then, in traditional financial terms, many cryptocurrencies represented trackable and linkable check or card options while we wanted to create a digital currency that worked more like cash. Inspired by the Cypherpunk anonymity movement, the Shadow Project developers began fusing several online technologies and services while simultaneously integrating security improvements based on zero knowledge cryptography. After its first birthday, Shadow had evolved from a simple idea into one of the most advanced cryptocurrency projects to date. ShadowSend development has created near-instant, untraceable/unlinkable and trustless transactions utilizing  non-interactive zero knowledge proofs, dual-key stealth addresses, and ring signatures. Shadow will soon offer a complete privacy platform which aims to establish an anonymous economy, delivering total financial freedom and privacy to all.

## Mission Statement

E­-cash systems, or virtual currencies, have become a very common way to transact due to the many benefits they hold over traditional methods of exchange. One of the largest problems for virtual currencies is preventing double­ spending, where a currency holder sends the same coins to multiple recipients. Bitcoin solves this problem using the blockchain, a public record of all transactions in the system. By viewing the blockchain, all participants in the currency can see the current state of the system at the same time,thus the double ­spending problem is solved. However, adding the blockchain causes a severe reduction of the anonymity and privacy of the participants in the currency. As the blockchain is public, anyone can see the transactions and total holdings of participants, unless suitable precautions are taken. 

We believe privacy is a human right ­ as enshrined in article 12 of the Universal Declaration of Human Rights of the United Nations. Transactions of value are an essential part of our daily lives. As such we strive to provide you with tools to transact in confidence. We are building anonymous systems and defending our privacy with cryptography, with anonymous mail forwarding systems, with digital signatures, and with electronic money. Creating a decentralized anonymous communication, commerce and currency platform available for all desktop and mobile operating systems.

## Shadow next to ...

### Bitcoin

Shadow functions on the same core principles from which Bitcoin was founded. There is no central authority or bank mechanism that controls the flow of transactions. 

### Zerocoin
Shadow does not require the initial trusted parameter setup which is present in the Zerocoin and Zerocash scheme.

### Monero

### Dash

## Users

Many have referred to Shadow as the “anti-Google” and hope that the project will become the solution for anyone seeking online anonymity, including private communication, shopping, browsing and publishing.
Shadow’s team sees potential for its services to be useful to the wider online community, by making secure and user friendly software that is easy to use and easily accessible. The recent release of ShadowCore is a foundational step towards that end goal. Potential users could include journalists looking for a neutral place to gather and discuss information outside of public networks, possible whistleblowers looking for an unmonitored area to collect and store sensitive materials, people who want to buy and sell goods or services without worrying about local restrictions or transaction fees, or simply anyone who – on general principles – isn’t interested in having their records monitored or captured by anyone.

Shadow’s financial unit, ShadowCash, also goes above and beyond other digital currencies to make the process invisible to outside eyes, but still nearly seamless for users, who can conduct their business anywhere in the world, on desktops or mobile devices.

## Contribute

Shadow is an Open Source project which is created almost entirely by volunteers. There are lots of ways you can get involved and help the project grow and improve. Here are some ways for you to get started.

### Code

Shadow is controlled by all Shadow users around the world. If you are a developer, you can use your super-powers to do good and contribute. The Shadow project is hosted over on GitHub. This is where developers work hard on the next version(s) of the software. To get involved with developing Shadow, check out our detailed contributing guidelines. We credit all contributors to the Shadow project in every major and minor release. We hold public development meetings and chat in our Slack team. We also maintain a public roadmap and dev blog to give you an idea of what's being worked on right now, and what's coming next. Are you someone who might be interested? Do not hesitate and contact us directly.

### Donate

We are a non-profit and Open Source software project and are trying to build a private economy. We appreciate all the help we can get in making this a reality. Both addresses are managed by Rynomster (lead developer). If applicable, please specify whether you want to remain anonymous. Many thanks to all our sponsors!
 
Official BTC donation address: 155cKQ5pk9kCQoXigxQapnLNyBK3hMrd2V
Official SDC development donation address: SdcdevXEaZaE9nDKjh6aH7kd3NcLX5rwAY

### Report

If you think you've found a bug or a problem with Shadow, please let us know! First, search our issue tracker to search to see if someone has already reported the problem. If they haven't, click here to open a new issue, and fill out the template with as much information as possible. The more you can tell us about the problem and how it occurred, the more likely we are to fix it. Please check out our bug and bounty program for our guidelines and more details. 

Please do not report security vulnerabilities publicly. The details for responsible disclosure of security issues can be found in our bug and bounty program.

#### Bugs & Bounty program

Official bug donation Address: SdcbugSrxsYSBzxB2cVfiAYdqwjftLBaF1
According to Linus’ Law, “given enough eyeballs, all bugs are shallow”. That’s one of the reasons why Shadow’s source code is publicly available; but merely making the source code available doesn’t accomplish anything if people don’t read it!
For this reason, Shadow has a series of bug bounties. Similar to the bounties offered by Mozilla and Google, Shadow bug bounties provide an opportunity for people who find bugs to be compensated. Unlike those programs, however, Shadow’s bounties are not limited to security vulnerabilities.
Depending on the type of bug and when it is reported, different bounties will be awarded. Bounties are paid out in SDC, at the 3-day average of each to a fixed US Dollar value.

#### Things that do not qualify under the bug bounty 

- Bugs found on third-party/community sites, software or services, which is not due to an improper configuration issue specific to us. Please submit any potential issues to the maintainers of that site or providers of that service.
- Vulnerabilities which are too broad or not documented properly (i.e. do not include a specific example relevant to a - Shadow-controlled site or application).
- Bugs or issues with a third-party site, software, or service that we use, which is not due to an improper configuration issue specific to us. Please submit any potential issues to the maintainers of that site or providers of that service.
- Bugs and errors found in software/code that is still undergoing alpha or beta testing.
- Usability issues
- Anything requiring social engineering
- DOS/DDOS attacks
- Missing HSTS (HttpOnly flags), Secure flag, Browser Cache vulnerabilities
- CSRF that doesn’t affect the victim
- Referrer leakage to pages an attacker cannot control.
- The presence of unnecessary files, e.g. for backups, when these files do not expose any sensitive information.
- Anything that is the result of an automated Nessus/PCI scans (too general)
- DNS issues (e.g. lack of an SPF record)
- SSL certificate issues
- Bugs that have received mainstream tech media or community attention before the date of your disclosure.

#### Bug Bounties and Rewards

$1500 Deanonymize ShadowChat or ShadowSend (proof that a protocol is not anonymous)
$750 A flaw in the protocol that allows for theft or loss of funds
$500 A bug in the reference client that leads to consensus issues
$250 ~ 1 Btc A bug which causes data corruption or loss
$100 A bug which causes the application to crash
$50 Other non-harmless bugs
$10 ‘Harmless’ bugs, e.g. cosmetic errors

#### How to report a bug

Security-related issues
Contact the developers privately by sending an e-mail to bounties@shadow.cash with the details of the issue. Do not post the issue on github or anywhere else until the issue has been resolved.
Code issues
We would strongly prefer if you create a pull-request on Github in the proper repository with the necessary fix (along with your SDC address to claim the bounty). For more information, see this link.

## Community

community 
Shadow has a very active community. Aboutshadow.com is dedicated to help Shadow’s community develop in a sustainable way. The website is registered and managed by community members, with the input of Shadow developers. Aboutshadow.com is not a foundation. Foundations imply centralization or a controlling body. All Shadow holders are equal and all have a say in the direction the project is heading. Just like nobody owns the email technology, nobody owns the Shadow network. As such, aboutshadow.com does not speak with authority in the name of the Shadow project.
Community channels

Below you will find a list of places where you can find other Shadow users, community members and news.
IRC: freenode.net #shadowcash
Forum: http://www.talk.shadowproject.io
Slack: http://shadowproject.herokuapp.com/
Reddit: https://www.reddit.com/r/ShadowCash
Twitter: http://www.twitter.com/allaboutshadow

## Support

For support please visit one of the links below:

Forum: http://www.talk.shadowproject.io
IRC: freenode.net #shadowcash
SLACK: http://shadowproject.herokuapp.com

# Installing and running a client

## Linux

The Linux Wallet comes in two variations :
- QT Wallet
 - Run the "shadow" executable from the linux download to run the Shadow QT Wallet
- Daemon
 - Run the "shadowcoind" executable from the linux download to start the Shadow daemon

### Shadowcoind from Source

If you wish you can also compile directly from source, below are the instructions to compile latest ShadowCore headless daemon based on Debian/Ubuntu. Please also refer to the build instructions for more detailed information.

> Update and Install dependencies:

```shell
sudo apt-get update && apt-get upgrade
sudo apt-get install git build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev libqrencode-dev
```

> Download the source code and compile shadowcoind

```shell
git clone https://github.com/ShadowProject/shadow
cd shadowcoin/src
make -f makefile.unix
strip shadowcoind
```

> Run the daemon

```shell
shadowcoind -daemon
```

> On the inital start-up shadowcoind will return an error because it cannot find the configuration file shadowcoin.conf

```shell
nano ~/.shadowcoin/shadowcoin.conf
```

> Add the following to your config file, changing the username and password to something secure:
> daemon=1
> rpcuser=<secure username>
> rpcpassword=<secure password>


Kittn uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>

# Kittens

## Get All Kittens

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get()
```

```shell
curl "http://example.com/api/kittens"
  -H "Authorization: meowmeowmeow"
```

> The above command returns JSON structured like this:

```json
[
  {
    "id": 1,
    "name": "Fluffums",
    "breed": "calico",
    "fluffiness": 6,
    "cuteness": 7
  },
  {
    "id": 2,
    "name": "Isis",
    "breed": "unknown",
    "fluffiness": 5,
    "cuteness": 10
  }
]
```

This endpoint retrieves all kittens.

### HTTP Request

`GET http://example.com/api/kittens`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
include_cats | false | If set to true, the result will also include cats.
available | true | If set to false, the result will include kittens that have already been adopted.

<aside class="success">
Remember — a happy kitten is an authenticated kitten!
</aside>

## Get a Specific Kitten

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get(2)
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get(2)
```

```shell
curl "http://example.com/api/kittens/2"
  -H "Authorization: meowmeowmeow"
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "name": "Isis",
  "breed": "unknown",
  "fluffiness": 5,
  "cuteness": 10
}
```

This endpoint retrieves a specific kitten.

<aside class="warning">If you're not using an administrator API key, note that some kittens will return 403 Forbidden if they are hidden for admins only.</aside>

### HTTP Request

`GET http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to retrieve

