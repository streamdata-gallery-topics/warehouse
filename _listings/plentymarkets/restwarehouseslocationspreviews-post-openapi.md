---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Generate warehouse location preview and saves it
  description: Generates warehouse location preview and saves it
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
  /rest/stockmanagement/warehouses/{warehouseId}/addresses/{relationTypeId?}:
    get:
      summary: List warehouse addresses
      description: List warehouse addresses. The ID of the warehouse must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseAddressesRelationtype
      x-api-path-slug: reststockmanagementwarehouseswarehouseidaddressesrelationtypeid-get
      parameters:
      - in: path
        name: relationTypeId?
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - List
      - Warehouse
      - Addresses
  /rest/stockmanagement/warehouses/{warehouseId}/stock:
    get:
      summary: List stock by warehouse
      description: Lists stock for a warehouse. The ID of the warehouse must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseStock
      x-api-path-slug: reststockmanagementwarehouseswarehouseidstock-get
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
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - By
      - Warehouse
  /rest/stockmanagement/warehouses/{warehouseId}/stock/storageLocations:
    get:
      summary: List stock of a warehouse per storage location
      description: Lists stock of a warehouse for each variation and storage location.
        The stock will only be listed if the stock is positive. Negative stock will
        not be listed. The ID of the warehouse must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseStockStoragelocations
      x-api-path-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
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
      - in: query
        name: storageLocationId
        description: Filter that restricts the search result to stock of a storage
          location
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
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: Load additional relations for a StockStorageLocation
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - Of
      - Warehouse
      - Per
      - Storage
      - Location
  /rest/warehouses/layouts:
    post:
      summary: Create a warehouse location layout
      description: Creates a warehouse location layout
      operationId: postRestWarehousesLayouts
      x-api-path-slug: restwarehouseslayouts-post
      parameters:
      - in: query
        name: dimensionId
        description: The warehouse location dimension ID of the warehouse location
          level
      - in: query
        name: isActiveForPickupPath
        description: Active flag for pickup path of the warehouse location dimension
      - in: query
        name: label
        description: The label of the warehouse location
      - in: query
        name: level
        description: The level of the warehouse location dimension
      - in: query
        name: levelId
        description: The warehouse location level ID of the warehouse location
      - in: query
        name: name
        description: The name of the warehouse location dimension
      - in: query
        name: parentId
        description: The parent ID of the warehouse location dimension
      - in: query
        name: position
        description: The position of the warehouse location level
      - in: query
        name: purposeKey
        description: The location type key of the warehouse location
      - in: query
        name: separator
        description: The separator of the warehouse location dimension
      - in: query
        name: shortcut
        description: The shortcut of the warehouse location dimension
      - in: query
        name: statusKey
        description: The location status key of the warehouse location
      - in: query
        name: warehouseId
        description: The warehouse ID of the warehouse location dimension
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Layout
  /rest/warehouses/locations:
    delete:
      summary: Delete multiple warehouse locations
      description: Deletes multiple warehouse locations
      operationId: deleteRestWarehousesLocations
      x-api-path-slug: restwarehouseslocations-delete
      responses:
        200:
          description: OK
      tags:
      - Multiple
      - Warehouse
      - Locations
    post:
      summary: Create a warehouse location
      description: Creates a warehouse location.
      operationId: postRestWarehousesLocations
      x-api-path-slug: restwarehouseslocations-post
      parameters:
      - in: query
        name: label
        description: The label of the warehouse location
      - in: query
        name: levelId
        description: The warehouse location level ID of the warehouse location
      - in: query
        name: position
        description: The position of the warehouse location
      - in: query
        name: purposeKey
        description: The location type key of the warehouse location
      - in: query
        name: statusKey
        description: The location status key of the warehouse location
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
  /rest/warehouses/locations/details:
    get:
      summary: Get warehouse location details
      description: Gets warehouse location details
      operationId: getRestWarehousesLocationsDetails
      x-api-path-slug: restwarehouseslocationsdetails-get
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Details
  /rest/warehouses/locations/dimensions:
    post:
      summary: Create a warehouse location dimension
      description: Creates a warehouse location dimension.
      operationId: postRestWarehousesLocationsDimensions
      x-api-path-slug: restwarehouseslocationsdimensions-post
      parameters:
      - in: query
        name: isActiveForPickupPath
        description: Active flag for pickup path of the warehouse location dimension
      - in: query
        name: level
        description: The level of the warehouse location dimension
      - in: query
        name: name
        description: The name of the warehouse location dimension
      - in: query
        name: parentId
        description: The parent ID of the warehouse location dimension
      - in: query
        name: separator
        description: The separator of the warehouse location dimension
      - in: query
        name: shortcut
        description: The shortcut of the warehouse location dimension
      - in: query
        name: warehouseId
        description: The warehouse ID of the warehouse location dimension
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Dimension
  /rest/warehouses/locations/dimensions/{warehouseLocationDimensionId}:
    delete:
      summary: Delete a warehouse location dimension
      description: Deletes a warehouse location dimension
      operationId: deleteRestWarehousesLocationsDimensionsWarehouselocationdimension
      x-api-path-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-delete
      parameters:
      - in: path
        name: warehouseLocationDimensionId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Dimension
    get:
      summary: Get a warehouse location dimension
      description: Gets a warehouse location dimension by ID. The warehouse location
        ID is required.
      operationId: getRestWarehousesLocationsDimensionsWarehouselocationdimension
      x-api-path-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-get
      parameters:
      - in: path
        name: warehouseLocationDimensionId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Dimension
    put:
      summary: Update a warehouse location dimension
      description: Updates a warehouse location dimension
      operationId: putRestWarehousesLocationsDimensionsWarehouselocationdimension
      x-api-path-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-put
      parameters:
      - in: path
        name: warehouseLocationDimensionId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Dimension
  /rest/warehouses/locations/levels:
    post:
      summary: Create a warehouse location level
      description: Creates a warehouse location level.
      operationId: postRestWarehousesLocationsLevels
      x-api-path-slug: restwarehouseslocationslevels-post
      parameters:
      - in: query
        name: dimensionId
        description: The warehouse location dimension ID of the warehouse location
          level
      - in: query
        name: name
        description: The name of the warehouse location level
      - in: query
        name: parentId
        description: The parent ID of the warehouse location level
      - in: query
        name: position
        description: The position of the warehouse location level
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Level
  /rest/warehouses/locations/levels/{warehouseLocationLevelId}:
    delete:
      summary: Delete a warehouse location level
      description: Deletes a warehouse location level
      operationId: deleteRestWarehousesLocationsLevelsWarehouselocationlevel
      x-api-path-slug: restwarehouseslocationslevelswarehouselocationlevelid-delete
      parameters:
      - in: path
        name: warehouseLocationLevelId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Level
    get:
      summary: Get a warehouse location level
      description: Gets a warehouse location level by ID. The warehouse location ID
        is required.
      operationId: getRestWarehousesLocationsLevelsWarehouselocationlevel
      x-api-path-slug: restwarehouseslocationslevelswarehouselocationlevelid-get
      parameters:
      - in: path
        name: warehouseLocationLevelId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Level
    put:
      summary: Update a warehouse location level
      description: Updates a warehouse location level
      operationId: putRestWarehousesLocationsLevelsWarehouselocationlevel
      x-api-path-slug: restwarehouseslocationslevelswarehouselocationlevelid-put
      parameters:
      - in: path
        name: warehouseLocationLevelId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Level
  /rest/warehouses/locations/multiple_dimensions:
    post:
      summary: Create multiple warehouse location dimensions
      description: Creates multiple warehouse location dimension.
      operationId: postRestWarehousesLocationsMultipleDimensions
      x-api-path-slug: restwarehouseslocationsmultiple-dimensions-post
      responses:
        200:
          description: OK
      tags:
      - Multiple
      - Warehouse
      - Location
      - Dimensions
  /rest/warehouses/locations/previews:
    post:
      summary: Generate warehouse location preview and saves it
      description: Generates warehouse location preview and saves it
      operationId: postRestWarehousesLocationsPreviews
      x-api-path-slug: restwarehouseslocationspreviews-post
      responses:
        200:
          description: OK
      tags:
      - Generate
      - Warehouse
      - Location
      - Preview
      - Saves
      - It
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