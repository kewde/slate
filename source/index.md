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

## Shadow compared too ...

### Bitcoin


> yep

# Authentication

> To authorize, use this code:

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
```

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Authorization: meowmeowmeow"
```

> Make sure to replace `meowmeowmeow` with your API key.

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

