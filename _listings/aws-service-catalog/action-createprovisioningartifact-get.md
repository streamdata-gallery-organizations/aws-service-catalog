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
  /?Action=CreateProvisioningArtifact:
    get:
      summary: ' Create Provisioning Artifact '
      description: Create a new provisioning artifact for the specified product
      operationId: createProvisioningArtifact
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: IdempotencyToken
        description: A token to disambiguate duplicate requests
        type: string
      - in: query
        name: Parameters
        description: The parameters to use when creating the new provisioning artifact
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - provisioning artifacts
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