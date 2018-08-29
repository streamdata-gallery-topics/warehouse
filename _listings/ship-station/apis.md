---
name: Ship Station
x-slug: ship-station
description: ShipStation is a web-based shipping solution that streamlines the order
  fulfillment process for your online business. ShipStation consolidates orders from
  over 70 ecommerce channels, creates shipping labels, packing slips, and pick lists
  in batch, communicates tracking information to your customers, provides endless
  automation, filters, and views, wireless printing, a mobile app, and a lot more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Warehouse
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/ship-station/apis.md
specificationVersion: "0.14"
apis:
- name: Ship Station Developer Portal - Create Warehouse
  x-api-slug: warehousescreatewarehouse-post
  description: |-
    Adds a Ship From Location (formerly known as warehouse) to your account.  The body of this request should specify the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
     ``warehouseName`` | string, optional | Name of Ship From Location.
     ``originAddress`` | Address, required | The origin address.  Shipping rates will be calculated from this address.  Use the [**Address**](https://www.shipstation.com/developer-api/#/reference/model-address) model.
     ``returnAddress`` | Address, optional | The return address.  If a "returnAddress" is not specified, your "originAddress" will be used as your "returnAddress". Use the [**Address**](https://www.shipstation.com/developer-api/#/reference/model-address) model.
     ``isDefault`` | boolean, optional | Specifies whether or not this will be your default Ship From Location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/ship-station/warehousescreatewarehouse-post-openapi.md
- name: Ship Station Developer Portal - Get Warehouse
  x-api-slug: warehouseswarehouseid-get
  description: Returns a list of active Ship From Locations (formerly known as warehouses)
    on the ShipStation account. Warehouses are now called "Ship From Locations" in
    the UI.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/ship-station/warehouseswarehouseid-get-openapi.md
- name: Ship Station Developer Portal - Update Warehouse
  x-api-slug: warehouseswarehouseid-put
  description: Updates an existing Ship From Location (formerly known as warehouse).
    This call does not currently support partial updates. The entire resource must
    be provided in the body of the request. If a "returnAddress" object is not specified,
    your "originAddress" will be used as your "returnAddress".
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/ship-station/warehouseswarehouseid-put-openapi.md
- name: Ship Station Developer Portal - List Warehouses
  x-api-slug: warehouses-get
  description: Retrieves a list of your Ship From Locations (formerly known as warehouses).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/ship-station/warehouses-get-openapi.md
- name: Ship Station Developer Portal - List Warehouses
  x-api-slug: warehouses-get
  description: Retrieves a list of your Ship From Locations (formerly known as warehouses).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/ship-station/warehouses-get-openapi.md
- name: Ship Station Developer Portal - List Warehouses
  x-api-slug: warehouses-get
  description: Retrieves a list of your Ship From Locations (formerly known as warehouses).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/ship-station/warehouses-get-openapi.md
x-common:
- type: x-website
  url: http://bit.ly/_ShipStation
- type: x-api-gallery
  url: http://server.density.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ship.station.stack.network
- type: x-blog
  url: https://www.shipstation.com/blog/
- type: x-developer
  url: https://shipstation.docs.apiary.io/#
- type: x-github
  url: https://github.com/shipstation
- type: x-partners
  url: https://www.shipstation.com/partners/
- type: x-pricing
  url: https://www.shipstation.com/pricing/
- type: x-twitter
  url: https://twitter.com/ShipStation
- type: x-website
  url: http://shipstation.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---