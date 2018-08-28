---
swagger: "2.0"
x-collection-name: Clover
x-complete: 0
info:
  title: Clover Update the priorities for a collection of up to 200 modifier groups
    at a time
  version: 1.0.0
  description: Update the priorities for a collection of up to 200 modifier groups
    at a time.
host: /merchants
basePath: https://api.clover.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/merchants/{mId}/modifier_group_sort_orders:
    post:
      summary: Update the priorities for a collection of up to 200 modifier groups
        at a time
      description: Update the priorities for a collection of up to 200 modifier groups
        at a time.
      operationId: UpdateModifierGroupSortOrders
      x-api-path-slug: v3merchantsmidmodifier-group-sort-orders-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Modifier
      - Group
      - Sort
      - Orders
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