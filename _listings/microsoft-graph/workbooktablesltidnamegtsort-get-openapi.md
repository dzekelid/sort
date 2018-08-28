---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Get Table Sort
  description: Get TableSort Retrieve the properties and relationships of tablesort
    object.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/range/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbooknamesltnamegtrangesortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/sort/apply:
    post:
      summary: Table Sort Apply
      description: 'TableSort: apply Perform a sort operation.'
      operationId: TableSort:Apply
      x-api-path-slug: workbooktablesltidnamegtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Apply
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/apply:
    post:
      summary: Table Sort Apply
      description: 'TableSort: apply Perform a sort operation.'
      operationId: TableSort:Apply
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/sort/clear:
    post:
      summary: Table Sort Clear
      description: 'TableSort: clear Clears the sorting that is currently on the table.
        While this doesn''t modify the table''s ordering, it clears the state of the
        header buttons.'
      operationId: TableSort:Clear
      x-api-path-slug: workbooktablesltidnamegtsortclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/clear:
    post:
      summary: Table Sort Clear
      description: 'TableSort: clear Clears the sorting that is currently on the table.
        While this doesn''t modify the table''s ordering, it clears the state of the
        header buttons.'
      operationId: TableSort:Clear
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Clear
  /workbook/tables(&lt;id|name&gt;)/sort:
    get:
      summary: Get Table Sort
      description: Get TableSort Retrieve the properties and relationships of tablesort
        object.
      operationId: GetTableSort
      x-api-path-slug: workbooktablesltidnamegtsort-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
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