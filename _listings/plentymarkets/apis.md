---
name: Plentymarkets
x-slug: plentymarkets
description: plentymarkets is an all-in-one e-commerce ERP solution, which combines
  a comprehensive stock management system with a versatile shop system and effortless
  multichannel sales. Thanks to comprehensive functions and interfaces that include
  all steps of the e-commerce value chain, you can use the cloud based software to
  completely automate all of your e-business processes as well as your companys own
  individual processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
x-kinRank: "7"
x-alexaRank: ""
tags: Warehouse
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/apis.md
specificationVersion: "0.14"
apis:
- name: plentymarkets REST-API - List stock of a variation per warehouse
  x-api-slug: restitemsidvariationsvariationidstock-get
  description: Lists stock of a variation per warehouse. The ID of the item and the
    ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidstock-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidstock-get-openapi.md
- name: plentymarkets REST-API - Create link between a variation and a warehouse
  x-api-slug: restitemsidvariationsvariationidvariation-warehouses-post
  description: Creates a link between a variation and a warehouse and adds warehouse
    data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouses-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouses-post-openapi.md
- name: plentymarkets REST-API - Delete link between a warehouse and a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-delete
  description: Deletes the link between a warehouse and a variation. The ID of the
    variation and the ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-delete-openapi.md
- name: plentymarkets REST-API - Get warehouse data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-get
  description: Gets the data of a warehouse linked to a variation. The ID of the variation
    and the ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-get-openapi.md
- name: plentymarkets REST-API - Update warehouse data of a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-put
  description: Updates the data of a warehouse linked to a variation. The ID of the
    variation and the ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-put-openapi.md
- name: plentymarkets REST-API - List stock by warehouse type
  x-api-slug: reststockmanagementstocktypestype-get
  description: Lists stock for all warehouses of the same warehouse type. The name
    of the type must be specified. Currently the only type available is 'sales'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementstocktypestype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementstocktypestype-get-openapi.md
- name: plentymarkets REST-API - List warehouse addresses
  x-api-slug: reststockmanagementwarehouseswarehouseidaddressesrelationtypeid-get
  description: List warehouse addresses. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidaddressesrelationtypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidaddressesrelationtypeid-get-openapi.md
- name: plentymarkets REST-API - Delete multiple warehouse locations
  x-api-slug: restwarehouseslocations-delete
  description: Deletes multiple warehouse locations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocations-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocations-delete-openapi.md
- name: plentymarkets REST-API - List warehouse locations
  x-api-slug: restwarehouseswarehouseidlocations-get
  description: Lists all warehouse locations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseswarehouseidlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseswarehouseidlocations-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.plentymarkets.co.uk/?ActionCall=WebActionRSS&rrss_id=1
- type: x-github
  url: https://github.com/plentymarkets
- type: x-twitter
  url: https://twitter.com/plentymarketsuk
- type: x-website
  url: http://www.plentymarkets.co.uk
- type: x-api-gallery
  url: http://pivotal.tracker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://plentymarkets.stack.network
- type: x-blog
  url: https://www.plentymarkets.co.uk/blog/
- type: x-pricing
  url: https://www.plentymarkets.co.uk/prices/
- type: x-website
  url: https://www.plentymarkets.co.uk
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---