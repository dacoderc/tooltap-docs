# ToolTap API Services

ToolTap is a set of commonly used API services under a single umbrella

<!-- theme: info -->
> ### Project Status
> * **Supported services:** IP to GeoLocation ([Geo API](./services/geo.md))
> * **Business Status:** Pilot, accepting design partners. Please read below

## About ToolTap

ToolTap is a developer-friendly set of commonly used consumable API services, intended to get the job done with minimum hassle, with a transparent and business fairness approach.

At ToolTap we believe that:
1. You want to focus on your main business or project's core, and consume the rest(ful) where possible; and 
1. Consumable APIs should be  easy to implement; and 
1. Be stable, robust and reliable, so you can "forget about it"; and 
1. Be cost-effective, priced fairly and transparently, with minimum commitments. 

## Usage 
ToolTap is a Headless service, relying on developer's skills to read API documentations.  

API documentations: 
* [OpenAPI json (swagger)](tooltap-api.json)
* [Stoplight website](https://tooltap.stoplight.io/docs/tooltap-api-services) with "try me" forms

### Getting Started

The only prerequisite for using ToolTap, is creating an account and an API access token.

This prerequisite is easily accomplished with 3 API calls at the following order:

1. [Create account](https://tooltap.stoplight.io/docs/tooltap-api-services/f417c3f883960-create-account) - With this call you create a new user's account. Only an email address is required.  
__Please keep the result account's ID for the next calls__
1. [Validate account](https://tooltap.stoplight.io/docs/tooltap-api-services/5cbc716f2e5c9-account-validation) - Validate ownership on the provided email address
1. [Create Access Token](https://tooltap.stoplight.io/docs/tooltap-api-services/2cd1af5cc8f25-validate-access-key) - Using your email validation result, this call will provide you with an Access Token, which you'll need for consuming ToolTap's APIs

### Pilot T&C

We're now accepting first 50 clients as early-bird design partners.  
**To join, please contact dacoderc at gmail.**

Being a design partner entitles you with the following benefits:

* Free usage for 2 years:
  * Up to 50,000 calls per month
  * Up to 100 GB accumulative storage
  * Up to 50 GB network I/O per month
  * Up to $200 worth of on-demand services
  * Monthly plans 100% free for 2 years
* After 2 years, 15% discount on all On-Demand pricing and monthly plans, FOREVER
* Get the opportunity to impact our existing products and ongoing roadmap
* We'll add your brand and logo on our documentations and future website (as sponsors & partners)

Please note that the above benefits assume a design-partner level of engagement and cooperation.  
We promise to be polite and fair, but we do need your help!

