---
name: Stripe
x-slug: stripe
description: Online payment processing for internet businesses. Stripe is a suite
  of payment APIs that powers commerce for online businesses of all sizes, including
  fraud prevention, and subscription management. Use Stripes payment platform to accept
  and process p...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
x-kinRank: "10"
x-alexaRank: "1914"
tags: Disputes
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/apis.md
specificationVersion: "0.14"
apis:
- name: Stripe - Get Disputes
  x-api-slug: disputes-get
  description: Returns a list of your disputes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputes-get-openapi.md
- name: Stripe - Get Disputes Dispute
  x-api-slug: disputesdispute-get
  description: Retrieves the dispute with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-get-openapi.md
- name: Stripe - Add Disputes Dispute
  x-api-slug: disputesdispute-post
  description: When you get a dispute, contacting your customer is always the best
    first step. If that doesn???t work, you can submit evidence in order to help us
    resolve the dispute in your favor. You can do this in your dashboard, but if you
    prefer, you can use the API to submit evidence programmatically.Depending on your
    dispute type, different evidence fields will give you a better chance of winning
    your dispute. You may want to consult our guide to dispute types to help you figure
    out which evidence fields to provide.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-post-openapi.md
- name: Stripe - Add Disputes Dispute Close
  x-api-slug: disputesdisputeclose-post
  description: Closing the dispute for a charge indicates that you do not have any
    evidence to submit and are essentially ???dismissing??? the dispute, acknowledging
    it as lostThe status of the dispute will change from needs_response to lost. Closing
    a dispute is irreversible.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdisputeclose-post-openapi.md
- name: Stripe - Get Charges Charge Dispute
  x-api-slug: chargeschargedispute-get
  description: Get Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedispute-get-openapi.md
- name: Stripe - Add Charges Charge Dispute
  x-api-slug: chargeschargedispute-post
  description: Post Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedispute-post-openapi.md
- name: Stripe - Add Charges Charge Dispute Close
  x-api-slug: chargeschargedisputeclose-post
  description: Post Charges, Charge, Dispute, Close
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedisputeclose-post-openapi.md
- name: Stripe - Get Disputes Dispute
  x-api-slug: disputesdispute-get
  description: Retrieves the dispute with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-get-openapi.md
- name: Stripe - Add Disputes Dispute
  x-api-slug: disputesdispute-post
  description: When you get a dispute, contacting your customer is always the best
    first step. If that doesn???t work, you can submit evidence in order to help us
    resolve the dispute in your favor. You can do this in your dashboard, but if you
    prefer, you can use the API to submit evidence programmatically.Depending on your
    dispute type, different evidence fields will give you a better chance of winning
    your dispute. You may want to consult our guide to dispute types to help you figure
    out which evidence fields to provide.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-post-openapi.md
- name: Stripe - Add Disputes Dispute Close
  x-api-slug: disputesdisputeclose-post
  description: Closing the dispute for a charge indicates that you do not have any
    evidence to submit and are essentially ???dismissing??? the dispute, acknowledging
    it as lostThe status of the dispute will change from needs_response to lost. Closing
    a dispute is irreversible.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdisputeclose-post-openapi.md
- name: Stripe - Get Charges Charge Dispute
  x-api-slug: chargeschargedispute-get
  description: Get Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedispute-get-openapi.md
- name: Stripe - Add Charges Charge Dispute
  x-api-slug: chargeschargedispute-post
  description: Post Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedispute-post-openapi.md
- name: Stripe - Add Charges Charge Dispute Close
  x-api-slug: chargeschargedisputeclose-post
  description: Post Charges, Charge, Dispute, Close
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedisputeclose-post-openapi.md
- name: Stripe - Get Disputes Dispute
  x-api-slug: disputesdispute-get
  description: Retrieves the dispute with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-get-openapi.md
- name: Stripe - Add Disputes Dispute
  x-api-slug: disputesdispute-post
  description: When you get a dispute, contacting your customer is always the best
    first step. If that doesn???t work, you can submit evidence in order to help us
    resolve the dispute in your favor. You can do this in your dashboard, but if you
    prefer, you can use the API to submit evidence programmatically.Depending on your
    dispute type, different evidence fields will give you a better chance of winning
    your dispute. You may want to consult our guide to dispute types to help you figure
    out which evidence fields to provide.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-post-openapi.md
- name: Stripe - Add Disputes Dispute Close
  x-api-slug: disputesdisputeclose-post
  description: Closing the dispute for a charge indicates that you do not have any
    evidence to submit and are essentially ???dismissing??? the dispute, acknowledging
    it as lostThe status of the dispute will change from needs_response to lost. Closing
    a dispute is irreversible.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdisputeclose-post-openapi.md
- name: Stripe - Add Disputes Dispute Close
  x-api-slug: disputesdisputeclose-post
  description: Closing the dispute for a charge indicates that you do not have any
    evidence to submit and are essentially ???dismissing??? the dispute, acknowledging
    it as lostThe status of the dispute will change from needs_response to lost. Closing
    a dispute is irreversible.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdisputeclose-post-openapi.md
- name: Stripe - Add Disputes Dispute
  x-api-slug: disputesdispute-post
  description: When you get a dispute, contacting your customer is always the best
    first step. If that doesn???t work, you can submit evidence in order to help us
    resolve the dispute in your favor. You can do this in your dashboard, but if you
    prefer, you can use the API to submit evidence programmatically.Depending on your
    dispute type, different evidence fields will give you a better chance of winning
    your dispute. You may want to consult our guide to dispute types to help you figure
    out which evidence fields to provide.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-post-openapi.md
- name: Stripe - Get Disputes Dispute
  x-api-slug: disputesdispute-get
  description: Retrieves the dispute with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/disputesdispute-get-openapi.md
- name: Stripe - Add Charges Charge Dispute Close
  x-api-slug: chargeschargedisputeclose-post
  description: Post Charges, Charge, Dispute, Close
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedisputeclose-post-openapi.md
- name: Stripe - Add Charges Charge Dispute
  x-api-slug: chargeschargedispute-post
  description: Post Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedispute-post-openapi.md
- name: Stripe - Get Charges Charge Dispute
  x-api-slug: chargeschargedispute-get
  description: Get Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/disputes/master/_listings/stripe/chargeschargedispute-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://stride.api.gallery.streamdata.io
- type: x-api-stack
  url: http://stripe.stack.network
- type: x-base
  url: https://api.stripe.com/
- type: x-blog
  url: https://stripe.com/blog
- type: x-blog-rss
  url: https://stripe.com/blog/feed.rss
- type: x-change-log
  url: https://stripe.com/docs/upgrades
- type: x-crunchbase
  url: http://www.crunchbase.com/company/stripe
- type: x-crunchbase
  url: https://crunchbase.com/organization/stripe
- type: x-email
  url: info@stripe.com
- type: x-email
  url: privacy@stripe.com
- type: x-email
  url: atlas@stripe.com
- type: x-email
  url: notices@stripe.com
- type: x-email
  url: jane.diaz@stripe.com
- type: x-email
  url: nonprofit@stripe.com
- type: x-email
  url: support@stripe.com
- type: x-email
  url: dpo@stripe.com
- type: x-github
  url: https://github.com/stripe
- type: x-linkedin
  url: https://www.linkedin.com/company/stripe/
- type: x-pricing
  url: https://stripe.com/us/pricing
- type: x-twitter
  url: https://twitter.com/stripe
- type: x-website
  url: https://stripe.com/
- type: x-website
  url: http://stripe.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---