---
name: AWS Service Catalog
x-slug: aws-service-catalog
description: AWS Service Catalog allows organizations to create and manage catalogs
  of IT services that are approved for use on AWS. These IT services can include everything
  from virtual machine images, servers, software, and databases to complete multi-tier
  application architectures. AWS Service Catalog allows you to centrally manage commonly
  deployed IT services, and helps you achieve consistent governance and meet your
  compliance requirements, while enabling users to quickly deploy only the approved
  IT services they need.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Service Catalog
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Service Catalog API Accept Portfolio Share
  x-api-slug: aws-service-catalog-api
  description: Accepts an offer to share a portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=AcceptPortfolioShare
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionacceptportfolioshare-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionacceptportfolioshare-get-openapi.md
- name: AWS Service Catalog API Associate Principal With Portfolio
  x-api-slug: aws-service-catalog-api
  description: Associates the specified principal ARN with the specified portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=AssociatePrincipalWithPortfolio
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionassociateprincipalwithportfolio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionassociateprincipalwithportfolio-get-openapi.md
- name: AWS Service Catalog API Associate Product With Portfolio
  x-api-slug: aws-service-catalog-api
  description: Associates a product with a portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=AssociateProductWithPortfolio
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionassociateproductwithportfolio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionassociateproductwithportfolio-get-openapi.md
- name: AWS Service Catalog API Create Constraint
  x-api-slug: aws-service-catalog-api
  description: Creates a new constraint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=CreateConstraint
  tags: Constraints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actioncreateconstraint-get-openapi.md
- name: AWS Service Catalog API Create Portfolio
  x-api-slug: aws-service-catalog-api
  description: Creates a new portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=CreatePortfolio
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actioncreateportfolio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actioncreateportfolio-get-openapi.md
- name: AWS Service Catalog API Create Portfolio Share
  x-api-slug: aws-service-catalog-api
  description: Creates a new portfolio share.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=CreatePortfolioShare
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actioncreateportfolioshare-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actioncreateportfolioshare-get-openapi.md
- name: AWS Service Catalog API Create Product
  x-api-slug: aws-service-catalog-api
  description: Creates a new product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=CreateProduct
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actioncreateproduct-get-openapi.md
- name: AWS Service Catalog API Create Provisioning Artifact
  x-api-slug: aws-service-catalog-api
  description: Create a new provisioning artifact for the specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=CreateProvisioningArtifact
  tags: Provisioning Artifacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actioncreateprovisioningartifact-get-openapi.md
- name: AWS Service Catalog API Delete Constraint
  x-api-slug: aws-service-catalog-api
  description: Deletes the specified constraint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DeleteConstraint
  tags: Constraints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondeleteconstraint-get-openapi.md
- name: AWS Service Catalog API Delete Portfolio
  x-api-slug: aws-service-catalog-api
  description: Deletes the specified portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DeletePortfolio
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondeleteportfolio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondeleteportfolio-get-openapi.md
- name: AWS Service Catalog API Delete Portfolio Share
  x-api-slug: aws-service-catalog-api
  description: Deletes the specified portfolio share.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DeletePortfolioShare
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondeleteportfolioshare-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondeleteportfolioshare-get-openapi.md
- name: AWS Service Catalog API Delete Product
  x-api-slug: aws-service-catalog-api
  description: Deletes the specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DeleteProduct
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondeleteproduct-get-openapi.md
- name: AWS Service Catalog API Delete Provisioning Artifact
  x-api-slug: aws-service-catalog-api
  description: Deletes the specified provisioning artifact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DeleteProvisioningArtifact
  tags: Provisioning Artifacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondeleteprovisioningartifact-get-openapi.md
- name: AWS Service Catalog API Describe Constraint
  x-api-slug: aws-service-catalog-api
  description: Retrieves detailed information for a specified constraint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeConstraint
  tags: Constraints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondescribeconstraint-get-openapi.md
- name: AWS Service Catalog API Describe Portfolio
  x-api-slug: aws-service-catalog-api
  description: |-
    Retrieves detailed information and any tags associated with the specified
             portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribePortfolio
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondescribeportfolio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondescribeportfolio-get-openapi.md
- name: AWS Service Catalog API Describe Product
  x-api-slug: aws-service-catalog-api
  description: Retrieves information about a specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeProduct
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondescribeproduct-get-openapi.md
- name: AWS Service Catalog API Describe Product As Admin
  x-api-slug: aws-service-catalog-api
  description: |-
    Retrieves information about a specified product, run with administrator
             access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeProductAsAdmin
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondescribeproductasadmin-get-openapi.md
- name: AWS Service Catalog API Describe Product View
  x-api-slug: aws-service-catalog-api
  description: Retrieves information about a specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeProductView
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondescribeproductview-get-openapi.md
- name: AWS Service Catalog API Describe Provisioning Artifact
  x-api-slug: aws-service-catalog-api
  description: Retrieves detailed information about the specified provisioning artifact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeProvisioningArtifact
  tags: Provisioning Artifacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondescribeprovisioningartifact-get-openapi.md
- name: AWS Service Catalog API Describe Provisioning Parameters
  x-api-slug: aws-service-catalog-api
  description: |-
    Provides information about parameters required to provision a specified product in a
             specified manner.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeProvisioningParameters
  tags: 'Provisioning Parameters '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondescribeprovisioningparameters-get-openapi.md
- name: AWS Service Catalog API Describe Record
  x-api-slug: aws-service-catalog-api
  description: Retrieves a paginated list of the full details of a specific request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeRecord
  tags: Records
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondescriberecord-get-openapi.md
- name: AWS Service Catalog API Disassociate Principal From Portfolio
  x-api-slug: aws-service-catalog-api
  description: |-
    Disassociates a previously associated principal ARN from a specified
             portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DisassociatePrincipalFromPortfolio
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondisassociateprincipalfromportfolio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondisassociateprincipalfromportfolio-get-openapi.md
- name: AWS Service Catalog API Disassociate Product From Portfolio
  x-api-slug: aws-service-catalog-api
  description: Disassociates the specified product from the specified portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DisassociateProductFromPortfolio
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondisassociateproductfromportfolio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actiondisassociateproductfromportfolio-get-openapi.md
- name: AWS Service Catalog API List Accepted Portfolio Shares
  x-api-slug: aws-service-catalog-api
  description: |-
    Lists details of all portfolios for which sharing was accepted by this
             account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ListAcceptedPortfolioShares
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistacceptedportfolioshares-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistacceptedportfolioshares-get-openapi.md
- name: AWS Service Catalog API List Constraints For Portfolio
  x-api-slug: aws-service-catalog-api
  description: |-
    Retrieves detailed constraint information for the specified portfolio and
             product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ListConstraintsForPortfolio
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistconstraintsforportfolio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistconstraintsforportfolio-get-openapi.md
- name: AWS Service Catalog API List Launch Paths
  x-api-slug: aws-service-catalog-api
  description: Returns a paginated list of all paths to a specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ListLaunchPaths
  tags: Launch Paths
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistlaunchpaths-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistlaunchpaths-get-openapi.md
- name: AWS Service Catalog API List Portfolio Access
  x-api-slug: aws-service-catalog-api
  description: |-
    Lists the account IDs that have been authorized sharing of the specified
             portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ListPortfolioAccess
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistportfolioaccess-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistportfolioaccess-get-openapi.md
- name: AWS Service Catalog API List Portfolios
  x-api-slug: aws-service-catalog-api
  description: Lists all portfolios in the catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ListPortfolios
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistportfolios-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistportfolios-get-openapi.md
- name: AWS Service Catalog API List Portfolios For Product
  x-api-slug: aws-service-catalog-api
  description: Lists all portfolios that the specified product is associated with.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ListPortfoliosForProduct
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistportfoliosforproduct-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistportfoliosforproduct-get-openapi.md
- name: AWS Service Catalog API List Principals For Portfolio
  x-api-slug: aws-service-catalog-api
  description: Lists all principal ARNs associated with the specified portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ListPrincipalsForPortfolio
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistprincipalsforportfolio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistprincipalsforportfolio-get-openapi.md
- name: AWS Service Catalog API List Provisioning Artifacts
  x-api-slug: aws-service-catalog-api
  description: Lists all provisioning artifacts associated with the specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ListProvisioningArtifacts
  tags: Provisioning Artifacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistprovisioningartifacts-get-openapi.md
- name: AWS Service Catalog API List Record History
  x-api-slug: aws-service-catalog-api
  description: |-
    Returns a paginated list of all performed requests, in the form of RecordDetails
             objects that are filtered as specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ListRecordHistory
  tags: Record History
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistrecordhistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionlistrecordhistory-get-openapi.md
- name: AWS Service Catalog API Provision Product
  x-api-slug: aws-service-catalog-api
  description: Requests a Provision of a specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ProvisionProduct
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionprovisionproduct-get-openapi.md
- name: AWS Service Catalog API Reject Portfolio Share
  x-api-slug: aws-service-catalog-api
  description: Rejects an offer to share a portfolio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=RejectPortfolioShare
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionrejectportfolioshare-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionrejectportfolioshare-get-openapi.md
- name: AWS Service Catalog API Scan Provisioned Products
  x-api-slug: aws-service-catalog-api
  description: |-
    Returns a paginated list of all the ProvisionedProduct objects that are currently
             available (not terminated).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ScanProvisionedProducts
  tags: Provisioned Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionscanprovisionedproducts-get-openapi.md
- name: AWS Service Catalog API Search Products
  x-api-slug: aws-service-catalog-api
  description: |-
    Returns a paginated list all of the Products objects to which the caller
             has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=SearchProducts
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionsearchproducts-get-openapi.md
- name: AWS Service Catalog API Search Products As Admin
  x-api-slug: aws-service-catalog-api
  description: |-
    Retrieves summary and status information about all products created within the
             caller's account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=SearchProductsAsAdmin
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionsearchproductsasadmin-get-openapi.md
- name: AWS Service Catalog API Terminate Provisioned Product
  x-api-slug: aws-service-catalog-api
  description: Requests termination of an existing ProvisionedProduct object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=TerminateProvisionedProduct
  tags: Provisioned Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionterminateprovisionedproduct-get-openapi.md
- name: AWS Service Catalog API Update Constraint
  x-api-slug: aws-service-catalog-api
  description: Updates an existing constraint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=UpdateConstraint
  tags: Constraints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionupdateconstraint-get-openapi.md
- name: AWS Service Catalog API Update Portfolio
  x-api-slug: aws-service-catalog-api
  description: Updates the specified portfolio's details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=UpdatePortfolio
  tags: Portfolios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionupdateportfolio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionupdateportfolio-get-openapi.md
- name: AWS Service Catalog API Update Product
  x-api-slug: aws-service-catalog-api
  description: Updates an existing product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=UpdateProduct
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionupdateproduct-get-openapi.md
- name: AWS Service Catalog API Update Provisioned Product
  x-api-slug: aws-service-catalog-api
  description: Requests updates to the configuration of an existing ProvisionedProduct
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=UpdateProvisionedProduct
  tags: Provisioned Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionupdateprovisionedproduct-get-openapi.md
- name: AWS Service Catalog API Update Provisioning Artifact
  x-api-slug: aws-service-catalog-api
  description: Updates an existing provisioning artifact's information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=UpdateProvisioningArtifact
  tags: Provisioning Artifacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/actionupdateprovisioningartifact-get-openapi.md
- name: AWS Service Catalog API
  x-api-slug: aws-service-catalog-api
  description: AWS Service Catalog allows organizations to create and manage catalogs
    of IT services that are approved for use on AWS. These IT services can include
    everything from virtual machine images, servers, software, and databases to complete
    multi-tier application architectures. AWS Service Catalog allows you to centrally
    manage commonly deployed IT services, and helps you achieve consistent governance
    and meet your compliance requirements, while enabling users to quickly deploy
    only the approved IT services they need.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: :///
  tags: AWS Service Catalog
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-service-catalog/master/_listings/aws-service-catalog/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/servicecatalog/latest/dg/service-catalog-api-overview.html
- type: x-faq
  url: https://aws.amazon.com/servicecatalog/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/servicecatalog/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/servicecatalog/pricing/
- type: x-website
  url: https://aws.amazon.com/servicecatalog/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---