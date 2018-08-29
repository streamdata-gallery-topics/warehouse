---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get a warehouse
  description: Gets a warehouse. The id of the warehouse must be specified.
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
  /rest/items/{id}/variations/{variationId}/variation_warehouses:
    post:
      summary: Create link between a variation and a warehouse
      description: Creates a link between a variation and a warehouse and adds warehouse
        data.
      operationId: postRestItemsVariationsVariationVariationWarehouses
      x-api-path-slug: restitemsidvariationsvariationidvariation-warehouses-post
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Link
      - Between
      - Variation
      - Warehouse
  /rest/items/{id}/variations/{variationId}/variation_warehouses/{warehouseId}:
    delete:
      summary: Delete link between a warehouse and a variation
      description: Deletes the link between a warehouse and a variation. The ID of
        the variation and the ID of the warehouse must be specified.
      operationId: deleteRestItemsVariationsVariationVariationWarehousesWarehouse
      x-api-path-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - Link
      - Between
      - Warehouse
      - Variation
    get:
      summary: Get warehouse data for a variation
      description: Gets the data of a warehouse linked to a variation. The ID of the
        variation and the ID of the warehouse must be specified.
      operationId: getRestItemsVariationsVariationVariationWarehousesWarehouse
      x-api-path-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Dataa
      - Variation
    put:
      summary: Update warehouse data of a variation
      description: Updates the data of a warehouse linked to a variation. The ID of
        the variation and the ID of the warehouse must be specified.
      operationId: putRestItemsVariationsVariationVariationWarehousesWarehouse
      x-api-path-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-put
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Data
      - Of
      - Variation
  /rest/stockmanagement/stock/types/{type}:
    get:
      summary: List stock by warehouse type
      description: Lists stock for all warehouses of the same warehouse type. The
        name of the type must be specified. Currently the only type available is 'sales'.
      operationId: getRestStockmanagementStockTypesType
      x-api-path-slug: reststockmanagementstocktypestype-get
      parameters:
      - in: query
        name: columns
        description: The properties to be loaded
      - in: query
        name: itemsPerPage
        description: The number of items per page
      - in: query
        name: page
        description: The requested page
      - in: path
        name: type
      - in: query
        name: updatedAtFrom
        description: Filter that restricts the search result to stock that were last
          updated on the specified date
      - in: query
        name: updatedAtTo
        description: Filter that restricts the search result to stock that were last
          updated within a specified period of time
      - in: query
        name: variationId
        description: Filter that restricts the search result to stock with a variation
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - By
      - Warehouse
      - Type
  /rest/stockmanagement/warehouses:
    post:
      summary: Create a warehouse
      description: Create a warehouse.
      operationId: postRestStockmanagementWarehouses
      x-api-path-slug: reststockmanagementwarehouses-post
      parameters:
      - in: body
        name: /rest/stockmanagement/warehouses
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Warehouse
  /rest/stockmanagement/warehouses/addresses:
    post:
      summary: Create an address for existing warehouse
      description: Create an address for existing warehouse.
      operationId: postRestStockmanagementWarehousesAddresses
      x-api-path-slug: reststockmanagementwarehousesaddresses-post
      responses:
        200:
          description: OK
      tags:
      - Addressexisting
      - Warehouse
  /rest/stockmanagement/warehouses/{warehouseId}:
    get:
      summary: Get a warehouse
      description: Gets a warehouse. The id of the warehouse must be specified.
      operationId: getRestStockmanagementWarehousesWarehouse
      x-api-path-slug: reststockmanagementwarehouseswarehouseid-get
      parameters:
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: Related objects to be loaded
      responses:
        200:
          description: OK
      tags:
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