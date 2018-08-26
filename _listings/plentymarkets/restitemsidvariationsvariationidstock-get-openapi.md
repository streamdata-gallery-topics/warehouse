---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List stock of a variation per warehouse
  description: Lists stock of a variation per warehouse. The ID of the item and the
    ID of the variation must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounts/addresses/warehouse_relations:
    post:
      summary: Create an address warehouse relation
      description: Create an address warehouse relation.
      operationId: postRestAccountsAddressesWarehouseRelations
      x-api-path-slug: restaccountsaddresseswarehouse-relations-post
      responses:
        200:
          description: OK
      tags:
      - Address
      - Warehouse
      - Relation
  /rest/accounts/addresses/warehouse_relations/{relationId}:
    delete:
      summary: Delete an address warehouse relation
      description: Deletes an address warehouse relation. The ID of the relation must
        be specified.
      operationId: deleteRestAccountsAddressesWarehouseRelationsRelation
      x-api-path-slug: restaccountsaddresseswarehouse-relationsrelationid-delete
      parameters:
      - in: path
        name: relationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Warehouse
      - Relation
    put:
      summary: Update an address warehouse relation
      description: Updates an address warehouse relation. The ID of the relation must
        be specified.
      operationId: putRestAccountsAddressesWarehouseRelationsRelation
      x-api-path-slug: restaccountsaddresseswarehouse-relationsrelationid-put
      parameters:
      - in: path
        name: relationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Warehouse
      - Relation
  /rest/items/{id}/variations/{variationId}/stock:
    get:
      summary: List stock of a variation per warehouse
      description: Lists stock of a variation per warehouse. The ID of the item and
        the ID of the variation must be specified.
      operationId: getRestItemsVariationsVariationStock
      x-api-path-slug: restitemsidvariationsvariationidstock-get
      parameters:
      - in: query
        name: columns
        description: The properties to be loaded
      - in: path
        name: id
      - in: query
        name: itemId
        description: The ID of the item
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - Of
      - Variation
      - Per
      - Warehouse
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