mermaid
graph TD
  Advertiser["Advertiser"] -->|creates| Campaign["Digital Advertisement"]
  Advertiser -->|works with| Agency["Agency"]
  Agency -->|manages| Campaign
  Campaign -->|delivered on| Device["Device Platform"]
  Campaign -->|placed in| Inventory["Ad Inventory"]
  Campaign -->|targets| Audience["Audience Demographics"]
  Campaign -->|measured by| Metrics["Performance Metrics"]
  Campaign -->|sold by| SalesRep["Sales Representative"]
  Campaign -->|linked to| SalesTxn["Sales Transaction"]
  Campaign -->|placed in| Content["Content Program"]
  Content -->|distributed by| Network["Network"]
  Network -->|partners with| DistPartner["Distribution Partner"]
  DistPartner -->|delivers to| Device
  Inventory -->|organized by| Content
  SalesTxn -->|processed by| SalesRep
  SalesTxn -->|tracked by| Metrics
