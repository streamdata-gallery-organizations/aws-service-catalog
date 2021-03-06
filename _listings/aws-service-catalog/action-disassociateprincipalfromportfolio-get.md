---
swagger: "2.0"
info:
  title: AWS Service Catalog API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DisassociatePrincipalFromPortfolio:
    get:
      summary: ' Disassociate Principal From Portfolio '
      description: |-
        Disassociates a previously associated principal ARN from a specified
                 portfolio
      operationId: disassociatePrincipalFromPortfolio
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: PortfolioId
        description: The portfolio identifier
        type: string
      - in: query
        name: PrincipalARN
        description: The ARN representing the principal (IAM user, role, or group)
        type: string
      responses:
        200:
          description: OK
      tags:
      - portfolios
definitions: []
x-collection-name: AWS Service Catalog
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