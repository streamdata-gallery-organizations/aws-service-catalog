---
swagger: "2.0"
x-collection-name: AWS Service Catalog
x-complete: 0
info:
  title: AWS Service Catalog API Accept Portfolio Share
  version: 1.0.0
  description: Accepts an offer to share a portfolio.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AcceptPortfolioShare:
    get:
      summary: Accept Portfolio Share
      description: Accepts an offer to share a portfolio.
      operationId: acceptPortfolioShare
      x-api-path-slug: actionacceptportfolioshare-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: PortfolioId
        description: The portfolio identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Portfolios
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