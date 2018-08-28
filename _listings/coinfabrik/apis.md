---
name: CoinFabrik
x-slug: coinfabrik
description: Our smart contract development and full stack blockchain development
  services are supported by more than 20 years of experience building and reviewing
  secure applications. CoinFabrik is a full stack blockchain development company.
  Our expertise range from extending cryptocurrency nodes like Bitcoin and Ethereum
  to providing high level APIs and UIs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coinfabrik.png
x-kinRank: "7"
x-alexaRank: "970321"
tags: Types
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/coinfabrik/apis.md
specificationVersion: "0.14"
apis:
- name: Coinbase API - Send or request money
  x-api-slug: accountsaccount-idtransactions-post
  description: |-
    Type=send
    =========

    Send funds to a bitcoin address or email address. No transaction fees are required for off blockchain transactions, and Coinbase waives fees for on-blockchain transactions greater than 0.0001 BTC, up to a threshold of 25 per day. Read more about free transactions.

    When used with OAuth2 authentication, this endpoint requires two factor authentication unless used with wallet:transactions:send:bypass-2fa scope.

    If the user is able to buy bitcoin, they can send funds from their fiat account using instant exchange feature. Buy fees will be included in the created transaction and the recipient will receive the user defined amount.

    To create a multisig transaction, visit Multisig documentation.

    Type=request
    ============

    Requests money from an email address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coinfabrik.png
  humanURL: https://www.coinfabrik.com
  baseURL: https://api.coinbase.com//v2
  tags: SaaS, Blockchain, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/coinfabrik/accountsaccount-idtransactions-post-openapi.md
x-common:
- type: x-blog-rss
  url: https://blog.coinfabrik.com/feed/
- type: x-github
  url: https://github.com/CoinFabrik
- type: x-openapi
  url: https://raw.githubusercontent.com/CoinFabrik/coinbase-api-swagger/master/swagger.json
- type: x-api-gallery
  url: http://codefresh.api.gallery.streamdata.io
- type: x-api-stack
  url: http://coinfabrik.stack.network
- type: x-blog
  url: https://blog.coinfabrik.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/coinfabrik
- type: x-twitter
  url: https://twitter.com/coinfabrik
- type: x-website
  url: https://www.coinfabrik.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---