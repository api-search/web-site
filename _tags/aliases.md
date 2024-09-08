---
name: Aliases
description: Needs a description.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/aliases.png
url: https://example.com/apis/aliases.yml
created: 2024/4/8
modified: 2024/4/8
specificationVersion: '0.16'
tags:
  - Aliases
apis:
  - name: bedrock-agent-runtime
    description: <p>Amazon Bedrock Agent</p>
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://example.com
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://example.com
      - type: OpenAPI
        data:
          openapi: 3.1.0
          info:
            title: bedrock-agent-runtime
          paths:
            /agents/{agentId}/agentAliases/{agentAliasId}/sessions/{sessionId}/text:
              POST:
                summary: InvokeAgent
                description: >-
                  <p>Invokes the specified Bedrock model to run inference using
                  the input provided in the request body.</p>
                tags:
                  - Invoke
                  - Agent
                  - Identifiers
                  - Agent
                  - Aliases
                  - Alias
                  - Sessions
                  - Sessions
                  - Text
            /knowledgebases/{knowledgeBaseId}/retrieve:
              POST:
                summary: Retrieve
                description: <p>Retrieve from knowledge base.</p>
                tags:
                  - Retrieve
                  - Identifiers
                  - Agent
                  - Aliases
                  - Alias
                  - Sessions
                  - Sessions
                  - Text
                  - Base
                  - Retrieve
            /retrieveAndGenerate:
              POST:
                summary: RetrieveAndGenerate
                description: <p>RetrieveAndGenera
                tags:
                  - Retrieve
                  - And
                  - Generate
                  - Identifiers
                  - Agent
                  - Aliases
                  - Alias
                  - Sessions
                  - Sessions
                  - Text
                  - Base
                  - Retrieve
                  - And
                  - General
    overlays:
      - type: APIs.io Search
        url: overlays/bedrock-agent-runtime-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bedrock-agent-runtime-openapi-api-evangelist-ratings.yml
    aid: amazon-web-services:bedrock-agent-runtime
  - name: bedrock-agent
    description: >-
      <p>An example service, deployed with the Octane Service creator, which
      will echo the string</p>
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://example.com
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://example.com
      - type: OpenAPI
        data:
          openapi: 3.1.0
          info:
            title: bedrock-agent
          paths:
            /agents/{agentId}/agentversions/{agentVersion}/knowledgebases/:
              POST:
                summary: ListAgentKnowledgeBases
                description: >-
                  <p>List of Knowledge Bases associated to an existing Amazon
                  Bedrock Agent Version</p>
                tags:
                  - Lists
                  - Agent
                  - Knowledge
                  - Bases
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
            /agents/:
              POST:
                summary: ListAgents
                description: <p>Lists Agents</p>
                tags:
                  - Lists
                  - Agents
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
            /agents/{agentId}/agentversions/{agentVersion}/actiongroups/:
              POST:
                summary: ListAgentActionGroups
                description: >-
                  <p>Lists an Action Group for existing Amazon Bedrock Agent
                  Version</p>
                tags:
                  - Lists
                  - Agent
                  - Actions
                  - Groups
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
            /agents/{agentId}/agentaliases/:
              POST:
                summary: ListAgentAliases
                description: <p>Lists all the Aliases for an Amazon Bedrock Agent</p>
                tags:
                  - Lists
                  - Agent
                  - Aliases
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
            /knowledgebases/{knowledgeBaseId}/datasources/:
              POST:
                summary: ListDataSources
                description: <p>List data sources</p>
                tags:
                  - Lists
                  - Data
                  - Sources
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
            /knowledgebases/:
              POST:
                summary: ListKnowledgeBases
                description: <p>List Knowledge Bases</p>
                tags:
                  - Lists
                  - Knowledge
                  - Bases
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
            /agents/{agentId}/:
              PUT:
                summary: UpdateAgent
                description: <p>Updates an existing Amazon Bedrock Agent</p>
                tags:
                  - Update
                  - Agent
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
            /agents/{agentId}/agentversions/{agentVersion}/actiongroups/{actionGroupId}/:
              PUT:
                summary: UpdateAgentActionGroup
                description: >-
                  <p>Updates an existing Action Group for Amazon Bedrock
                  Agent</p>
                tags:
                  - Update
                  - Agent
                  - Actions
                  - Group
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
                  - Actions
                  - Group
            /agents/{agentId}/agentaliases/{agentAliasId}/:
              PUT:
                summary: UpdateAgentAlias
                description: <p>Updates an existing Alias for an Amazon Bedrock Agent</p>
                tags:
                  - Update
                  - Agent
                  - Alias
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
                  - Actions
                  - Group
                  - Alias
            /agents/{agentId}/agentversions/{agentVersion}/:
              GET:
                summary: GetAgentVersion
                description: <p>Gets an Agent version for existing Amazon Bedrock Agent</p>
                tags:
                  - Get
                  - Agent
                  - Versions
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
                  - Actions
                  - Group
                  - Alias
            /knowledgebases/{knowledgeBaseId}/datasources/{dataSourceId}:
              PUT:
                summary: UpdateDataSource
                description: <p>Update an existing data source</p>
                tags:
                  - Update
                  - Data
                  - Source
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
                  - Actions
                  - Group
                  - Alias
                  - Data
                  - Source
            /knowledgebases/{knowledgeBaseId}:
              PUT:
                summary: UpdateKnowledgeBase
                description: <p>Update an existing knowledge base</p>
                tags:
                  - Update
                  - Knowledge
                  - Base
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
                  - Actions
                  - Group
                  - Alias
                  - Data
                  - Source
            /agents/{agentId}/agentversions/{agentVersion}/knowledgebases/{knowledgeBaseId}/:
              PUT:
                summary: UpdateAgentKnowledgeBase
                description: >-
                  <p>Updates an existing Knowledge Base associated to an Amazon
                  Bedrock Agent</p>
                tags:
                  - Update
                  - Agent
                  - Knowledge
                  - Base
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
                  - Actions
                  - Group
                  - Alias
                  - Data
                  - Source
                  - Knowledge
            /knowledgebases/{knowledgeBaseId}/datasources/{dataSourceId}/ingestionjobs/{ingestionJobId}:
              GET:
                summary: GetIngestionJob
                description: <p>Get an ingestion job</p>
                tags:
                  - Get
                  - Ingestion
                  - Jobs
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
                  - Actions
                  - Group
                  - Alias
                  - Data
                  - Source
                  - Knowledge
                  - Ingestion Jobs
                  - Ingestion
                  - Jobs
            /agents/{agentId}/agentversions/:
              POST:
                summary: ListAgentVersions
                description: <p>Lists Agent Versions</p>
                tags:
                  - Lists
                  - Agent
                  - Versions
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
                  - Actions
                  - Group
                  - Alias
                  - Data
                  - Source
                  - Knowledge
                  - Ingestion Jobs
                  - Ingestion
                  - Jobs
            /knowledgebases/{knowledgeBaseId}/datasources/{dataSourceId}/ingestionjobs/:
              PUT:
                summary: StartIngestionJob
                description: <p>Start a new ingestion job</p>
                tags:
                  - Start
                  - Ingestion
                  - Jobs
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
                  - Actions
                  - Group
                  - Alias
                  - Data
                  - Source
                  - Knowledge
                  - Ingestion Jobs
                  - Ingestion
                  - Jobs
            /tags/{resourceArn}:
              DELETE:
                summary: UntagResource
                description: <p>Untag a re
                tags:
                  - Untag
                  - Resources
                  - Identifiers
                  - Agent Versions
                  - Agent
                  - Versions
                  - Knowledgebases
                  - Agents
                  - Action Groups
                  - Agent Aliases
                  - Base
                  - Data Source
                  - Actions
                  - Group
                  - Alias
                  - Data
                  - Source
                  - Knowledge
                  - Ingestion Jobs
                  - Ingestion
                  - Jobs
                  - A
    overlays:
      - type: APIs.io Search
        url: overlays/bedrock-agent-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bedrock-agent-openapi-api-evangelist-ratings.yml
    aid: amazon-web-services:bedrock-agent
  - name: cloudfront
    description: >-
      <fullname>Amazon CloudFront</fullname> <p>Amazon CloudFront is a global
      content delivery network (CDN) service that accelerates delivery of your
      websites, APIs, video content or other web assets. It integrates with
      other Amazon Web Services products to give developers and businesses an
      easy way to accelerate content to end users with no minimum usage
      commitments.</p>
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://example.com
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://example.com
      - type: OpenAPI
        data:
          openapi: 3.1.0
          info:
            title: cloudfront
          paths:
            /2020-05-31/distribution/{TargetDistributionId}/associate-alias:
              PUT:
                summary: AssociateAlias
                description: >-
                  <p>Associates an alias (also known as a CNAME or an alternate
                  domain name) with a CloudFront distribution.</p> <p>With this
                  operation you can move an alias that's already in use on a
                  CloudFront distribution to a different distribution in one
                  step. This prevents the downtime that could occur if you first
                  remove the alias from one distribution and then separately add
                  the alias to another distribution.</p> <p>To use this
                  operation to associate an alias with a distribution, you
                  provide the alias and the ID of the target distribution for
                  the alias. For more information, including how to set up the
                  target distribution, prerequisites that you must complete, and
                  other restrictions, see <a
                  href="https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/CNAMEs.html#alternate-domain-names-move">Moving
                  an alternate domain name to a different distribution</a> in
                  the <i>Amazon CloudFront Developer Guide</i>.</p>
                tags:
                  - Associate
                  - Alias
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
            /2020-05-31/distribution/{PrimaryDistributionId}/copy:
              POST:
                summary: CopyDistribution
                description: >-
                  <p>Creates a staging distribution using the configuration of
                  the provided primary distribution. A staging distribution is a
                  copy of an existing distribution (called the primary
                  distribution) that you can use in a continuous deployment
                  workflow.</p> <p>After you create a staging distribution, you
                  can use <code>UpdateDistribution</code> to modify the staging
                  distribution's configuration. Then you can use
                  <code>CreateContinuousDeploymentPolicy</code> to incrementally
                  move traffic to the staging distribution.</p> <p>This API
                  operation requires the following IAM permissions:</p> <ul>
                  <li> <p> <a
                  href="https://docs.aws.amazon.com/cloudfront/latest/APIReference/API_GetDistribution.html">GetDistribution</a>
                  </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/cloudfront/latest/APIReference/API_CreateDistribution.html">CreateDistribution</a>
                  </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/cloudfront/latest/APIReference/API_CopyDistribution.html">CopyDistribution</a>
                  </p> </li> </ul>
                tags:
                  - Copy
                  - Distributions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
            /2020-05-31/cache-policy:
              GET:
                summary: ListCachePolicies
                description: >-
                  <p>Gets a list of cache policies.</p> <p>You can optionally
                  apply a filter to return only the managed policies created by
                  Amazon Web Services, or only the custom policies created in
                  your Amazon Web Services account.</p> <p>You can optionally
                  specify the maximum number of items to receive in the
                  response. If the total number of items in the list exceeds the
                  maximum that you specify, or the default maximum, the response
                  is paginated. To get the next page of items, send a subsequent
                  request that specifies the <code>NextMarker</code> value from
                  the current response as the <code>Marker</code> value in the
                  subsequent request.</p>
                tags:
                  - Lists
                  - Cache
                  - Policies
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
            /2020-05-31/origin-access-identity/cloudfront:
              GET:
                summary: ListCloudFrontOriginAccessIdentities
                description: <p>Lists origin access identities.</p>
                tags:
                  - Lists
                  - Cloud
                  - Front
                  - Origin
                  - Access
                  - Identities
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
            /2020-05-31/continuous-deployment-policy:
              GET:
                summary: ListContinuousDeploymentPolicies
                description: >-
                  <p>Gets a list of the continuous deployment policies in your
                  Amazon Web Services account.</p> <p>You can optionally specify
                  the maximum number of items to receive in the response. If the
                  total number of items in the list exceeds the maximum that you
                  specify, or the default maximum, the response is paginated. To
                  get the next page of items, send a subsequent request that
                  specifies the <code>NextMarker</code> value from the current
                  response as the <code>Marker</code> value in the subsequent
                  request.</p>
                tags:
                  - Lists
                  - Continuous
                  - Deployments
                  - Policies
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
            /2020-05-31/distribution:
              GET:
                summary: ListDistributions
                description: <p>List CloudFront distributions.</p>
                tags:
                  - Lists
                  - Distributions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
            /2020-05-31/distribution?WithTags:
              POST:
                summary: CreateDistributionWithTags
                description: >-
                  <p>Create a new distribution with tags. This API operation
                  requires the following IAM permissions:</p> <ul> <li> <p> <a
                  href="https://docs.aws.amazon.com/cloudfront/latest/APIReference/API_CreateDistribution.html">CreateDistribution</a>
                  </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/cloudfront/latest/APIReference/API_TagResource.html">TagResource</a>
                  </p> </li> </ul>
                tags:
                  - Create
                  - Distributions
                  - With
                  - Tags
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
            /2020-05-31/field-level-encryption:
              GET:
                summary: ListFieldLevelEncryptionConfigs
                description: >-
                  <p>List all field-level encryption configurations that have
                  been created in CloudFront for this account.</p>
                tags:
                  - Lists
                  - Fields
                  - Levels
                  - Encryption
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
            /2020-05-31/field-level-encryption-profile:
              GET:
                summary: ListFieldLevelEncryptionProfiles
                description: >-
                  <p>Request a list of field-level encryption profiles that have
                  been created in CloudFront for this account.</p>
                tags:
                  - Lists
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
            /2020-05-31/function:
              GET:
                summary: ListFunctions
                description: >-
                  <p>Gets a list of all CloudFront functions in your Amazon Web
                  Services account.</p> <p>You can optionally apply a filter to
                  return only the functions that are in the specified stage,
                  either <code>DEVELOPMENT</code> or <code>LIVE</code>.</p>
                  <p>You can optionally specify the maximum number of items to
                  receive in the response. If the total number of items in the
                  list exceeds the maximum that you specify, or the default
                  maximum, the response is paginated. To get the next page of
                  items, send a subsequent request that specifies the
                  <code>NextMarker</code> value from the current response as the
                  <code>Marker</code> value in the subsequent request.</p>
                tags:
                  - Lists
                  - Functions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
            /2020-05-31/distribution/{DistributionId}/invalidation:
              GET:
                summary: ListInvalidations
                description: <p>Lists invalidation batches.</p>
                tags:
                  - Lists
                  - Invalidations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
            /2020-05-31/key-group:
              GET:
                summary: ListKeyGroups
                description: >-
                  <p>Gets a list of key groups.</p> <p>You can optionally
                  specify the maximum number of items to receive in the
                  response. If the total number of items in the list exceeds the
                  maximum that you specify, or the default maximum, the response
                  is paginated. To get the next page of items, send a subsequent
                  request that specifies the <code>NextMarker</code> value from
                  the current response as the <code>Marker</code> value in the
                  subsequent request.</p>
                tags:
                  - Lists
                  - Keys
                  - Groups
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
            /2020-05-31/key-value-store/:
              POST:
                summary: CreateKeyValueStore
                description: >-
                  <p>Specifies the Key Value Store resource to add to your
                  account. In your account, the Key Value Store names must be
                  unique. You can also import Key Value Store data in JSON
                  format from an S3 bucket by providing a valid
                  <code>ImportSource</code> that you own.</p>
                tags:
                  - Create
                  - Keys
                  - Value
                  - Store
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
            /2020-05-31/distributions/{DistributionId}/monitoring-subscription/:
              GET:
                summary: GetMonitoringSubscription
                description: >-
                  <p>Gets information about whether additional CloudWatch
                  metrics are enabled for the specified CloudFront
                  distribution.</p>
                tags:
                  - Get
                  - Monitoring
                  - Subscriptions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
            /2020-05-31/origin-access-control:
              GET:
                summary: ListOriginAccessControls
                description: >-
                  <p>Gets the list of CloudFront origin access controls in this
                  Amazon Web Services account.</p> <p>You can optionally specify
                  the maximum number of items to receive in the response. If the
                  total number of items in the list exceeds the maximum that you
                  specify, or the default maximum, the response is paginated. To
                  get the next page of items, send another request that
                  specifies the <code>NextMarker</code> value from the current
                  response as the <code>Marker</code> value in the next
                  request.</p>
                tags:
                  - Lists
                  - Origin
                  - Access
                  - Controls
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
            /2020-05-31/origin-request-policy:
              GET:
                summary: ListOriginRequestPolicies
                description: >-
                  <p>Gets a list of origin request policies.</p> <p>You can
                  optionally apply a filter to return only the managed policies
                  created by Amazon Web Services, or only the custom policies
                  created in your Amazon Web Services account.</p> <p>You can
                  optionally specify the maximum number of items to receive in
                  the response. If the total number of items in the list exceeds
                  the maximum that you specify, or the default maximum, the
                  response is paginated. To get the next page of items, send a
                  subsequent request that specifies the <code>NextMarker</code>
                  value from the current response as the <code>Marker</code>
                  value in the subsequent request.</p>
                tags:
                  - Lists
                  - Origin
                  - Request
                  - Policies
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
            /2020-05-31/public-key:
              GET:
                summary: ListPublicKeys
                description: >-
                  <p>List all public keys that have been added to CloudFront for
                  this account.</p>
                tags:
                  - Lists
                  - Public
                  - Keys
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
            /2020-05-31/realtime-log-config:
              GET:
                summary: ListRealtimeLogConfigs
                description: >-
                  <p>Gets a list of real-time log configurations.</p> <p>You can
                  optionally specify the maximum number of items to receive in
                  the response. If the total number of items in the list exceeds
                  the maximum that you specify, or the default maximum, the
                  response is paginated. To get the next page of items, send a
                  subsequent request that specifies the <code>NextMarker</code>
                  value from the current response as the <code>Marker</code>
                  value in the subsequent request.</p>
                tags:
                  - Lists
                  - Real Time
                  - Logs
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
            /2020-05-31/response-headers-policy:
              GET:
                summary: ListResponseHeadersPolicies
                description: >-
                  <p>Gets a list of response headers policies.</p> <p>You can
                  optionally apply a filter to get only the managed policies
                  created by Amazon Web Services, or only the custom policies
                  created in your Amazon Web Services account.</p> <p>You can
                  optionally specify the maximum number of items to receive in
                  the response. If the total number of items in the list exceeds
                  the maximum that you specify, or the default maximum, the
                  response is paginated. To get the next page of items, send a
                  subsequent request that specifies the <code>NextMarker</code>
                  value from the current response as the <code>Marker</code>
                  value in the subsequent request.</p>
                tags:
                  - Lists
                  - Responses
                  - Headers
                  - Policies
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
            /2020-05-31/streaming-distribution:
              GET:
                summary: ListStreamingDistributions
                description: <p>List streaming distributions.</p>
                tags:
                  - Lists
                  - Streaming
                  - Distributions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
            /2020-05-31/streaming-distribution?WithTags:
              POST:
                summary: CreateStreamingDistributionWithTags
                description: >-
                  <p>This API is deprecated. Amazon CloudFront is deprecating
                  real-time messaging protocol (RTMP) distributions on December
                  31, 2020. For more information, <a
                  href="http://forums.aws.amazon.com/ann.jspa?annID=7356">read
                  the announcement</a> on the Amazon CloudFront discussion
                  forum.</p>
                tags:
                  - Create
                  - Streaming
                  - Distributions
                  - With
                  - Tags
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
            /2020-05-31/cache-policy/{Id}:
              PUT:
                summary: UpdateCachePolicy
                description: >-
                  <p>Updates a cache policy configuration.</p> <p>When you
                  update a cache policy configuration, all the fields are
                  updated with the values provided in the request. You cannot
                  update some fields independent of others. To update a cache
                  policy configuration:</p> <ol> <li> <p>Use
                  <code>GetCachePolicyConfig</code> to get the current
                  configuration.</p> </li> <li> <p>Locally modify the fields in
                  the cache policy configuration that you want to update.</p>
                  </li> <li> <p>Call <code>UpdateCachePolicy</code> by providing
                  the entire cache policy configuration, including the fields
                  that you modified and those that you didn't.</p> </li> </ol>
                tags:
                  - Update
                  - Cache
                  - Policies
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
            /2020-05-31/origin-access-identity/cloudfront/{Id}:
              GET:
                summary: GetCloudFrontOriginAccessIdentity
                description: <p>Get the information about an origin access identity.</p>
                tags:
                  - Get
                  - Cloud
                  - Front
                  - Origin
                  - Access
                  - Identity
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
            /2020-05-31/continuous-deployment-policy/{Id}:
              PUT:
                summary: UpdateContinuousDeploymentPolicy
                description: >-
                  <p>Updates a continuous deployment policy. You can update a
                  continuous deployment policy to enable or disable it, to
                  change the percentage of traffic that it sends to the staging
                  distribution, or to change the staging distribution that it
                  sends traffic to.</p> <p>When you update a continuous
                  deployment policy configuration, all the fields are updated
                  with the values that are provided in the request. You cannot
                  update some fields independent of others. To update a
                  continuous deployment policy configuration:</p> <ol> <li>
                  <p>Use <code>GetContinuousDeploymentPolicyConfig</code> to get
                  the current configuration.</p> </li> <li> <p>Locally modify
                  the fields in the continuous deployment policy configuration
                  that you want to update.</p> </li> <li> <p>Use
                  <code>UpdateContinuousDeploymentPolicy</code>, providing the
                  entire continuous deployment policy configuration, including
                  the fields that you modified and those that you didn't.</p>
                  </li> </ol>
                tags:
                  - Update
                  - Continuous
                  - Deployments
                  - Policies
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
            /2020-05-31/distribution/{Id}:
              GET:
                summary: GetDistribution
                description: <p>Get the information about a distribution.</p>
                tags:
                  - Get
                  - Distributions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
            /2020-05-31/field-level-encryption/{Id}:
              GET:
                summary: GetFieldLevelEncryption
                description: >-
                  <p>Get the field-level encryption configuration
                  information.</p>
                tags:
                  - Get
                  - Fields
                  - Levels
                  - Encryption
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
            /2020-05-31/field-level-encryption-profile/{Id}:
              GET:
                summary: GetFieldLevelEncryptionProfile
                description: <p>Get the field-level encryption profile information.</p>
                tags:
                  - Get
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
            /2020-05-31/function/{Name}:
              PUT:
                summary: UpdateFunction
                description: >-
                  <p>Updates a CloudFront function.</p> <p>You can update a
                  function's code or the comment that describes the function.
                  You cannot update a function's name.</p> <p>To update a
                  function, you provide the function's name and version
                  (<code>ETag</code> value) along with the updated function
                  code. To get the name and version, you can use
                  <code>ListFunctions</code> and
                  <code>DescribeFunction</code>.</p>
                tags:
                  - Update
                  - Functions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
            /2020-05-31/key-group/{Id}:
              PUT:
                summary: UpdateKeyGroup
                description: >-
                  <p>Updates a key group.</p> <p>When you update a key group,
                  all the fields are updated with the values provided in the
                  request. You cannot update some fields independent of others.
                  To update a key group:</p> <ol> <li> <p>Get the current key
                  group with <code>GetKeyGroup</code> or
                  <code>GetKeyGroupConfig</code>.</p> </li> <li> <p>Locally
                  modify the fields in the key group that you want to update.
                  For example, add or remove public key IDs.</p> </li> <li>
                  <p>Call <code>UpdateKeyGroup</code> with the entire key group
                  object, including the fields that you modified and those that
                  you didn't.</p> </li> </ol>
                tags:
                  - Update
                  - Keys
                  - Group
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
            /2020-05-31/key-value-store/{Name}:
              PUT:
                summary: UpdateKeyValueStore
                description: <p>Specifies the Key Value Store to update.</p>
                tags:
                  - Update
                  - Keys
                  - Value
                  - Store
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
            /2020-05-31/origin-access-control/{Id}:
              GET:
                summary: GetOriginAccessControl
                description: >-
                  <p>Gets a CloudFront origin access control, including its
                  unique identifier.</p>
                tags:
                  - Get
                  - Origin
                  - Access
                  - Control
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
            /2020-05-31/origin-request-policy/{Id}:
              PUT:
                summary: UpdateOriginRequestPolicy
                description: >-
                  <p>Updates an origin request policy configuration.</p> <p>When
                  you update an origin request policy configuration, all the
                  fields are updated with the values provided in the request.
                  You cannot update some fields independent of others. To update
                  an origin request policy configuration:</p> <ol> <li> <p>Use
                  <code>GetOriginRequestPolicyConfig</code> to get the current
                  configuration.</p> </li> <li> <p>Locally modify the fields in
                  the origin request policy configuration that you want to
                  update.</p> </li> <li> <p>Call
                  <code>UpdateOriginRequestPolicy</code> by providing the entire
                  origin request policy configuration, including the fields that
                  you modified and those that you didn't.</p> </li> </ol>
                tags:
                  - Update
                  - Origin
                  - Request
                  - Policies
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
            /2020-05-31/public-key/{Id}:
              GET:
                summary: GetPublicKey
                description: <p>Gets a public key.</p>
                tags:
                  - Get
                  - Public
                  - Keys
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
            /2020-05-31/delete-realtime-log-config/:
              POST:
                summary: DeleteRealtimeLogConfig
                description: >-
                  <p>Deletes a real-time log configuration.</p> <p>You cannot
                  delete a real-time log configuration if it's attached to a
                  cache behavior. First update your distributions to remove the
                  real-time log configuration from all cache behaviors, then
                  delete the real-time log configuration.</p> <p>To delete a
                  real-time log configuration, you can provide the
                  configuration's name or its Amazon Resource Name (ARN). You
                  must provide at least one. If you provide both, CloudFront
                  uses the name to identify the real-time log configuration to
                  delete.</p>
                tags:
                  - Delete
                  - Real Time
                  - Logs
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
            /2020-05-31/response-headers-policy/{Id}:
              PUT:
                summary: UpdateResponseHeadersPolicy
                description: >-
                  <p>Updates a response headers policy.</p> <p>When you update a
                  response headers policy, the entire policy is replaced. You
                  cannot update some policy fields independent of others. To
                  update a response headers policy configuration:</p> <ol> <li>
                  <p>Use <code>GetResponseHeadersPolicyConfig</code> to get the
                  current policy's configuration.</p> </li> <li> <p>Modify the
                  fields in the response headers policy configuration that you
                  want to update.</p> </li> <li> <p>Call
                  <code>UpdateResponseHeadersPolicy</code>, providing the entire
                  response headers policy configuration, including the fields
                  that you modified and those that you didn't.</p> </li> </ol>
                tags:
                  - Update
                  - Responses
                  - Headers
                  - Policies
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
            /2020-05-31/streaming-distribution/{Id}:
              GET:
                summary: GetStreamingDistribution
                description: >-
                  <p>Gets information about a specified RTMP distribution,
                  including the distribution configuration.</p>
                tags:
                  - Get
                  - Streaming
                  - Distributions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
            /2020-05-31/function/{Name}/describe:
              GET:
                summary: DescribeFunction
                description: >-
                  <p>Gets configuration information and metadata about a
                  CloudFront function, but not the function's code. To get a
                  function's code, use <code>GetFunction</code>.</p> <p>To get
                  configuration information and metadata about a function, you
                  must provide the function's name and stage. To get these
                  values, you can use <code>ListFunctions</code>.</p>
                tags:
                  - Describe
                  - Functions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/cache-policy/{Id}/config:
              GET:
                summary: GetCachePolicyConfig
                description: >-
                  <p>Gets a cache policy configuration.</p> <p>To get a cache
                  policy configuration, you must provide the policy's
                  identifier. If the cache policy is attached to a
                  distribution's cache behavior, you can get the policy's
                  identifier using <code>ListDistributions</code> or
                  <code>GetDistribution</code>. If the cache policy is not
                  attached to a cache behavior, you can get the identifier using
                  <code>ListCachePolicies</code>.</p>
                tags:
                  - Get
                  - Cache
                  - Policies
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/origin-access-identity/cloudfront/{Id}/config:
              PUT:
                summary: UpdateCloudFrontOriginAccessIdentity
                description: <p>Update an origin access identity.</p>
                tags:
                  - Update
                  - Cloud
                  - Front
                  - Origin
                  - Access
                  - Identity
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/continuous-deployment-policy/{Id}/config:
              GET:
                summary: GetContinuousDeploymentPolicyConfig
                description: >-
                  <p>Gets configuration information about a continuous
                  deployment policy.</p>
                tags:
                  - Get
                  - Continuous
                  - Deployments
                  - Policies
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/distribution/{Id}/config:
              PUT:
                summary: UpdateDistribution
                description: >-
                  <p>Updates the configuration for a CloudFront
                  distribution.</p> <p>The update process includes getting the
                  current distribution configuration, updating it to make your
                  changes, and then submitting an
                  <code>UpdateDistribution</code> request to make the
                  updates.</p> <p> <b>To update a web distribution using the
                  CloudFront API</b> </p> <ol> <li> <p>Use
                  <code>GetDistributionConfig</code> to get the current
                  configuration, including the version identifier
                  (<code>ETag</code>).</p> </li> <li> <p>Update the distribution
                  configuration that was returned in the response. Note the
                  following important requirements and restrictions:</p> <ul>
                  <li> <p>You must rename the <code>ETag</code> field to
                  <code>IfMatch</code>, leaving the value unchanged. (Set the
                  value of <code>IfMatch</code> to the value of
                  <code>ETag</code>, then remove the <code>ETag</code>
                  field.)</p> </li> <li> <p>You can't change the value of
                  <code>CallerReference</code>.</p> </li> </ul> </li> <li>
                  <p>Submit an <code>UpdateDistribution</code> request,
                  providing the distribution configuration. The new
                  configuration replaces the existing configuration. The values
                  that you specify in an <code>UpdateDistribution</code> request
                  are not merged into your existing configuration. Make sure to
                  include all fields: the ones that you modified and also the
                  ones that you didn't.</p> </li> </ol>
                tags:
                  - Update
                  - Distributions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/field-level-encryption/{Id}/config:
              PUT:
                summary: UpdateFieldLevelEncryptionConfig
                description: <p>Update a field-level encryption configuration.</p>
                tags:
                  - Update
                  - Fields
                  - Levels
                  - Encryption
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/field-level-encryption-profile/{Id}/config:
              PUT:
                summary: UpdateFieldLevelEncryptionProfile
                description: <p>Update a field-level encryption profile.</p>
                tags:
                  - Update
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/distribution/{DistributionId}/invalidation/{Id}:
              GET:
                summary: GetInvalidation
                description: <p>Get the information about an invalidation.</p>
                tags:
                  - Get
                  - Invalidations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/key-group/{Id}/config:
              GET:
                summary: GetKeyGroupConfig
                description: >-
                  <p>Gets a key group configuration.</p> <p>To get a key group
                  configuration, you must provide the key group's identifier. If
                  the key group is referenced in a distribution's cache
                  behavior, you can get the key group's identifier using
                  <code>ListDistributions</code> or
                  <code>GetDistribution</code>. If the key group is not
                  referenced in a cache behavior, you can get the identifier
                  using <code>ListKeyGroups</code>.</p>
                tags:
                  - Get
                  - Keys
                  - Group
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/origin-access-control/{Id}/config:
              PUT:
                summary: UpdateOriginAccessControl
                description: <p>Updates a CloudFront origin access control.</p>
                tags:
                  - Update
                  - Origin
                  - Access
                  - Control
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/origin-request-policy/{Id}/config:
              GET:
                summary: GetOriginRequestPolicyConfig
                description: >-
                  <p>Gets an origin request policy configuration.</p> <p>To get
                  an origin request policy configuration, you must provide the
                  policy's identifier. If the origin request policy is attached
                  to a distribution's cache behavior, you can get the policy's
                  identifier using <code>ListDistributions</code> or
                  <code>GetDistribution</code>. If the origin request policy is
                  not attached to a cache behavior, you can get the identifier
                  using <code>ListOriginRequestPolicies</code>.</p>
                tags:
                  - Get
                  - Origin
                  - Request
                  - Policies
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/public-key/{Id}/config:
              PUT:
                summary: UpdatePublicKey
                description: >-
                  <p>Update public key information. Note that the only value you
                  can change is the comment.</p>
                tags:
                  - Update
                  - Public
                  - Keys
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
            /2020-05-31/get-realtime-log-config/:
              POST:
                summary: GetRealtimeLogConfig
                description: >-
                  <p>Gets a real-time log configuration.</p> <p>To get a
                  real-time log configuration, you can provide the
                  configuration's name or its Amazon Resource Name (ARN). You
                  must provide at least one. If you provide both, CloudFront
                  uses the name to identify the real-time log configuration to
                  get.</p>
                tags:
                  - Get
                  - Real Time
                  - Logs
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
            /2020-05-31/response-headers-policy/{Id}/config:
              GET:
                summary: GetResponseHeadersPolicyConfig
                description: >-
                  <p>Gets a response headers policy configuration.</p> <p>To get
                  a response headers policy configuration, you must provide the
                  policy's identifier. If the response headers policy is
                  attached to a distribution's cache behavior, you can get the
                  policy's identifier using <code>ListDistributions</code> or
                  <code>GetDistribution</code>. If the response headers policy
                  is not attached to a cache behavior, you can get the
                  identifier using <code>ListResponseHeadersPolicies</code>.</p>
                tags:
                  - Get
                  - Responses
                  - Headers
                  - Policies
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
            /2020-05-31/streaming-distribution/{Id}/config:
              PUT:
                summary: UpdateStreamingDistribution
                description: <p>Update a streaming distribution.</p>
                tags:
                  - Update
                  - Streaming
                  - Distributions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
            /2020-05-31/conflicting-alias:
              GET:
                summary: ListConflictingAliases
                description: >-
                  <p>Gets a list of aliases (also called CNAMEs or alternate
                  domain names) that conflict or overlap with the provided
                  alias, and the associated CloudFront distributions and Amazon
                  Web Services accounts for each conflicting alias. In the
                  returned list, the distribution and account IDs are partially
                  hidden, which allows you to identify the distributions and
                  accounts that you own, but helps to protect the information of
                  ones that you don't own.</p> <p>Use this operation to find
                  aliases that are in use in CloudFront that conflict or overlap
                  with the provided alias. For example, if you provide
                  <code>www.example.com</code> as input, the returned list can
                  include <code>www.example.com</code> and the overlapping
                  wildcard alternate domain name (<code>*.example.com</code>),
                  if they exist. If you provide <code>*.example.com</code> as
                  input, the returned list can include
                  <code>*.example.com</code> and any alternate domain names
                  covered by that wildcard (for example,
                  <code>www.example.com</code>, <code>test.example.com</code>,
                  <code>dev.example.com</code>, and so on), if they exist.</p>
                  <p>To list conflicting aliases, you provide the alias to
                  search and the ID of a distribution in your account that has
                  an attached SSL/TLS certificate that includes the provided
                  alias. For more information, including how to set up the
                  distribution and certificate, see <a
                  href="https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/CNAMEs.html#alternate-domain-names-move">Moving
                  an alternate domain name to a different distribution</a> in
                  the <i>Amazon CloudFront Developer Guide</i>.</p> <p>You can
                  optionally specify the maximum number of items to receive in
                  the response. If the total number of items in the list exceeds
                  the maximum that you specify, or the default maximum, the
                  response is paginated. To get the next page of items, send a
                  subsequent request that specifies the <code>NextMarker</code>
                  value from the current response as the <code>Marker</code>
                  value in the subsequent request.</p>
                tags:
                  - Lists
                  - Conflicting
                  - Aliases
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
            /2020-05-31/distributionsByCachePolicyId/{CachePolicyId}:
              GET:
                summary: ListDistributionsByCachePolicyId
                description: >-
                  <p>Gets a list of distribution IDs for distributions that have
                  a cache behavior that's associated with the specified cache
                  policy.</p> <p>You can optionally specify the maximum number
                  of items to receive in the response. If the total number of
                  items in the list exceeds the maximum that you specify, or the
                  default maximum, the response is paginated. To get the next
                  page of items, send a subsequent request that specifies the
                  <code>NextMarker</code> value from the current response as the
                  <code>Marker</code> value in the subsequent request.</p>
                tags:
                  - Lists
                  - Distributions
                  - By
                  - Cache
                  - Policies
                  - Identifiers
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
            /2020-05-31/distributionsByKeyGroupId/{KeyGroupId}:
              GET:
                summary: ListDistributionsByKeyGroup
                description: >-
                  <p>Gets a list of distribution IDs for distributions that have
                  a cache behavior that references the specified key group.</p>
                  <p>You can optionally specify the maximum number of items to
                  receive in the response. If the total number of items in the
                  list exceeds the maximum that you specify, or the default
                  maximum, the response is paginated. To get the next page of
                  items, send a subsequent request that specifies the
                  <code>NextMarker</code> value from the current response as the
                  <code>Marker</code> value in the subsequent request.</p>
                tags:
                  - Lists
                  - Distributions
                  - By
                  - Keys
                  - Group
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
            /2020-05-31/distributionsByOriginRequestPolicyId/{OriginRequestPolicyId}:
              GET:
                summary: ListDistributionsByOriginRequestPolicyId
                description: >-
                  <p>Gets a list of distribution IDs for distributions that have
                  a cache behavior that's associated with the specified origin
                  request policy.</p> <p>You can optionally specify the maximum
                  number of items to receive in the response. If the total
                  number of items in the list exceeds the maximum that you
                  specify, or the default maximum, the response is paginated. To
                  get the next page of items, send a subsequent request that
                  specifies the <code>NextMarker</code> value from the current
                  response as the <code>Marker</code> value in the subsequent
                  request.</p>
                tags:
                  - Lists
                  - Distributions
                  - By
                  - Origin
                  - Request
                  - Policies
                  - Identifiers
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
            /2020-05-31/distributionsByRealtimeLogConfig/:
              POST:
                summary: ListDistributionsByRealtimeLogConfig
                description: >-
                  <p>Gets a list of distributions that have a cache behavior
                  that's associated with the specified real-time log
                  configuration.</p> <p>You can specify the real-time log
                  configuration by its name or its Amazon Resource Name (ARN).
                  You must provide at least one. If you provide both, CloudFront
                  uses the name to identify the real-time log configuration to
                  list distributions for.</p> <p>You can optionally specify the
                  maximum number of items to receive in the response. If the
                  total number of items in the list exceeds the maximum that you
                  specify, or the default maximum, the response is paginated. To
                  get the next page of items, send a subsequent request that
                  specifies the <code>NextMarker</code> value from the current
                  response as the <code>Marker</code> value in the subsequent
                  request.</p>
                tags:
                  - Lists
                  - Distributions
                  - By
                  - Real Time
                  - Logs
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
            /2020-05-31/distributionsByResponseHeadersPolicyId/{ResponseHeadersPolicyId}:
              GET:
                summary: ListDistributionsByResponseHeadersPolicyId
                description: >-
                  <p>Gets a list of distribution IDs for distributions that have
                  a cache behavior that's associated with the specified response
                  headers policy.</p> <p>You can optionally specify the maximum
                  number of items to receive in the response. If the total
                  number of items in the list exceeds the maximum that you
                  specify, or the default maximum, the response is paginated. To
                  get the next page of items, send a subsequent request that
                  specifies the <code>NextMarker</code> value from the current
                  response as the <code>Marker</code> value in the subsequent
                  request.</p>
                tags:
                  - Lists
                  - Distributions
                  - By
                  - Responses
                  - Headers
                  - Policies
                  - Identifiers
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
            /2020-05-31/distributionsByWebACLId/{WebACLId}:
              GET:
                summary: ListDistributionsByWebACLId
                description: >-
                  <p>List the distributions that are associated with a specified
                  WAF web ACL.</p>
                tags:
                  - Lists
                  - Distributions
                  - By
                  - Web
                  - Identifiers
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
                  - Web
            /2020-05-31/key-value-store:
              GET:
                summary: ListKeyValueStores
                description: <p>Specifies the Key Value Stores to list.</p>
                tags:
                  - Lists
                  - Keys
                  - Value
                  - Stores
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
                  - Web
            /2020-05-31/tagging:
              GET:
                summary: ListTagsForResource
                description: <p>List tags for a CloudFront resource.</p>
                tags:
                  - Lists
                  - Tags
                  - For
                  - Resources
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
                  - Web
                  - Tagging
            /2020-05-31/function/{Name}/publish:
              POST:
                summary: PublishFunction
                description: >-
                  <p>Publishes a CloudFront function by copying the function
                  code from the <code>DEVELOPMENT</code> stage to
                  <code>LIVE</code>. This automatically updates all cache
                  behaviors that are using this function to use the newly
                  published copy in the <code>LIVE</code> stage.</p> <p>When a
                  function is published to the <code>LIVE</code> stage, you can
                  attach the function to a distribution's cache behavior, using
                  the function's Amazon Resource Name (ARN).</p> <p>To publish a
                  function, you must provide the function's name and version
                  (<code>ETag</code> value). To get these values, you can use
                  <code>ListFunctions</code> and
                  <code>DescribeFunction</code>.</p>
                tags:
                  - Publish
                  - Functions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
                  - Web
                  - Tagging
                  - Publish
            /2020-05-31/tagging?Operation=Tag:
              POST:
                summary: TagResource
                description: <p>Add tags to a CloudFront resource.</p>
                tags:
                  - Tags
                  - Resources
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
                  - Web
                  - Tagging
                  - Publish
                  - Operations
                  - Tags
            /2020-05-31/function/{Name}/test:
              POST:
                summary: TestFunction
                description: >-
                  <p>Tests a CloudFront function.</p> <p>To test a function, you
                  provide an <i>event object</i> that represents an HTTP request
                  or response that your CloudFront distribution could receive in
                  production. CloudFront runs the function, passing it the event
                  object that you provided, and returns the function's result
                  (the modified event object) in the response. The response also
                  contains function logs and error messages, if any exist. For
                  more information about testing functions, see <a
                  href="https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/managing-functions.html#test-function">Testing
                  functions</a> in the <i>Amazon CloudFront Developer
                  Guide</i>.</p> <p>To test a function, you provide the
                  function's name and version (<code>ETag</code> value) along
                  with the event object. To get the function's name and version,
                  you can use <code>ListFunctions</code> and
                  <code>DescribeFunction</code>.</p>
                tags:
                  - Tests
                  - Functions
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
                  - Web
                  - Tagging
                  - Publish
                  - Operations
                  - Tags
                  - Tests
            /2020-05-31/tagging?Operation=Untag:
              POST:
                summary: UntagResource
                description: <p>Remove tags from a CloudFront resource.</p>
                tags:
                  - Untag
                  - Resources
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
                  - Web
                  - Tagging
                  - Publish
                  - Operations
                  - Tags
                  - Tests
                  - Untag
            /2020-05-31/distribution/{Id}/promote-staging-config:
              PUT:
                summary: UpdateDistributionWithStagingConfig
                description: >-
                  <p>Copies the staging distribution's configuration to its
                  corresponding primary distribution. The primary distribution
                  retains its <code>Aliases</code> (also known as alternate
                  domain names or CNAMEs) and
                  <code>ContinuousDeploymentPolicyId</code> value, but otherwise
                  its configuration is overwritten to match the staging
                  distribution.</p> <p>You can use this operation in a
                  continuous deployment workflow after you have tested
                  configuration changes on the staging distribution. After using
                  a continuous deployment policy to move a portion of your
                  domain name's traffic to the staging distribution and
                  verifying that it works as intended, you can use this
                  operation to copy the staging distribution's configuration to
                  the primary distribution. This action will disable the
                  continuous deployment policy and move your domain's traffic
                  back to the primary distribution.</p> <p>This API operation
                  requires the following IAM permissions:</p> <ul> <li> <p> <a
                  href="https://docs.aws.amazon.com/cloudfront/latest/APIReference/API_GetDistribution.html">GetDistribution</a>
                  </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/cloudfront/latest/APIReference/API_UpdateDistribution.html">UpdateDistribution</a>
                  </p> </li> </ul>
                tags:
                  - Update
                  - Distributions
                  - With
                  - Staging
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
                  - Web
                  - Tagging
                  - Publish
                  - Operations
                  - Tags
                  - Tests
                  - Untag
                  - Promote
                  - Staging
            /2020-05-31/realtime-log-config/:
              PUT:
                summary: UpdateRealtimeLogConfig
                description: >-
                  <p>Updates a real-time log configuration.</p> <p>When you
                  update a real-time log configuration, all the parameters are
                  updated with the values provided in the request. You cannot
                  update some parameters independent of others. To update a
                  real-time log configuration:</p> <ol> <li> <p>Call
                  <code>GetRealtimeLogConfig</code> to get the current real-time
                  log configuration.</p> </li> <li> <p>Locally modify the
                  parameters in the real-time log configuration that you want to
                  update.</p> </li> <li> <p>Call this API
                  (<code>UpdateRealtimeLogConfig</code>) by providing the entire
                  real-time log configuration, including the parameters that you
                  modified and those that you didn't.</p> </li> </ol> <p>You
                  cannot update a real-time log configuration's
                  <code>Name</code> or <code>ARN</
                tags:
                  - Update
                  - Real Time
                  - Logs
                  - Configurations
                  - Target
                  - Distributions
                  - Identifiers
                  - Associate
                  - Alias
                  - Primary
                  - Copy
                  - '2020'
                  - '05'
                  - '31'
                  - Cache
                  - Policies
                  - Origin
                  - Access
                  - Identity
                  - Cloudfront
                  - Continuous
                  - Deployments
                  - With
                  - Tags
                  - Fields
                  - Levels
                  - Encryption
                  - Profiles
                  - Functions
                  - Invalidations
                  - Keys
                  - Group
                  - Value
                  - Store
                  - Monitoring
                  - Subscriptions
                  - Control
                  - Request
                  - Public
                  - Real Time
                  - Logs
                  - Configurations
                  - Responses
                  - Headers
                  - Streaming
                  - Names
                  - Delete
                  - Describe
                  - Get
                  - Conflicting
                  - By
                  - Web
                  - Tagging
                  - Publish
                  - Operations
                  - Tags
                  - Tests
                  - Untag
                  - Promote
                  - Staging
    overlays:
      - type: APIs.io Search
        url: overlays/cloudfront-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/cloudfront-openapi-api-evangelist-ratings.yml
    aid: amazon-web-services:cloudfront
  - name: iot
    description: >-
      <fullname>IoT</fullname> <p>IoT provides secure, bi-directional
      communication between Internet-connected devices (such as sensors,
      actuators, embedded devices, or smart appliances) and the Amazon Web
      Services cloud. You can discover your custom IoT-Data endpoint to
      communicate with, configure rules for data processing and integration with
      other services, organize resources associated with each device (Registry),
      configure logging, and create and manage policies and credentials to
      authenticate devices.</p> <p>The service endpoints that expose this API
      are listed in <a
      href="https://docs.aws.amazon.com/general/latest/gr/iot-core.html">Amazon
      Web Services IoT Core Endpoints and Quotas</a>. You must use the endpoint
      for the region that has the resources you want to access.</p> <p>The
      service name used by <a
      href="https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html">Amazon
      Web Services Signature Version 4</a> to sign the request is:
      <i>execute-api</i>.</p> <p>For more information about how IoT works, see
      the <a
      href="https://docs.aws.amazon.com/iot/latest/developerguide/aws-iot-how-it-works.html">Developer
      Guide</a>.</p> <p>For information about how to use the credentials
      provider for IoT, see <a
      href="https://docs.aws.amazon.com/iot/latest/developerguide/authorizing-direct-aws.html">Authorizing
      Direct Calls to Amazon Web Services Services</a>.</p>
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://example.com
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://example.com
      - type: OpenAPI
        data:
          openapi: 3.1.0
          info:
            title: iot
          paths:
            /accept-certificate-transfer/{certificateId}:
              PATCH:
                summary: AcceptCertificateTransfer
                description: >-
                  <p>Accepts a pending certificate transfer. The default state
                  of the certificate is INACTIVE.</p> <p>To check for pending
                  certificate transfers, call <a>ListCertificates</a> to
                  enumerate your certificates.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">AcceptCertificateTransfer</a>
                  action.</p>
                tags:
                  - Accept
                  - Certificates
                  - Transfers
                  - Identifiers
            /billing-groups/addThingToBillingGroup:
              PUT:
                summary: AddThingToBillingGroup
                description: >-
                  <p>Adds a thing to a billing group.</p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">AddThingToBillingGroup</a>
                  action.</p>
                tags:
                  - Add
                  - Things
                  - To
                  - Billing
                  - Group
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
            /thing-groups/addThingToThingGroup:
              PUT:
                summary: AddThingToThingGroup
                description: >-
                  <p>Adds a thing to a thing group.</p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">AddThingToThingGroup</a>
                  action.</p>
                tags:
                  - Add
                  - Things
                  - To
                  - Group
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
            /jobs/{jobId}/targets:
              POST:
                summary: AssociateTargetsWithJob
                description: >-
                  <p>Associates a group with a continuous job. The following
                  criteria must be met: </p> <ul> <li> <p>The job must have been
                  created with the <code>targetSelection</code> field set to
                  "CONTINUOUS".</p> </li> <li> <p>The job status must currently
                  be "IN_PROGRESS".</p> </li> <li> <p>The total number of
                  targets associated with a job must not exceed 100.</p> </li>
                  </ul> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">AssociateTargetsWithJob</a>
                  action.</p>
                tags:
                  - Associate
                  - Targets
                  - With
                  - Jobs
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
            /target-policies/{policyName}:
              POST:
                summary: DetachPolicy
                description: >-
                  <p>Detaches a policy from the specified target.</p> <note>
                  <p>Because of the distributed nature of Amazon Web Services,
                  it can take up to five minutes after a policy is detached
                  before it's ready to be deleted.</p> </note> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DetachPolicy</a>
                  action.</p>
                tags:
                  - Detach
                  - Policies
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
            /principal-policies/{policyName}:
              DELETE:
                summary: DetachPrincipalPolicy
                description: >-
                  <p>Removes the specified policy from the specified
                  certificate.</p> <p> <b>Note:</b> This action is deprecated
                  and works as expected for backward compatibility, but we won't
                  add enhancements. Use <a>DetachPolicy</a> instead.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DetachPrincipalPolicy</a>
                  action.</p>
                tags:
                  - Detach
                  - Principals
                  - Policies
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
            /security-profiles/{securityProfileName}/targets:
              GET:
                summary: ListTargetsForSecurityProfile
                description: >-
                  <p>Lists the targets (thing groups) associated with a given
                  Device Defender security profile.</p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListTargetsForSecurityProfile</a>
                  action.</p>
                tags:
                  - Lists
                  - Targets
                  - For
                  - Security
                  - Profiles
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
            /things/{thingName}/principals:
              GET:
                summary: ListThingPrincipals
                description: >-
                  <p>Lists the principals associated with the specified thing. A
                  principal can be X.509 certificates, IAM users, groups, and
                  roles, Amazon Cognito identities or federated identities.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListThingPrincipals</a>
                  action.</p>
                tags:
                  - Lists
                  - Things
                  - Principals
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
            /audit/mitigationactions/tasks/{taskId}/cancel:
              PUT:
                summary: CancelAuditMitigationActionsTask
                description: >-
                  <p>Cancels a mitigation action task that is in progress. If
                  the task is not in progress, an InvalidRequestException
                  occurs.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">CancelAuditMitigationActionsTask</a>
                  action.</p>
                tags:
                  - Cancel
                  - Audit
                  - Mitigation
                  - Actions
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
            /audit/tasks/{taskId}/cancel:
              PUT:
                summary: CancelAuditTask
                description: >-
                  <p>Cancels an audit that is in progress. The audit can be
                  either scheduled or on demand. If the audit isn't in progress,
                  an "InvalidRequestException" occurs.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">CancelAuditTask</a>
                  action.</p>
                tags:
                  - Cancel
                  - Audit
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
            /cancel-certificate-transfer/{certificateId}:
              PATCH:
                summary: CancelCertificateTransfer
                description: >-
                  <p>Cancels a pending transfer for the specified
                  certificate.</p> <p> <b>Note</b> Only the transfer source
                  account can use this operation to cancel a transfer. (Transfer
                  destinations can use <a>RejectCertificateTransfer</a>
                  instead.) After transfer, IoT returns the certificate to the
                  source account in the INACTIVE state. After the destination
                  account has accepted the transfer, the transfer cannot be
                  cancelled.</p> <p>After a certificate transfer is cancelled,
                  the status of the certificate changes from PENDING_TRANSFER to
                  INACTIVE.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">CancelCertificateTransfer</a>
                  action.</p>
                tags:
                  - Cancel
                  - Certificates
                  - Transfers
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
            /detect/mitigationactions/tasks/{taskId}/cancel:
              PUT:
                summary: CancelDetectMitigationActionsTask
                description: >-
                  <p> Cancels a Device Defender ML Detect mitigation action.
                  </p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">CancelDetectMitigationActionsTask</a>
                  action.</p>
                tags:
                  - Cancel
                  - Detect
                  - Mitigation
                  - Actions
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
            /jobs/{jobId}/cancel:
              PUT:
                summary: CancelJob
                description: >-
                  <p>Cancels a job.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">CancelJob</a>
                  action.</p>
                tags:
                  - Cancel
                  - Jobs
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
            /things/{thingName}/jobs/{jobId}/cancel:
              PUT:
                summary: CancelJobExecution
                description: >-
                  <p>Cancels the execution of a job for a given thing.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">CancelJobExecution</a>
                  action.</p>
                tags:
                  - Cancel
                  - Jobs
                  - Execution
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
            /default-authorizer:
              POST:
                summary: SetDefaultAuthorizer
                description: >-
                  <p>Sets the default authorizer. This will be used if a
                  websocket connection is made without specifying an
                  authorizer.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">SetDefaultAuthorizer</a>
                  action.</p>
                tags:
                  - Sets
                  - Default
                  - Authorizer
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
            /confirmdestination/{confirmationToken+}:
              GET:
                summary: ConfirmTopicRuleDestination
                description: >-
                  <p>Confirms a topic rule destination. When you create a rule
                  requiring a destination, IoT sends a confirmation message to
                  the endpoint or base address you specify. The message includes
                  a token which you pass back when calling
                  <code>ConfirmTopicRuleDestination</code> to confirm that you
                  own or have access to the endpoint.</p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ConfirmTopicRuleDestination</a>
                  action.</p>
                tags:
                  - Confirm
                  - Topics
                  - Rules
                  - Destinations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
            /audit/suppressions/create:
              POST:
                summary: CreateAuditSuppression
                description: >-
                  <p> Creates a Device Defender audit suppression. </p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">CreateAuditSuppression</a>
                  action.</p>
                tags:
                  - Create
                  - Audit
                  - Suppressions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
            /authorizer/{authorizerName}:
              PUT:
                summary: UpdateAuthorizer
                description: >-
                  <p>Updates an authorizer.</p> <p>Requires permission to access
                  the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateAuthorizer</a>
                  action.</p>
                tags:
                  - Update
                  - Authorizer
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
            /billing-groups/{billingGroupName}:
              PATCH:
                summary: UpdateBillingGroup
                description: >-
                  <p>Updates information about the billing group.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateBillingGroup</a>
                  action.</p>
                tags:
                  - Update
                  - Billing
                  - Group
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
            /certificates:
              GET:
                summary: ListCertificates
                description: >-
                  <p>Lists the certificates registered in your Amazon Web
                  Services account.</p> <p>The results are paginated with a
                  default page size of 25. You can use the returned marker to
                  retrieve additional results.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListCertificates</a>
                  action.</p>
                tags:
                  - Lists
                  - Certificates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
            /certificate-providers/{certificateProviderName}:
              PUT:
                summary: UpdateCertificateProvider
                description: >-
                  <p>Updates a certificate provider.</p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateCertificateProvider</a>
                  action. </p>
                tags:
                  - Update
                  - Certificates
                  - Providers
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
            /custom-metric/{metricName}:
              PATCH:
                summary: UpdateCustomMetric
                description: >-
                  <p>Updates a Device Defender detect custom metric. </p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateCustomMetric</a>
                  action.</p>
                tags:
                  - Update
                  - Custom
                  - Metrics
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
            /dimensions/{name}:
              PATCH:
                summary: UpdateDimension
                description: >-
                  <p>Updates the definition for a dimension. You cannot change
                  the type of a dimension after it is created (you can delete it
                  and recreate it).</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateDimension</a>
                  action.</p>
                tags:
                  - Update
                  - Dimensions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
            /domainConfigurations/{domainConfigurationName}:
              PUT:
                summary: UpdateDomainConfiguration
                description: >-
                  <p>Updates values stored in the domain configuration. Domain
                  configurations for default endpoints can't be updated.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateDomainConfiguration</a>
                  action.</p>
                tags:
                  - Update
                  - Domains
                  - Configurations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
            /dynamic-thing-groups/{thingGroupName}:
              PATCH:
                summary: UpdateDynamicThingGroup
                description: >-
                  <p>Updates a dynamic thing group.</p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateDynamicThingGroup</a>
                  action.</p>
                tags:
                  - Update
                  - Dynamic
                  - Things
                  - Group
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
            /fleet-metric/{metricName}:
              PATCH:
                summary: UpdateFleetMetric
                description: >-
                  <p>Updates the data for a fleet metric.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateFleetMetric</a>
                  action.</p>
                tags:
                  - Update
                  - Fleets
                  - Metrics
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
            /jobs/{jobId}:
              PATCH:
                summary: UpdateJob
                description: >-
                  <p>Updates supported fields of the specified job.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateJob</a>
                  action.</p>
                tags:
                  - Update
                  - Jobs
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
            /job-templates/{jobTemplateId}:
              GET:
                summary: DescribeJobTemplate
                description: <p>Returns information about a job template.</p>
                tags:
                  - Describe
                  - Jobs
                  - Templates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
            /keys-and-certificate:
              POST:
                summary: CreateKeysAndCertificate
                description: >-
                  <p>Creates a 2048-bit RSA key pair and issues an X.509
                  certificate using the issued public key. You can also call
                  <code>CreateKeysAndCertificate</code> over MQTT from a device,
                  for more information, see <a
                  href="https://docs.aws.amazon.com/iot/latest/developerguide/provision-wo-cert.html#provision-mqtt-api">Provisioning
                  MQTT API</a>.</p> <p> <b>Note</b> This is the only time IoT
                  issues the private key for this certificate, so it is
                  important to keep it in a secure location.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">CreateKeysAndCertificate</a>
                  action.</p>
                tags:
                  - Create
                  - Keys
                  - And
                  - Certificates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
            /mitigationactions/actions/{actionName}:
              PATCH:
                summary: UpdateMitigationAction
                description: >-
                  <p>Updates the definition for the specified mitigation
                  action.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateMitigationAction</a>
                  action.</p>
                tags:
                  - Update
                  - Mitigation
                  - Actions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
            /otaUpdates/{otaUpdateId}:
              GET:
                summary: GetOTAUpdate
                description: >-
                  <p>Gets an OTA update.</p> <p>Requires permission to access
                  the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetOTAUpdate</a>
                  action.</p>
                tags:
                  - Get
                  - Update
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
            /packages/{packageName}:
              PATCH:
                summary: UpdatePackage
                description: >-
                  <p>Updates the supported fields for a specific software
                  package.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdatePackage</a>
                  and <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetIndexingConfiguration</a>
                  actions.</p>
                tags:
                  - Update
                  - Packages
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
            /packages/{packageName}/versions/{versionName}:
              PATCH:
                summary: UpdatePackageVersion
                description: >-
                  <p>Updates the supported fields for a specific package
                  version.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdatePackageVersion</a>
                  and <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetIndexingConfiguration</a>
                  actions.</p>
                tags:
                  - Update
                  - Packages
                  - Versions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
            /policies/{policyName}:
              GET:
                summary: GetPolicy
                description: >-
                  <p>Gets information about the specified policy with the policy
                  document of the default version.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetPolicy</a>
                  action.</p>
                tags:
                  - Get
                  - Policies
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
            /policies/{policyName}/version:
              GET:
                summary: ListPolicyVersions
                description: >-
                  <p>Lists the versions of the specified policy and identifies
                  the default version.</p> <p>Requires permission to access the
                  <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListPolicyVersions</a>
                  action.</p>
                tags:
                  - Lists
                  - Policies
                  - Versions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
            /provisioning-templates/{templateName}/provisioning-claim:
              POST:
                summary: CreateProvisioningClaim
                description: >-
                  <p>Creates a provisioning claim.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">CreateProvisioningClaim</a>
                  action.</p>
                tags:
                  - Create
                  - Provisioning
                  - Claim
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
            /provisioning-templates:
              GET:
                summary: ListProvisioningTemplates
                description: >-
                  <p>Lists the provisioning templates in your Amazon Web
                  Services account.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListProvisioningTemplates</a>
                  action.</p>
                tags:
                  - Lists
                  - Provisioning
                  - Templates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
            /provisioning-templates/{templateName}/versions:
              GET:
                summary: ListProvisioningTemplateVersions
                description: >-
                  <p>A list of provisioning template versions.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListProvisioningTemplateVersions</a>
                  action.</p>
                tags:
                  - Lists
                  - Provisioning
                  - Templates
                  - Versions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
            /role-aliases/{roleAlias}:
              PUT:
                summary: UpdateRoleAlias
                description: >-
                  <p>Updates a role alias.</p> <p>Requires permission to access
                  the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateRoleAlias</a>
                  action.</p>
                tags:
                  - Update
                  - Roles
                  - Alias
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
            /audit/scheduledaudits/{scheduledAuditName}:
              PATCH:
                summary: UpdateScheduledAudit
                description: >-
                  <p>Updates a scheduled audit, including which checks are
                  performed and how often the audit takes place.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateScheduledAudit</a>
                  action.</p>
                tags:
                  - Update
                  - Scheduled
                  - Audit
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
            /security-profiles/{securityProfileName}:
              PATCH:
                summary: UpdateSecurityProfile
                description: >-
                  <p>Updates a Device Defender security profile.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateSecurityProfile</a>
                  action.</p>
                tags:
                  - Update
                  - Security
                  - Profiles
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
            /streams/{streamId}:
              PUT:
                summary: UpdateStream
                description: >-
                  <p>Updates an existing stream. The stream version will be
                  incremented by one.</p> <p>Requires permission to access the
                  <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateStream</a>
                  action.</p>
                tags:
                  - Update
                  - Stream
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
            /things/{thingName}:
              PATCH:
                summary: UpdateThing
                description: >-
                  <p>Updates the data for a thing.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateThing</a>
                  action.</p>
                tags:
                  - Update
                  - Things
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
            /thing-groups/{thingGroupName}:
              PATCH:
                summary: UpdateThingGroup
                description: >-
                  <p>Update a thing group.</p> <p>Requires permission to access
                  the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateThingGroup</a>
                  action.</p>
                tags:
                  - Update
                  - Things
                  - Group
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
            /thing-types/{thingTypeName}:
              GET:
                summary: DescribeThingType
                description: >-
                  <p>Gets information about the specified thing type.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DescribeThingType</a>
                  action.</p>
                tags:
                  - Describe
                  - Things
                  - Types
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
            /rules/{ruleName}:
              PATCH:
                summary: ReplaceTopicRule
                description: >-
                  <p>Replaces the rule. You must specify all parameters for the
                  new rule. Creating rules is an administrator-level action. Any
                  user who has permission to create rules will be able to access
                  data processed by the rule.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ReplaceTopicRule</a>
                  action.</p>
                tags:
                  - Replace
                  - Topics
                  - Rules
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
            /destinations:
              PATCH:
                summary: UpdateTopicRuleDestination
                description: >-
                  <p>Updates a topic rule destination. You use this to change
                  the status, endpoint URL, or confirmation URL of the
                  destination.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateTopicRuleDestination</a>
                  action.</p>
                tags:
                  - Update
                  - Topics
                  - Rules
                  - Destinations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
            /audit/configuration:
              PATCH:
                summary: UpdateAccountAuditConfiguration
                description: >-
                  <p>Configures or reconfigures the Device Defender audit
                  settings for this account. Settings include how audit
                  notifications are sent and which audit checks are enabled or
                  disabled.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateAccountAuditConfiguration</a>
                  action.</p>
                tags:
                  - Update
                  - Account
                  - Audit
                  - Configurations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
            /audit/suppressions/delete:
              POST:
                summary: DeleteAuditSuppression
                description: >-
                  <p> Deletes a Device Defender audit suppression. </p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DeleteAuditSuppression</a>
                  action.</p>
                tags:
                  - Delete
                  - Audit
                  - Suppressions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
            /cacertificate/{caCertificateId}:
              PUT:
                summary: UpdateCACertificate
                description: >-
                  <p>Updates a registered CA certificate.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateCACertificate</a>
                  action.</p>
                tags:
                  - Update
                  - Certificates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
            /certificates/{certificateId}:
              PUT:
                summary: UpdateCertificate
                description: >-
                  <p>Updates the status of the specified certificate. This
                  operation is idempotent.</p> <p>Requires permission to access
                  the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateCertificate</a>
                  action.</p> <p>Certificates must be in the ACTIVE state to
                  authenticate devices that use a certificate to connect to
                  IoT.</p> <p>Within a few minutes of updating a certificate
                  from the ACTIVE state to any other state, IoT disconnects all
                  devices that used that certificate to connect. Devices cannot
                  use a certificate that is not in the ACTIVE state to
                  reconnect.</p>
                tags:
                  - Update
                  - Certificates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
            /things/{thingName}/jobs/{jobId}/executionNumber/{executionNumber}:
              DELETE:
                summary: DeleteJobExecution
                description: >-
                  <p>Deletes a job execution.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DeleteJobExecution</a>
                  action.</p>
                tags:
                  - Delete
                  - Jobs
                  - Execution
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
            /policies/{policyName}/version/{policyVersionId}:
              PATCH:
                summary: SetDefaultPolicyVersion
                description: >-
                  <p>Sets the specified version of the specified policy as the
                  policy's default (operative) version. This action affects all
                  certificates to which the policy is attached. To list the
                  principals the policy is attached to, use the
                  <a>ListPrincipalPolicies</a> action.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">SetDefaultPolicyVersion</a>
                  action.</p>
                tags:
                  - Sets
                  - Default
                  - Policies
                  - Versions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
            /provisioning-templates/{templateName}:
              PATCH:
                summary: UpdateProvisioningTemplate
                description: >-
                  <p>Updates a provisioning template.</p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateProvisioningTemplate</a>
                  action.</p>
                tags:
                  - Update
                  - Provisioning
                  - Templates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
            /provisioning-templates/{templateName}/versions/{versionId}:
              GET:
                summary: DescribeProvisioningTemplateVersion
                description: >-
                  <p>Returns information about a provisioning template
                  version.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DescribeProvisioningTemplateVersion</a>
                  action.</p>
                tags:
                  - Describe
                  - Provisioning
                  - Templates
                  - Versions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
            /registrationcode:
              GET:
                summary: GetRegistrationCode
                description: >-
                  <p>Gets a registration code used to register a CA certificate
                  with IoT.</p> <p>IoT will create a registration code as part
                  of this API call if the registration code doesn't exist or has
                  been deleted. If you already have a registration code, this
                  API call will return the same registration code.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetRegistrationCode</a>
                  action.</p>
                tags:
                  - Get
                  - Registrations
                  - Code
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
            /destinations/{arn+}:
              GET:
                summary: GetTopicRuleDestination
                description: >-
                  <p>Gets information about a topic rule destination.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetTopicRuleDestination</a>
                  action.</p>
                tags:
                  - Get
                  - Topics
                  - Rules
                  - Destinations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
            /v2LoggingLevel:
              POST:
                summary: SetV2LoggingLevel
                description: >-
                  <p>Sets the logging level.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">SetV2LoggingLevel</a>
                  action.</p>
                tags:
                  - Sets
                  - V2
                  - Logging
                  - Levels
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
            /thing-types/{thingTypeName}/deprecate:
              POST:
                summary: DeprecateThingType
                description: >-
                  <p>Deprecates a thing type. You can not associate new things
                  with deprecated thing type.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DeprecateThingType</a>
                  action.</p>
                tags:
                  - Deprecate
                  - Things
                  - Types
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
            /audit/findings/{findingId}:
              GET:
                summary: DescribeAuditFinding
                description: >-
                  <p>Gets information about a single audit finding. Properties
                  include the reason for noncompliance, the severity of the
                  issue, and the start time when the audit that returned the
                  finding.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DescribeAuditFinding</a>
                  action.</p>
                tags:
                  - Describe
                  - Audit
                  - Findings
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
            /audit/mitigationactions/tasks/{taskId}:
              POST:
                summary: StartAuditMitigationActionsTask
                description: >-
                  <p>Starts a task that applies a set of mitigation actions to
                  the specified target.</p> <p>Requires permission to access the
                  <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">StartAuditMitigationActionsTask</a>
                  action.</p>
                tags:
                  - Start
                  - Audit
                  - Mitigation
                  - Actions
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
            /audit/suppressions/describe:
              POST:
                summary: DescribeAuditSuppression
                description: >-
                  <p> Gets information about a Device Defender audit
                  suppression. </p>
                tags:
                  - Describe
                  - Audit
                  - Suppressions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
            /audit/tasks/{taskId}:
              GET:
                summary: DescribeAuditTask
                description: >-
                  <p>Gets information about a Device Defender audit.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DescribeAuditTask</a>
                  action.</p>
                tags:
                  - Describe
                  - Audit
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
            /detect/mitigationactions/tasks/{taskId}:
              PUT:
                summary: StartDetectMitigationActionsTask
                description: >-
                  <p> Starts a Device Defender ML Detect mitigation actions
                  task. </p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">StartDetectMitigationActionsTask</a>
                  action.</p>
                tags:
                  - Start
                  - Detect
                  - Mitigation
                  - Actions
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
            /endpoint:
              GET:
                summary: DescribeEndpoint
                description: >-
                  <p>Returns or creates a unique endpoint specific to the Amazon
                  Web Services account making the call.</p> <note> <p>The first
                  time <code>DescribeEndpoint</code> is called, an endpoint is
                  created. All subsequent calls to <code>DescribeEndpoint</code>
                  return the same endpoint.</p> </note> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DescribeEndpoint</a>
                  action.</p>
                tags:
                  - Describe
                  - Endpoints
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
            /event-configurations:
              PATCH:
                summary: UpdateEventConfigurations
                description: >-
                  <p>Updates the event configurations.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateEventConfigurations</a>
                  action.</p>
                tags:
                  - Update
                  - Events
                  - Configurations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
            /indices/{indexName}:
              GET:
                summary: DescribeIndex
                description: >-
                  <p>Describes a search index.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DescribeIndex</a>
                  action.</p>
                tags:
                  - Describe
                  - Index
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
            /things/{thingName}/jobs/{jobId}:
              GET:
                summary: DescribeJobExecution
                description: >-
                  <p>Describes a job execution.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DescribeJobExecution</a>
                  action.</p>
                tags:
                  - Describe
                  - Jobs
                  - Execution
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
            /managed-job-templates/{templateName}:
              GET:
                summary: DescribeManagedJobTemplate
                description: <p>View details of a managed job template.</p>
                tags:
                  - Describe
                  - Managed
                  - Jobs
                  - Templates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
            /thing-registration-tasks/{taskId}:
              GET:
                summary: DescribeThingRegistrationTask
                description: >-
                  <p>Describes a bulk thing provisioning task.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DescribeThingRegistrationTask</a>
                  action.</p>
                tags:
                  - Describe
                  - Things
                  - Registrations
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
            /rules/{ruleName}/disable:
              POST:
                summary: DisableTopicRule
                description: >-
                  <p>Disables the rule.</p> <p>Requires permission to access the
                  <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">DisableTopicRule</a>
                  action.</p>
                tags:
                  - Disable
                  - Topics
                  - Rules
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
            /rules/{ruleName}/enable:
              POST:
                summary: EnableTopicRule
                description: >-
                  <p>Enables the rule.</p> <p>Requires permission to access the
                  <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">EnableTopicRule</a>
                  action.</p>
                tags:
                  - Enable
                  - Topics
                  - Rules
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
            /behavior-model-training/summaries:
              GET:
                summary: GetBehaviorModelTrainingSummaries
                description: >-
                  <p> Returns a Device Defender's ML Detect Security Profile
                  training model's status. </p> <p>Requires permission to access
                  the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetBehaviorModelTrainingSummaries</a>
                  action.</p>
                tags:
                  - Get
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
            /indices/buckets:
              POST:
                summary: GetBucketsAggregation
                description: >-
                  <p>Aggregates on indexed data with search queries pertaining
                  to particular fields. </p> <p>Requires permission to access
                  the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetBucketsAggregation</a>
                  action.</p>
                tags:
                  - Get
                  - Buckets
                  - Aggregation
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
            /indices/cardinality:
              POST:
                summary: GetCardinality
                description: >-
                  <p>Returns the approximate count of unique values that match
                  the query.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetCardinality</a>
                  action.</p>
                tags:
                  - Get
                  - Cardinality
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
            /effective-policies:
              POST:
                summary: GetEffectivePolicies
                description: >-
                  <p>Gets a list of the policies that have an effect on the
                  authorization behavior of the specified device when it
                  connects to the IoT device gateway.</p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetEffectivePolicies</a>
                  action.</p>
                tags:
                  - Get
                  - Effective
                  - Policies
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
            /indexing/config:
              POST:
                summary: UpdateIndexingConfiguration
                description: >-
                  <p>Updates the search configuration.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateIndexingConfiguration</a>
                  action.</p>
                tags:
                  - Update
                  - Indexing
                  - Configurations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
            /jobs/{jobId}/job-document:
              GET:
                summary: GetJobDocument
                description: >-
                  <p>Gets a job document.</p> <p>Requires permission to access
                  the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetJobDocument</a>
                  action.</p>
                tags:
                  - Get
                  - Jobs
                  - Document
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
            /loggingOptions:
              POST:
                summary: SetLoggingOptions
                description: >-
                  <p>Sets the logging options.</p> <p>NOTE: use of this command
                  is not recommended. Use <code>SetV2LoggingOptions</code>
                  instead.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">SetLoggingOptions</a>
                  action.</p>
                tags:
                  - Sets
                  - Logging
                  - Options
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
            /package-configuration:
              PATCH:
                summary: UpdatePackageConfiguration
                description: >-
                  <p>Updates the software package configuration.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdatePackageConfiguration</a>
                  and <a
                  href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_use_passrole.html">iam:PassRole</a>
                  actions.</p>
                tags:
                  - Update
                  - Packages
                  - Configurations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
            /indices/percentiles:
              POST:
                summary: GetPercentiles
                description: >-
                  <p>Groups the aggregated values that match the query into
                  percentile groupings. The default percentile groupings are:
                  1,5,25,50,75,95,99, although you can specify your own when you
                  call <code>GetPercentiles</code>. This function returns a
                  value for each percentile group specified (or the default
                  percentile groupings). The percentile group "1" contains the
                  aggregated field value that occurs in approximately one
                  percent of the values that match the query. The percentile
                  group "5" contains the aggregated field value that occurs in
                  approximately five percent of the values that match the query,
                  and so on. The result is an approximation, the more values
                  that match the query, the more accurate the percentile
                  values.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetPercentiles</a>
                  action.</p>
                tags:
                  - Get
                  - Percentiles
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
            /indices/statistics:
              POST:
                summary: GetStatistics
                description: >-
                  <p>Returns the count, average, sum, minimum, maximum, sum of
                  squares, variance, and standard deviation for the specified
                  aggregated field. If the aggregation field is of type
                  <code>String</code>, only the count statistic is returned.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">GetStatistics</a>
                  action.</p>
                tags:
                  - Get
                  - Statistics
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
            /v2LoggingOptions:
              POST:
                summary: SetV2LoggingOptions
                description: >-
                  <p>Sets the logging options for the V2 logging service.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">SetV2LoggingOptions</a>
                  action.</p>
                tags:
                  - Sets
                  - V2
                  - Logging
                  - Options
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
            /active-violations:
              GET:
                summary: ListActiveViolations
                description: >-
                  <p>Lists the active violations for a given Device Defender
                  security profile.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListActiveViolations</a>
                  action.</p>
                tags:
                  - Lists
                  - Active
                  - Violations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
            /attached-policies/{target}:
              POST:
                summary: ListAttachedPolicies
                description: >-
                  <p>Lists the policies attached to the specified thing
                  group.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListAttachedPolicies</a>
                  action.</p>
                tags:
                  - Lists
                  - Attached
                  - Policies
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
            /audit/findings:
              POST:
                summary: ListAuditFindings
                description: >-
                  <p>Lists the findings (results) of a Device Defender audit or
                  of the audits performed during a specified time period.
                  (Findings are retained for 90 days.)</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListAuditFindings</a>
                  action.</p>
                tags:
                  - Lists
                  - Audit
                  - Findings
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
            /audit/mitigationactions/executions:
              GET:
                summary: ListAuditMitigationActionsExecutions
                description: >-
                  <p>Gets the status of audit mitigation action tasks that were
                  executed.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListAuditMitigationActionsExecutions</a>
                  action.</p>
                tags:
                  - Lists
                  - Audit
                  - Mitigation
                  - Actions
                  - Executions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
            /audit/mitigationactions/tasks:
              GET:
                summary: ListAuditMitigationActionsTasks
                description: >-
                  <p>Gets a list of audit mitigation action tasks that match the
                  specified filters.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListAuditMitigationActionsTasks</a>
                  action.</p>
                tags:
                  - Lists
                  - Audit
                  - Mitigation
                  - Actions
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
            /audit/suppressions/list:
              POST:
                summary: ListAuditSuppressions
                description: >-
                  <p> Lists your Device Defender audit listings. </p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListAuditSuppressions</a>
                  action.</p>
                tags:
                  - Lists
                  - Audit
                  - Suppressions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
            /audit/tasks:
              POST:
                summary: StartOnDemandAuditTask
                description: >-
                  <p>Starts an on-demand Device Defender audit.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">StartOnDemandAuditTask</a>
                  action.</p>
                tags:
                  - Start
                  - 'On'
                  - Demand
                  - Audit
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
            /authorizers/:
              GET:
                summary: ListAuthorizers
                description: >-
                  <p>Lists the authorizers registered in your account.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListAuthorizers</a>
                  action.</p>
                tags:
                  - Lists
                  - Authorizers
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
            /billing-groups:
              GET:
                summary: ListBillingGroups
                description: >-
                  <p>Lists the billing groups you have created.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListBillingGroups</a>
                  action.</p>
                tags:
                  - Lists
                  - Billing
                  - Groups
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
            /cacertificates:
              GET:
                summary: ListCACertificates
                description: >-
                  <p>Lists the CA certificates registered for your Amazon Web
                  Services account.</p> <p>The results are paginated with a
                  default page size of 25. You can use the returned marker to
                  retrieve additional results.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListCACertificates</a>
                  action.</p>
                tags:
                  - Lists
                  - Certificates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
            /certificate-providers/:
              GET:
                summary: ListCertificateProviders
                description: >-
                  <p>Lists all your certificate providers in your Amazon Web
                  Services account.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListCertificateProviders</a>
                  action. </p>
                tags:
                  - Lists
                  - Certificates
                  - Providers
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
            /certificates-by-ca/{caCertificateId}:
              GET:
                summary: ListCertificatesByCA
                description: >-
                  <p>List the device certificates signed by the specified CA
                  certificate.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListCertificatesByCA</a>
                  action.</p>
                tags:
                  - Lists
                  - Certificates
                  - By
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
            /custom-metrics:
              GET:
                summary: ListCustomMetrics
                description: >-
                  <p> Lists your Device Defender detect custom metrics. </p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListCustomMetrics</a>
                  action.</p>
                tags:
                  - Lists
                  - Custom
                  - Metrics
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
            /detect/mitigationactions/executions:
              GET:
                summary: ListDetectMitigationActionsExecutions
                description: >-
                  <p> Lists mitigation actions executions for a Device Defender
                  ML Detect Security Profile. </p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListDetectMitigationActionsExecutions</a>
                  action.</p>
                tags:
                  - Lists
                  - Detect
                  - Mitigation
                  - Actions
                  - Executions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
            /detect/mitigationactions/tasks:
              GET:
                summary: ListDetectMitigationActionsTasks
                description: >-
                  <p> List of Device Defender ML Detect mitigation actions
                  tasks. </p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListDetectMitigationActionsTasks</a>
                  action.</p>
                tags:
                  - Lists
                  - Detect
                  - Mitigation
                  - Actions
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
            /dimensions:
              GET:
                summary: ListDimensions
                description: >-
                  <p>List the set of dimensions that are defined for your Amazon
                  Web Services accounts.</p> <p>Requires permission to access
                  the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListDimensions</a>
                  action.</p>
                tags:
                  - Lists
                  - Dimensions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
            /domainConfigurations:
              GET:
                summary: ListDomainConfigurations
                description: >-
                  <p>Gets a list of domain configurations for the user. This
                  list is sorted alphabetically by domain configuration
                  name.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListDomainConfigurations</a>
                  action.</p>
                tags:
                  - Lists
                  - Domains
                  - Configurations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
            /fleet-metrics:
              GET:
                summary: ListFleetMetrics
                description: >-
                  <p>Lists all your fleet metrics. </p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListFleetMetrics</a>
                  action.</p>
                tags:
                  - Lists
                  - Fleets
                  - Metrics
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
            /indices:
              GET:
                summary: ListIndices
                description: >-
                  <p>Lists the search indices.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListIndices</a>
                  action.</p>
                tags:
                  - Lists
                  - Indices
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
            /jobs/{jobId}/things:
              GET:
                summary: ListJobExecutionsForJob
                description: >-
                  <p>Lists the job executions for a job.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListJobExecutionsForJob</a>
                  action.</p>
                tags:
                  - Lists
                  - Jobs
                  - Executions
                  - For
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
            /things/{thingName}/jobs:
              GET:
                summary: ListJobExecutionsForThing
                description: >-
                  <p>Lists the job executions for the specified thing.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListJobExecutionsForThing</a>
                  action.</p>
                tags:
                  - Lists
                  - Jobs
                  - Executions
                  - For
                  - Things
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
            /job-templates:
              GET:
                summary: ListJobTemplates
                description: >-
                  <p>Returns a list of job templates.</p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListJobTemplates</a>
                  action.</p>
                tags:
                  - Lists
                  - Jobs
                  - Templates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
            /jobs:
              GET:
                summary: ListJobs
                description: >-
                  <p>Lists jobs.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListJobs</a>
                  action.</p>
                tags:
                  - Lists
                  - Jobs
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
            /managed-job-templates:
              GET:
                summary: ListManagedJobTemplates
                description: <p>Returns a list of managed job templates.</p>
                tags:
                  - Lists
                  - Managed
                  - Jobs
                  - Templates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
            /metric-values:
              GET:
                summary: ListMetricValues
                description: >-
                  <p>Lists the values reported for an IoT Device Defender metric
                  (device-side metric, cloud-side metric, or custom metric) by
                  the given thing during the specified time period.</p>
                tags:
                  - Lists
                  - Metrics
                  - Values
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
            /mitigationactions/actions:
              GET:
                summary: ListMitigationActions
                description: >-
                  <p>Gets a list of all mitigation actions that match the
                  specified filter criteria.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListMitigationActions</a>
                  action.</p>
                tags:
                  - Lists
                  - Mitigation
                  - Actions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
            /otaUpdates:
              GET:
                summary: ListOTAUpdates
                description: >-
                  <p>Lists OTA updates.</p> <p>Requires permission to access the
                  <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListOTAUpdates</a>
                  action.</p>
                tags:
                  - Lists
                  - Updates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
            /certificates-out-going:
              GET:
                summary: ListOutgoingCertificates
                description: >-
                  <p>Lists certificates that are being transferred but not yet
                  accepted.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListOutgoingCertificates</a>
                  action.</p>
                tags:
                  - Lists
                  - Outgoing
                  - Certificates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
            /packages/{packageName}/versions:
              GET:
                summary: ListPackageVersions
                description: >-
                  <p>Lists the software package versions associated to the
                  account.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListPackageVersions</a>
                  action.</p>
                tags:
                  - Lists
                  - Packages
                  - Versions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
            /packages:
              GET:
                summary: ListPackages
                description: >-
                  <p>Lists the software packages associated to the account.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListPackages</a>
                  action.</p>
                tags:
                  - Lists
                  - Packages
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
            /policies:
              GET:
                summary: ListPolicies
                description: >-
                  <p>Lists your policies.</p> <p>Requires permission to access
                  the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListPolicies</a>
                  action.</p>
                tags:
                  - Lists
                  - Policies
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
            /policy-principals:
              GET:
                summary: ListPolicyPrincipals
                description: >-
                  <p>Lists the principals associated with the specified
                  policy.</p> <p> <b>Note:</b> This action is deprecated and
                  works as expected for backward compatibility, but we won't add
                  enhancements. Use <a>ListTargetsForPolicy</a> instead.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListPolicyPrincipals</a>
                  action.</p>
                tags:
                  - Lists
                  - Policies
                  - Principals
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
            /principal-policies:
              GET:
                summary: ListPrincipalPolicies
                description: >-
                  <p>Lists the policies attached to the specified principal. If
                  you use an Cognito identity, the ID must be in <a
                  href="https://docs.aws.amazon.com/cognitoidentity/latest/APIReference/API_GetCredentialsForIdentity.html#API_GetCredentialsForIdentity_RequestSyntax">AmazonCognito
                  Identity format</a>.</p> <p> <b>Note:</b> This action is
                  deprecated and works as expected for backward compatibility,
                  but we won't add enhancements. Use <a>ListAttachedPolicies</a>
                  instead.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListPrincipalPolicies</a>
                  action.</p>
                tags:
                  - Lists
                  - Principals
                  - Policies
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
            /principals/things:
              GET:
                summary: ListPrincipalThings
                description: >-
                  <p>Lists the things associated with the specified principal. A
                  principal can be X.509 certificates, IAM users, groups, and
                  roles, Amazon Cognito identities or federated identities. </p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListPrincipalThings</a>
                  action.</p>
                tags:
                  - Lists
                  - Principals
                  - Things
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
            /audit/relatedResources:
              GET:
                summary: ListRelatedResourcesForAuditFinding
                description: >-
                  <p>The related resources of an Audit finding. The following
                  resources can be returned from calling this API:</p> <ul> <li>
                  <p>DEVICE_CERTIFICATE</p> </li> <li> <p>CA_CERTIFICATE</p>
                  </li> <li> <p>IOT_POLICY</p> </li> <li>
                  <p>COGNITO_IDENTITY_POOL</p> </li> <li> <p>CLIENT_ID</p> </li>
                  <li> <p>ACCOUNT_SETTINGS</p> </li> <li> <p>ROLE_ALIAS</p>
                  </li> <li> <p>IAM_ROLE</p> </li> <li>
                  <p>ISSUER_CERTIFICATE</p> </li> </ul> <note> <p>This API is
                  similar to DescribeAuditFinding's <a
                  href="https://docs.aws.amazon.com/iot/latest/apireference/API_DescribeAuditFinding.html">RelatedResources</a>
                  but provides pagination and is not limited to 10 resources.
                  When calling <a
                  href="https://docs.aws.amazon.com/iot/latest/apireference/API_DescribeAuditFinding.html">DescribeAuditFinding</a>
                  for the intermediate CA revoked for active device certificates
                  check, RelatedResources will not be populated. You must use
                  this API, ListRelatedResourcesForAuditFinding, to list the
                  certificates.</p> </note>
                tags:
                  - Lists
                  - Related
                  - Resources
                  - For
                  - Audit
                  - Findings
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
            /role-aliases:
              GET:
                summary: ListRoleAliases
                description: >-
                  <p>Lists the role aliases registered in your account.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListRoleAliases</a>
                  action.</p>
                tags:
                  - Lists
                  - Roles
                  - Aliases
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
            /audit/scheduledaudits:
              GET:
                summary: ListScheduledAudits
                description: >-
                  <p>Lists all of your scheduled audits.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListScheduledAudits</a>
                  action.</p>
                tags:
                  - Lists
                  - Scheduled
                  - Audits
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
            /security-profiles:
              GET:
                summary: ListSecurityProfiles
                description: >-
                  <p>Lists the Device Defender security profiles you've created.
                  You can filter security profiles by dimension or custom
                  metric.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListSecurityProfiles</a>
                  action.</p> <note> <p> <code>dimensionName</code> and
                  <code>metricName</code> cannot be used in the same
                  request.</p> </note>
                tags:
                  - Lists
                  - Security
                  - Profiles
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
            /security-profiles-for-target:
              GET:
                summary: ListSecurityProfilesForTarget
                description: >-
                  <p>Lists the Device Defender security profiles attached to a
                  target (thing group).</p> <p>Requires permission to access the
                  <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListSecurityProfilesForTarget</a>
                  action.</p>
                tags:
                  - Lists
                  - Security
                  - Profiles
                  - For
                  - Target
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
            /streams:
              GET:
                summary: ListStreams
                description: >-
                  <p>Lists all of the streams in your Amazon Web Services
                  account.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListStreams</a>
                  action.</p>
                tags:
                  - Lists
                  - Streams
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
            /tags:
              POST:
                summary: TagResource
                description: >-
                  <p>Adds to or modifies the tags of the given resource. Tags
                  are metadata which can be used to manage a resource.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">TagResource</a>
                  action.</p>
                tags:
                  - Tags
                  - Resources
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
            /policy-targets/{policyName}:
              POST:
                summary: ListTargetsForPolicy
                description: >-
                  <p>List targets for the specified policy.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListTargetsForPolicy</a>
                  action.</p>
                tags:
                  - Lists
                  - Targets
                  - For
                  - Policies
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
            /thing-groups:
              GET:
                summary: ListThingGroups
                description: >-
                  <p>List the thing groups in your account.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListThingGroups</a>
                  action.</p>
                tags:
                  - Lists
                  - Things
                  - Groups
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
            /things/{thingName}/thing-groups:
              GET:
                summary: ListThingGroupsForThing
                description: >-
                  <p>List the thing groups to which the specified thing
                  belongs.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListThingGroupsForThing</a>
                  action.</p>
                tags:
                  - Lists
                  - Things
                  - Groups
                  - For
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
            /thing-registration-tasks/{taskId}/reports:
              GET:
                summary: ListThingRegistrationTaskReports
                description: <p>Information about the thing registration tasks.</p>
                tags:
                  - Lists
                  - Things
                  - Registrations
                  - Tasks
                  - Reports
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
            /thing-registration-tasks:
              POST:
                summary: StartThingRegistrationTask
                description: >-
                  <p>Creates a bulk thing provisioning task.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">StartThingRegistrationTask</a>
                  action.</p>
                tags:
                  - Start
                  - Things
                  - Registrations
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
            /thing-types:
              GET:
                summary: ListThingTypes
                description: >-
                  <p>Lists the existing thing types.</p> <p>Requires permission
                  to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListThingTypes</a>
                  action.</p>
                tags:
                  - Lists
                  - Things
                  - Types
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
            /things:
              POST:
                summary: RegisterThing
                description: >-
                  <p>Provisions a thing in the device registry. RegisterThing
                  calls other IoT control plane APIs. These calls might exceed
                  your account level <a
                  href="https://docs.aws.amazon.com/general/latest/gr/aws_service_limits.html#limits_iot">
                  IoT Throttling Limits</a> and cause throttle errors. Please
                  contact <a
                  href="https://console.aws.amazon.com/support/home">Amazon Web
                  Services Customer Support</a> to raise your throttling limits
                  if necessary.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">RegisterThing</a>
                  action.</p>
                tags:
                  - Register
                  - Things
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
            /billing-groups/{billingGroupName}/things:
              GET:
                summary: ListThingsInBillingGroup
                description: >-
                  <p>Lists the things you have added to the given billing
                  group.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListThingsInBillingGroup</a>
                  action.</p>
                tags:
                  - Lists
                  - Things
                  - In
                  - Billing
                  - Group
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
            /thing-groups/{thingGroupName}/things:
              GET:
                summary: ListThingsInThingGroup
                description: >-
                  <p>Lists the things in the specified group.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListThingsInThingGroup</a>
                  action.</p>
                tags:
                  - Lists
                  - Things
                  - In
                  - Things
                  - Group
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
            /rules:
              GET:
                summary: ListTopicRules
                description: >-
                  <p>Lists the rules for the specific topic.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListTopicRules</a>
                  action.</p>
                tags:
                  - Lists
                  - Topics
                  - Rules
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
            /violation-events:
              GET:
                summary: ListViolationEvents
                description: >-
                  <p>Lists the Device Defender security profile violations
                  discovered during the given time period. You can use filters
                  to limit the results to those alerts issued for a particular
                  security profile, behavior, or thing (device).</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ListViolationEvents</a>
                  action.</p>
                tags:
                  - Lists
                  - Violations
                  - Events
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
            /violations/verification-state/{violationId}:
              POST:
                summary: PutVerificationStateOnViolation
                description: >-
                  <p>Set a verification state and provide a description of that
                  verification state on a violation (detect alarm).</p>
                tags:
                  - Put
                  - Verification
                  - States
                  - 'On'
                  - Violations
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
            /cacertificate:
              POST:
                summary: RegisterCACertificate
                description: >-
                  <p>Registers a CA certificate with Amazon Web Services IoT
                  Core. There is no limit to the number of CA certificates you
                  can register in your Amazon Web Services account. You can
                  register up to 10 CA certificates with the same <code>CA
                  subject field</code> per Amazon Web Services account.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">RegisterCACertificate</a>
                  action.</p>
                tags:
                  - Register
                  - Certificates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
            /certificate/register:
              POST:
                summary: RegisterCertificate
                description: >-
                  <p>Registers a device certificate with IoT in the same <a
                  href="https://docs.aws.amazon.com/iot/latest/apireference/API_CertificateDescription.html#iot-Type-CertificateDescription-certificateMode">certificate
                  mode</a> as the signing CA. If you have more than one CA
                  certificate that has the same subject field, you must specify
                  the CA certificate that was used to sign the device
                  certificate being registered.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">RegisterCertificate</a>
                  action.</p>
                tags:
                  - Register
                  - Certificates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
            /certificate/register-no-ca:
              POST:
                summary: RegisterCertificateWithoutCA
                description: >-
                  <p>Register a certificate that does not have a certificate
                  authority (CA). For supported certificates, consult <a
                  href="https://docs.aws.amazon.com/iot/latest/developerguide/x509-client-certs.html#x509-cert-algorithms">
                  Certificate signing algorithms supported by IoT</a>. </p>
                tags:
                  - Register
                  - Certificates
                  - Without
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
            /reject-certificate-transfer/{certificateId}:
              PATCH:
                summary: RejectCertificateTransfer
                description: >-
                  <p>Rejects a pending certificate transfer. After IoT rejects a
                  certificate transfer, the certificate status changes from
                  <b>PENDING_TRANSFER</b> to <b>INACTIVE</b>.</p> <p>To check
                  for pending certificate transfers, call
                  <a>ListCertificates</a> to enumerate your certificates.</p>
                  <p>This operation can only be called by the transfer
                  destination. After it is called, the certificate will be
                  returned to the source's account in the INACTIVE state.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">RejectCertificateTransfer</a>
                  action.</p>
                tags:
                  - Reject
                  - Certificates
                  - Transfers
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
            /billing-groups/removeThingFromBillingGroup:
              PUT:
                summary: RemoveThingFromBillingGroup
                description: >-
                  <p>Removes the given thing from the billing group.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">RemoveThingFromBillingGroup</a>
                  action.</p> <note> <p>This call is asynchronous. It might take
                  several seconds for the detachment to propagate.</p> </note>
                tags:
                  - Removes
                  - Things
                  - From
                  - Billing
                  - Group
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
            /thing-groups/removeThingFromThingGroup:
              PUT:
                summary: RemoveThingFromThingGroup
                description: >-
                  <p>Remove the specified thing from the specified group.</p>
                  <p>You must specify either a <code>thingGroupArn</code> or a
                  <code>thingGroupName</code> to identify the thing group and
                  either a <code>thingArn</code> or a <code>thingName</code> to
                  identify the thing to remove from the thing group. </p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">RemoveThingFromThingGroup</a>
                  action.</p>
                tags:
                  - Removes
                  - Things
                  - From
                  - Group
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
            /indices/search:
              POST:
                summary: SearchIndex
                description: >-
                  <p>The query search index.</p> <p>Requires permission to
                  access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">SearchIndex</a>
                  action.</p>
                tags:
                  - Search
                  - Index
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
                  - Search
            /thing-registration-tasks/{taskId}/cancel:
              PUT:
                summary: StopThingRegistrationTask
                description: >-
                  <p>Cancels a bulk thing provisioning task.</p> <p>Requires
                  permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">StopThingRegistrationTask</a>
                  action.</p>
                tags:
                  - Stop
                  - Things
                  - Registrations
                  - Tasks
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
                  - Search
            /test-authorization:
              POST:
                summary: TestAuthorization
                description: >-
                  <p>Tests if a specified principal is authorized to perform an
                  IoT action on a specified resource. Use this to test and debug
                  the authorization behavior of devices that connect to the IoT
                  device gateway.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">TestAuthorization</a>
                  action.</p>
                tags:
                  - Tests
                  - Authorization
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
                  - Search
                  - Tests
                  - Authorization
            /authorizer/{authorizerName}/test:
              POST:
                summary: TestInvokeAuthorizer
                description: >-
                  <p>Tests a custom authorization behavior by invoking a
                  specified custom authorizer. Use this to test and debug the
                  custom authorization behavior of devices that connect to the
                  IoT device gateway.</p> <p>Requires permission to access the
                  <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">TestInvokeAuthorizer</a>
                  action.</p>
                tags:
                  - Tests
                  - Invoke
                  - Authorizer
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
                  - Search
                  - Tests
                  - Authorization
            /transfer-certificate/{certificateId}:
              PATCH:
                summary: TransferCertificate
                description: >-
                  <p>Transfers the specified certificate to the specified Amazon
                  Web Services account.</p> <p>Requires permission to access the
                  <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">TransferCertificate</a>
                  action.</p> <p>You can cancel the transfer until it is
                  acknowledged by the recipient.</p> <p>No notification is sent
                  to the transfer destination's account. It is up to the caller
                  to notify the transfer target.</p> <p>The certificate being
                  transferred must not be in the ACTIVE state. You can use the
                  <a>UpdateCertificate</a> action to deactivate it.</p> <p>The
                  certificate must not have any policies attached to it. You can
                  use the <a>DetachPolicy</a> action to detach them.</p>
                tags:
                  - Transfers
                  - Certificates
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
                  - Search
                  - Tests
                  - Authorization
            /untag:
              POST:
                summary: UntagResource
                description: >-
                  <p>Removes the given tags (metadata) from the resource.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UntagResource</a>
                  action.</p>
                tags:
                  - Untag
                  - Resources
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
                  - Search
                  - Tests
                  - Authorization
                  - Untag
            /audit/suppressions/update:
              PATCH:
                summary: UpdateAuditSuppression
                description: <p> Updates a Device Defender audit suppression. </p>
                tags:
                  - Update
                  - Audit
                  - Suppressions
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
                  - Search
                  - Tests
                  - Authorization
                  - Untag
            /thing-groups/updateThingGroupsForThing:
              PUT:
                summary: UpdateThingGroupsForThing
                description: >-
                  <p>Updates the groups to which the thing belongs.</p>
                  <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">UpdateThingGroupsForThing</a>
                  action.</p>
                tags:
                  - Update
                  - Things
                  - Groups
                  - For
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
                  - Search
                  - Tests
                  - Authorization
                  - Untag
            /security-profile-behaviors/validate:
              POST:
                summary: ValidateSecurityProfileBehaviors
                description: >-
                  <p>Validates a Device Defender security profile behaviors
                  specification.</p> <p>Requires permission to access the <a
                  href="https://docs.aws.amazon.com/service-authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions">ValidateSecurityProfileBehaviors</a>
                  a
                tags:
                  - Validate
                  - Security
                  - Profiles
                  - Behaviors
                  - Identifiers
                  - Things
                  - To
                  - Billing
                  - Group
                  - Targets
                  - Names
                  - Profiles
                  - Principals
                  - Cancel
                  - Jobs
                  - Jobs
                  - Default
                  - Authorizer
                  - Tokens
                  - Audit
                  - Suppressions
                  - Create
                  - Certificates
                  - Providers
                  - Dimensions
                  - Configurations
                  - Domains
                  - Configurations
                  - Templates
                  - Keys
                  - And
                  - Certificates
                  - Updates
                  - Ota
                  - Update
                  - Versions
                  - Versions
                  - Provisioning
                  - Claim
                  - Templates
                  - Alias
                  - Types
                  - Destinations
                  - Delete
                  - Execution
                  - Numbers
                  - Policies
                  - Registration Codes
                  - ARN
                  - Logging
                  - Levels
                  - Deprecate
                  - Describe
                  - Endpoints
                  - Events
                  - Disable
                  - Enable
                  - Behavior
                  - Models
                  - Training
                  - Summaries
                  - Indices
                  - Buckets
                  - Cardinality
                  - Effective
                  - Policies
                  - Indexing
                  - Configurations
                  - Document
                  - Options
                  - Packages
                  - Percentiles
                  - Statistics
                  - Active
                  - Violations
                  - Attached
                  - Target
                  - Findings
                  - Mitigation Actions
                  - Executions
                  - Tasks
                  - Lists
                  - Authorizers
                  - Groups
                  - Certificates
                  - Providers
                  - Custom
                  - Metrics
                  - Detect
                  - Fleets
                  - Things
                  - Managed
                  - Metrics
                  - Values
                  - Actions
                  - Out
                  - Going
                  - Packages
                  - Principals
                  - Resources
                  - Roles
                  - Aliases
                  - Scheduled Audits
                  - Security
                  - Profiles
                  - For
                  - Streams
                  - Tags
                  - Reports
                  - Registrations
                  - Types
                  - Rules
                  - Violations
                  - Events
                  - Certificates
                  - Register
                  - 'No'
                  - Ca
                  - From
                  - Search
                  - Tests
                  - Authorization
                  - Untag
                  - Behaviors
                  - Validate
    overlays:
      - type: APIs.io Search
        url: overlays/iot-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/iot-openapi-api-evangelist-ratings.yml
    aid: amazon-web-services:iot
  - name: lambda
    description: >-
      <fullname>AWS Lambda</fullname> <p><b>Overview</b></p> <p>This is the AWS
      Lambda API Reference. The AWS Lambda Developer Guide provides additional
      information. For the service overview, go to <a
      href="http://docs.aws.amazon.com/lambda/latest/dg/welcome.html">What is
      AWS Lambda</a>, and for information about how the service works, go to <a
      href="http://docs.aws.amazon.com/lambda/latest/dg/lambda-introduction.html">AWS
      LambdaL How it Works</a> in the AWS Lambda Developer Guide.</p>
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://example.com
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://example.com
      - type: OpenAPI
        data:
          openapi: 3.1.0
          info:
            title: lambda
          paths:
            /2018-10-31/layers/{LayerName}/versions/{VersionNumber}/policy:
              GET:
                summary: GetLayerVersionPolicy
                description: >-
                  <p>Returns the permission policy for a version of an <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html">Lambda
                  layer</a>. For more information, see
                  <a>AddLayerVersionPermission</a>.</p>
                tags:
                  - Get
                  - Layers
                  - Versions
                  - Policies
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
            /2015-03-31/functions/{FunctionName}/policy:
              GET:
                summary: GetPolicy
                description: >-
                  <p>Returns the <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/access-control-resource-based.html">resource-based
                  IAM policy</a> for a function, version, or alias.</p>
                tags:
                  - Get
                  - Policies
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
            /2015-03-31/functions/{FunctionName}/aliases:
              GET:
                summary: ListAliases
                description: >-
                  <p>Returns a list of <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/configuration-aliases.html">aliases</a>
                  for a Lambda function.</p>
                tags:
                  - Lists
                  - Aliases
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
            /2020-04-22/code-signing-configs/:
              GET:
                summary: ListCodeSigningConfigs
                description: >-
                  <p>Returns a list of <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/configuring-codesigning.html">code
                  signing configurations</a>. A request returns up to 10,000
                  configurations per call. You can use the <code>MaxItems</code>
                  parameter to return fewer configurations per call. </p>
                tags:
                  - Lists
                  - Code
                  - Signing
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
            /2015-03-31/event-source-mappings/:
              GET:
                summary: ListEventSourceMappings
                description: >-
                  <p>Lists event source mappings. Specify an
                  <code>EventSourceArn</code> to show only event source mappings
                  for a single event source.</p>
                tags:
                  - Lists
                  - Events
                  - Source
                  - Mapping
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
            /2015-03-31/functions:
              POST:
                summary: CreateFunction
                description: >-
                  <p>Creates a Lambda function. To create a function, you need a
                  <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-package.html">deployment
                  package</a> and an <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/intro-permission-model.html#lambda-intro-execution-role">execution
                  role</a>. The deployment package is a .zip file archive or
                  container image that contains your function code. The
                  execution role grants the function permission to use Amazon
                  Web Services, such as Amazon CloudWatch Logs for log streaming
                  and X-Ray for request tracing.</p> <p>If the deployment
                  package is a <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/lambda-images.html">container
                  image</a>, then you set the package type to
                  <code>Image</code>. For a container image, the code property
                  must include the URI of a container image in the Amazon ECR
                  registry. You do not need to specify the handler and runtime
                  properties.</p> <p>If the deployment package is a <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-package.html#gettingstarted-package-zip">.zip
                  file archive</a>, then you set the package type to
                  <code>Zip</code>. For a .zip file archive, the code property
                  specifies the location of the .zip file. You must also specify
                  the handler and runtime properties. The code in the deployment
                  package must be compatible with the target instruction set
                  architecture of the function (<code>x86-64</code> or
                  <code>arm64</code>). If you do not specify the architecture,
                  then the default value is <code>x86-64</code>.</p> <p>When you
                  create a function, Lambda provisions an instance of the
                  function and its supporting resources. If your function
                  connects to a VPC, this process can take a minute or so.
                  During this time, you can't invoke or modify the function. The
                  <code>State</code>, <code>StateReason</code>, and
                  <code>StateReasonCode</code> fields in the response from
                  <a>GetFunctionConfiguration</a> indicate when the function is
                  ready to invoke. For more information, see <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/functions-states.html">Lambda
                  function states</a>.</p> <p>A function has an unpublished
                  version, and can have published versions and aliases. The
                  unpublished version changes when you update your function's
                  code and configuration. A published version is a snapshot of
                  your function code and configuration that can't be changed. An
                  alias is a named resource that maps to a version, and can be
                  changed to map to a different version. Use the
                  <code>Publish</code> parameter to create version
                  <code>1</code> of your function from its initial
                  configuration.</p> <p>The other parameters let you configure
                  version-specific and function-level settings. You can modify
                  version-specific settings later with
                  <a>UpdateFunctionConfiguration</a>. Function-level settings
                  apply to both the unpublished and published versions of the
                  function, and include tags (<a>TagResource</a>) and
                  per-function concurrency limits
                  (<a>PutFunctionConcurrency</a>).</p> <p>You can use code
                  signing if your deployment package is a .zip file archive. To
                  enable code signing for this function, specify the ARN of a
                  code-signing configuration. When a user attempts to deploy a
                  code package with <a>UpdateFunctionCode</a>, Lambda checks
                  that the code package has a valid signature from a trusted
                  publisher. The code-signing configuration includes set of
                  signing profiles, which define the trusted publishers for this
                  function.</p> <p>If another Amazon Web Services account or an
                  Amazon Web Service invokes your function, use
                  <a>AddPermission</a> to grant permission by creating a
                  resource-based Identity and Access Management (IAM) policy.
                  You can grant permissions at the function level, on a version,
                  or on an alias.</p> <p>To invoke your function directly, use
                  <a>Invoke</a>. To invoke your function in response to events
                  in other Amazon Web Services, create an event source mapping
                  (<a>CreateEventSourceMapping</a>), or configure a function
                  trigger in the other service. For more information, see <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/lambda-invocation.html">Invoking
                  Lambda functions</a>.</p>
                tags:
                  - Create
                  - Functions
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
            /2021-10-31/functions/{FunctionName}/url:
              PUT:
                summary: UpdateFunctionUrlConfig
                description: <p>Updates the configuration for a Lambda function URL.</p>
                tags:
                  - Update
                  - Functions
                  - URL
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
            /2015-03-31/functions/{FunctionName}/aliases/{Name}:
              PUT:
                summary: UpdateAlias
                description: >-
                  <p>Updates the configuration of a Lambda function <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/configuration-aliases.html">alias</a>.</p>
                tags:
                  - Update
                  - Alias
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
            /2020-04-22/code-signing-configs/{CodeSigningConfigArn}:
              PUT:
                summary: UpdateCodeSigningConfig
                description: >-
                  <p>Update the code signing configuration. Changes to the code
                  signing configuration take effect the next time a user tries
                  to deploy a code package to the function. </p>
                tags:
                  - Update
                  - Code
                  - Signing
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
            /2015-03-31/event-source-mappings/{UUID}:
              PUT:
                summary: UpdateEventSourceMapping
                description: >-
                  <p>Updates an event source mapping. You can change the
                  function that Lambda invokes, or pause invocation and resume
                  later from the same location.</p> <p>For details about how to
                  configure different event sources, see the following topics.
                  </p> <ul> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-ddb.html#services-dynamodb-eventsourcemapping">
                  Amazon DynamoDB Streams</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-kinesis.html#services-kinesis-eventsourcemapping">
                  Amazon Kinesis</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-sqs.html#events-sqs-eventsource">
                  Amazon SQS</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-mq.html#services-mq-eventsourcemapping">
                  Amazon MQ and RabbitMQ</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-msk.html">
                  Amazon MSK</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/kafka-smaa.html">
                  Apache Kafka</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-documentdb.html">
                  Amazon DocumentDB</a> </p> </li> </ul> <p>The following error
                  handling options are available only for stream sources
                  (DynamoDB and Kinesis):</p> <ul> <li> <p>
                  <code>BisectBatchOnFunctionError</code> – If the function
                  returns an error, split the batch in two and retry.</p> </li>
                  <li> <p> <code>DestinationConfig</code> – Send discarded
                  records to an Amazon SQS queue or Amazon SNS topic.</p> </li>
                  <li> <p> <code>MaximumRecordAgeInSeconds</code> – Discard
                  records older than the specified age. The default value is
                  infinite (-1). When set to infinite (-1), failed records are
                  retried until the record expires</p> </li> <li> <p>
                  <code>MaximumRetryAttempts</code> – Discard records after the
                  specified number of retries. The default value is infinite
                  (-1). When set to infinite (-1), failed records are retried
                  until the record expires.</p> </li> <li> <p>
                  <code>ParallelizationFactor</code> – Process multiple batches
                  from each shard concurrently.</p> </li> </ul> <p>For
                  information about which configuration parameters apply to each
                  event source, see the following topics.</p> <ul> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-ddb.html#services-ddb-params">
                  Amazon DynamoDB Streams</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-kinesis.html#services-kinesis-params">
                  Amazon Kinesis</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-sqs.html#services-sqs-params">
                  Amazon SQS</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-mq.html#services-mq-params">
                  Amazon MQ and RabbitMQ</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-msk.html#services-msk-parms">
                  Amazon MSK</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-kafka.html#services-kafka-parms">
                  Apache Kafka</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/with-documentdb.html#docdb-configuration">
                  Amazon DocumentDB</a> </p> </li> </ul>
                tags:
                  - Update
                  - Events
                  - Source
                  - Mapping
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
            /2015-03-31/functions/{FunctionName}:
              GET:
                summary: GetFunction
                description: >-
                  <p>Returns information about the function or function version,
                  with a link to download the deployment package that's valid
                  for 10 minutes. If you specify a function version, only
                  details that are specific to that version are returned.</p>
                tags:
                  - Get
                  - Functions
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
            /2020-06-30/functions/{FunctionName}/code-signing-config:
              PUT:
                summary: PutFunctionCodeSigningConfig
                description: >-
                  <p>Update the code signing configuration for the function.
                  Changes to the code signing configuration take effect the next
                  time a user tries to deploy a code package to the function.
                  </p>
                tags:
                  - Put
                  - Functions
                  - Code
                  - Signing
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
            /2017-10-31/functions/{FunctionName}/concurrency:
              PUT:
                summary: PutFunctionConcurrency
                description: >-
                  <p>Sets the maximum number of simultaneous executions for a
                  function, and reserves capacity for that concurrency
                  level.</p> <p>Concurrency settings apply to the function as a
                  whole, including all published versions and the unpublished
                  version. Reserving concurrency both ensures that your function
                  has capacity to process the specified number of events
                  simultaneously, and prevents it from scaling beyond that
                  level. Use <a>GetFunction</a> to see the current setting for a
                  function.</p> <p>Use <a>GetAccountSettings</a> to see your
                  Regional concurrency limit. You can reserve concurrency for as
                  many functions as you like, as long as you leave at least 100
                  simultaneous executions unreserved for functions that aren't
                  configured with a per-function limit. For more information,
                  see <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/invocation-scaling.html">Lambda
                  function scaling</a>.</p>
                tags:
                  - Put
                  - Functions
                  - Concurrency
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
            /2019-09-25/functions/{FunctionName}/event-invoke-config:
              POST:
                summary: UpdateFunctionEventInvokeConfig
                description: >-
                  <p>Updates the configuration for asynchronous invocation for a
                  function, version, or alias.</p> <p>To configure options for
                  asynchronous invocation, use
                  <a>PutFunctionEventInvokeConfig</a>.</p>
                tags:
                  - Update
                  - Functions
                  - Events
                  - Invoke
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
            /2018-10-31/layers/{LayerName}/versions/{VersionNumber}:
              GET:
                summary: GetLayerVersion
                description: >-
                  <p>Returns information about a version of an <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html">Lambda
                  layer</a>, with a link to download the layer archive that's
                  valid for 10 minutes.</p>
                tags:
                  - Get
                  - Layers
                  - Versions
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
            /2019-09-30/functions/{FunctionName}/provisioned-concurrency:
              PUT:
                summary: PutProvisionedConcurrencyConfig
                description: >-
                  <p>Adds a provisioned concurrency configuration to a
                  function's alias or version.</p>
                tags:
                  - Put
                  - Provisioned
                  - Concurrency
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
            /2016-08-19/account-settings/:
              GET:
                summary: GetAccountSettings
                description: >-
                  <p>Retrieves details about your account's <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/limits.html">limits</a>
                  and usage in an Amazon Web Services Region.</p>
                tags:
                  - Get
                  - Account
                  - Settings
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
            /2019-09-30/functions/{FunctionName}/concurrency:
              GET:
                summary: GetFunctionConcurrency
                description: >-
                  <p>Returns details about the reserved concurrency
                  configuration for a function. To set a concurrency limit for a
                  function, use <a>PutFunctionConcurrency</a>.</p>
                tags:
                  - Get
                  - Functions
                  - Concurrency
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
            /2015-03-31/functions/{FunctionName}/configuration:
              PUT:
                summary: UpdateFunctionConfiguration
                description: >-
                  <p>Modify the version-specific settings of a Lambda
                  function.</p> <p>When you update a function, Lambda provisions
                  an instance of the function and its supporting resources. If
                  your function connects to a VPC, this process can take a
                  minute. During this time, you can't modify the function, but
                  you can still invoke it. The <code>LastUpdateStatus</code>,
                  <code>LastUpdateStatusReason</code>, and
                  <code>LastUpdateStatusReasonCode</code> fields in the response
                  from <a>GetFunctionConfiguration</a> indicate when the update
                  is complete and the function is processing events with the new
                  configuration. For more information, see <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/functions-states.html">Lambda
                  function states</a>.</p> <p>These settings can vary between
                  versions of a function and are locked when you publish a
                  version. You can't modify the configuration of a published
                  version, only the unpublished version.</p> <p>To configure
                  function concurrency, use <a>PutFunctionConcurrency</a>. To
                  grant invoke permissions to an Amazon Web Services account or
                  Amazon Web Service, use <a>AddPermission</a>.</p>
                tags:
                  - Update
                  - Functions
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
            /2018-10-31/layers?find=LayerVersion:
              GET:
                summary: GetLayerVersionByArn
                description: >-
                  <p>Returns information about a version of an <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html">Lambda
                  layer</a>, with a link to download the layer archive that's
                  valid for 10 minutes.</p>
                tags:
                  - Get
                  - Layers
                  - Versions
                  - By
                  - ARN
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
            /2021-07-20/functions/{FunctionName}/runtime-management-config:
              PUT:
                summary: PutRuntimeManagementConfig
                description: >-
                  <p>Sets the runtime management configuration for a function's
                  version. For more information, see <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/runtimes-update.html">Runtime
                  updates</a>.</p>
                tags:
                  - Put
                  - Runtime
                  - Management
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
            /2015-03-31/functions/{FunctionName}/invocations:
              POST:
                summary: Invoke
                description: >-
                  <p>Invokes a Lambda function. You can invoke a function
                  synchronously (and wait for the response), or asynchronously.
                  By default, Lambda invokes your function synchronously (i.e.
                  the<code>InvocationType</code> is
                  <code>RequestResponse</code>). To invoke a function
                  asynchronously, set <code>InvocationType</code> to
                  <code>Event</code>. Lambda passes the
                  <code>ClientContext</code> object to your function for
                  synchronous invocations only.</p> <p>For <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/invocation-sync.html">synchronous
                  invocation</a>, details about the function response, including
                  errors, are included in the response body and headers. For
                  either invocation type, you can find more information in the
                  <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/monitoring-functions.html">execution
                  log</a> and <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/lambda-x-ray.html">trace</a>.</p>
                  <p>When an error occurs, your function may be invoked multiple
                  times. Retry behavior varies by error type, client, event
                  source, and invocation type. For example, if you invoke a
                  function asynchronously and it returns an error, Lambda
                  executes the function up to two more times. For more
                  information, see <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/invocation-retries.html">Error
                  handling and automatic retries in Lambda</a>.</p> <p>For <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/invocation-async.html">asynchronous
                  invocation</a>, Lambda adds events to a queue before sending
                  them to your function. If your function does not have enough
                  capacity to keep up with the queue, events may be lost.
                  Occasionally, your function may receive the same event
                  multiple times, even if no error occurs. To retain events that
                  were not processed, configure your function with a <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/invocation-async.html#invocation-dlq">dead-letter
                  queue</a>.</p> <p>The status code in the API response doesn't
                  reflect function errors. Error codes are reserved for errors
                  that prevent your function from executing, such as permissions
                  errors, <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-limits.html">quota</a>
                  errors, or issues with your function's code and configuration.
                  For example, Lambda returns
                  <code>TooManyRequestsException</code> if running the function
                  would cause you to exceed a concurrency limit at either the
                  account level (<code>ConcurrentInvocationLimitExceeded</code>)
                  or function level
                  (<code>ReservedFunctionConcurrentInvocationLimitExceeded</code>).</p>
                  <p>For functions with a long timeout, your client might
                  disconnect during synchronous invocation while it waits for a
                  response. Configure your HTTP client, SDK, firewall, proxy, or
                  operating system to allow for long connections with timeout or
                  keep-alive settings.</p> <p>This operation requires permission
                  for the <a
                  href="https://docs.aws.amazon.com/IAM/latest/UserGuide/list_awslambda.html">lambda:InvokeFunction</a>
                  action. For details on how to set up permissions for
                  cross-account invocations, see <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/access-control-resource-based.html#permissions-resource-xaccountinvoke">Granting
                  function access to other accounts</a>.</p>
                tags:
                  - Invoke
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
            /2014-11-13/functions/{FunctionName}/invoke-async/:
              POST:
                summary: InvokeAsync
                description: >-
                  <important> <p>For asynchronous function invocation, use
                  <a>Invoke</a>.</p> </important> <p>Invokes a function
                  asynchronously.</p>
                tags:
                  - Invoke
                  - Async
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
            /2021-11-15/functions/{FunctionName}/response-streaming-invocations:
              POST:
                summary: InvokeWithResponseStream
                description: >-
                  <p>Configure your Lambda functions to stream response payloads
                  back to clients. For more information, see <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/configuration-response-streaming.html">Configuring
                  a Lambda function to stream responses</a>.</p> <p>This
                  operation requires permission for the <a
                  href="https://docs.aws.amazon.com/IAM/latest/UserGuide/list_awslambda.html">lambda:InvokeFunction</a>
                  action. For details on how to set up permissions for
                  cross-account invocations, see <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/access-control-resource-based.html#permissions-resource-xaccountinvoke">Granting
                  function access to other accounts</a>.</p>
                tags:
                  - Invoke
                  - With
                  - Responses
                  - Stream
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
            /2019-09-25/functions/{FunctionName}/event-invoke-config/list:
              GET:
                summary: ListFunctionEventInvokeConfigs
                description: >-
                  <p>Retrieves a list of configurations for asynchronous
                  invocation for a function.</p> <p>To configure options for
                  asynchronous invocation, use
                  <a>PutFunctionEventInvokeConfig</a>.</p>
                tags:
                  - Lists
                  - Functions
                  - Events
                  - Invoke
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
            /2021-10-31/functions/{FunctionName}/urls:
              GET:
                summary: ListFunctionUrlConfigs
                description: >-
                  <p>Returns a list of Lambda function URLs for the specified
                  function.</p>
                tags:
                  - Lists
                  - Functions
                  - URL
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
            /2015-03-31/functions/:
              GET:
                summary: ListFunctions
                description: >-
                  <p>Returns a list of Lambda functions, with the
                  version-specific configuration of each. Lambda returns up to
                  50 functions per call.</p> <p>Set <code>FunctionVersion</code>
                  to <code>ALL</code> to include all published versions of each
                  function in addition to the unpublished version.</p> <note>
                  <p>The <code>ListFunctions</code> operation returns a subset
                  of the <a>FunctionConfiguration</a> fields. To get the
                  additional fields (State, StateReasonCode, StateReason,
                  LastUpdateStatus, LastUpdateStatusReason,
                  LastUpdateStatusReasonCode, RuntimeVersionConfig) for a
                  function or version, use <a>GetFunction</a>.</p> </note>
                tags:
                  - Lists
                  - Functions
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
            /2020-04-22/code-signing-configs/{CodeSigningConfigArn}/functions:
              GET:
                summary: ListFunctionsByCodeSigningConfig
                description: >-
                  <p>List the functions that use the specified code signing
                  configuration. You can use this method prior to deleting a
                  code signing configuration, to verify that no functions are
                  using it.</p>
                tags:
                  - Lists
                  - Functions
                  - By
                  - Code
                  - Signing
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
            /2018-10-31/layers/{LayerName}/versions:
              POST:
                summary: PublishLayerVersion
                description: >-
                  <p>Creates an <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html">Lambda
                  layer</a> from a ZIP archive. Each time you call
                  <code>PublishLayerVersion</code> with the same layer name, a
                  new version is created.</p> <p>Add layers to your function
                  with <a>CreateFunction</a> or
                  <a>UpdateFunctionConfiguration</a>.</p>
                tags:
                  - Publish
                  - Layers
                  - Versions
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
            /2018-10-31/layers:
              GET:
                summary: ListLayers
                description: >-
                  <p>Lists <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/invocation-layers.html">Lambda
                  layers</a> and shows information about the latest version of
                  each. Specify a <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/lambda-runtimes.html">runtime
                  identifier</a> to list only layers that indicate that they're
                  compatible with that runtime. Specify a compatible
                  architecture to include only layers that are compatible with
                  that <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/foundation-arch.html">instruction
                  set architecture</a>.</p>
                tags:
                  - Lists
                  - Layers
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
                  - '2018'
                  - '10'
                  - Layers
            /2019-09-30/functions/{FunctionName}/provisioned-concurrency?List=ALL:
              GET:
                summary: ListProvisionedConcurrencyConfigs
                description: >-
                  <p>Retrieves a list of provisioned concurrency configurations
                  for a function.</p>
                tags:
                  - Lists
                  - Provisioned
                  - Concurrency
                  - Configurations
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
                  - '2018'
                  - '10'
                  - Layers
                  - Concurrency
                  - Lists
            /2017-03-31/tags/{ARN}:
              DELETE:
                summary: UntagResource
                description: >-
                  <p>Removes <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/tagging.html">tags</a>
                  from a function.</p>
                tags:
                  - Untag
                  - Resources
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
                  - '2018'
                  - '10'
                  - Layers
                  - Concurrency
                  - Lists
                  - '2017'
                  - Tags
            /2015-03-31/functions/{FunctionName}/versions:
              POST:
                summary: PublishVersion
                description: >-
                  <p>Creates a <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/versioning-aliases.html">version</a>
                  from the current code and configuration of a function. Use
                  versions to create a snapshot of your function code and
                  configuration that doesn't change.</p> <p>Lambda doesn't
                  publish a version if the function's configuration and code
                  haven't changed since the last version. Use
                  <a>UpdateFunctionCode</a> or
                  <a>UpdateFunctionConfiguration</a> to update the function
                  before publishing a version.</p> <p>Clients can invoke
                  versions directly or with an alias. To create an alias, use
                  <a>CreateAlias</a>.</p>
                tags:
                  - Publish
                  - Versions
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
                  - '2018'
                  - '10'
                  - Layers
                  - Concurrency
                  - Lists
                  - '2017'
                  - Tags
            /2018-10-31/layers/{LayerName}/versions/{VersionNumber}/policy/{StatementId}:
              DELETE:
                summary: RemoveLayerVersionPermission
                description: >-
                  <p>Removes a statement from the permissions policy for a
                  version of an <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html">Lambda
                  layer</a>. For more information, see
                  <a>AddLayerVersionPermission</a>.</p>
                tags:
                  - Removes
                  - Layers
                  - Versions
                  - Permission
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
                  - '2018'
                  - '10'
                  - Layers
                  - Concurrency
                  - Lists
                  - '2017'
                  - Tags
                  - Statements
                  - Identifiers
            /2015-03-31/functions/{FunctionName}/policy/{StatementId}:
              DELETE:
                summary: RemovePermission
                description: >-
                  <p>Revokes function-use permission from an Amazon Web Service
                  or another Amazon Web Services account. You can get the ID of
                  the statement from the output of <a>GetPolicy</a>.</p>
                tags:
                  - Removes
                  - Permission
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
                  - '2018'
                  - '10'
                  - Layers
                  - Concurrency
                  - Lists
                  - '2017'
                  - Tags
                  - Statements
                  - Identifiers
            /2015-03-31/functions/{FunctionName}/code:
              PUT:
                summary: UpdateFunctionCode
                description: >-
                  <p>Updates a Lambda function's code. If code signing is
                  enabled for the function, the code package must be signed by a
                  trusted publisher. For more information, see <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/configuration-codesigning.html">Configuring
                  code signing for Lambda</a>.</p> <p>If the function's package
                  type is <code>Image</code>, then you must specify the code
                  package in <code>ImageUri</code> as the URI of a <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/lambda-images.html">container
                  image</a> in the Amazon ECR registry.</p> <p>If the function's
                  package type is <code>Zip</code>, then you must specify the
                  deployment package as a <a
                  href="https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-package.html#gettingstarted-package-zip">.zip
                  file archive</a>. Enter the Amazon S3 bucket and key of the
                  code .zip file location. You can also provide the function
                  code inline using the <code>ZipFile</code> field.</p> <p>The
                  code in the deployment package must be compatible with the
                  target instruction set architecture of the function
                  (<code>x86-64</code> or <code>arm64</code>).</p> <p>The
                  function's code is locked when you publish a version. You
                  can't modify the code of a published version, only the
                  unpublished version.</p> <note> <p>For a function defined as a
                  container image, Lambda resolves the image tag to an image
                  digest. In Amazon ECR, if you update the image tag to a new
                  image, Lambda does not automatically update the function.</
                tags:
                  - Update
                  - Functions
                  - Code
                  - Layers
                  - Names
                  - Versions
                  - Versions
                  - Numbers
                  - Policies
                  - Functions
                  - Aliases
                  - '2020'
                  - '04'
                  - '22'
                  - Code
                  - Signing
                  - Configurations
                  - '2015'
                  - '03'
                  - '31'
                  - Events
                  - Source
                  - Mapping
                  - Functions
                  - URL
                  - Configurations
                  - ARN
                  - UUID
                  - Concurrency
                  - Invoke
                  - Provisioned
                  - '2016'
                  - '08'
                  - '19'
                  - Account
                  - Settings
                  - Configurations
                  - Runtime
                  - Management
                  - Invocations
                  - Async
                  - Responses
                  - Streaming
                  - Lists
                  - URL
                  - '2018'
                  - '10'
                  - Layers
                  - Concurrency
                  - Lists
                  - '2017'
                  - Tags
                  - Statements
                  - null
    overlays:
      - type: APIs.io Search
        url: overlays/lambda-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/lambda-openapi-api-evangelist-ratings.yml
    aid: amazon-web-services:lambda
  - name: lex-models
    description: >-
      <fullname>Amazon Lex Build-Time Actions</fullname> <p> Amazon Lex is an
      AWS service for building conversational voice and text interfaces. Use
      these actions to create, update, and delete conversational bots for new
      and existing client applications. </p>
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://example.com
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://example.com
      - type: OpenAPI
        data:
          openapi: 3.1.0
          info:
            title: lex-models
          paths:
            /bots/{name}/versions:
              POST:
                summary: CreateBotVersion
                description: >-
                  <p>Creates a new version of the bot based on the
                  <code>$LATEST</code> version. If the <code>$LATEST</code>
                  version of this resource hasn't changed since you created the
                  last version, Amazon Lex doesn't create a new version. It
                  returns the last created version.</p> <note> <p>You can update
                  only the <code>$LATEST</code> version of the bot. You can't
                  update the numbered versions that you create with the
                  <code>CreateBotVersion</code> operation.</p> </note> <p> When
                  you create the first version of a bot, Amazon Lex sets the
                  version to 1. Subsequent versions increment by 1. For more
                  information, see <a>versioning-intro</a>. </p> <p> This
                  operation requires permission for the
                  <code>lex:CreateBotVersion</code> action. </p>
                tags:
                  - Create
                  - Bot
                  - Versions
                  - Bots
                  - Names
                  - Versions
            /intents/{name}/versions:
              POST:
                summary: CreateIntentVersion
                description: >-
                  <p>Creates a new version of an intent based on the
                  <code>$LATEST</code> version of the intent. If the
                  <code>$LATEST</code> version of this intent hasn't changed
                  since you last updated it, Amazon Lex doesn't create a new
                  version. It returns the last version you created.</p> <note>
                  <p>You can update only the <code>$LATEST</code> version of the
                  intent. You can't update the numbered versions that you create
                  with the <code>CreateIntentVersion</code> operation.</p>
                  </note> <p> When you create a version of an intent, Amazon Lex
                  sets the version to 1. Subsequent versions increment by 1. For
                  more information, see <a>versioning-intro</a>. </p> <p>This
                  operation requires permissions to perform the
                  <code>lex:CreateIntentVersion</code> action. </p>
                tags:
                  - Create
                  - Intent
                  - Versions
                  - Bots
                  - Names
                  - Versions
                  - Intents
            /slottypes/{name}/versions:
              POST:
                summary: CreateSlotTypeVersion
                description: >-
                  <p>Creates a new version of a slot type based on the
                  <code>$LATEST</code> version of the specified slot type. If
                  the <code>$LATEST</code> version of this resource has not
                  changed since the last version that you created, Amazon Lex
                  doesn't create a new version. It returns the last version that
                  you created. </p> <note> <p>You can update only the
                  <code>$LATEST</code> version of a slot type. You can't update
                  the numbered versions that you create with the
                  <code>CreateSlotTypeVersion</code> operation.</p> </note>
                  <p>When you create a version of a slot type, Amazon Lex sets
                  the version to 1. Subsequent versions increment by 1. For more
                  information, see <a>versioning-intro</a>. </p> <p>This
                  operation requires permissions for the
                  <code>lex:CreateSlotTypeVersion</code> action.</p>
                tags:
                  - Create
                  - Slots
                  - Types
                  - Versions
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
            /bots/{name}:
              DELETE:
                summary: DeleteBot
                description: >-
                  <p>Deletes all versions of the bot, including the
                  <code>$LATEST</code> version. To delete a specific version of
                  the bot, use the <a>DeleteBotVersion</a> operation. The
                  <code>DeleteBot</code> operation doesn't immediately remove
                  the bot schema. Instead, it is marked for deletion and removed
                  later.</p> <p>Amazon Lex stores utterances indefinitely for
                  improving the ability of your bot to respond to user inputs.
                  These utterances are not removed when the bot is deleted. To
                  remove the utterances, use the <a>DeleteUtterances</a>
                  operation.</p> <p>If a bot has an alias, you can't delete it.
                  Instead, the <code>DeleteBot</code> operation returns a
                  <code>ResourceInUseException</code> exception that includes a
                  reference to the alias that refers to the bot. To remove the
                  reference to the bot, delete the alias. If you get the same
                  exception again, delete the referring alias until the
                  <code>DeleteBot</code> operation is successful.</p> <p>This
                  operation requires permissions for the
                  <code>lex:DeleteBot</code> action.</p>
                tags:
                  - Delete
                  - Bot
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
            /bots/{botName}/aliases/{name}:
              PUT:
                summary: PutBotAlias
                description: >-
                  <p>Creates an alias for the specified version of the bot or
                  replaces an alias for the specified bot. To change the version
                  of the bot that the alias points to, replace the alias. For
                  more information about aliases, see
                  <a>versioning-aliases</a>.</p> <p>This operation requires
                  permissions for the <code>lex:PutBotAlias</code> action. </p>
                tags:
                  - Put
                  - Bot
                  - Alias
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
            /bots/{botName}/aliases/{aliasName}/channels/{name}:
              GET:
                summary: GetBotChannelAssociation
                description: >-
                  <p>Returns information about the association between an Amazon
                  Lex bot and a messaging platform.</p> <p>This operation
                  requires permissions for the
                  <code>lex:GetBotChannelAssociation</code> action.</p>
                tags:
                  - Get
                  - Bot
                  - Channels
                  - Association
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
            /bots/{name}/versions/{version}:
              DELETE:
                summary: DeleteBotVersion
                description: >-
                  <p>Deletes a specific version of a bot. To delete all versions
                  of a bot, use the <a>DeleteBot</a> operation. </p> <p>This
                  operation requires permissions for the
                  <code>lex:DeleteBotVersion</code> action.</p>
                tags:
                  - Delete
                  - Bot
                  - Versions
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
            /intents/{name}:
              DELETE:
                summary: DeleteIntent
                description: >-
                  <p>Deletes all versions of the intent, including the
                  <code>$LATEST</code> version. To delete a specific version of
                  the intent, use the <a>DeleteIntentVersion</a> operation.</p>
                  <p> You can delete a version of an intent only if it is not
                  referenced. To delete an intent that is referred to in one or
                  more bots (see <a>how-it-works</a>), you must remove those
                  references first. </p> <note> <p> If you get the
                  <code>ResourceInUseException</code> exception, it provides an
                  example reference that shows where the intent is referenced.
                  To remove the reference to the intent, either update the bot
                  or delete it. If you get the same exception when you attempt
                  to delete the intent again, repeat until the intent has no
                  references and the call to <code>DeleteIntent</code> is
                  successful. </p> </note> <p> This operation requires
                  permission for the <code>lex:DeleteIntent</code> action. </p>
                tags:
                  - Delete
                  - Intent
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
            /intents/{name}/versions/{version}:
              GET:
                summary: GetIntent
                description: >-
                  <p> Returns information about an intent. In addition to the
                  intent name, you must specify the intent version. </p> <p>
                  This operation requires permissions to perform the
                  <code>lex:GetIntent</code> action. </p>
                tags:
                  - Get
                  - Intent
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
            /slottypes/{name}:
              DELETE:
                summary: DeleteSlotType
                description: >-
                  <p>Deletes all versions of the slot type, including the
                  <code>$LATEST</code> version. To delete a specific version of
                  the slot type, use the <a>DeleteSlotTypeVersion</a>
                  operation.</p> <p> You can delete a version of a slot type
                  only if it is not referenced. To delete a slot type that is
                  referred to in one or more intents, you must remove those
                  references first. </p> <note> <p> If you get the
                  <code>ResourceInUseException</code> exception, the exception
                  provides an example reference that shows the intent where the
                  slot type is referenced. To remove the reference to the slot
                  type, either update the intent or delete it. If you get the
                  same exception when you attempt to delete the slot type again,
                  repeat until the slot type has no references and the
                  <code>DeleteSlotType</code> call is successful. </p> </note>
                  <p>This operation requires permission for the
                  <code>lex:DeleteSlotType</code> action.</p>
                tags:
                  - Delete
                  - Slots
                  - Types
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
            /slottypes/{name}/version/{version}:
              DELETE:
                summary: DeleteSlotTypeVersion
                description: >-
                  <p>Deletes a specific version of a slot type. To delete all
                  versions of a slot type, use the <a>DeleteSlotType</a>
                  operation. </p> <p>This operation requires permissions for the
                  <code>lex:DeleteSlotTypeVersion</code> action.</p>
                tags:
                  - Delete
                  - Slots
                  - Types
                  - Versions
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
            /bots/{botName}/utterances/{userId}:
              DELETE:
                summary: DeleteUtterances
                description: >-
                  <p>Deletes stored utterances.</p> <p>Amazon Lex stores the
                  utterances that users send to your bot. Utterances are stored
                  for 15 days for use with the <a>GetUtterancesView</a>
                  operation, and then stored indefinitely for use in improving
                  the ability of your bot to respond to user input.</p> <p>Use
                  the <code>DeleteUtterances</code> operation to manually delete
                  stored utterances for a specific user. When you use the
                  <code>DeleteUtterances</code> operation, utterances stored for
                  improving your bot's ability to respond to user input are
                  deleted immediately. Utterances stored for use with the
                  <code>GetUtterancesView</code> operation are deleted after 15
                  days.</p> <p>This operation requires permissions for the
                  <code>lex:DeleteUtterances</code> action.</p>
                tags:
                  - Delete
                  - Utterances
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
            /bots/{name}/versions/{versionoralias}:
              GET:
                summary: GetBot
                description: >-
                  <p>Returns metadata information for a specific bot. You must
                  provide the bot name and the bot version or alias. </p> <p>
                  This operation requires permissions for the
                  <code>lex:GetBot</code> action. </p>
                tags:
                  - Get
                  - Bot
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
            /bots/{botName}/aliases/:
              GET:
                summary: GetBotAliases
                description: >-
                  <p>Returns a list of aliases for a specified Amazon Lex
                  bot.</p> <p>This operation requires permissions for the
                  <code>lex:GetBotAliases</code> action.</p>
                tags:
                  - Get
                  - Bot
                  - Aliases
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
            /bots/{botName}/aliases/{aliasName}/channels/:
              GET:
                summary: GetBotChannelAssociations
                description: >-
                  <p> Returns a list of all of the channels associated with the
                  specified bot. </p> <p>The
                  <code>GetBotChannelAssociations</code> operation requires
                  permissions for the <code>lex:GetBotChannelAssociations</code>
                  action.</p>
                tags:
                  - Get
                  - Bot
                  - Channels
                  - Associations
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
            /bots/{name}/versions/:
              GET:
                summary: GetBotVersions
                description: >-
                  <p>Gets information about all of the versions of a bot.</p>
                  <p>The <code>GetBotVersions</code> operation returns a
                  <code>BotMetadata</code> object for each version of a bot. For
                  example, if a bot has three numbered versions, the
                  <code>GetBotVersions</code> operation returns four
                  <code>BotMetadata</code> objects in the response, one for each
                  numbered version and one for the <code>$LATEST</code> version.
                  </p> <p>The <code>GetBotVersions</code> operation always
                  returns at least one version, the <code>$LATEST</code>
                  version.</p> <p>This operation requires permissions for the
                  <code>lex:GetBotVersions</code> action.</p>
                tags:
                  - Get
                  - Bot
                  - Versions
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
            /bots/:
              GET:
                summary: GetBots
                description: >-
                  <p>Returns bot information as follows: </p> <ul> <li> <p>If
                  you provide the <code>nameContains</code> field, the response
                  includes information for the <code>$LATEST</code> version of
                  all bots whose name contains the specified string.</p> </li>
                  <li> <p>If you don't specify the <code>nameContains</code>
                  field, the operation returns information about the
                  <code>$LATEST</code> version of all of your bots.</p> </li>
                  </ul> <p>This operation requires permission for the
                  <code>lex:GetBots</code> action.</p>
                tags:
                  - Get
                  - Bots
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
            /builtins/intents/{signature}:
              GET:
                summary: GetBuiltinIntent
                description: >-
                  <p>Returns information about a built-in intent.</p> <p>This
                  operation requires permission for the
                  <code>lex:GetBuiltinIntent</code> action.</p>
                tags:
                  - Get
                  - Built In
                  - Intent
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
            /builtins/intents/:
              GET:
                summary: GetBuiltinIntents
                description: >-
                  <p>Gets a list of built-in intents that meet the specified
                  criteria.</p> <p>This operation requires permission for the
                  <code>lex:GetBuiltinIntents</code> action.</p>
                tags:
                  - Get
                  - Built In
                  - Intents
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
            /builtins/slottypes/:
              GET:
                summary: GetBuiltinSlotTypes
                description: >-
                  <p>Gets a list of built-in slot types that meet the specified
                  criteria.</p> <p>For a list of built-in slot types, see <a
                  href="https://developer.amazon.com/public/solutions/alexa/alexa-skills-kit/docs/built-in-intent-ref/slot-type-reference">Slot
                  Type Reference</a> in the <i>Alexa Skills Kit</i>.</p> <p>This
                  operation requires permission for the
                  <code>lex:GetBuiltInSlotTypes</code> action.</p>
                tags:
                  - Get
                  - Built In
                  - Slots
                  - Types
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
            /exports/:
              GET:
                summary: GetExport
                description: >-
                  <p>Exports the contents of a Amazon Lex resource in a
                  specified format. </p>
                tags:
                  - Get
                  - Export
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
            /imports/{importId}:
              GET:
                summary: GetImport
                description: >-
                  <p>Gets information about an import job started with the
                  <code>StartImport</code> operation.</p>
                tags:
                  - Get
                  - Import
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
            /intents/{name}/versions/:
              GET:
                summary: GetIntentVersions
                description: >-
                  <p>Gets information about all of the versions of an
                  intent.</p> <p>The <code>GetIntentVersions</code> operation
                  returns an <code>IntentMetadata</code> object for each version
                  of an intent. For example, if an intent has three numbered
                  versions, the <code>GetIntentVersions</code> operation returns
                  four <code>IntentMetadata</code> objects in the response, one
                  for each numbered version and one for the <code>$LATEST</code>
                  version. </p> <p>The <code>GetIntentVersions</code> operation
                  always returns at least one version, the <code>$LATEST</code>
                  version.</p> <p>This operation requires permissions for the
                  <code>lex:GetIntentVersions</code> action.</p>
                tags:
                  - Get
                  - Intent
                  - Versions
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
            /intents/:
              GET:
                summary: GetIntents
                description: >-
                  <p>Returns intent information as follows: </p> <ul> <li> <p>If
                  you specify the <code>nameContains</code> field, returns the
                  <code>$LATEST</code> version of all intents that contain the
                  specified string.</p> </li> <li> <p> If you don't specify the
                  <code>nameContains</code> field, returns information about the
                  <code>$LATEST</code> version of all intents. </p> </li> </ul>
                  <p> The operation requires permission for the
                  <code>lex:GetIntents</code> action. </p>
                tags:
                  - Get
                  - Intents
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
            /migrations/{migrationId}:
              GET:
                summary: GetMigration
                description: >-
                  <p>Provides details about an ongoing or complete migration
                  from an Amazon Lex V1 bot to an Amazon Lex V2 bot. Use this
                  operation to view the migration alerts and warnings related to
                  the migration.</p>
                tags:
                  - Get
                  - Migrations
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
            /migrations:
              POST:
                summary: StartMigration
                description: >-
                  <p>Starts migrating a bot from Amazon Lex V1 to Amazon Lex V2.
                  Migrate your bot when you want to take advantage of the new
                  features of Amazon Lex V2.</p> <p>For more information, see <a
                  href="https://docs.aws.amazon.com/lex/latest/dg/migrate.html">Migrating
                  a bot</a> in the <i>Amazon Lex developer guide</i>.</p>
                tags:
                  - Start
                  - Migrations
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
                  - Migrations
            /slottypes/{name}/versions/{version}:
              GET:
                summary: GetSlotType
                description: >-
                  <p>Returns information about a specific version of a slot
                  type. In addition to specifying the slot type name, you must
                  specify the slot type version.</p> <p>This operation requires
                  permissions for the <code>lex:GetSlotType</code> action.</p>
                tags:
                  - Get
                  - Slots
                  - Types
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
                  - Migrations
            /slottypes/{name}/versions/:
              GET:
                summary: GetSlotTypeVersions
                description: >-
                  <p>Gets information about all versions of a slot type.</p>
                  <p>The <code>GetSlotTypeVersions</code> operation returns a
                  <code>SlotTypeMetadata</code> object for each version of a
                  slot type. For example, if a slot type has three numbered
                  versions, the <code>GetSlotTypeVersions</code> operation
                  returns four <code>SlotTypeMetadata</code> objects in the
                  response, one for each numbered version and one for the
                  <code>$LATEST</code> version. </p> <p>The
                  <code>GetSlotTypeVersions</code> operation always returns at
                  least one version, the <code>$LATEST</code> version.</p>
                  <p>This operation requires permissions for the
                  <code>lex:GetSlotTypeVersions</code> action.</p>
                tags:
                  - Get
                  - Slots
                  - Types
                  - Versions
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
                  - Migrations
            /slottypes/:
              GET:
                summary: GetSlotTypes
                description: >-
                  <p>Returns slot type information as follows: </p> <ul> <li>
                  <p>If you specify the <code>nameContains</code> field, returns
                  the <code>$LATEST</code> version of all slot types that
                  contain the specified string.</p> </li> <li> <p> If you don't
                  specify the <code>nameContains</code> field, returns
                  information about the <code>$LATEST</code> version of all slot
                  types. </p> </li> </ul> <p> The operation requires permission
                  for the <code>lex:GetSlotTypes</code> action. </p>
                tags:
                  - Get
                  - Slots
                  - Types
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
                  - Migrations
            /bots/{botname}/utterances?view=aggregation:
              GET:
                summary: GetUtterancesView
                description: >-
                  <p>Use the <code>GetUtterancesView</code> operation to get
                  information about the utterances that your users have made to
                  your bot. You can use this list to tune the utterances that
                  your bot responds to.</p> <p>For example, say that you have
                  created a bot to order flowers. After your users have used
                  your bot for a while, use the <code>GetUtterancesView</code>
                  operation to see the requests that they have made and whether
                  they have been successful. You might find that the utterance
                  "I want flowers" is not being recognized. You could add this
                  utterance to the <code>OrderFlowers</code> intent so that your
                  bot recognizes that utterance.</p> <p>After you publish a new
                  version of a bot, you can get information about the old
                  version and the new so that you can compare the performance
                  across the two versions. </p> <p>Utterance statistics are
                  generated once a day. Data is available for the last 15 days.
                  You can request information for up to 5 versions of your bot
                  in each request. Amazon Lex returns the most frequent
                  utterances received by the bot in the last 15 days. The
                  response contains information about a maximum of 100
                  utterances for each version.</p> <p>If you set
                  <code>childDirected</code> field to true when you created your
                  bot, if you are using slot obfuscation with one or more slots,
                  or if you opted out of participating in improving Amazon Lex,
                  utterances are not available.</p> <p>This operation requires
                  permissions for the <code>lex:GetUtterancesView</code>
                  action.</p>
                tags:
                  - Get
                  - Utterances
                  - View
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
                  - Migrations
                  - Bot Name
                  - Utterances
            /tags/{resourceArn}:
              DELETE:
                summary: UntagResource
                description: <p>Removes tags from a bot, bot alias or bot channel.</p>
                tags:
                  - Untag
                  - Resources
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
                  - Migrations
                  - Bot Name
                  - Utterances
                  - ARN
            /bots/{name}/versions/$LATEST:
              PUT:
                summary: PutBot
                description: >-
                  <p>Creates an Amazon Lex conversational bot or replaces an
                  existing bot. When you create or update a bot you are only
                  required to specify a name, a locale, and whether the bot is
                  directed toward children under age 13. You can use this to add
                  intents later, or to remove intents from an existing bot. When
                  you create a bot with the minimum information, the bot is
                  created or updated but Amazon Lex returns the <code/> response
                  <code>FAILED</code>. You can build the bot after you add one
                  or more intents. For more information about Amazon Lex bots,
                  see <a>how-it-works</a>. </p> <p>If you specify the name of an
                  existing bot, the fields in the request replace the existing
                  values in the <code>$LATEST</code> version of the bot. Amazon
                  Lex removes any fields that you don't provide values for in
                  the request, except for the <code>idleTTLInSeconds</code> and
                  <code>privacySettings</code> fields, which are set to their
                  default values. If you don't specify values for required
                  fields, Amazon Lex throws an exception.</p> <p>This operation
                  requires permissions for the <code>lex:PutBot</code> action.
                  For more information, see <a>security-iam</a>.</p>
                tags:
                  - Put
                  - Bot
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
                  - Migrations
                  - Bot Name
                  - Utterances
                  - ARN
                  - $LATEST
            /intents/{name}/versions/$LATEST:
              PUT:
                summary: PutIntent
                description: >-
                  <p>Creates an intent or replaces an existing intent.</p> <p>To
                  define the interaction between the user and your bot, you use
                  one or more intents. For a pizza ordering bot, for example,
                  you would create an <code>OrderPizza</code> intent. </p> <p>To
                  create an intent or replace an existing intent, you must
                  provide the following:</p> <ul> <li> <p>Intent name. For
                  example, <code>OrderPizza</code>.</p> </li> <li> <p>Sample
                  utterances. For example, "Can I order a pizza, please." and "I
                  want to order a pizza."</p> </li> <li> <p>Information to be
                  gathered. You specify slot types for the information that your
                  bot will request from the user. You can specify standard slot
                  types, such as a date or a time, or custom slot types such as
                  the size and crust of a pizza.</p> </li> <li> <p>How the
                  intent will be fulfilled. You can provide a Lambda function or
                  configure the intent to return the intent information to the
                  client application. If you use a Lambda function, when all of
                  the intent information is available, Amazon Lex invokes your
                  Lambda function. If you configure your intent to return the
                  intent information to the client application. </p> </li> </ul>
                  <p>You can specify other optional information in the request,
                  such as:</p> <ul> <li> <p>A confirmation prompt to ask the
                  user to confirm an intent. For example, "Shall I order your
                  pizza?"</p> </li> <li> <p>A conclusion statement to send to
                  the user after the intent has been fulfilled. For example, "I
                  placed your pizza order."</p> </li> <li> <p>A follow-up prompt
                  that asks the user for additional activity. For example,
                  asking "Do you want to order a drink with your pizza?"</p>
                  </li> </ul> <p>If you specify an existing intent name to
                  update the intent, Amazon Lex replaces the values in the
                  <code>$LATEST</code> version of the intent with the values in
                  the request. Amazon Lex removes fields that you don't provide
                  in the request. If you don't specify the required fields,
                  Amazon Lex throws an exception. When you update the
                  <code>$LATEST</code> version of an intent, the
                  <code>status</code> field of any bot that uses the
                  <code>$LATEST</code> version of the intent is set to
                  <code>NOT_BUILT</code>.</p> <p>For more information, see
                  <a>how-it-works</a>.</p> <p>This operation requires
                  permissions for the <code>lex:PutIntent</code> action.</p>
                tags:
                  - Put
                  - Intent
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
                  - Migrations
                  - Bot Name
                  - Utterances
                  - ARN
                  - $LATEST
            /slottypes/{name}/versions/$LATEST:
              PUT:
                summary: PutSlotType
                description: >-
                  <p>Creates a custom slot type or replaces an existing custom
                  slot type.</p> <p>To create a custom slot type, specify a name
                  for the slot type and a set of enumeration values, which are
                  the values that a slot of this type can assume. For more
                  information, see <a>how-it-works</a>.</p> <p>If you specify
                  the name of an existing slot type, the fields in the request
                  replace the existing values in the <code>$LATEST</code>
                  version of the slot type. Amazon Lex removes the fields that
                  you don't provide in the request. If you don't specify
                  required fields, Amazon Lex throws an exception. When you
                  update the <code>$LATEST</code> version of a slot type, if a
                  bot uses the <code>$LATEST</code> version of an intent that
                  contains the slot type, the bot's <code>status</code> field is
                  set to <code>NOT_BUILT</code>.</p> <p>This operation requires
                  permissions for the <code>lex:PutSlotType</code> action.</p>
                tags:
                  - Put
                  - Slots
                  - Types
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
                  - Migrations
                  - Bot Name
                  - Utterances
                  - ARN
                  - $LATEST
            /imports/:
              POST:
                summary: StartImport
                description: <p>Starts a job to import a resource to Amaz
                tags:
                  - Start
                  - Import
                  - Bots
                  - Names
                  - Versions
                  - Intents
                  - Slot Types
                  - Aliases
                  - Alias
                  - Channels
                  - Versions
                  - Utterances
                  - Users
                  - Identifiers
                  - Versionoralias
                  - Built In
                  - Signatures
                  - Exports
                  - Migrations
                  - Bot Name
                  - Utterances
                  - ARN
                  - $LATEST
                  - Import
    overlays:
      - type: APIs.io Search
        url: overlays/lex-models-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/lex-models-openapi-api-evangelist-ratings.yml
    aid: amazon-web-services:lex-models
  - name: models.lex.v2
    description: <p/>
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://example.com
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://example.com
      - type: OpenAPI
        data:
          openapi: 3.1.0
          info:
            title: models.lex.v2
          paths:
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/customvocabulary/DEFAULT/batchcreate:
              PUT:
                summary: BatchCreateCustomVocabularyItem
                description: >-
                  <p>Create a batch of custom vocabulary items for a given bot
                  locale's custom vocabulary.</p>
                tags:
                  - Batches
                  - Create
                  - Custom
                  - Vocabularies
                  - Items
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/customvocabulary/DEFAULT/batchdelete:
              POST:
                summary: BatchDeleteCustomVocabularyItem
                description: >-
                  <p>Delete a batch of custom vocabulary items for a given bot
                  locale's custom vocabulary.</p>
                tags:
                  - Batches
                  - Delete
                  - Custom
                  - Vocabularies
                  - Items
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/customvocabulary/DEFAULT/batchupdate:
              PUT:
                summary: BatchUpdateCustomVocabularyItem
                description: >-
                  <p>Update a batch of custom vocabulary items for a given bot
                  locale's custom vocabulary.</p>
                tags:
                  - Batches
                  - Update
                  - Custom
                  - Vocabularies
                  - Items
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/:
              PUT:
                summary: UpdateBotLocale
                description: >-
                  <p>Updates the settings that a bot has for a specific
                  locale.</p>
                tags:
                  - Update
                  - Bot
                  - Locales
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
            /bots/:
              POST:
                summary: ListBots
                description: <p>Gets a list of available bots.</p>
                tags:
                  - Lists
                  - Bots
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
            /bots/{botId}/botaliases/:
              POST:
                summary: ListBotAliases
                description: <p>Gets a list of aliases for the specified bot.</p>
                tags:
                  - Lists
                  - Bot
                  - Aliases
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
            /bots/{botId}/botversions/{botVersion}/botlocales/:
              POST:
                summary: ListBotLocales
                description: <p>Gets a list of locales for the specified bot.</p>
                tags:
                  - Lists
                  - Bot
                  - Locales
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
            /bots/{botId}/replicas/:
              POST:
                summary: ListBotReplicas
                description: <p>The action to list the replicated bots.</p>
                tags:
                  - Lists
                  - Bot
                  - Replicas
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
            /bots/{botId}/botversions/:
              POST:
                summary: ListBotVersions
                description: >-
                  <p>Gets information about all of the versions of a bot.</p>
                  <p>The <code>ListBotVersions</code> operation returns a
                  summary of each version of a bot. For example, if a bot has
                  three numbered versions, the <code>ListBotVersions</code>
                  operation returns for summaries, one for each numbered version
                  and one for the <code>DRAFT</code> version.</p> <p>The
                  <code>ListBotVersions</code> operation always returns at least
                  one version, the <code>DRAFT</code> version.</p>
                tags:
                  - Lists
                  - Bot
                  - Versions
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
            /exports/:
              POST:
                summary: ListExports
                description: >-
                  <p>Lists the exports for a bot, bot locale, or custom
                  vocabulary. Exports are kept in the list for 7 days.</p>
                tags:
                  - Lists
                  - Exports
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/intents/:
              POST:
                summary: ListIntents
                description: <p>Get a list of intents that meet the specified criteria.</p>
                tags:
                  - Lists
                  - Intents
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
            /policy/{resourceArn}/:
              PUT:
                summary: UpdateResourcePolicy
                description: >-
                  <p>Replaces the existing resource policy for a bot or bot
                  alias with a new one. If the policy doesn't exist, Amazon Lex
                  returns an exception.</p>
                tags:
                  - Update
                  - Resources
                  - Policies
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
            /policy/{resourceArn}/statements/:
              POST:
                summary: CreateResourcePolicyStatement
                description: >-
                  <p>Adds a new resource policy statement to a bot or bot alias.
                  If a resource policy exists, the statement is added to the
                  current resource policy. If a policy doesn't exist, a new
                  policy is created.</p> <p>You can't create a resource policy
                  statement that allows cross-account access.</p>
                tags:
                  - Create
                  - Resources
                  - Policies
                  - Statements
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/intents/{intentId}/slots/:
              POST:
                summary: ListSlots
                description: <p>Gets a list of slots that match the specified criteria.</p>
                tags:
                  - Lists
                  - Slots
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/slottypes/:
              POST:
                summary: ListSlotTypes
                description: >-
                  <p>Gets a list of slot types that match the specified
                  criteria.</p>
                tags:
                  - Lists
                  - Slots
                  - Types
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
            /testsets/{testSetId}/testsetdiscrepancy:
              POST:
                summary: CreateTestSetDiscrepancyReport
                description: >-
                  <p>Create a report that describes the differences between the
                  bot and the test set.</p>
                tags:
                  - Create
                  - Tests
                  - Sets
                  - Discrepancy
                  - Reports
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
            /createuploadurl/:
              POST:
                summary: CreateUploadUrl
                description: >-
                  <p>Gets a pre-signed S3 write URL that you use to upload the
                  zip archive when importing a bot or a bot locale. </p>
                tags:
                  - Create
                  - Uploads
                  - URL
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
            /bots/{botId}/:
              PUT:
                summary: UpdateBot
                description: <p>Updates the configuration of an existing bot. </p>
                tags:
                  - Update
                  - Bot
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
            /bots/{botId}/botaliases/{botAliasId}/:
              PUT:
                summary: UpdateBotAlias
                description: <p>Updates the configuration of an existing bot alias.</p>
                tags:
                  - Update
                  - Bot
                  - Alias
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
            /bots/{botId}/replicas/{replicaRegion}/:
              GET:
                summary: DescribeBotReplica
                description: >-
                  <p>Monitors the bot replication status through the UI
                  console.</p>
                tags:
                  - Describe
                  - Bot
                  - Replicas
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
            /bots/{botId}/botversions/{botVersion}/:
              GET:
                summary: DescribeBotVersion
                description: <p>Provides metadata about a version of a bot.</p>
                tags:
                  - Describe
                  - Bot
                  - Versions
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/customvocabulary:
              DELETE:
                summary: DeleteCustomVocabulary
                description: >-
                  <p>Removes a custom vocabulary from the specified locale in
                  the specified bot.</p>
                tags:
                  - Delete
                  - Custom
                  - Vocabularies
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
            /exports/{exportId}/:
              PUT:
                summary: UpdateExport
                description: >-
                  <p>Updates the password used to protect an export zip
                  archive.</p> <p>The password is not required. If you don't
                  supply a password, Amazon Lex generates a zip file that is not
                  protected by a password. This is the archive that is available
                  at the pre-signed S3 URL provided by the <a
                  href="https://docs.aws.amazon.com/lexv2/latest/APIReference/API_DescribeExport.html">DescribeExport</a>
                  operation.</p>
                tags:
                  - Update
                  - Export
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
            /imports/{importId}/:
              GET:
                summary: DescribeImport
                description: <p>Gets information about a specific import.</p>
                tags:
                  - Describe
                  - Import
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/intents/{intentId}/:
              PUT:
                summary: UpdateIntent
                description: <p>Updates the settings for an intent.</p>
                tags:
                  - Update
                  - Intent
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
            /policy/{resourceArn}/statements/{statementId}/:
              DELETE:
                summary: DeleteResourcePolicyStatement
                description: >-
                  <p>Deletes a policy statement from a resource policy. If you
                  delete the last statement from a policy, the policy is
                  deleted. If you specify a statement ID that doesn't exist in
                  the policy, or if the bot or bot alias doesn't have a policy
                  attached, Amazon Lex returns an exception.</p>
                tags:
                  - Delete
                  - Resources
                  - Policies
                  - Statements
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/intents/{intentId}/slots/{slotId}/:
              PUT:
                summary: UpdateSlot
                description: <p>Updates the settings for a slot.</p>
                tags:
                  - Update
                  - Slots
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/slottypes/{slotTypeId}/:
              PUT:
                summary: UpdateSlotType
                description: <p>Updates the configuration of an existing slot type.</p>
                tags:
                  - Update
                  - Slots
                  - Types
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
            /testsets/{testSetId}:
              PUT:
                summary: UpdateTestSet
                description: <p>The action to update the test set.</p>
                tags:
                  - Update
                  - Tests
                  - Sets
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
            /bots/{botId}/utterances/:
              DELETE:
                summary: DeleteUtterances
                description: >-
                  <p>Deletes stored utterances.</p> <p>Amazon Lex stores the
                  utterances that users send to your bot. Utterances are stored
                  for 15 days for use with the <a
                  href="https://docs.aws.amazon.com/lexv2/latest/APIReference/API_ListAggregatedUtterances.html">ListAggregatedUtterances</a>
                  operation, and then stored indefinitely for use in improving
                  the ability of your bot to respond to user input..</p> <p>Use
                  the <code>DeleteUtterances</code> operation to manually delete
                  utterances for a specific session. When you use the
                  <code>DeleteUtterances</code> operation, utterances stored for
                  improving your bot's ability to respond to user input are
                  deleted immediately. Utterances stored for use with the
                  <code>ListAggregatedUtterances</code> operation are deleted
                  after 15 days.</p>
                tags:
                  - Delete
                  - Utterances
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/botrecommendations/{botRecommendationId}/:
              PUT:
                summary: UpdateBotRecommendation
                description: <p>Updates an existing bot recommendation request.</p>
                tags:
                  - Update
                  - Bot
                  - Recommendations
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/generations/{generationId}:
              GET:
                summary: DescribeBotResourceGeneration
                description: >-
                  <p>Returns information about a request to generate a bot
                  through natural language description, made through the
                  <code>StartBotResource</code> API. Use the
                  <code>generatedBotLocaleUrl</code> to retrieve the Amazon S3
                  object containing the bot locale configuration. You can then
                  modify and import this configuration.</p>
                tags:
                  - Describe
                  - Bot
                  - Resources
                  - Generation
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/customvocabulary/DEFAULT/metadata:
              GET:
                summary: DescribeCustomVocabularyMetadata
                description: >-
                  <p>Provides metadata information about a custom
                  vocabulary.</p>
                tags:
                  - Describe
                  - Custom
                  - Vocabularies
                  - Metadata
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
            /testexecutions/{testExecutionId}:
              GET:
                summary: DescribeTestExecution
                description: <p>Gets metadata information about the test execution.</p>
                tags:
                  - Describe
                  - Tests
                  - Execution
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
            /testsetdiscrepancy/{testSetDiscrepancyReportId}:
              GET:
                summary: DescribeTestSetDiscrepancyReport
                description: >-
                  <p>Gets metadata information about the test set discrepancy
                  report.</p>
                tags:
                  - Describe
                  - Tests
                  - Sets
                  - Discrepancy
                  - Reports
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
            /testsetgenerations/{testSetGenerationId}:
              GET:
                summary: DescribeTestSetGeneration
                description: >-
                  <p>Gets metadata information about the test set
                  generation.</p>
                tags:
                  - Describe
                  - Tests
                  - Sets
                  - Generation
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/generate:
              POST:
                summary: GenerateBotElement
                description: <p>Generates sample utterances for an intent.</p>
                tags:
                  - Generate
                  - Bot
                  - Elements
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
            /testexecutions/{testExecutionId}/artifacturl:
              GET:
                summary: GetTestExecutionArtifactsUrl
                description: >-
                  <p>The pre-signed Amazon S3 URL to download the test execution
                  result artifacts.</p>
                tags:
                  - Get
                  - Tests
                  - Execution
                  - Artifacts
                  - URL
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
            /bots/{botId}/aggregatedutterances/:
              POST:
                summary: ListAggregatedUtterances
                description: >-
                  <p>Provides a list of utterances that users have sent to the
                  bot.</p> <p>Utterances are aggregated by the text of the
                  utterance. For example, all instances where customers used the
                  phrase "I want to order pizza" are aggregated into the same
                  line in the response.</p> <p>You can see both detected
                  utterances and missed utterances. A detected utterance is
                  where the bot properly recognized the utterance and activated
                  the associated intent. A missed utterance was not recognized
                  by the bot and didn't activate an intent.</p> <p>Utterances
                  can be aggregated for a bot alias or for a bot version, but
                  not both at the same time.</p> <p>Utterances statistics are
                  not generated under the following conditions:</p> <ul> <li>
                  <p>The <code>childDirected</code> field was set to true when
                  the bot was created.</p> </li> <li> <p>You are using slot
                  obfuscation with one or more slots.</p> </li> <li> <p>You
                  opted out of participating in improving Amazon Lex.</p> </li>
                  </ul>
                tags:
                  - Lists
                  - Aggregated
                  - Utterances
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
            /bots/{botId}/replicas/{replicaRegion}/botaliases/:
              POST:
                summary: ListBotAliasReplicas
                description: >-
                  <p>The action to list the replicated bots created from the
                  source bot alias.</p>
                tags:
                  - Lists
                  - Bot
                  - Alias
                  - Replicas
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/botrecommendations/:
              PUT:
                summary: StartBotRecommendation
                description: >-
                  <p>Use this to provide your transcript data, and to start the
                  bot recommendation process.</p>
                tags:
                  - Start
                  - Bot
                  - Recommendations
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/generations:
              POST:
                summary: ListBotResourceGenerations
                description: <p>Lists the generation requests made for a bot locale.</p>
                tags:
                  - Lists
                  - Bot
                  - Resources
                  - Generations
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
            /bots/{botId}/replicas/{replicaRegion}/botversions/:
              POST:
                summary: ListBotVersionReplicas
                description: >-
                  <p>Contains information about all the versions replication
                  statuses applicable for Global Resiliency.</p>
                tags:
                  - Lists
                  - Bot
                  - Versions
                  - Replicas
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
            /builtins/locales/{localeId}/intents/:
              POST:
                summary: ListBuiltInIntents
                description: >-
                  <p>Gets a list of built-in intents provided by Amazon Lex that
                  you can use in your bot. </p> <p>To use a built-in intent as a
                  the base for your own intent, include the built-in intent
                  signature in the <code>parentIntentSignature</code> parameter
                  when you call the <code>CreateIntent</code> operation. For
                  more information, see <a
                  href="https://docs.aws.amazon.com/lexv2/latest/APIReference/API_CreateIntent.html">CreateIntent</a>.</p>
                tags:
                  - Lists
                  - Built
                  - In
                  - Intents
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
            /builtins/locales/{localeId}/slottypes/:
              POST:
                summary: ListBuiltInSlotTypes
                description: >-
                  <p>Gets a list of built-in slot types that meet the specified
                  criteria.</p>
                tags:
                  - Lists
                  - Built
                  - In
                  - Slots
                  - Types
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/customvocabulary/DEFAULT/list:
              POST:
                summary: ListCustomVocabularyItems
                description: >-
                  <p>Paginated list of custom vocabulary items for a given bot
                  locale's custom vocabulary.</p>
                tags:
                  - Lists
                  - Custom
                  - Vocabularies
                  - Items
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
            /imports/:
              PUT:
                summary: StartImport
                description: >-
                  <p>Starts importing a bot, bot locale, or custom vocabulary
                  from a zip archive that you uploaded to an S3 bucket.</p>
                tags:
                  - Start
                  - Import
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
            /bots/{botId}/analytics/intentmetrics:
              POST:
                summary: ListIntentMetrics
                description: >-
                  <p>Retrieves summary metrics for the intents in your bot. The
                  following fields are required:</p> <ul> <li> <p>
                  <code>metrics</code> – A list of <a
                  href="https://docs.aws.amazon.com/lexv2/latest/APIReference/API_AnalyticsIntentMetric.html">AnalyticsIntentMetric</a>
                  objects. In each object, use the <code>name</code> field to
                  specify the metric to calculate, the <code>statistic</code>
                  field to specify whether to calculate the <code>Sum</code>,
                  <code>Average</code>, or <code>Max</code> number, and the
                  <code>order</code> field to specify whether to sort the
                  results in <code>Ascending</code> or <code>Descending</code>
                  order.</p> </li> <li> <p> <code>startDateTime</code> and
                  <code>endDateTime</code> – Define a time range for which you
                  want to retrieve results.</p> </li> </ul> <p>Of the optional
                  fields, you can organize the results in the following
                  ways:</p> <ul> <li> <p>Use the <code>filters</code> field to
                  filter the results, the <code>groupBy</code> field to specify
                  categories by which to group the results, and the
                  <code>binBy</code> field to specify time intervals by which to
                  group the results.</p> </li> <li> <p>Use the
                  <code>maxResults</code> field to limit the number of results
                  to return in a single response and the <code>nextToken</code>
                  field to return the next batch of results if the response does
                  not return the full set of results.</p> </li> </ul> <p>Note
                  that an <code>order</code> field exists in both
                  <code>binBy</code> and <code>metrics</code>. You can specify
                  only one <code>order</code> in a given request.</p>
                tags:
                  - Lists
                  - Intent
                  - Metrics
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
            /bots/{botId}/analytics/intentpaths:
              POST:
                summary: ListIntentPaths
                description: >-
                  <p>Retrieves summary statistics for a path of intents that
                  users take over sessions with your bot. The following fields
                  are required:</p> <ul> <li> <p> <code>startDateTime</code> and
                  <code>endDateTime</code> – Define a time range for which you
                  want to retrieve results.</p> </li> <li> <p>
                  <code>intentPath</code> – Define an order of intents for which
                  you want to retrieve metrics. Separate intents in the path
                  with a forward slash. For example, populate the
                  <code>intentPath</code> field with
                  <code>/BookCar/BookHotel</code> to see details about how many
                  times users invoked the <code>BookCar</code> and
                  <code>BookHotel</code> intents in that order.</p> </li> </ul>
                  <p>Use the optional <code>filters</code> field to filter the
                  results.</p>
                tags:
                  - Lists
                  - Intent
                  - Paths
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
            /bots/{botId}/analytics/intentstagemetrics:
              POST:
                summary: ListIntentStageMetrics
                description: >-
                  <p>Retrieves summary metrics for the stages within intents in
                  your bot. The following fields are required:</p> <ul> <li> <p>
                  <code>metrics</code> – A list of <a
                  href="https://docs.aws.amazon.com/lexv2/latest/APIReference/API_AnalyticsIntentStageMetric.html">AnalyticsIntentStageMetric</a>
                  objects. In each object, use the <code>name</code> field to
                  specify the metric to calculate, the <code>statistic</code>
                  field to specify whether to calculate the <code>Sum</code>,
                  <code>Average</code>, or <code>Max</code> number, and the
                  <code>order</code> field to specify whether to sort the
                  results in <code>Ascending</code> or <code>Descending</code>
                  order.</p> </li> <li> <p> <code>startDateTime</code> and
                  <code>endDateTime</code> – Define a time range for which you
                  want to retrieve results.</p> </li> </ul> <p>Of the optional
                  fields, you can organize the results in the following
                  ways:</p> <ul> <li> <p>Use the <code>filters</code> field to
                  filter the results, the <code>groupBy</code> field to specify
                  categories by which to group the results, and the
                  <code>binBy</code> field to specify time intervals by which to
                  group the results.</p> </li> <li> <p>Use the
                  <code>maxResults</code> field to limit the number of results
                  to return in a single response and the <code>nextToken</code>
                  field to return the next batch of results if the response does
                  not return the full set of results.</p> </li> </ul> <p>Note
                  that an <code>order</code> field exists in both
                  <code>binBy</code> and <code>metrics</code>. You can only
                  specify one <code>order</code> in a given request.</p>
                tags:
                  - Lists
                  - Intent
                  - Stage
                  - Metrics
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/botrecommendations/{botRecommendationId}/intents:
              POST:
                summary: ListRecommendedIntents
                description: >-
                  <p>Gets a list of recommended intents provided by the bot
                  recommendation that you can use in your bot. Intents in the
                  response are ordered by relevance.</p>
                tags:
                  - Lists
                  - Recommended
                  - Intents
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
            /bots/{botId}/analytics/sessions:
              POST:
                summary: ListSessionAnalyticsData
                description: >-
                  <p>Retrieves a list of metadata for individual user sessions
                  with your bot. The <code>startDateTime</code> and
                  <code>endDateTime</code> fields are required. These fields
                  define a time range for which you want to retrieve results. Of
                  the optional fields, you can organize the results in the
                  following ways:</p> <ul> <li> <p>Use the <code>filters</code>
                  field to filter the results and the <code>sortBy</code> field
                  to specify the values by which to sort the results.</p> </li>
                  <li> <p>Use the <code>maxResults</code> field to limit the
                  number of results to return in a single response and the
                  <code>nextToken</code> field to return the next batch of
                  results if the response does not return the full set of
                  results.</p> </li> </ul>
                tags:
                  - Lists
                  - Sessions
                  - Analytics
                  - Data
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
            /bots/{botId}/analytics/sessionmetrics:
              POST:
                summary: ListSessionMetrics
                description: >-
                  <p>Retrieves summary metrics for the user sessions with your
                  bot. The following fields are required:</p> <ul> <li> <p>
                  <code>metrics</code> – A list of <a
                  href="https://docs.aws.amazon.com/lexv2/latest/APIReference/API_AnalyticsSessionMetric.html">AnalyticsSessionMetric</a>
                  objects. In each object, use the <code>name</code> field to
                  specify the metric to calculate, the <code>statistic</code>
                  field to specify whether to calculate the <code>Sum</code>,
                  <code>Average</code>, or <code>Max</code> number, and the
                  <code>order</code> field to specify whether to sort the
                  results in <code>Ascending</code> or <code>Descending</code>
                  order.</p> </li> <li> <p> <code>startDateTime</code> and
                  <code>endDateTime</code> – Define a time range for which you
                  want to retrieve results.</p> </li> </ul> <p>Of the optional
                  fields, you can organize the results in the following
                  ways:</p> <ul> <li> <p>Use the <code>filters</code> field to
                  filter the results, the <code>groupBy</code> field to specify
                  categories by which to group the results, and the
                  <code>binBy</code> field to specify time intervals by which to
                  group the results.</p> </li> <li> <p>Use the
                  <code>maxResults</code> field to limit the number of results
                  to return in a single response and the <code>nextToken</code>
                  field to return the next batch of results if the response does
                  not return the full set of results.</p> </li> </ul> <p>Note
                  that an <code>order</code> field exists in both
                  <code>binBy</code> and <code>metrics</code>. Currently, you
                  can specify it in either field, but not in both.</p>
                tags:
                  - Lists
                  - Sessions
                  - Metrics
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
            /tags/{resourceARN}:
              DELETE:
                summary: UntagResource
                description: <p>Removes tags from a bot, bot alias, or bot channel.</p>
                tags:
                  - Untag
                  - Resources
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
            /testexecutions/{testExecutionId}/results:
              POST:
                summary: ListTestExecutionResultItems
                description: <p>Gets a list of test execution result items.</p>
                tags:
                  - Lists
                  - Tests
                  - Execution
                  - Results
                  - Items
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
            /testexecutions:
              POST:
                summary: ListTestExecutions
                description: <p>The list of test set executions.</p>
                tags:
                  - Lists
                  - Tests
                  - Executions
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
                  - Test Executions
            /testsets/{testSetId}/records:
              POST:
                summary: ListTestSetRecords
                description: <p>The list of test set records.</p>
                tags:
                  - Lists
                  - Tests
                  - Sets
                  - Records
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
                  - Test Executions
                  - Records
            /testsets:
              POST:
                summary: ListTestSets
                description: <p>The list of the test sets</p>
                tags:
                  - Lists
                  - Tests
                  - Sets
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
                  - Test Executions
                  - Records
                  - Test Sets
            /bots/{botId}/analytics/utterances:
              POST:
                summary: ListUtteranceAnalyticsData
                description: >-
                  <note> <p>To use this API operation, your IAM role must have
                  permissions to perform the <a
                  href="https://docs.aws.amazon.com/lexv2/latest/APIReference/API_ListAggregatedUtterances.html">ListAggregatedUtterances</a>
                  operation, which provides access to utterance-related
                  analytics. See <a
                  href="https://docs.aws.amazon.com/lexv2/latest/dg/monitoring-utterances.html">Viewing
                  utterance statistics</a> for the IAM policy to apply to the
                  IAM role.</p> </note> <p>Retrieves a list of metadata for
                  individual user utterances to your bot. The following fields
                  are required:</p> <ul> <li> <p> <code>startDateTime</code> and
                  <code>endDateTime</code> – Define a time range for which you
                  want to retrieve results.</p> </li> </ul> <p>Of the optional
                  fields, you can organize the results in the following
                  ways:</p> <ul> <li> <p>Use the <code>filters</code> field to
                  filter the results and the <code>sortBy</code> field to
                  specify the values by which to sort the results.</p> </li>
                  <li> <p>Use the <code>maxResults</code> field to limit the
                  number of results to return in a single response and the
                  <code>nextToken</code> field to return the next batch of
                  results if the response does not return the full set of
                  results.</p> </li> </ul>
                tags:
                  - Lists
                  - Utterances
                  - Analytics
                  - Data
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
                  - Test Executions
                  - Records
                  - Test Sets
            /bots/{botId}/analytics/utterancemetrics:
              POST:
                summary: ListUtteranceMetrics
                description: >-
                  <note> <p>To use this API operation, your IAM role must have
                  permissions to perform the <a
                  href="https://docs.aws.amazon.com/lexv2/latest/APIReference/API_ListAggregatedUtterances.html">ListAggregatedUtterances</a>
                  operation, which provides access to utterance-related
                  analytics. See <a
                  href="https://docs.aws.amazon.com/lexv2/latest/dg/monitoring-utterances.html">Viewing
                  utterance statistics</a> for the IAM policy to apply to the
                  IAM role.</p> </note> <p>Retrieves summary metrics for the
                  utterances in your bot. The following fields are required:</p>
                  <ul> <li> <p> <code>metrics</code> – A list of <a
                  href="https://docs.aws.amazon.com/lexv2/latest/APIReference/API_AnalyticsUtteranceMetric.html">AnalyticsUtteranceMetric</a>
                  objects. In each object, use the <code>name</code> field to
                  specify the metric to calculate, the <code>statistic</code>
                  field to specify whether to calculate the <code>Sum</code>,
                  <code>Average</code>, or <code>Max</code> number, and the
                  <code>order</code> field to specify whether to sort the
                  results in <code>Ascending</code> or <code>Descending</code>
                  order.</p> </li> <li> <p> <code>startDateTime</code> and
                  <code>endDateTime</code> – Define a time range for which you
                  want to retrieve results.</p> </li> </ul> <p>Of the optional
                  fields, you can organize the results in the following
                  ways:</p> <ul> <li> <p>Use the <code>filters</code> field to
                  filter the results, the <code>groupBy</code> field to specify
                  categories by which to group the results, and the
                  <code>binBy</code> field to specify time intervals by which to
                  group the results.</p> </li> <li> <p>Use the
                  <code>maxResults</code> field to limit the number of results
                  to return in a single response and the <code>nextToken</code>
                  field to return the next batch of results if the response does
                  not return the full set of results.</p> </li> </ul> <p>Note
                  that an <code>order</code> field exists in both
                  <code>binBy</code> and <code>metrics</code>. Currently, you
                  can specify it in either field, but not in both.</p>
                tags:
                  - Lists
                  - Utterances
                  - Metrics
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
                  - Test Executions
                  - Records
                  - Test Sets
                  - Utterance Metrics
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/botrecommendations/{botRecommendationId}/associatedtranscripts:
              POST:
                summary: SearchAssociatedTranscripts
                description: >-
                  <p>Search for associated transcripts that meet the specified
                  criteria.</p>
                tags:
                  - Search
                  - Associated
                  - Transcripts
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
                  - Test Executions
                  - Records
                  - Test Sets
                  - Utterance Metrics
                  - Associated Transcripts
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/startgeneration:
              PUT:
                summary: StartBotResourceGeneration
                description: >-
                  <p>Starts a request for the descriptive bot builder to
                  generate a bot locale configuration based on the prompt you
                  provide it. After you make this call, use the
                  <code>DescribeBotResourceGeneration</code> operation to check
                  on the status of the generation and for the
                  <code>generatedBotLocaleUrl</code> when the generation is
                  complete. Use that value to retrieve the Amazon S3 object
                  containing the bot locale configuration. You can then modify
                  and import this configuration.</p>
                tags:
                  - Start
                  - Bot
                  - Resources
                  - Generation
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
                  - Test Executions
                  - Records
                  - Test Sets
                  - Utterance Metrics
                  - Associated Transcripts
                  - Start Generation
            /testsets/{testSetId}/testexecutions:
              POST:
                summary: StartTestExecution
                description: <p>The action to start test set execution.</p>
                tags:
                  - Start
                  - Tests
                  - Execution
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
                  - Test Executions
                  - Records
                  - Test Sets
                  - Utterance Metrics
                  - Associated Transcripts
                  - Start Generation
            /testsetgenerations:
              PUT:
                summary: StartTestSetGeneration
                description: <p>The action to start the generation of test set.</p>
                tags:
                  - Start
                  - Tests
                  - Sets
                  - Generation
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
                  - Test Executions
                  - Records
                  - Test Sets
                  - Utterance Metrics
                  - Associated Transcripts
                  - Start Generation
                  - Test Set Generations
            /bots/{botId}/botversions/{botVersion}/botlocales/{localeId}/botrecommendations/{botRecommendationId}/stopbotrecommendation:
              PUT:
                summary: StopBotRecommendation
                description: <p>Stop an already running Bot Recommendation re
                tags:
                  - Stop
                  - Bot
                  - Recommendations
                  - Identifiers
                  - Bot Versions
                  - Bot
                  - Versions
                  - Bot Locales
                  - Locales
                  - Custom Vocabulary
                  - Batches
                  - Batches
                  - Batches
                  - Bots
                  - Bot Aliases
                  - Replicas
                  - Exports
                  - Intents
                  - ARN
                  - Statements
                  - Intent
                  - Slots
                  - Slot Types
                  - Sets
                  - Test Set Discrepancy
                  - Upload URLs
                  - Alias
                  - Replicas
                  - Regions
                  - Statements
                  - Slots
                  - Types
                  - Utterances
                  - Bot Recommendations
                  - Recommendations
                  - Generations
                  - Generation
                  - Metadata
                  - Execution
                  - Discrepancy
                  - Reports
                  - Generate
                  - Artifact URL
                  - Aggregated Utterances
                  - Lists
                  - Imports
                  - Analytics
                  - Intent Metrics
                  - Intent Paths
                  - Intent Stage Metrics
                  - Sessions
                  - Session Metrics
                  - Tags
                  - ResourceARN
                  - Results
                  - Test Executions
                  - Records
                  - Test Sets
                  - Utterance Metrics
                  - Associated Transcripts
                  - Start Generation
                  - Test Set Generations
                  - Stopbotrecommendati
    overlays:
      - type: APIs.io Search
        url: overlays/modelslexv2-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/modelslexv2-openapi-api-evangelist-ratings.yml
    aid: amazon-web-services:modelslexv2
  - name: quicksight
    description: >-
      <fullname>Amazon QuickSight API Reference</fullname> <p>Amazon QuickSight
      is a fully managed, serverless business intelligence service for the
      Amazon Web Services Cloud that makes it easy to extend data and insights
      to every user in your organization. This API reference contains
      documentation for a programming interface that you can use to manage
      Amazon QuickSight. </p>
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://example.com
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://example.com
      - type: OpenAPI
        data:
          openapi: 3.1.0
          info:
            title: quicksight
          paths:
            /accounts/{AwsAccountId}/data-sets/{DataSetId}/ingestions/{IngestionId}:
              GET:
                summary: DescribeIngestion
                description: <p>Describes a SPICE ingestion.</p>
                tags:
                  - Describe
                  - Ingestion
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
            /accounts/{AwsAccountId}/customizations:
              PUT:
                summary: UpdateAccountCustomization
                description: >-
                  <p>Updates Amazon QuickSight customizations for the current
                  Amazon Web Services Region. Currently, the only customization
                  that you can use is a theme.</p> <p>You can use customizations
                  for your Amazon Web Services account or, if you specify a
                  namespace, for a Amazon QuickSight namespace instead.
                  Customizations that apply to a namespace override
                  customizations that apply to an Amazon Web Services account.
                  To find out which customizations apply, use the
                  <code>DescribeAccountCustomization</code> API operation. </p>
                tags:
                  - Update
                  - Account
                  - Customizations
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
            /account/{AwsAccountId}:
              GET:
                summary: DescribeAccountSubscription
                description: >-
                  <p>Use the DescribeAccountSubscription operation to receive a
                  description of an Amazon QuickSight account's subscription. A
                  successful API call returns an <code>AccountInfo</code> object
                  that includes an account's name, subscription status,
                  authentication type, edition, and notification email
                  address.</p>
                tags:
                  - Describe
                  - Account
                  - Subscriptions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
            /accounts/{AwsAccountId}/analyses/{AnalysisId}:
              PUT:
                summary: UpdateAnalysis
                description: <p>Updates an analysis in Amazon QuickSight</p>
                tags:
                  - Update
                  - Analysis
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
            /accounts/{AwsAccountId}/dashboards/{DashboardId}:
              PUT:
                summary: UpdateDashboard
                description: >-
                  <p>Updates a dashboard in an Amazon Web Services account.</p>
                  <note> <p>Updating a Dashboard creates a new dashboard version
                  but does not immediately publish the new version. You can
                  update the published version of a dashboard by using the
                  <code> <a
                  href="https://docs.aws.amazon.com/quicksight/latest/APIReference/API_UpdateDashboardPublishedVersion.html">UpdateDashboardPublishedVersion</a>
                  </code> API operation.</p> </note>
                tags:
                  - Update
                  - Dashboard
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
            /accounts/{AwsAccountId}/data-sets:
              GET:
                summary: ListDataSets
                description: >-
                  <p>Lists all of the datasets belonging to the current Amazon
                  Web Services account in an Amazon Web Services Region.</p>
                  <p>The permissions resource is
                  <code>arn:aws:quicksight:region:aws-account-id:dataset/*</code>.</p>
                tags:
                  - Lists
                  - Data
                  - Sets
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
            /accounts/{AwsAccountId}/data-sources:
              GET:
                summary: ListDataSources
                description: >-
                  <p>Lists data sources in current Amazon Web Services Region
                  that belong to this Amazon Web Services account.</p>
                tags:
                  - Lists
                  - Data
                  - Sources
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
            /accounts/{AwsAccountId}/folders/{FolderId}:
              PUT:
                summary: UpdateFolder
                description: <p>Updates the name of a folder.</p>
                tags:
                  - Update
                  - Folder
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
            /accounts/{AwsAccountId}/folders/{FolderId}/members/{MemberType}/{MemberId}:
              DELETE:
                summary: DeleteFolderMembership
                description: >-
                  <p>Removes an asset, such as a dashboard, analysis, or
                  dataset, from a folder.</p>
                tags:
                  - Delete
                  - Folder
                  - Membership
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
            /accounts/{AwsAccountId}/namespaces/{Namespace}/groups:
              GET:
                summary: ListGroups
                description: <p>Lists all user groups in Amazon QuickSight. </p>
                tags:
                  - Lists
                  - Groups
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
            /accounts/{AwsAccountId}/namespaces/{Namespace}/groups/{GroupName}/members/{MemberName}:
              GET:
                summary: DescribeGroupMembership
                description: >-
                  <p>Use the <code>DescribeGroupMembership</code> operation to
                  determine if a user is a member of the specified group. If the
                  user exists and is a member of the specified group, an
                  associated <code>GroupMember</code> object is returned.</p>
                tags:
                  - Describe
                  - Group
                  - Membership
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
            /accounts/{AwsAccountId}/namespaces/{Namespace}/iam-policy-assignments/:
              POST:
                summary: CreateIAMPolicyAssignment
                description: >-
                  <p>Creates an assignment with one specified IAM policy,
                  identified by its Amazon Resource Name (ARN). This policy
                  assignment is attached to the specified groups or users of
                  Amazon QuickSight. Assignment names are unique per Amazon Web
                  Services account. To avoid overwriting rules in other
                  namespaces, use assignment names that are unique.</p>
                tags:
                  - Create
                  - Policies
                  - Assignment
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
            /accounts/{AwsAccountId}:
              POST:
                summary: CreateNamespace
                description: >-
                  <p>(Enterprise edition only) Creates a new namespace for you
                  to use with Amazon QuickSight.</p> <p>A namespace allows you
                  to isolate the Amazon QuickSight users and groups that are
                  registered for that namespace. Users that access the namespace
                  can share assets only with other users or groups in the same
                  namespace. They can't see users and groups in other
                  namespaces. You can create a namespace after your Amazon Web
                  Services account is subscribed to Amazon QuickSight. The
                  namespace must be unique within the Amazon Web Services
                  account. By default, there is a limit of 100 namespaces per
                  Amazon Web Services account. To increase your limit, create a
                  ticket with Amazon Web Services Support. </p>
                tags:
                  - Create
                  - Namespaces
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
            /accounts/{AwsAccountId}/data-sets/{DataSetId}/refresh-schedules:
              PUT:
                summary: UpdateRefreshSchedule
                description: <p>Updates a refresh schedule for a dataset.</p>
                tags:
                  - Update
                  - Refresh
                  - Schedules
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
            /accounts/{AwsAccountId}/namespaces/{Namespace}/roles/{Role}/members/{MemberName}:
              DELETE:
                summary: DeleteRoleMembership
                description: <p>Removes a group from a role.</p>
                tags:
                  - Delete
                  - Roles
                  - Membership
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
            /accounts/{AwsAccountId}/templates/{TemplateId}:
              PUT:
                summary: UpdateTemplate
                description: >-
                  <p>Updates a template from an existing Amazon QuickSight
                  analysis or another template.</p>
                tags:
                  - Update
                  - Templates
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
            /accounts/{AwsAccountId}/templates/{TemplateId}/aliases/{AliasName}:
              PUT:
                summary: UpdateTemplateAlias
                description: <p>Updates the template alias of a template.</p>
                tags:
                  - Update
                  - Templates
                  - Alias
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
            /accounts/{AwsAccountId}/themes/{ThemeId}:
              PUT:
                summary: UpdateTheme
                description: <p>Updates a theme.</p>
                tags:
                  - Update
                  - Theme
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
            /accounts/{AwsAccountId}/themes/{ThemeId}/aliases/{AliasName}:
              PUT:
                summary: UpdateThemeAlias
                description: <p>Updates an alias of a theme.</p>
                tags:
                  - Update
                  - Theme
                  - Alias
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
            /accounts/{AwsAccountId}/topics:
              GET:
                summary: ListTopics
                description: <p>Lists all of the topics within an account.</p>
                tags:
                  - Lists
                  - Topics
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
            /accounts/{AwsAccountId}/topics/{TopicId}/schedules:
              GET:
                summary: ListTopicRefreshSchedules
                description: <p>Lists all of the refresh schedules for a topic.</p>
                tags:
                  - Lists
                  - Topics
                  - Refresh
                  - Schedules
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
            /accounts/{AwsAccountId}/vpc-connections:
              GET:
                summary: ListVPCConnections
                description: >-
                  <p>Lists all of the VPC connections in the current set Amazon
                  Web Services Region of an Amazon Web Services account.</p>
                tags:
                  - Lists
                  - Connections
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
            /accounts/{AwsAccountId}/data-sets/{DataSetId}:
              PUT:
                summary: UpdateDataSet
                description: >-
                  <p>Updates a dataset. This operation doesn't support datasets
                  that include uploaded files as a source. Partial updates are
                  not supported by this operation.</p>
                tags:
                  - Update
                  - Data
                  - Sets
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
            /accounts/{AwsAccountId}/data-sets/{DataSetId}/refresh-properties:
              PUT:
                summary: PutDataSetRefreshProperties
                description: >-
                  <p>Creates or updates the dataset refresh properties for the
                  dataset.</p>
                tags:
                  - Put
                  - Data
                  - Sets
                  - Refresh
                  - Properties
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
            /accounts/{AwsAccountId}/data-sources/{DataSourceId}:
              PUT:
                summary: UpdateDataSource
                description: <p>Updates a data source.</p>
                tags:
                  - Update
                  - Data
                  - Source
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
            /accounts/{AwsAccountId}/namespaces/{Namespace}/groups/{GroupName}:
              PUT:
                summary: UpdateGroup
                description: <p>Changes a group description. </p>
                tags:
                  - Update
                  - Group
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
            /accounts/{AwsAccountId}/namespace/{Namespace}/iam-policy-assignments/{AssignmentName}:
              DELETE:
                summary: DeleteIAMPolicyAssignment
                description: <p>Deletes an existing IAM policy assignment.</p>
                tags:
                  - Delete
                  - Policies
                  - Assignment
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
            /accounts/{AwsAccountId}/identity-propagation-config/{Service}:
              POST:
                summary: UpdateIdentityPropagationConfig
                description: >-
                  <p>Adds or updates services and authorized targets to
                  configure what the Amazon QuickSight IAM Identity Center
                  application can access.</p> <p>This operation is only
                  supported for Amazon QuickSight accounts using IAM Identity
                  Center</p>
                tags:
                  - Update
                  - Identity
                  - Propagation
                  - Configurations
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
            /accounts/{AwsAccountId}/namespaces/{Namespace}:
              GET:
                summary: DescribeNamespace
                description: <p>Describes the current namespace.</p>
                tags:
                  - Describe
                  - Namespaces
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
            /accounts/{AwsAccountId}/data-sets/{DataSetId}/refresh-schedules/{ScheduleId}:
              GET:
                summary: DescribeRefreshSchedule
                description: <p>Provides a summary of a refresh schedule.</p>
                tags:
                  - Describe
                  - Refresh
                  - Schedules
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
            /accounts/{AwsAccountId}/namespaces/{Namespace}/roles/{Role}/custom-permission:
              PUT:
                summary: UpdateRoleCustomPermission
                description: >-
                  <p>Updates the custom permissions that are associated with a
                  role.</p>
                tags:
                  - Update
                  - Roles
                  - Custom
                  - Permission
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
            /accounts/{AwsAccountId}/topics/{TopicId}:
              PUT:
                summary: UpdateTopic
                description: <p>Updates a topic.</p>
                tags:
                  - Update
                  - Topics
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
            /accounts/{AwsAccountId}/topics/{TopicId}/schedules/{DatasetId}:
              PUT:
                summary: UpdateTopicRefreshSchedule
                description: <p>Updates a topic refresh schedule.</p>
                tags:
                  - Update
                  - Topics
                  - Refresh
                  - Schedules
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
            /accounts/{AwsAccountId}/namespaces/{Namespace}/users/{UserName}:
              PUT:
                summary: UpdateUser
                description: <p>Updates an Amazon QuickSight user.</p>
                tags:
                  - Update
                  - Users
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
            /accounts/{AwsAccountId}/namespaces/{Namespace}/user-principals/{PrincipalId}:
              DELETE:
                summary: DeleteUserByPrincipalId
                description: <p>Deletes a user identified by its principal ID. </p>
                tags:
                  - Delete
                  - Users
                  - By
                  - Principals
                  - Identifiers
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
            /accounts/{AwsAccountId}/vpc-connections/{VPCConnectionId}:
              PUT:
                summary: UpdateVPCConnection
                description: <p>Updates a VPC connection.</p>
                tags:
                  - Update
                  - Connections
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
            /accounts/{AwsAccountId}/settings:
              PUT:
                summary: UpdateAccountSettings
                description: >-
                  <p>Updates the Amazon QuickSight settings in your Amazon Web
                  Services account.</p>
                tags:
                  - Update
                  - Account
                  - Settings
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
            /accounts/{AwsAccountId}/analyses/{AnalysisId}/definition:
              GET:
                summary: DescribeAnalysisDefinition
                description: >-
                  <p>Provides a detailed description of the definition of an
                  analysis.</p> <note> <p>If you do not need to know details
                  about the content of an Analysis, for instance if you are
                  trying to check the status of a recently created or updated
                  Analysis, use the <a
                  href="https://docs.aws.amazon.com/quicksight/latest/APIReference/API_DescribeAnalysis.html">
                  <code>DescribeAnalysis</code> </a> instead. </p> </note>
                tags:
                  - Describe
                  - Analysis
                  - Definitions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
            /accounts/{AwsAccountId}/analyses/{AnalysisId}/permissions:
              PUT:
                summary: UpdateAnalysisPermissions
                description: <p>Updates the read and write permissions for an analysis.</p>
                tags:
                  - Update
                  - Analysis
                  - Permissions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
            /accounts/{AwsAccountId}/asset-bundle-export-jobs/{AssetBundleExportJobId}:
              GET:
                summary: DescribeAssetBundleExportJob
                description: >-
                  <p>Describes an existing export job.</p> <p>Poll job
                  descriptions after a job starts to know the status of the job.
                  When a job succeeds, a URL is provided to download the
                  exported assets' data from. Download URLs are valid for five
                  minutes after they are generated. You can call the
                  <code>DescribeAssetBundleExportJob</code> API for a new
                  download URL as needed.</p> <p>Job descriptions are available
                  for 14 days after the job starts.</p>
                tags:
                  - Describe
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
            /accounts/{AwsAccountId}/asset-bundle-import-jobs/{AssetBundleImportJobId}:
              GET:
                summary: DescribeAssetBundleImportJob
                description: >-
                  <p>Describes an existing import job.</p> <p>Poll job
                  descriptions after starting a job to know when it has
                  succeeded or failed. Job descriptions are available for 14
                  days after job starts.</p>
                tags:
                  - Describe
                  - Assets
                  - Bundles
                  - Import
                  - Jobs
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
            /accounts/{AwsAccountId}/dashboards/{DashboardId}/definition:
              GET:
                summary: DescribeDashboardDefinition
                description: >-
                  <p>Provides a detailed description of the definition of a
                  dashboard.</p> <note> <p>If you do not need to know details
                  about the content of a dashboard, for instance if you are
                  trying to check the status of a recently created or updated
                  dashboard, use the <a
                  href="https://docs.aws.amazon.com/quicksight/latest/APIReference/API_DescribeDashboard.html">
                  <code>DescribeDashboard</code> </a> instead. </p> </note>
                tags:
                  - Describe
                  - Dashboard
                  - Definitions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
            /accounts/{AwsAccountId}/dashboards/{DashboardId}/permissions:
              PUT:
                summary: UpdateDashboardPermissions
                description: <p>Updates read and write permissions on a dashboard.</p>
                tags:
                  - Update
                  - Dashboard
                  - Permissions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
            /accounts/{AwsAccountId}/dashboards/{DashboardId}/snapshot-jobs/{SnapshotJobId}:
              GET:
                summary: DescribeDashboardSnapshotJob
                description: >-
                  <p>Describes an existing snapshot job.</p> <p>Poll job
                  descriptions after a job starts to know the status of the job.
                  For information on available status codes, see
                  <code>JobStatus</code>.</p>
                tags:
                  - Describe
                  - Dashboard
                  - Snapshots
                  - Jobs
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
            /accounts/{AwsAccountId}/dashboards/{DashboardId}/snapshot-jobs/{SnapshotJobId}/result:
              GET:
                summary: DescribeDashboardSnapshotJobResult
                description: >-
                  <p>Describes the result of an existing snapshot job that has
                  finished running.</p> <p>A finished snapshot job will return a
                  <code>COMPLETED</code> or <code>FAILED</code> status when you
                  poll the job with a <code>DescribeDashboardSnapshotJob</code>
                  API call.</p> <p>If the job has not finished running, this
                  operation returns a message that says <code>Dashboard Snapshot
                  Job with id &lt;SnapshotjobId&gt; has not reached a terminal
                  state.</code>.</p>
                tags:
                  - Describe
                  - Dashboard
                  - Snapshots
                  - Jobs
                  - Results
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
            /accounts/{AwsAccountId}/data-sets/{DataSetId}/permissions:
              POST:
                summary: UpdateDataSetPermissions
                description: >-
                  <p>Updates the permissions on a dataset.</p> <p>The
                  permissions resource is
                  <code>arn:aws:quicksight:region:aws-account-id:dataset/data-set-id</code>.</p>
                tags:
                  - Update
                  - Data
                  - Sets
                  - Permissions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
            /accounts/{AwsAccountId}/data-sources/{DataSourceId}/permissions:
              POST:
                summary: UpdateDataSourcePermissions
                description: <p>Updates the permissions to a data source.</p>
                tags:
                  - Update
                  - Data
                  - Source
                  - Permissions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
            /accounts/{AwsAccountId}/folders/{FolderId}/permissions:
              PUT:
                summary: UpdateFolderPermissions
                description: <p>Updates permissions of a folder.</p>
                tags:
                  - Update
                  - Folder
                  - Permissions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
            /accounts/{AwsAccountId}/folders/{FolderId}/resolved-permissions:
              GET:
                summary: DescribeFolderResolvedPermissions
                description: >-
                  <p>Describes the folder resolved permissions. Permissions
                  consists of both folder direct permissions and the inherited
                  permissions from the ancestor folders.</p>
                tags:
                  - Describe
                  - Folder
                  - Resolved
                  - Permissions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
            /accounts/{AwsAccountId}/namespaces/{Namespace}/iam-policy-assignments/{AssignmentName}:
              PUT:
                summary: UpdateIAMPolicyAssignment
                description: >-
                  <p>Updates an existing IAM policy assignment. This operation
                  updates only the optional parameter or parameters that are
                  specified in the request. This overwrites all of the users
                  included in <code>Identities</code>. </p>
                tags:
                  - Update
                  - Policies
                  - Assignment
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
            /accounts/{AwsAccountId}/ip-restriction:
              POST:
                summary: UpdateIpRestriction
                description: >-
                  <p>Updates the content and status of IP rules. To use this
                  operation, you must provide the entire map of rules. You can
                  use the <code>DescribeIpRestriction</code> operation to get
                  the current rule map.</p>
                tags:
                  - Update
                  - IP
                  - Restrictions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
            /accounts/{AwsAccountId}/templates/{TemplateId}/definition:
              GET:
                summary: DescribeTemplateDefinition
                description: >-
                  <p>Provides a detailed description of the definition of a
                  template.</p> <note> <p>If you do not need to know details
                  about the content of a template, for instance if you are
                  trying to check the status of a recently created or updated
                  template, use the <a
                  href="https://docs.aws.amazon.com/quicksight/latest/APIReference/API_DescribeTemplate.html">
                  <code>DescribeTemplate</code> </a> instead. </p> </note>
                tags:
                  - Describe
                  - Templates
                  - Definitions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
            /accounts/{AwsAccountId}/templates/{TemplateId}/permissions:
              PUT:
                summary: UpdateTemplatePermissions
                description: <p>Updates the resource permissions for a template.</p>
                tags:
                  - Update
                  - Templates
                  - Permissions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
            /accounts/{AwsAccountId}/themes/{ThemeId}/permissions:
              PUT:
                summary: UpdateThemePermissions
                description: >-
                  <p>Updates the resource permissions for a theme. Permissions
                  apply to the action to grant or revoke permissions on, for
                  example <code>"quicksight:DescribeTheme"</code>.</p> <p>Theme
                  permissions apply in groupings. Valid groupings include the
                  following for the three levels of permissions, which are user,
                  owner, or no permissions: </p> <ul> <li> <p>User</p> <ul> <li>
                  <p> <code>"quicksight:DescribeTheme"</code> </p> </li> <li>
                  <p> <code>"quicksight:DescribeThemeAlias"</code> </p> </li>
                  <li> <p> <code>"quicksight:ListThemeAliases"</code> </p> </li>
                  <li> <p> <code>"quicksight:ListThemeVersions"</code> </p>
                  </li> </ul> </li> <li> <p>Owner</p> <ul> <li> <p>
                  <code>"quicksight:DescribeTheme"</code> </p> </li> <li> <p>
                  <code>"quicksight:DescribeThemeAlias"</code> </p> </li> <li>
                  <p> <code>"quicksight:ListThemeAliases"</code> </p> </li> <li>
                  <p> <code>"quicksight:ListThemeVersions"</code> </p> </li>
                  <li> <p> <code>"quicksight:DeleteTheme"</code> </p> </li> <li>
                  <p> <code>"quicksight:UpdateTheme"</code> </p> </li> <li> <p>
                  <code>"quicksight:CreateThemeAlias"</code> </p> </li> <li> <p>
                  <code>"quicksight:DeleteThemeAlias"</code> </p> </li> <li> <p>
                  <code>"quicksight:UpdateThemeAlias"</code> </p> </li> <li> <p>
                  <code>"quicksight:UpdateThemePermissions"</code> </p> </li>
                  <li> <p> <code>"quicksight:DescribeThemePermissions"</code>
                  </p> </li> </ul> </li> <li> <p>To specify no permissions, omit
                  the permissions list.</p> </li> </ul>
                tags:
                  - Update
                  - Theme
                  - Permissions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
            /accounts/{AwsAccountId}/topics/{TopicId}/permissions:
              PUT:
                summary: UpdateTopicPermissions
                description: <p>Updates the permissions of a topic.</p>
                tags:
                  - Update
                  - Topics
                  - Permissions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
            /accounts/{AwsAccountId}/topics/{TopicId}/refresh/{RefreshId}:
              GET:
                summary: DescribeTopicRefresh
                description: <p>Describes the status of a topic refresh.</p>
                tags:
                  - Describe
                  - Topics
                  - Refresh
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
            /accounts/{AwsAccountId}/embed-url/anonymous-user:
              POST:
                summary: GenerateEmbedUrlForAnonymousUser
                description: >-
                  <p>Generates an embed URL that you can use to embed an Amazon
                  QuickSight dashboard or visual in your website, without having
                  to register any reader users. Before you use this action, make
                  sure that you have configured the dashboards and
                  permissions.</p> <p>The following rules apply to the generated
                  URL:</p> <ul> <li> <p>It contains a temporary bearer token. It
                  is valid for 5 minutes after it is generated. Once redeemed
                  within this period, it cannot be re-used again.</p> </li> <li>
                  <p>The URL validity period should not be confused with the
                  actual session lifetime that can be customized using the
                  <code> <a
                  href="https://docs.aws.amazon.com/quicksight/latest/APIReference/API_GenerateEmbedUrlForAnonymousUser.html#QS-GenerateEmbedUrlForAnonymousUser-request-SessionLifetimeInMinutes">SessionLifetimeInMinutes</a>
                  </code> parameter. The resulting user session is valid for 15
                  minutes (minimum) to 10 hours (maximum). The default session
                  duration is 10 hours.</p> </li> <li> <p>You are charged only
                  when the URL is used or there is interaction with Amazon
                  QuickSight.</p> </li> </ul> <p>For more information, see <a
                  href="https://docs.aws.amazon.com/quicksight/latest/user/embedded-analytics.html">Embedded
                  Analytics</a> in the <i>Amazon QuickSight User Guide</i>.</p>
                  <p>For more information about the high-level steps for
                  embedding and for an interactive demo of the ways you can
                  customize embedding, visit the <a
                  href="https://docs.aws.amazon.com/quicksight/latest/user/quicksight-dev-portal.html">Amazon
                  QuickSight Developer Portal</a>.</p>
                tags:
                  - Generate
                  - Embed
                  - URL
                  - For
                  - Anonymous
                  - Users
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
            /accounts/{AwsAccountId}/embed-url/registered-user:
              POST:
                summary: GenerateEmbedUrlForRegisteredUser
                description: >-
                  <p>Generates an embed URL that you can use to embed an Amazon
                  QuickSight experience in your website. This action can be used
                  for any type of user registered in an Amazon QuickSight
                  account. Before you use this action, make sure that you have
                  configured the relevant Amazon QuickSight resource and
                  permissions.</p> <p>The following rules apply to the generated
                  URL:</p> <ul> <li> <p>It contains a temporary bearer token. It
                  is valid for 5 minutes after it is generated. Once redeemed
                  within this period, it cannot be re-used again.</p> </li> <li>
                  <p>The URL validity period should not be confused with the
                  actual session lifetime that can be customized using the
                  <code> <a
                  href="https://docs.aws.amazon.com/quicksight/latest/APIReference/API_GenerateEmbedUrlForRegisteredUser.html#QS-GenerateEmbedUrlForRegisteredUser-request-SessionLifetimeInMinutes">SessionLifetimeInMinutes</a>
                  </code> parameter.</p> <p>The resulting user session is valid
                  for 15 minutes (minimum) to 10 hours (maximum). The default
                  session duration is 10 hours.</p> </li> <li> <p>You are
                  charged only when the URL is used or there is interaction with
                  Amazon QuickSight.</p> </li> </ul> <p>For more information,
                  see <a
                  href="https://docs.aws.amazon.com/quicksight/latest/user/embedded-analytics.html">Embedded
                  Analytics</a> in the <i>Amazon QuickSight User Guide</i>.</p>
                  <p>For more information about the high-level steps for
                  embedding and for an interactive demo of the ways you can
                  customize embedding, visit the <a
                  href="https://docs.aws.amazon.com/quicksight/latest/user/quicksight-dev-portal.html">Amazon
                  QuickSight Developer Portal</a>.</p>
                tags:
                  - Generate
                  - Embed
                  - URL
                  - For
                  - Registered
                  - Users
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
            /accounts/{AwsAccountId}/dashboards/{DashboardId}/embed-url:
              GET:
                summary: GetDashboardEmbedUrl
                description: >-
                  <p>Generates a temporary session URL and authorization
                  code(bearer token) that you can use to embed an Amazon
                  QuickSight read-only dashboard in your website or application.
                  Before you use this command, make sure that you have
                  configured the dashboards and permissions. </p> <p>Currently,
                  you can use <code>GetDashboardEmbedURL</code> only from the
                  server, not from the user's browser. The following rules apply
                  to the generated URL:</p> <ul> <li> <p>They must be used
                  together.</p> </li> <li> <p>They can be used one time
                  only.</p> </li> <li> <p>They are valid for 5 minutes after you
                  run this command.</p> </li> <li> <p>You are charged only when
                  the URL is used or there is interaction with Amazon
                  QuickSight.</p> </li> <li> <p>The resulting user session is
                  valid for 15 minutes (default) up to 10 hours (maximum). You
                  can use the optional <code>SessionLifetimeInMinutes</code>
                  parameter to customize session duration.</p> </li> </ul>
                  <p>For more information, see <a
                  href="https://docs.aws.amazon.com/quicksight/latest/user/embedded-analytics-deprecated.html">Embedding
                  Analytics Using GetDashboardEmbedUrl</a> in the <i>Amazon
                  QuickSight User Guide</i>.</p> <p>For more information about
                  the high-level steps for embedding and for an interactive demo
                  of the ways you can customize embedding, visit the <a
                  href="https://docs.aws.amazon.com/quicksight/latest/user/quicksight-dev-portal.html">Amazon
                  QuickSight Developer Portal</a>.</p>
                tags:
                  - Get
                  - Dashboard
                  - Embed
                  - URL
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
            /accounts/{AwsAccountId}/session-embed-url:
              GET:
                summary: GetSessionEmbedUrl
                description: >-
                  <p>Generates a session URL and authorization code that you can
                  use to embed the Amazon Amazon QuickSight console in your web
                  server code. Use <code>GetSessionEmbedUrl</code> where you
                  want to provide an authoring portal that allows users to
                  create data sources, datasets, analyses, and dashboards. The
                  users who access an embedded Amazon QuickSight console need
                  belong to the author or admin security cohort. If you want to
                  restrict permissions to some of these features, add a custom
                  permissions profile to the user with the <code> <a
                  href="https://docs.aws.amazon.com/quicksight/latest/APIReference/API_UpdateUser.html">UpdateUser</a>
                  </code> API operation. Use <code> <a
                  href="https://docs.aws.amazon.com/quicksight/latest/APIReference/API_RegisterUser.html">RegisterUser</a>
                  </code> API operation to add a new user with a custom
                  permission profile attached. For more information, see the
                  following sections in the <i>Amazon QuickSight User
                  Guide</i>:</p> <ul> <li> <p> <a
                  href="https://docs.aws.amazon.com/quicksight/latest/user/embedded-analytics.html">Embedding
                  Analytics</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/quicksight/latest/user/customizing-permissions-to-the-quicksight-console.html">Customizing
                  Access to the Amazon QuickSight Console</a> </p> </li> </ul>
                tags:
                  - Get
                  - Sessions
                  - Embed
                  - URL
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
            /accounts/{AwsAccountId}/analyses:
              GET:
                summary: ListAnalyses
                description: >-
                  <p>Lists Amazon QuickSight analyses that exist in the
                  specified Amazon Web Services account.</p>
                tags:
                  - Lists
                  - Analysis
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
            /accounts/{AwsAccountId}/asset-bundle-export-jobs:
              GET:
                summary: ListAssetBundleExportJobs
                description: >-
                  <p>Lists all asset bundle export jobs that have been taken
                  place in the last 14 days. Jobs created more than 14 days ago
                  are deleted forever and are not returned. If you are using the
                  same job ID for multiple jobs,
                  <code>ListAssetBundleExportJobs</code> only returns the most
                  recent job that uses the repeated job ID.</p>
                tags:
                  - Lists
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
            /accounts/{AwsAccountId}/asset-bundle-import-jobs:
              GET:
                summary: ListAssetBundleImportJobs
                description: >-
                  <p>Lists all asset bundle import jobs that have taken place in
                  the last 14 days. Jobs created more than 14 days ago are
                  deleted forever and are not returned. If you are using the
                  same job ID for multiple jobs,
                  <code>ListAssetBundleImportJobs</code> only returns the most
                  recent job that uses the repeated job ID.</p>
                tags:
                  - Lists
                  - Assets
                  - Bundles
                  - Import
                  - Jobs
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
            /accounts/{AwsAccountId}/dashboards/{DashboardId}/versions:
              GET:
                summary: ListDashboardVersions
                description: >-
                  <p>Lists all the versions of the dashboards in the Amazon
                  QuickSight subscription.</p>
                tags:
                  - Lists
                  - Dashboard
                  - Versions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
            /accounts/{AwsAccountId}/dashboards:
              GET:
                summary: ListDashboards
                description: <p>Lists dashboards in an Amazon Web Services account.</p>
                tags:
                  - Lists
                  - Dashboards
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
            /accounts/{AwsAccountId}/folders/{FolderId}/members:
              GET:
                summary: ListFolderMembers
                description: >-
                  <p>List all assets (<code>DASHBOARD</code>,
                  <code>ANALYSIS</code>, and <code>DATASET</code>) in a folder.
                  </p>
                tags:
                  - Lists
                  - Folder
                  - Members
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
            /accounts/{AwsAccountId}/folders:
              GET:
                summary: ListFolders
                description: <p>Lists all folders in an account.</p>
                tags:
                  - Lists
                  - Folders
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
            /accounts/{AwsAccountId}/namespaces/{Namespace}/groups/{GroupName}/members:
              GET:
                summary: ListGroupMemberships
                description: <p>Lists member users in a group.</p>
                tags:
                  - Lists
                  - Group
                  - Memberships
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
            /accounts/{AwsAccountId}/namespaces/{Namespace}/v2/iam-policy-assignments:
              GET:
                summary: ListIAMPolicyAssignments
                description: >-
                  <p>Lists the IAM policy assignments in the current Amazon
                  QuickSight account.</p>
                tags:
                  - Lists
                  - Policies
                  - Assignments
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
            /accounts/{AwsAccountId}/namespaces/{Namespace}/users/{UserName}/iam-policy-assignments:
              GET:
                summary: ListIAMPolicyAssignmentsForUser
                description: >-
                  <p>Lists all of the IAM policy assignments, including the
                  Amazon Resource Names (ARNs), for the IAM policies assigned to
                  the specified user and group, or groups that the user belongs
                  to.</p>
                tags:
                  - Lists
                  - Policies
                  - Assignments
                  - For
                  - Users
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
            /accounts/{AwsAccountId}/identity-propagation-config:
              GET:
                summary: ListIdentityPropagationConfigs
                description: >-
                  <p>Lists all services and authorized targets that the Amazon
                  QuickSight IAM Identity Center application can access.</p>
                  <p>This operation is only supported for Amazon QuickSight
                  accounts that use IAM Identity Center.</p>
                tags:
                  - Lists
                  - Identity
                  - Propagation
                  - Configurations
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
            /accounts/{AwsAccountId}/data-sets/{DataSetId}/ingestions:
              GET:
                summary: ListIngestions
                description: <p>Lists the history of SPICE ingestions for a dataset.</p>
                tags:
                  - Lists
                  - Ingestions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
            /accounts/{AwsAccountId}/namespaces:
              GET:
                summary: ListNamespaces
                description: >-
                  <p>Lists the namespaces for the specified Amazon Web Services
                  account. This operation doesn't list deleted namespaces.</p>
                tags:
                  - Lists
                  - Namespaces
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
            /accounts/{AwsAccountId}/namespaces/{Namespace}/roles/{Role}/members:
              GET:
                summary: ListRoleMemberships
                description: <p>Lists all groups that are associated with a role.</p>
                tags:
                  - Lists
                  - Roles
                  - Memberships
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
            /resources/{ResourceArn}/tags:
              DELETE:
                summary: UntagResource
                description: <p>Removes a tag or tags from a resource.</p>
                tags:
                  - Untag
                  - Resources
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
            /accounts/{AwsAccountId}/templates/{TemplateId}/aliases:
              GET:
                summary: ListTemplateAliases
                description: <p>Lists all the aliases of a template.</p>
                tags:
                  - Lists
                  - Templates
                  - Aliases
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
            /accounts/{AwsAccountId}/templates/{TemplateId}/versions:
              GET:
                summary: ListTemplateVersions
                description: >-
                  <p>Lists all the versions of the templates in the current
                  Amazon QuickSight account.</p>
                tags:
                  - Lists
                  - Templates
                  - Versions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
            /accounts/{AwsAccountId}/templates:
              GET:
                summary: ListTemplates
                description: >-
                  <p>Lists all the templates in the current Amazon QuickSight
                  account.</p>
                tags:
                  - Lists
                  - Templates
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
            /accounts/{AwsAccountId}/themes/{ThemeId}/aliases:
              GET:
                summary: ListThemeAliases
                description: <p>Lists all the aliases of a theme.</p>
                tags:
                  - Lists
                  - Theme
                  - Aliases
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
            /accounts/{AwsAccountId}/themes/{ThemeId}/versions:
              GET:
                summary: ListThemeVersions
                description: >-
                  <p>Lists all the versions of the themes in the current Amazon
                  Web Services account.</p>
                tags:
                  - Lists
                  - Theme
                  - Versions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
            /accounts/{AwsAccountId}/themes:
              GET:
                summary: ListThemes
                description: >-
                  <p>Lists all the themes in the current Amazon Web Services
                  account.</p>
                tags:
                  - Lists
                  - Themes
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
            /accounts/{AwsAccountId}/namespaces/{Namespace}/users/{UserName}/groups:
              GET:
                summary: ListUserGroups
                description: >-
                  <p>Lists the Amazon QuickSight groups that an Amazon
                  QuickSight user is a member of.</p>
                tags:
                  - Lists
                  - Users
                  - Groups
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
            /accounts/{AwsAccountId}/namespaces/{Namespace}/users:
              POST:
                summary: RegisterUser
                description: >-
                  <p>Creates an Amazon QuickSight user whose identity is
                  associated with the Identity and Access Management (IAM)
                  identity or role specified in the request. When you register a
                  new user from the Amazon QuickSight API, Amazon QuickSight
                  generates a registration URL. The user accesses this
                  registration URL to create their account. Amazon QuickSight
                  doesn't send a registration email to users who are registered
                  from the Amazon QuickSight API. If you want new users to
                  receive a registration email, then add those users in the
                  Amazon QuickSight console. For more information on registering
                  a new user in the Amazon QuickSight console, see <a
                  href="https://docs.aws.amazon.com/quicksight/latest/user/managing-users.html#inviting-users">
                  Inviting users to access Amazon QuickSight</a>.</p>
                tags:
                  - Register
                  - Users
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
            /accounts/{AwsAccountId}/restore/analyses/{AnalysisId}:
              POST:
                summary: RestoreAnalysis
                description: <p>Restores an analysis.</p>
                tags:
                  - Restore
                  - Analysis
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
            /accounts/{AwsAccountId}/search/analyses:
              POST:
                summary: SearchAnalyses
                description: >-
                  <p>Searches for analyses that belong to the user specified in
                  the filter.</p> <note> <p>This operation is eventually
                  consistent. The results are best effort and may not reflect
                  very recent updates and changes.</p> </note>
                tags:
                  - Search
                  - Analysis
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
            /accounts/{AwsAccountId}/search/dashboards:
              POST:
                summary: SearchDashboards
                description: >-
                  <p>Searches for dashboards that belong to a user. </p> <note>
                  <p>This operation is eventually consistent. The results are
                  best effort and may not reflect very recent updates and
                  changes.</p> </note>
                tags:
                  - Search
                  - Dashboards
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
            /accounts/{AwsAccountId}/search/data-sets:
              POST:
                summary: SearchDataSets
                description: >-
                  <p>Use the <code>SearchDataSets</code> operation to search for
                  datasets that belong to an account.</p>
                tags:
                  - Search
                  - Data
                  - Sets
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
            /accounts/{AwsAccountId}/search/data-sources:
              POST:
                summary: SearchDataSources
                description: >-
                  <p>Use the <code>SearchDataSources</code> operation to search
                  for data sources that belong to an account.</p>
                tags:
                  - Search
                  - Data
                  - Sources
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
            /accounts/{AwsAccountId}/search/folders:
              POST:
                summary: SearchFolders
                description: <p>Searches the subfolders in a folder.</p>
                tags:
                  - Search
                  - Folders
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
            /accounts/{AwsAccountId}/namespaces/{Namespace}/groups-search:
              POST:
                summary: SearchGroups
                description: >-
                  <p>Use the <code>SearchGroups</code> operation to search
                  groups in a specified Amazon QuickSight namespace using the
                  supplied filters.</p>
                tags:
                  - Search
                  - Groups
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
            /accounts/{AwsAccountId}/asset-bundle-export-jobs/export:
              POST:
                summary: StartAssetBundleExportJob
                description: >-
                  <p>Starts an Asset Bundle export job.</p> <p>An Asset Bundle
                  export job exports specified Amazon QuickSight assets. You can
                  also choose to export any asset dependencies in the same job.
                  Export jobs run asynchronously and can be polled with a
                  <code>DescribeAssetBundleExportJob</code> API call. When a job
                  is successfully completed, a download URL that contains the
                  exported assets is returned. The URL is valid for 5 minutes
                  and can be refreshed with a
                  <code>DescribeAssetBundleExportJob</code> API call. Each
                  Amazon QuickSight account can run up to 5 export jobs
                  concurrently.</p> <p>The API caller must have the necessary
                  permissions in their IAM role to access each resource before
                  the resources can be exported.</p>
                tags:
                  - Start
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
            /accounts/{AwsAccountId}/asset-bundle-import-jobs/import:
              POST:
                summary: StartAssetBundleImportJob
                description: >-
                  <p>Starts an Asset Bundle import job.</p> <p>An Asset Bundle
                  import job imports specified Amazon QuickSight assets into an
                  Amazon QuickSight account. You can also choose to import a
                  naming prefix and specified configuration overrides. The
                  assets that are contained in the bundle file that you provide
                  are used to create or update a new or existing asset in your
                  Amazon QuickSight account. Each Amazon QuickSight account can
                  run up to 5 import jobs concurrently.</p> <p>The API caller
                  must have the necessary <code>"create"</code>,
                  <code>"describe"</code>, and <code>"update"</code> permissions
                  in their IAM role to access each resource type that is
                  contained in the bundle file before the resources can be
                  imported.</p>
                tags:
                  - Start
                  - Assets
                  - Bundles
                  - Import
                  - Jobs
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
            /accounts/{AwsAccountId}/dashboards/{DashboardId}/snapshot-jobs:
              POST:
                summary: StartDashboardSnapshotJob
                description: >-
                  <p>Starts an asynchronous job that generates a dashboard
                  snapshot. You can request one of the following format
                  configurations per API call.</p> <ul> <li> <p>1 paginated
                  PDF</p> </li> <li> <p>1 Excel workbook</p> </li> <li> <p>5
                  CSVs</p> </li> </ul> <p>Poll job descriptions with a
                  <code>DescribeDashboardSnapshotJob</code> API call. Once the
                  job succeeds, use the
                  <code>DescribeDashboardSnapshotJobResult</code> API to obtain
                  the download URIs that the job generates.</p>
                tags:
                  - Start
                  - Dashboard
                  - Snapshots
                  - Jobs
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
            /accounts/{AwsAccountId}/dashboards/{DashboardId}/linked-entities:
              PUT:
                summary: UpdateDashboardLinks
                description: <p>Updates the linked analyses on a dashboard.</p>
                tags:
                  - Update
                  - Dashboard
                  - Links
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
                  - Linked
                  - Entities
            /accounts/{AwsAccountId}/dashboards/{DashboardId}/versions/{VersionNumber}:
              PUT:
                summary: UpdateDashboardPublishedVersion
                description: <p>Updates the published version of a dashboard.</p>
                tags:
                  - Update
                  - Dashboard
                  - Published
                  - Versions
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
                  - Linked
                  - Entities
                  - Versions
                  - Numbers
            /accounts/{AwsAccountId}/public-sharing-settings:
              PUT:
                summary: UpdatePublicSharingSettings
                description: >-
                  <p>Use the <code>UpdatePublicSharingSettings</code> operation
                  to turn on or turn off the public sharing settings of an
                  Amazon QuickSight dashboard.</p> <p>To use this operation,
                  turn on session capacity pricing for your Amazon QuickSight
                  account.</p> <p>Before you can turn on public sharing on your
                  account, make sure to give public sharing permissions to an
                  administrative user in the Identity and Access Management
                  (IAM) console. For more information on using IAM with Amazon
                  QuickSight, see <a
                  href="https://docs.aws.amazon.com/quicksight/latest/user/security_iam_service-with-iam.html">Using
                  Amazon QuickSight with IAM</a> in the <i>Amazon QuickSight
                  User Guid
                tags:
                  - Update
                  - Public
                  - Sharing
                  - Settings
                  - Aws
                  - Account
                  - Identifiers
                  - Data
                  - Sets
                  - Sets
                  - Ingestions
                  - Ingestion
                  - Customizations
                  - Analysis
                  - Analysis
                  - Dashboards
                  - Dashboard
                  - Sources
                  - Folders
                  - Folder
                  - Members
                  - Members
                  - Types
                  - Namespaces
                  - Namespaces
                  - Groups
                  - Group
                  - Names
                  - IAM
                  - Policies
                  - Assignments
                  - Refresh
                  - Schedules
                  - Roles
                  - Roles
                  - Templates
                  - Templates
                  - Aliases
                  - Alias
                  - Themes
                  - Theme
                  - Topics
                  - Topics
                  - VPC
                  - Connections
                  - Properties
                  - Source
                  - Assignment
                  - Identity
                  - Propagation
                  - Configurations
                  - Services
                  - Schedules
                  - Custom
                  - Permission
                  - Datasets
                  - Users
                  - Users
                  - Principals
                  - Principals
                  - Connections
                  - Settings
                  - Definitions
                  - Permissions
                  - Assets
                  - Bundles
                  - Export
                  - Jobs
                  - Jobs
                  - Import
                  - Snapshots
                  - Results
                  - Resolved
                  - IP
                  - Restrictions
                  - Embed
                  - URL
                  - Anonymous
                  - Registered
                  - Sessions
                  - Versions
                  - V2
                  - Resources
                  - ARN
                  - Tags
                  - Restore
                  - Search
                  - Linked
                  - Entities
                  - Versions
                  - Numbers
                  - Public
                  - Shari
    overlays:
      - type: APIs.io Search
        url: overlays/quicksight-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/quicksight-openapi-api-evangelist-ratings.yml
    aid: amazon-web-services:quicksight
  - name: runtime.lex.v2
    description: >-
      <p>This section contains documentation for the Amazon Lex V2 Runtime V2
      API operations.</p>
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://example.com
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://example.com
      - type: OpenAPI
        data:
          openapi: 3.1.0
          info:
            title: runtime.lex.v2
          paths:
            /bots/{botId}/botAliases/{botAliasId}/botLocales/{localeId}/sessions/{sessionId}:
              POST:
                summary: PutSession
                description: >-
                  <p>Creates a new session or modifies an existing session with
                  an Amazon Lex V2 bot. Use this operation to enable your
                  application to set the state of the bot.</p>
                tags:
                  - Put
                  - Sessions
                  - Identifiers
                  - Bot
                  - Aliases
                  - Alias
                  - Locales
                  - Locales
                  - Sessions
                  - Sessions
            /bots/{botId}/botAliases/{botAliasId}/botLocales/{localeId}/sessions/{sessionId}/text:
              POST:
                summary: RecognizeText
                description: >-
                  <p>Sends user input to Amazon Lex V2. Client applications use
                  this API to send requests to Amazon Lex V2 at runtime. Amazon
                  Lex V2 then interprets the user input using the machine
                  learning model that it build for the bot.</p> <p>In response,
                  Amazon Lex V2 returns the next message to convey to the user
                  and an optional response card to display.</p> <p>If the
                  optional post-fulfillment response is specified, the messages
                  are returned as follows. For more information, see <a
                  href="https://docs.aws.amazon.com/lexv2/latest/dg/API_PostFulfillmentStatusSpecification.html">PostFulfillmentStatusSpecification</a>.</p>
                  <ul> <li> <p> <b>Success message</b> - Returned if the Lambda
                  function completes successfully and the intent state is
                  fulfilled or ready fulfillment if the message is present.</p>
                  </li> <li> <p> <b>Failed message</b> - The failed message is
                  returned if the Lambda function throws an exception or if the
                  Lambda function returns a failed intent state without a
                  message.</p> </li> <li> <p> <b>Timeout message</b> - If you
                  don't configure a timeout message and a timeout, and the
                  Lambda function doesn't return within 30 seconds, the timeout
                  message is returned. If you configure a timeout, the timeout
                  message is returned when the period times out. </p> </li>
                  </ul> <p>For more information, see <a
                  href="https://docs.aws.amazon.com/lexv2/latest/dg/streaming-progress.html#progress-complete.html">Completion
                  message</a>.</p>
                tags:
                  - Recognize
                  - Text
                  - Identifiers
                  - Bot
                  - Aliases
                  - Alias
                  - Locales
                  - Locales
                  - Sessions
                  - Sessions
                  - Text
            /bots/{botId}/botAliases/{botAliasId}/botLocales/{localeId}/sessions/{sessionId}/utterance:
              POST:
                summary: RecognizeUtterance
                description: >-
                  <p>Sends user input to Amazon Lex V2. You can send text or
                  speech. Clients use this API to send text and audio requests
                  to Amazon Lex V2 at runtime. Amazon Lex V2 interprets the user
                  input using the machine learning model built for the bot.</p>
                  <p>The following request fields must be compressed with gzip
                  and then base64 encoded before you send them to Amazon Lex V2.
                  </p> <ul> <li> <p>requestAttributes</p> </li> <li>
                  <p>sessionState</p> </li> </ul> <p>The following response
                  fields are compressed using gzip and then base64 encoded by
                  Amazon Lex V2. Before you can use these fields, you must
                  decode and decompress them. </p> <ul> <li>
                  <p>inputTranscript</p> </li> <li> <p>interpretations</p> </li>
                  <li> <p>messages</p> </li> <li> <p>requestAttributes</p> </li>
                  <li> <p>sessionState</p> </li> </ul> <p>The example contains a
                  Java application that compresses and encodes a Java object to
                  send to Amazon Lex V2, and a second that decodes and
                  decompresses a response from Amazon Lex V2.</p> <p>If the
                  optional post-fulfillment response is specified, the messages
                  are returned as follows. For more information, see <a
                  href="https://docs.aws.amazon.com/lexv2/latest/dg/API_PostFulfillmentStatusSpecification.html">PostFulfillmentStatusSpecification</a>.</p>
                  <ul> <li> <p> <b>Success message</b> - Returned if the Lambda
                  function completes successfully and the intent state is
                  fulfilled or ready fulfillment if the message is present.</p>
                  </li> <li> <p> <b>Failed message</b> - The failed message is
                  returned if the Lambda function throws an exception or if the
                  Lambda function returns a failed intent state without a
                  message.</p> </li> <li> <p> <b>Timeout message</b> - If you
                  don't configure a timeout message and a timeout, and the
                  Lambda function doesn't return within 30 seconds, the timeout
                  message is returned. If you configure a timeout, the timeout
                  message is returned when the period times out. </p> </li>
                  </ul> <p>For more information, see <a
                  href="https://docs.aws.amazon.com/lexv2/latest/dg/streaming-progress.html#progress-complete.html">Completion
                  message</a>.</p>
                tags:
                  - Recognize
                  - Utterances
                  - Identifiers
                  - Bot
                  - Aliases
                  - Alias
                  - Locales
                  - Locales
                  - Sessions
                  - Sessions
                  - Text
                  - Utterances
            /bots/{botId}/botAliases/{botAliasId}/botLocales/{localeId}/sessions/{sessionId}/conversation:
              POST:
                summary: StartConversation
                description: >-
                  <p>Starts an HTTP/2 bidirectional event stream that enables
                  you to send audio, text, or DTMF input in real time. After
                  your application starts a conversation, users send input to
                  Amazon Lex V2 as a stream of events. Amazon Lex V2 processes
                  the incoming events and responds with streaming text or audio
                  events. </p> <p>Audio input must be in the following format:
                  <code>audio/lpcm sample-rate=8000 sample-size-bits=16
                  channel-count=1; is-big-endian=false</code>.</p> <p>If the
                  optional post-fulfillment response is specified, the messages
                  are returned as follows. For more information, see <a
                  href="https://docs.aws.amazon.com/lexv2/latest/dg/API_PostFulfillmentStatusSpecification.html">PostFulfillmentStatusSpecification</a>.</p>
                  <ul> <li> <p> <b>Success message</b> - Returned if the Lambda
                  function completes successfully and the intent state is
                  fulfilled or ready fulfillment if the message is present.</p>
                  </li> <li> <p> <b>Failed message</b> - The failed message is
                  returned if the Lambda function throws an exception or if the
                  Lambda function returns a failed intent state without a
                  message.</p> </li> <li> <p> <b>Timeout message</b> - If you
                  don't configure a timeout message and a timeout, and the
                  Lambda function doesn't return within 30 seconds, the timeout
                  message is returned. If you configure a timeout, the timeout
                  message is returned when the period times out. </p> </li>
                  </ul> <p>For more information, see <a
                  href="https://docs.aws.amazon.com/lexv2/latest/dg/streaming-progress.html#progress-complete.html">Completion
                  message</a>.</p> <p>If the optional update message is
                  configured, it is played at the specified frequency while the
                  Lambda function is running and the update message state is
                  active. If the fulfillment update message is not active, the
                  Lambda function runs with a 30 second timeout. </p> <p>For
                  more information, see <a
                  href="https://docs.aws.amazon.com/lexv2/latest/dg/streaming-progress.html#progress-update.html">Update
                  message </a> </p> <p>The <code>StartConversation</code>
                  operation is supported only in the following SDKs: </p> <ul>
                  <li> <p> <a
                  href="https://docs.aws.amazon.com/goto/SdkForCpp/runtime.lex.v2-2020-08-07/StartConversation">AWS
                  SDK for C++</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/goto/SdkForJavaV2/runtime.lex.v2-2020-08-07/StartConversation">AWS
                  SDK for Java V2</a> </p> </li> <li> <p> <a
                  href="https://docs.aws.amazon.com/goto/SdkForRubyV3/runtime.lex.v2-2020-08-07/StartConversation">AWS
                  SDK for Ruby V3</a> </p> <
                tags:
                  - Start
                  - Conversations
                  - Identifiers
                  - Bot
                  - Aliases
                  - Alias
                  - Locales
                  - Locales
                  - Sessions
                  - Sessions
                  - Text
                  - Utterances
                  - Conversations
    overlays:
      - type: APIs.io Search
        url: overlays/runtimelexv2-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/runtimelexv2-openapi-api-evangelist-ratings.yml
    aid: amazon-web-services:runtimelexv2
  - aid: box:box-users-api
    name: Box Users API
    description: Needs a description
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.box.com/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.box.com/
      - type: OpenAPI
        data:
          openapi: 3.1.0
          info:
            title: Box Users API
          paths:
            /users:
              get:
                summary: List enterprise users
                tags:
                  - List
                  - Enterprise
                  - Users
                  - Users
                description: >-
                  Returns a list of all users for the Enterprise along with
                  their `user_id`,

                  `public_name`, and `login`.


                  The application and the authenticated user need to

                  have the permission to look up users in the entire

                  enterprise.
              post:
                summary: Create user
                tags:
                  - Create
                  - User
                  - Users
                description: |-
                  Creates a new managed user in an enterprise. This endpoint
                  is only available to users and applications with the right
                  admin permissions.
            /users/me:
              get:
                summary: Get current user
                tags:
                  - Get
                  - Current
                  - User
                  - Users
                  - Me
                description: >-
                  Retrieves information about the user who is currently
                  authenticated.


                  In the case of a client-side authenticated OAuth 2.0
                  application

                  this will be the user who authorized the app.


                  In the case of a JWT, server-side authenticated application

                  this will be the service account that belongs to the
                  application

                  by default.


                  Use the `As-User` header to change who this API call is made
                  on behalf of.
            /users/terminate_sessions:
              post:
                summary: Create jobs to terminate users session
                tags:
                  - Create
                  - Jobs
                  - To
                  - Terminate
                  - Users
                  - Session
                  - Users
                  - Me
                  - Terminate_sessions
                description: |-
                  Validates the roles and permissions of the user,
                  and creates asynchronous jobs
                  to terminate the user's sessions.
                  Returns the status for the POST request.
            /users/{user_id}:
              get:
                summary: Get user
                tags:
                  - Get
                  - User
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                description: |-
                  Retrieves information about a user in the enterprise.

                  The application and the authenticated user need to
                  have the permission to look up users in the entire
                  enterprise.

                  This endpoint also returns a limited set of information
                  for external users who are collaborated on content
                  owned by the enterprise for authenticated users with the
                  right scopes. In this case, disallowed fields will return
                  null instead.
              put:
                summary: Update user
                tags:
                  - Update
                  - User
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                description: |-
                  Updates a managed or app user in an enterprise. This endpoint
                  is only available to users and applications with the right
                  admin permissions.
              delete:
                summary: Delete user
                tags:
                  - Delete
                  - User
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                description: |-
                  Deletes a user. By default this will fail if the user
                  still owns any content. Move their owned content first
                  before proceeding, or use the `force` field to delete
                  the user and their files.
            /users/{user_id}/avatar:
              get:
                summary: Get user avatar
                tags:
                  - Get
                  - User
                  - Avatar
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                  - Avatar
                description: Retrieves an image of a the user's avatar.
              post:
                summary: Add or update user avatar
                tags:
                  - Add
                  - Or
                  - Update
                  - User
                  - Avatar
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                  - Avatar
                description: Adds or updates a user avatar.
              delete:
                summary: Delete user avatar
                tags:
                  - Delete
                  - User
                  - Avatar
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                  - Avatar
                description: |-
                  Removes an existing user avatar.
                  You cannot reverse this operation.
            /users/{user_id}/folders/0:
              put:
                summary: Transfer owned folders
                tags:
                  - Transfer
                  - Owned
                  - Folders
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                  - Avatar
                  - Folders
                description: >-
                  Move all of the items (files, folders and workflows) owned by
                  a user into

                  another user's account


                  Only the root folder (`0`) can be transferred.


                  Folders can only be moved across users by users with
                  administrative

                  permissions.


                  All existing shared links and folder-level collaborations are
                  transferred

                  during the operation. Please note that while collaborations at
                  the individual

                  file-level are transferred during the operation, the
                  collaborations are

                  deleted when the original user is deleted.


                  This call will be performed synchronously which might lead to
                  a slow response

                  when the source user has a large number of items in all of its
                  folders.


                  If the destination path has a metadata cascade policy attached
                  to any of

                  the parent folders, a metadata cascade operation will be
                  kicked off

                  asynchronously.


                  There is currently no way to check for when this operation is
                  finished.


                  The destination folder's name will be in the format `{User}'s
                  Files and

                  Folders`, where `{User}` is the display name of the user.


                  To make this API call your application will need to have the
                  "Read and write

                  all files and folders stored in Box" scope enabled.


                  Please make sure the destination user has access to `Relay` or
                  `Relay Lite`,

                  and has access to the files and folders involved in the
                  workflows being

                  transferred.


                  Admins will receive an email when the operation is completed.
            /users/{user_id}/email_aliases:
              get:
                summary: List user's email aliases
                tags:
                  - List
                  - User's
                  - Email
                  - Aliases
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                  - Avatar
                  - Folders
                  - Email_aliases
                description: |-
                  Retrieves all email aliases for a user. The collection
                  does not include the primary login for the user.
              post:
                summary: Create email alias
                tags:
                  - Create
                  - Email
                  - Alias
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                  - Avatar
                  - Folders
                  - Email_aliases
                description: Adds a new email alias to a user account..
            /users/{user_id}/email_aliases/{email_alias_id}:
              delete:
                summary: Remove email alias
                tags:
                  - Remove
                  - Email
                  - Alias
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                  - Avatar
                  - Folders
                  - Email_aliases
                  - Email_alias_id
                description: Removes an email alias from a user.
            /users/{user_id}/memberships:
              get:
                summary: List user's groups
                tags:
                  - List
                  - User's
                  - Groups
                  - Users
                  - Me
                  - Terminate_sessions
                  - User_id
                  - Avatar
                  - Folders
                  - Email_aliases
                  - Email_alias_id
                  - Memberships
                description: |-
                  Retrieves all the groups for a user. Only members of this
                  group or users with admin-level permissions will be able to
                  u
    overlays:
      - type: APIs.io Search
        url: overlays/users-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/users-openapi-api-evangelist-ratings.yml
maintainers:
  - FN: API Evangelist
    email: info@apievangelist.com
---