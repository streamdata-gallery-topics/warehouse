---
swagger: "2.0"
x-collection-name: Ship Station
x-complete: 0
info:
  title: Ship Station Create Warehouse
  description: |-
    Adds a Ship From Location (formerly known as warehouse) to your account.  The body of this request should specify the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
     ``warehouseName`` | string, optional | Name of Ship From Location.
     ``originAddress`` | Address, required | The origin address.  Shipping rates will be calculated from this address.  Use the [**Address**](https://www.shipstation.com/developer-api/#/reference/model-address) model.
     ``returnAddress`` | Address, optional | The return address.  If a "returnAddress" is not specified, your "originAddress" will be used as your "returnAddress". Use the [**Address**](https://www.shipstation.com/developer-api/#/reference/model-address) model.
     ``isDefault`` | boolean, optional | Specifies whether or not this will be your default Ship From Location.
  version: 1.0.0
host: ssapi.shipstation.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /warehouses/createwarehouse:
    post:
      summary: Create Warehouse
      description: |-
        Adds a Ship From Location (formerly known as warehouse) to your account.  The body of this request should specify the following attributes:

        Name               |Data Type          |Description
        -------------------|-------------------|-------------------
         ``warehouseName`` | string, optional | Name of Ship From Location.
         ``originAddress`` | Address, required | The origin address.  Shipping rates will be calculated from this address.  Use the [**Address**](https://www.shipstation.com/developer-api/#/reference/model-address) model.
         ``returnAddress`` | Address, optional | The return address.  If a "returnAddress" is not specified, your "originAddress" will be used as your "returnAddress". Use the [**Address**](https://www.shipstation.com/developer-api/#/reference/model-address) model.
         ``isDefault`` | boolean, optional | Specifies whether or not this will be your default Ship From Location.
      operationId: warehouses.createwarehouse.post
      x-api-path-slug: warehousescreatewarehouse-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
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