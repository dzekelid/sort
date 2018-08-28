swagger: "2.0"
x-collection-name: Clover
x-complete: 1
info:
  title: ""
  version: 1.0.0
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