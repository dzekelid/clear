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
tags: Clear
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Filter Clear
  x-api-slug: microsoft-graph
  description: 'Filter: clear Clear the filter on the given column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/clear
  tags: Filter, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtfilterclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtfilterclear-post-openapi.md
- name: Microsoft Graph Filter Clear
  x-api-slug: microsoft-graph
  description: 'Filter: clear Clear the filter on the given column.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/clear
  tags: Filter, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtfilterclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtfilterclear-post-openapi.md
- name: Microsoft Graph Range Clear
  x-api-slug: microsoft-graph
  description: 'Range: clear Clear range values, format, fill, border, etc.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/clear
  tags: Range, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooknamesltnamegtrangeclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooknamesltnamegtrangeclear-post-openapi.md
- name: Microsoft Graph Range Clear
  x-api-slug: microsoft-graph
  description: 'Range: clear Clear range values, format, fill, border, etc.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/clear
  tags: Range, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtclear-post-openapi.md
- name: Microsoft Graph Range Clear
  x-api-slug: microsoft-graph
  description: 'Range: clear Clear range values, format, fill, border, etc.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/clear
  tags: Range, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeclear-post-openapi.md
- name: Microsoft Graph Range Fill Clear
  x-api-slug: microsoft-graph
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/fill/clear
  tags: Range, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfillclear-post-openapi.md
- name: Microsoft Graph Range Fill Clear
  x-api-slug: microsoft-graph
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill/clear
  tags: Range, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post-openapi.md
- name: Microsoft Graph Range Fill Clear
  x-api-slug: microsoft-graph
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill/clear
  tags: Range, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post-openapi.md
- name: Microsoft Graph Table Clear Filters
  x-api-slug: microsoft-graph
  description: 'Table: clearFilters Clears all the filters currently applied on the
    table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/clearFilters
  tags: Table, Clear, Filters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooktablesltidnamegtclearfilters-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooktablesltidnamegtclearfilters-post-openapi.md
- name: Microsoft Graph Table Clear Filters
  x-api-slug: microsoft-graph
  description: 'Table: clearFilters Clears all the filters currently applied on the
    table.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/clearFilters
  tags: Table, Clear, Filters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtclearfilters-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtclearfilters-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooktablesltidnamegtsortclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbooktablesltidnamegtsortclear-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtsortclear-post-openapi.md
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
  tags: Clear
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/microsoft-graph/openapi.md
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