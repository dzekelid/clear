swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/clear:
    post:
      summary: Filter Clear
      description: 'Filter: clear Clear the filter on the given column.'
      operationId: Filter:Clear
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtfilterclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Filter
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/filter/clear:
    post:
      summary: Filter Clear
      description: 'Filter: clear Clear the filter on the given column.'
      operationId: Filter:Clear
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtfilterclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Filter
      - Clear
  /workbook/names(&lt;name&gt;)/range/clear:
    post:
      summary: Range Clear
      description: 'Range: clear Clear range values, format, fill, border, etc.'
      operationId: Range:Clear
      x-api-path-slug: workbooknamesltnamegtrangeclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/clear:
    post:
      summary: Range Clear
      description: 'Range: clear Clear range values, format, fill, border, etc.'
      operationId: Range:Clear
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Clear
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/clear:
    post:
      summary: Range Clear
      description: 'Range: clear Clear range values, format, fill, border, etc.'
      operationId: Range:Clear
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Clear
  /workbook/names(&lt;name&gt;)/range/format/fill/clear:
    post:
      summary: Range Fill Clear
      description: 'RangeFill: clear Resets the range background.'
      operationId: RangeFill:Clear
      x-api-path-slug: workbooknamesltnamegtrangeformatfillclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill/clear:
    post:
      summary: Range Fill Clear
      description: 'RangeFill: clear Resets the range background.'
      operationId: RangeFill:Clear
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
      - Clear
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill/clear:
    post:
      summary: Range Fill Clear
      description: 'RangeFill: clear Resets the range background.'
      operationId: RangeFill:Clear
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
      - Clear
  /workbook/tables(&lt;id|name&gt;)/clearFilters:
    post:
      summary: Table Clear Filters
      description: 'Table: clearFilters Clears all the filters currently applied on
        the table.'
      operationId: Table:ClearFilters
      x-api-path-slug: workbooktablesltidnamegtclearfilters-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Clear
      - Filters
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/clearFilters:
    post:
      summary: Table Clear Filters
      description: 'Table: clearFilters Clears all the filters currently applied on
        the table.'
      operationId: Table:ClearFilters
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtclearfilters-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Clear
      - Filters
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