---
swagger: "2.0"
x-collection-name: AWS Service Catalog
x-complete: 0
info:
  title: AWS Service Catalog API List Launch Paths
  version: 1.0.0
  description: Returns a paginated list of all paths to a specified product.
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
  /?Action=AssociatePrincipalWithPortfolio:
    get:
      summary: Associate Principal With Portfolio
      description: Associates the specified principal ARN with the specified portfolio.
      operationId: associatePrincipalWithPortfolio
      x-api-path-slug: actionassociateprincipalwithportfolio-get
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
      - in: query
        name: PrincipalType
        description: The principal type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Portfolios
  /?Action=AssociateProductWithPortfolio:
    get:
      summary: Associate Product With Portfolio
      description: Associates a product with a portfolio.
      operationId: associateProductWithPortfolio
      x-api-path-slug: actionassociateproductwithportfolio-get
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
        name: ProductId
        description: The product identifier
        type: string
      - in: query
        name: SourcePortfolioId
        description: The identifier of the source portfolio to use with this association
        type: string
      responses:
        200:
          description: OK
      tags:
      - Portfolios
  /?Action=CreateConstraint:
    get:
      summary: Create Constraint
      description: Creates a new constraint.
      operationId: createConstraint
      x-api-path-slug: actioncreateconstraint-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Description
        description: The text description of the constraint
        type: string
      - in: query
        name: IdempotencyToken
        description: A token to disambiguate duplicate requests
        type: string
      - in: query
        name: Parameters
        description: The constraint parameters
        type: string
      - in: query
        name: PortfolioId
        description: The portfolio identifier
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      - in: query
        name: Type
        description: The type of the constraint
        type: string
      responses:
        200:
          description: OK
      tags:
      - Constraints
  /?Action=CreatePortfolio:
    get:
      summary: Create Portfolio
      description: Creates a new portfolio.
      operationId: createPortfolio
      x-api-path-slug: actioncreateportfolio-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Description
        description: The text description of the portfolio
        type: string
      - in: query
        name: DisplayName
        description: The name to use for display purposes
        type: string
      - in: query
        name: IdempotencyToken
        description: A token to disambiguate duplicate requests
        type: string
      - in: query
        name: ProviderName
        description: The name of the portfolio provider
        type: string
      - in: query
        name: Tags
        description: Tags to associate with the new portfolio
        type: string
      responses:
        200:
          description: OK
      tags:
      - Portfolios
  /?Action=CreatePortfolioShare:
    get:
      summary: Create Portfolio Share
      description: Creates a new portfolio share.
      operationId: createPortfolioShare
      x-api-path-slug: actioncreateportfolioshare-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: AccountId
        description: The account ID with which to share the portfolio
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
  /?Action=CreateProduct:
    get:
      summary: Create Product
      description: Creates a new product.
      operationId: createProduct
      x-api-path-slug: actioncreateproduct-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Description
        description: The text description of the product
        type: string
      - in: query
        name: Distributor
        description: The distributor of the product
        type: string
      - in: query
        name: IdempotencyToken
        description: A token to disambiguate duplicate requests
        type: string
      - in: query
        name: Name
        description: The name of the product
        type: string
      - in: query
        name: Owner
        description: The owner of the product
        type: string
      - in: query
        name: ProductType
        description: The type of the product to create
        type: string
      - in: query
        name: ProvisioningArtifactParameters
        description: Parameters for the provisioning artifact
        type: string
      - in: query
        name: SupportDescription
        description: Support information about the product
        type: string
      - in: query
        name: SupportEmail
        description: Contact email for product support
        type: string
      - in: query
        name: SupportUrl
        description: Contact URL for product support
        type: string
      - in: query
        name: Tags
        description: Tags to associate with the new product
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=CreateProvisioningArtifact:
    get:
      summary: Create Provisioning Artifact
      description: Create a new provisioning artifact for the specified product.
      operationId: createProvisioningArtifact
      x-api-path-slug: actioncreateprovisioningartifact-get
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
      - Provisioning Artifacts
  /?Action=DeleteConstraint:
    get:
      summary: Delete Constraint
      description: Deletes the specified constraint.
      operationId: deleteConstraint
      x-api-path-slug: actiondeleteconstraint-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the constraint to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Constraints
  /?Action=DeletePortfolio:
    get:
      summary: Delete Portfolio
      description: Deletes the specified portfolio.
      operationId: deletePortfolio
      x-api-path-slug: actiondeleteportfolio-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the portfolio for the delete request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Portfolios
  /?Action=DeletePortfolioShare:
    get:
      summary: Delete Portfolio Share
      description: Deletes the specified portfolio share.
      operationId: deletePortfolioShare
      x-api-path-slug: actiondeleteportfolioshare-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: AccountId
        description: The account ID associated with the share to delete
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
  /?Action=DeleteProduct:
    get:
      summary: Delete Product
      description: Deletes the specified product.
      operationId: deleteProduct
      x-api-path-slug: actiondeleteproduct-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the product for the delete request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=DeleteProvisioningArtifact:
    get:
      summary: Delete Provisioning Artifact
      description: Deletes the specified provisioning artifact.
      operationId: deleteProvisioningArtifact
      x-api-path-slug: actiondeleteprovisioningartifact-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      - in: query
        name: ProvisioningArtifactId
        description: The identifier of the provisioning artifact for the delete request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Provisioning Artifacts
  /?Action=DescribeConstraint:
    get:
      summary: Describe Constraint
      description: Retrieves detailed information for a specified constraint.
      operationId: describeConstraint
      x-api-path-slug: actiondescribeconstraint-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the constraint
        type: string
      responses:
        200:
          description: OK
      tags:
      - Constraints
  /?Action=DescribePortfolio:
    get:
      summary: Describe Portfolio
      description: |-
        Retrieves detailed information and any tags associated with the specified
                 portfolio.
      operationId: describePortfolio
      x-api-path-slug: actiondescribeportfolio-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the portfolio for which to retrieve information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Portfolios
  /?Action=DescribeProduct:
    get:
      summary: Describe Product
      description: Retrieves information about a specified product.
      operationId: describeProduct
      x-api-path-slug: actiondescribeproduct-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The ProductId of the product to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=DescribeProductAsAdmin:
    get:
      summary: Describe Product As Admin
      description: |-
        Retrieves information about a specified product, run with administrator
                 access.
      operationId: describeProductAsAdmin
      x-api-path-slug: actiondescribeproductasadmin-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the product for which to retrieve information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=DescribeProductView:
    get:
      summary: Describe Product View
      description: Retrieves information about a specified product.
      operationId: describeProductView
      x-api-path-slug: actiondescribeproductview-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The ProductViewId of the product to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=DescribeProvisioningArtifact:
    get:
      summary: Describe Provisioning Artifact
      description: Retrieves detailed information about the specified provisioning
        artifact.
      operationId: describeProvisioningArtifact
      x-api-path-slug: actiondescribeprovisioningartifact-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      - in: query
        name: ProvisioningArtifactId
        description: The identifier of the provisioning artifact
        type: string
      responses:
        200:
          description: OK
      tags:
      - Provisioning Artifacts
  /?Action=DescribeProvisioningParameters:
    get:
      summary: Describe Provisioning Parameters
      description: |-
        Provides information about parameters required to provision a specified product in a
                 specified manner.
      operationId: describeProvisioningParameters
      x-api-path-slug: actiondescribeprovisioningparameters-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: PathId
        description: The identifier of the path for this products provisioning
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      - in: query
        name: ProvisioningArtifactId
        description: The provisioning artifact identifier for this product
        type: string
      responses:
        200:
          description: OK
      tags:
      - Provisioning Parameters
  /?Action=DescribeRecord:
    get:
      summary: Describe Record
      description: Retrieves a paginated list of the full details of a specific request.
      operationId: describeRecord
      x-api-path-slug: actiondescriberecord-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The record identifier of the ProvisionedProduct object for which
          to retrieve output         information
        type: string
      - in: query
        name: PageSize
        description: The maximum number of items to return in the results
        type: string
      - in: query
        name: PageToken
        description: The page token of the first page retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Records
  /?Action=DisassociatePrincipalFromPortfolio:
    get:
      summary: Disassociate Principal From Portfolio
      description: |-
        Disassociates a previously associated principal ARN from a specified
                 portfolio.
      operationId: disassociatePrincipalFromPortfolio
      x-api-path-slug: actiondisassociateprincipalfromportfolio-get
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
      - Portfolios
  /?Action=DisassociateProductFromPortfolio:
    get:
      summary: Disassociate Product From Portfolio
      description: Disassociates the specified product from the specified portfolio.
      operationId: disassociateProductFromPortfolio
      x-api-path-slug: actiondisassociateproductfromportfolio-get
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
        name: ProductId
        description: The product identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Portfolios
  /?Action=ListAcceptedPortfolioShares:
    get:
      summary: List Accepted Portfolio Shares
      description: |-
        Lists details of all portfolios for which sharing was accepted by this
                 account.
      operationId: listAcceptedPortfolioShares
      x-api-path-slug: actionlistacceptedportfolioshares-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: PageSize
        description: The maximum number of items to return in the results
        type: string
      - in: query
        name: PageToken
        description: The page token of the first page retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Portfolios
  /?Action=ListConstraintsForPortfolio:
    get:
      summary: List Constraints For Portfolio
      description: |-
        Retrieves detailed constraint information for the specified portfolio and
                 product.
      operationId: listConstraintsForPortfolio
      x-api-path-slug: actionlistconstraintsforportfolio-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: PageSize
        description: The maximum number of items to return in the results
        type: string
      - in: query
        name: PageToken
        description: The page token of the first page retrieved
        type: string
      - in: query
        name: PortfolioId
        description: The portfolio identifier
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Portfolios
  /?Action=ListLaunchPaths:
    get:
      summary: List Launch Paths
      description: Returns a paginated list of all paths to a specified product.
      operationId: listLaunchPaths
      x-api-path-slug: actionlistlaunchpaths-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: PageSize
        description: The maximum number of items to return in the results
        type: string
      - in: query
        name: PageToken
        description: The page token of the first page retrieved
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Launch Paths
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