---
name: PayPal
x-slug: paypal
description: PayPal is the faster, safer way to send money, make an online payment,
  receive money or set up a merchant account.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/237-paypal.jpg
x-kinRank: "10"
x-alexaRank: "71"
tags: Types
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/paypal/apis.md
specificationVersion: "0.14"
apis:
- name: PayPal (Sandbox) - Execute Payment
  x-api-slug: adaptivepaymentsexecutepayment-post
  description: The ExecutePayment API operation lets you execute a payment set up
    with the Pay API operation with the actionType CREATE. To pay receivers identified
    in the Pay call, set the pay key from the PayResponse message in the ExecutePaymentRequest
    message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/237-paypal.jpg
  humanURL: https://paypal.com
  baseURL: https://svcs.sandbox.paypal.com//
  tags: International, Payments, Billing, Merchant, Indie EdTech Data Jam, Getting
    Started Example, Stack Network, Stack, Hypermedia API, Financial Services, Technology,
    Mobile, SaaS, internet, Invoices, Payments, Payments, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/paypal/adaptivepaymentsexecutepayment-post-openapi.md
- name: PayPal (Sandbox) - Set Payment Options
  x-api-slug: adaptivepaymentssetpaymentoptions-post
  description: "You use the SetPaymentOptions API operation to specify settings for
    a payment of the actionType CREATE. \n\t\t\t\t\tThis actionType is specified in
    the PayRequest message."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/237-paypal.jpg
  humanURL: https://paypal.com
  baseURL: https://svcs.sandbox.paypal.com//
  tags: International, Payments, Billing, Merchant, Indie EdTech Data Jam, Getting
    Started Example, Stack Network, Stack, Hypermedia API, Financial Services, Technology,
    Mobile, SaaS, internet, Invoices, Payments, Payments, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/types/master/_listings/paypal/adaptivepaymentssetpaymentoptions-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://paylocity.api.gallery.streamdata.io
- type: x-api-stack
  url: http://paypal.stack.network
- type: x-base-url
  url: https://api.paypal.com
- type: x-crunchbase
  url: https://crunchbase.com/organization/paypal
- type: x-crunchbase
  url: http://www.crunchbase.com/company/paypal
- type: x-developer
  url: https://developer.paypal.com/
- type: x-faq
  url: https://developer.paypal.com/docs/faq/
- type: x-getting-started
  url: https://developer.paypal.com/docs/
- type: x-github
  url: https://github.com/paypal
- type: x-playground
  url: https://devtools-paypal.com/hateoas/index.html
- type: x-privacy
  url: https://www.paypal.com/us/cgi-bin/webscr?cmd=p/gen/ua/policy_privacy-outside
- type: x-release-notes
  url: https://developer.paypal.com/docs/release-notes/
- type: x-terms-of-service
  url: https://cms.paypal.com/us/cgi-bin/?cmd=_render-content&content_ID=ua/Legal_Hub_full
- type: x-twitter
  url: https://twitter.com/paypal
- type: x-website
  url: https://paypal.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---