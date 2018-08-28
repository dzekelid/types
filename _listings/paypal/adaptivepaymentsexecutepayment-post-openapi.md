---
swagger: "2.0"
x-collection-name: PayPal
x-complete: 0
info:
  title: Paypal Execute Payment
  description: The ExecutePayment API operation lets you execute a payment set up
    with the Pay API operation with the actionType CREATE. To pay receivers identified
    in the Pay call, set the pay key from the PayResponse message in the ExecutePaymentRequest
    message.
  version: 1.0.0
host: svcs.sandbox.paypal.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /AdaptivePayments/ExecutePayment:
    post:
      summary: Execute Payment
      description: The ExecutePayment API operation lets you execute a payment set
        up with the Pay API operation with the actionType CREATE. To pay receivers
        identified in the Pay call, set the pay key from the PayResponse message in
        the ExecutePaymentRequest message.
      operationId: AdaptivePayments.ExecutePayment.post
      x-api-path-slug: adaptivepaymentsexecutepayment-post
      responses:
        200:
          description: OK
      tags:
      - Payments
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---