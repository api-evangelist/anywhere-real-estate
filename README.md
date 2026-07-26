# Anywhere Real Estate (anywhere-real-estate)

Anywhere Real Estate Inc. (formerly Realogy Holdings Corp., NYSE: HOUS) is one of the largest residential real estate services companies in the United States, headquartered at 175 Park Avenue, Madison, New Jersey. It franchises and operates Better Homes and Gardens Real Estate, CENTURY 21, Coldwell Banker, Coldwell Banker Commercial, Corcoran, ERA and Sotheby's International Realty; runs the Anywhere Advisors brokerage, the Anywhere Integrated Services title and settlement business, the Anywhere Leads referral network and Cartus relocation. Its own home page states that as of January 9, 2026 Anywhere Real Estate and Compass came together as Compass International Holdings. Unusually for a brokerage, Anywhere operates a genuine Apigee-backed developer portal at developers.anywhere.re that publicly lists 23 documented API products spanning MLS and listing data, marketing syndication, transactions, back office, leads, agent recruiting, earnest money, title settlement, relocation and user access. Anywhere is a RESO consumer rather than a RESO certificant: its MLS Data Service returns listings in "canonical RESO format" and its Master Data product uses RESO name space convention, but Anywhere appears nowhere in the RESO Certification Status directory. Access is licensed, not open — every specification, Postman collection and SDK page redirects anonymous visitors to login, and both sandbox and production access require an Anywhere review of up to two business days under a binding API Terms of Use and License Agreement.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/anywhere-real-estate/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/anywhere-real-estate/refs/heads/main/apis.yml)

## Tags

- Real Estate
- United States
- Property Listings
- MLS
- RESO
- Brokerage
- Franchising
- PropTech
- Title
- Escrow
- Relocation
- Leads
- Transactions

## Timestamps

- **Created:** 2026-07-26
- **Modified:** 2026-07-26

## Access

- **Pricing:** enterprise
- **Onboarding:** approval
- **Publicly callable:** no
- **Label:** Enterprise · Approval required (portal signup, then Anywhere approval for sandbox and again for production)

## APIs

### Anywhere MLS Data Service API

Endpoints for MLS listings data assembled by Anywhere's MLS Data Platform (MDP), which downloads, processes and enriches listings from multiple MLS sources. Returns listings in canonical RESO format enriched with media and open house data, real-time MLS events, MLS display rules and active/sold listing statistics. Component APIs named on the product page are mls, mls-display-rules, mls-listings-stats, mlsagent, mlsagentroster, mlsofficeroster and listingsdirect-event-processing.

- **Human URL:** [https://developers.anywhere.re/api-product/mls-data-service/summary](https://developers.anywhere.re/api-product/mls-data-service/summary)

#### Tags

- Real Estate
- Listings
- MLS
- RESO
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/mls-data-service/summary)
- [APIReference](https://developers.anywhere.re/api-product/mls-data-service/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Master Data (MDM) API

A bundle of APIs representing clean, curated master data for Agent, Office, Company, Staff and Listings entities, plus shared address and property services. Data is normalized from Anywhere and non-Anywhere (MLS) sources. The Listings APIs provide listings, images and open house data using Real Estate Standards Organization (RESO) name space convention.

- **Human URL:** [https://developers.anywhere.re/api-product/master-data-services/summary](https://developers.anywhere.re/api-product/master-data-services/summary)

#### Tags

- Real Estate
- Listings
- MLS
- RESO
- Master Data
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/master-data-services/summary)
- [APIReference](https://developers.anywhere.re/api-product/master-data-services/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Listing Syndication API

Synchronize marketing data for all Anywhere franchise brands and the brokerage group to an external system. Marketing data includes Company, Office, Agent, Team, Listings and New Development information, read in real time for syndicating marketing information to affiliate websites and generating listing and agent advertising.

- **Human URL:** [https://developers.anywhere.re/api-product/listing-syndication/summary](https://developers.anywhere.re/api-product/listing-syndication/summary)

#### Tags

- Real Estate
- Listings
- Syndication
- Marketing
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/listing-syndication/summary)
- [APIReference](https://developers.anywhere.re/api-product/listing-syndication/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Dynamic Search API

Real-time search over Anywhere listing details for applications that do not maintain a local data store. Documented as short-response-time and typically used for mobile applications.

- **Human URL:** [https://developers.anywhere.re/api-product/dynamic-search/summary](https://developers.anywhere.re/api-product/dynamic-search/summary)

#### Tags

- Real Estate
- Listings
- Search
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/dynamic-search/summary)
- [APIReference](https://developers.anywhere.re/api-product/dynamic-search/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Listing Extensions API

A bundle of APIs for listings submitted through external and internal products, enhancing property listings with SMS Property ID, RealVitalize ID and Dash attribute management.

- **Human URL:** [https://developers.anywhere.re/api-product/listingextensions/summary](https://developers.anywhere.re/api-product/listingextensions/summary)

#### Tags

- Real Estate
- Listings
- Franchise

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/listingextensions/summary)
- [APIReference](https://developers.anywhere.re/api-product/listingextensions/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Listings Promotions API

Synchronize promotion data from Anywhere, covering channels, publication lists in each channel, nominated listings and listings flagged in each publication list. Used to create and update channels and publication lists and to flag nominated listings to publication channels.

- **Human URL:** [https://developers.anywhere.re/api-product/property-promotions/summary](https://developers.anywhere.re/api-product/property-promotions/summary)

#### Tags

- Real Estate
- Listings
- Promotions
- Marketing
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/property-promotions/summary)
- [APIReference](https://developers.anywhere.re/api-product/property-promotions/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Listing Metric API

Listing management metric information for Anywhere franchise brands, including video views, virtual tour views and listing views, available as soon as data is received from Anywhere source systems.

- **Human URL:** [https://developers.anywhere.re/api-product/realogy-listings-metrics/summary](https://developers.anywhere.re/api-product/realogy-listings-metrics/summary)

#### Tags

- Real Estate
- Listings
- Analytics
- Metrics
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/realogy-listings-metrics/summary)
- [APIReference](https://developers.anywhere.re/api-product/realogy-listings-metrics/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Marketing - Franchise API

Synchronize marketing data for all Anywhere franchise brands and brokerages, including Corporate Staff, Company, Office, Agent, Team, Listings and New Developments information.

- **Human URL:** [https://developers.anywhere.re/api-product/broker-agent-tools/summary](https://developers.anywhere.re/api-product/broker-agent-tools/summary)

#### Tags

- Real Estate
- Marketing
- Listings
- Back Office
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/broker-agent-tools/summary)
- [APIReference](https://developers.anywhere.re/api-product/broker-agent-tools/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Marketing and Transactions API

Synchronize Anywhere marketing data together with franchise brokerage production (transaction) details. Marketing detail includes Corporate Staff, Company, Office, Agent, Team, Listings and New Development information.

- **Human URL:** [https://developers.anywhere.re/api-product/broker-agent-tools-plus/summary](https://developers.anywhere.re/api-product/broker-agent-tools-plus/summary)

#### Tags

- Real Estate
- Marketing
- Transactions
- Listings
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/broker-agent-tools-plus/summary)
- [APIReference](https://developers.anywhere.re/api-product/broker-agent-tools-plus/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Transactions - Franchise API

Synchronize brokerage production (transaction) data from Anywhere, including Sale and Other Income transactions and the associated buyer and seller information.

- **Human URL:** [https://developers.anywhere.re/api-product/realogy-broker-production/summary](https://developers.anywhere.re/api-product/realogy-broker-production/summary)

#### Tags

- Real Estate
- Transactions
- Back Office
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/realogy-broker-production/summary)
- [APIReference](https://developers.anywhere.re/api-product/realogy-broker-production/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Back Office Management API

Write and update data into Anywhere systems, covering Listing, Transaction, Agent, Team, Office and Company data across all Anywhere franchise brands. Backed by the Anywhere Dash back-office platform.

- **Human URL:** [https://developers.anywhere.re/api-product/backoffice/summary](https://developers.anywhere.re/api-product/backoffice/summary)
- **Base URL:** `https://api.realogy.com/1.0/dash`

#### Tags

- Real Estate
- Back Office
- Listings
- Transactions
- Franchise

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/backoffice/summary)
- [APIReference](https://developers.anywhere.re/api-product/backoffice/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere BackOffice Read-only API

Read-only access to Anywhere back-office data from the Dash platform, including listing, transaction, agent, team, office and company data.

- **Human URL:** [https://developers.anywhere.re/api-product/realogyentitiesro/summary](https://developers.anywhere.re/api-product/realogyentitiesro/summary)

#### Tags

- Real Estate
- Back Office
- Listings
- Transactions
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/realogyentitiesro/summary)
- [APIReference](https://developers.anywhere.re/api-product/realogyentitiesro/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Leads Management API

Powers third-party CRM applications to sync lead data with Anywhere source systems so agents can manage leads and contacts in one place. Third-party CRMs can receive, submit and update leads, and query leads by Company, Agents and Teams.

- **Human URL:** [https://developers.anywhere.re/api-product/agentcrmintegration/summary](https://developers.anywhere.re/api-product/agentcrmintegration/summary)

#### Tags

- Real Estate
- Leads
- CRM
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/agentcrmintegration/summary)
- [APIReference](https://developers.anywhere.re/api-product/agentcrmintegration/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Referral Leads API

Submit a new lead to Anywhere's referral platform for a specific real estate referral program and share status updates across the customer's home buying or selling journey, including agent placement, pending sale and final sale.

- **Human URL:** [https://developers.anywhere.re/api-product/referralplatformv2/summary](https://developers.anywhere.re/api-product/referralplatformv2/summary)

#### Tags

- Real Estate
- Leads
- Referrals
- Franchise

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/referralplatformv2/summary)
- [APIReference](https://developers.anywhere.re/api-product/referralplatformv2/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Referral Partner Integration API

Submit a new lead to Anywhere's referral platform for a specific real estate referral program, creating a connected experience between the client, Anywhere and the agent, with status updates throughout the transaction journey.

- **Human URL:** [https://developers.anywhere.re/api-product/referral-partner-integration/summary](https://developers.anywhere.re/api-product/referral-partner-integration/summary)

#### Tags

- Real Estate
- Leads
- Referrals
- Franchise

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/referral-partner-integration/summary)
- [APIReference](https://developers.anywhere.re/api-product/referral-partner-integration/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Agent Recruiting API

An endpoint for third-party CRM integration partners to deliver recruiting activities into Anywhere's iProspect application, validated against current iProspect business rules to prevent invalid data entry.

- **Human URL:** [https://developers.anywhere.re/api-product/iprospect/summary](https://developers.anywhere.re/api-product/iprospect/summary)

#### Tags

- Real Estate
- Recruiting
- Leads
- CRM
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/iprospect/summary)
- [APIReference](https://developers.anywhere.re/api-product/iprospect/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Consumer Journey API

Track a consumer's real estate transaction end to end, giving buyers visibility into the closing process with clear milestones, action items and status updates. Backed by Anywhere Integrated Services (AIS) Homebase.

- **Human URL:** [https://developers.anywhere.re/api-product/c2shinningc/summary](https://developers.anywhere.re/api-product/c2shinningc/summary)

#### Tags

- Real Estate
- Consumer
- Transactions
- Title

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/c2shinningc/summary)
- [APIReference](https://developers.anywhere.re/api-product/c2shinningc/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Earnest Money API

Manage and access earnest money data for brokered trades: payee search, buyer and seller retrieval for a deal, creation of disbursement records, and retrieval and update of bank and transaction details.

- **Human URL:** [https://developers.anywhere.re/api-product/earnestmoney/summary](https://developers.anywhere.re/api-product/earnestmoney/summary)

#### Tags

- Real Estate
- Escrow
- Finance
- Transactions
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/earnestmoney/summary)
- [APIReference](https://developers.anywhere.re/api-product/earnestmoney/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Settlement Company API

Exposes Anywhere Integrated Services settlement companies and their details, letting a consuming application retrieve settlement companies by filter criteria with results sorted by proximity.

- **Human URL:** [https://developers.anywhere.re/api-product/settlement-company-capability/summary](https://developers.anywhere.re/api-product/settlement-company-capability/summary)

#### Tags

- Real Estate
- Title
- Settlement
- Escrow

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/settlement-company-capability/summary)
- [APIReference](https://developers.anywhere.re/api-product/settlement-company-capability/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Relocation Authorization API

Lets corporate clients trigger new relocation initiations or authorizations into Cartus. Authorizations are processed, a new customer file is created in the Cartus case management system, and the new Cartus file ID is returned to the client system.

- **Human URL:** [https://developers.anywhere.re/api-product/relocationauthorization/summary](https://developers.anywhere.re/api-product/relocationauthorization/summary)

#### Tags

- Real Estate
- Relocation
- Cartus

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/relocationauthorization/summary)
- [APIReference](https://developers.anywhere.re/api-product/relocationauthorization/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere RealVitalize API

Allows HomeAdvisor to integrate its backend services with the RealVitalize backend — accessing enrollment information and adding or updating enrollment-related jobs, invoices and project status.

- **Human URL:** [https://developers.anywhere.re/api-product/realvitalize-vendor-services/summary](https://developers.anywhere.re/api-product/realvitalize-vendor-services/summary)

#### Tags

- Real Estate
- Home Services
- Vendors
- Franchise
- Brokerage

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/realvitalize-vendor-services/summary)
- [APIReference](https://developers.anywhere.re/api-product/realvitalize-vendor-services/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere User Access Management API

Build and manage user access to Anywhere brand extranet applications and build user access reports. Exposes a user's profile plus the list of applications, brands, companies, master franchises and offices the user can reach.

- **Human URL:** [https://developers.anywhere.re/api-product/realogy-user-access/summary](https://developers.anywhere.re/api-product/realogy-user-access/summary)

#### Tags

- Real Estate
- Identity
- Access Management
- Franchise

#### Properties

- [Documentation](https://developers.anywhere.re/api-product/realogy-user-access/summary)
- [APIReference](https://developers.anywhere.re/api-product/realogy-user-access/specification)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)

### Anywhere Leads Engine API

Handles ingestion, routing and assignment of leads for Anywhere brands. Listed on the developer portal home page as a Partner-visibility product; its product page returns HTTP 403 to anonymous visitors, so only the portal's own one-line summary is public.

- **Human URL:** [https://developers.anywhere.re/api-product/anywhere-leads-engine/summary](https://developers.anywhere.re/api-product/anywhere-leads-engine/summary)

#### Tags

- Real Estate
- Leads
- Routing
- Franchise
- Brokerage
- Digital Fabric

#### Properties

- [Documentation](https://developers.anywhere.re/api-products)

## Common

- [Website](https://anywhere.re/)
- [Portal](https://developers.anywhere.re/)
- [Documentation](https://developers.anywhere.re/api-products)
- [GettingStarted](https://developers.anywhere.re/docs/how-it-works)
- [Authentication](https://developers.anywhere.re/docs/realogy-oauth)
- [Anywhere (Realogy) Okta production OAuth 2.0 authorization server metadata](authentication/anywhere-real-estate-okta-prod-authorization-server.json)
- [Anywhere (Realogy) Okta production OpenID Connect discovery document](authentication/anywhere-real-estate-okta-prod-openid-configuration.json)
- [Anywhere (Realogy) Okta non-production OAuth 2.0 authorization server metadata](authentication/anywhere-real-estate-okta-nonprod-authorization-server.json)
- [Signup](https://developers.anywhere.re/user/register)
- [Login](https://developers.anywhere.re/Login)
- [Support](https://developers.anywhere.re/support)
- [StatusPage](https://developers.anywhere.re/status)
- [ChangeLog](https://developers.anywhere.re/release-notes)
- [TermsOfService](https://developers.anywhere.re/terms-use-api-license-agreement)
- [PrivacyPolicy](https://privacy.anywhere.re/en/global-privacy-notice)
- [Blog](https://developers.anywhere.re/get-inspired?type=blog)
- [GitHubOrganization](https://github.com/Anywhererealestate)
- [LinkedIn](https://www.linkedin.com/company/anywhere-real-estate-inc/)
- [X (Twitter)](https://x.com/anywhere_re)
- [YouTube](https://www.youtube.com/@anywhererealestateinc)
- [InvestorRelations](https://ir.anywhere.re/)

## Maintainers

- Kin Lane — kin@apievangelist.com
