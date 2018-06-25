---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Sort
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Range Sort Apply
  x-api-slug: microsoft-graph
  description: 'RangeSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/sort/apply
  tags: Range, Sort, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooknamesltnamegtrangesortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooknamesltnamegtrangesortapply-post-openapi.md
- name: Microsoft Graph Range Sort Apply
  x-api-slug: microsoft-graph
  description: 'RangeSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/sort/apply
  tags: Range, Sort, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtsortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtsortapply-post-openapi.md
- name: Microsoft Graph Range Sort Apply
  x-api-slug: microsoft-graph
  description: 'RangeSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/sort/apply
  tags: Range, Sort, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post-openapi.md
- name: Microsoft Graph Table Sort Apply
  x-api-slug: microsoft-graph
  description: 'TableSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/sort/apply
  tags: Table, Sort, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooktablesltidnamegtsortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooktablesltidnamegtsortapply-post-openapi.md
- name: Microsoft Graph Table Sort Apply
  x-api-slug: microsoft-graph
  description: 'TableSort: apply Perform a sort operation.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/apply
  tags: Table, Sort, Apply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortapply-post-openapi.md
- name: Microsoft Graph Table Sort Clear
  x-api-slug: microsoft-graph
  description: 'TableSort: clear Clears the sorting that is currently on the table.
    While this doesn''t modify the table''s ordering, it clears the state of the header
    buttons.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/sort/clear
  tags: Table, Sort, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooktablesltidnamegtsortclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooktablesltidnamegtsortclear-post-openapi.md
- name: Microsoft Graph Table Sort Clear
  x-api-slug: microsoft-graph
  description: 'TableSort: clear Clears the sorting that is currently on the table.
    While this doesn''t modify the table''s ordering, it clears the state of the header
    buttons.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/clear
  tags: Table, Sort, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortclear-post-openapi.md
- name: Microsoft Graph Get Table Sort
  x-api-slug: microsoft-graph
  description: Get TableSort Retrieve the properties and relationships of tablesort
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/sort
  tags: Table, Sort
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooktablesltidnamegtsort-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooktablesltidnamegtsort-get-openapi.md
- name: Microsoft Graph Get Table Sort
  x-api-slug: microsoft-graph
  description: Get TableSort Retrieve the properties and relationships of tablesort
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort
  tags: Table, Sort
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsort-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsort-get-openapi.md
- name: Microsoft Graph Table Sort Reapply
  x-api-slug: microsoft-graph
  description: 'TableSort: reapply Reapplies the current sorting parameters to the
    table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/sort/reapply
  tags: Table, Sort, Reapply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooktablesltidnamegtsortreapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbooktablesltidnamegtsortreapply-post-openapi.md
- name: Microsoft Graph Table Sort Reapply
  x-api-slug: microsoft-graph
  description: 'TableSort: reapply Reapplies the current sorting parameters to the
    table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/reapply
  tags: Table, Sort, Reapply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortreapply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortreapply-post-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Sort
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sort/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---