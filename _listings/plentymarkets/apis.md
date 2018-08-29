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
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/apis.md
specificationVersion: "0.14"
apis:
- name: plentymarkets REST-API - Create an address warehouse relation
  x-api-slug: restaccountsaddresseswarehouse-relations-post
  description: Create an address warehouse relation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restaccountsaddresseswarehouse-relations-post-openapi.md
- name: plentymarkets REST-API - Delete an address warehouse relation
  x-api-slug: restaccountsaddresseswarehouse-relationsrelationid-delete
  description: Deletes an address warehouse relation. The ID of the relation must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restaccountsaddresseswarehouse-relationsrelationid-delete-openapi.md
- name: plentymarkets REST-API - Update an address warehouse relation
  x-api-slug: restaccountsaddresseswarehouse-relationsrelationid-put
  description: Updates an address warehouse relation. The ID of the relation must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restaccountsaddresseswarehouse-relationsrelationid-put-openapi.md
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
- name: plentymarkets REST-API - Create a warehouse
  x-api-slug: reststockmanagementwarehouses-post
  description: Create a warehouse.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementwarehouses-post-openapi.md
- name: plentymarkets REST-API - Create an address for existing warehouse
  x-api-slug: reststockmanagementwarehousesaddresses-post
  description: Create an address for existing warehouse.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementwarehousesaddresses-post-openapi.md
- name: plentymarkets REST-API - Get a warehouse
  x-api-slug: reststockmanagementwarehouseswarehouseid-get
  description: Gets a warehouse. The id of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseid-get-openapi.md
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
- name: plentymarkets REST-API - List stock by warehouse
  x-api-slug: reststockmanagementwarehouseswarehouseidstock-get
  description: Lists stock for a warehouse. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstock-get-openapi.md
- name: plentymarkets REST-API - List stock of a warehouse per storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
  description: Lists stock of a warehouse for each variation and storage location.
    The stock will only be listed if the stock is positive. Negative stock will not
    be listed. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Create a warehouse location layout
  x-api-slug: restwarehouseslayouts-post
  description: Creates a warehouse location layout
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslayouts-post-openapi.md
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
- name: plentymarkets REST-API - Create a warehouse location
  x-api-slug: restwarehouseslocations-post
  description: Creates a warehouse location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocations-post-openapi.md
- name: plentymarkets REST-API - Get warehouse location details
  x-api-slug: restwarehouseslocationsdetails-get
  description: Gets warehouse location details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationsdetails-get-openapi.md
- name: plentymarkets REST-API - Create a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensions-post
  description: Creates a warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationsdimensions-post-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-delete
  description: Deletes a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-get
  description: Gets a warehouse location dimension by ID. The warehouse location ID
    is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-put
  description: Updates a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-put-openapi.md
- name: plentymarkets REST-API - Create a warehouse location level
  x-api-slug: restwarehouseslocationslevels-post
  description: Creates a warehouse location level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationslevels-post-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-delete
  description: Deletes a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-get
  description: Gets a warehouse location level by ID. The warehouse location ID is
    required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-put
  description: Updates a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-put-openapi.md
- name: plentymarkets REST-API - Create multiple warehouse location dimensions
  x-api-slug: restwarehouseslocationsmultiple-dimensions-post
  description: Creates multiple warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationsmultiple-dimensions-post-openapi.md
- name: plentymarkets REST-API - Generate warehouse location preview and saves it
  x-api-slug: restwarehouseslocationspreviews-post
  description: Generates warehouse location preview and saves it
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationspreviews-post-openapi.md
- name: plentymarkets REST-API - Generate the warehouse location label
  x-api-slug: restwarehouseslocationswarehouseidlabel-get
  description: Generates the warehouse location label
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationswarehouseidlabel-get-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-delete
  description: Deletes a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-get
  description: Gets a warehouse location by ID. The warehouse location ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-put
  description: Updates a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-put-openapi.md
- name: plentymarkets REST-API - Get a warehouse location structure
  x-api-slug: restwarehousesstructurewarehouseid-get
  description: Gets a warehouse location structure by warehouse ID. The warehouse
    ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehousesstructurewarehouseid-get-openapi.md
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
- name: plentymarkets REST-API - List warehouse location dimensions
  x-api-slug: restwarehouseswarehouseidlocationsdimensions-get
  description: Lists all warehouse location dimensions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseswarehouseidlocationsdimensions-get-openapi.md
- name: plentymarkets REST-API - List warehouse location levels
  x-api-slug: restwarehouseswarehouseidlocationslevels-get
  description: Lists all warehouse location levels.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restwarehouseswarehouseidlocationslevels-get-openapi.md
- name: plentymarkets REST-API - List the warehouses linked to a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouses-get
  description: Lists the warehouses linked to a variation. The ID of the item and
    the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouses-get-openapi.md
- name: plentymarkets REST-API - List warehouses
  x-api-slug: reststockmanagementwarehouses-get
  description: Lists warehouses without applying any filters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementwarehouses-get-openapi.md
- name: plentymarkets REST-API - List the warehouses linked to a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouses-get
  description: Lists the warehouses linked to a variation. The ID of the item and
    the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouses-get-openapi.md
- name: plentymarkets REST-API - List warehouses
  x-api-slug: reststockmanagementwarehouses-get
  description: Lists warehouses without applying any filters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementwarehouses-get-openapi.md
- name: plentymarkets REST-API - List warehouses
  x-api-slug: reststockmanagementwarehouses-get
  description: Lists warehouses without applying any filters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/reststockmanagementwarehouses-get-openapi.md
- name: plentymarkets REST-API - List the warehouses linked to a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouses-get
  description: Lists the warehouses linked to a variation. The ID of the item and
    the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/warehouse/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouses-get-openapi.md
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