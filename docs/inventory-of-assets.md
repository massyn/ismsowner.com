# Inventory of Assets

When you start to perform your [risk assessment](risk-assessment.md), you will inadvertently have to maintain an inventory of assets.  So what is an inventory of assets?

Let's start with an _asset_.  An asset is **anything (or anyone) that has some inherent value** to the organisation.  On it's own, that statement doesn't really mean anything - it simply says _anything of value_.  The problem with _value_ is that is very subjective, so we need some guidance.

Annex A.8 has detailed control requirements around how assets should be managed.

* **A.8.1.1 - Inventory of assets** specifies that a list of the necessary assets are maintained, the list is accurate and up-to-date.
* **A.8.1.2 - Ownership of assets** defines that an asset must have an owner, and specifies the responsibility the owner has to ensure the asset inventory is being maintained, and correctly classified.

Let's take a look at ISO 27005.  It has some examples of what an asset could be.

## Examples of assets categories

* Business Processes and activities
* Information
    - Proprietary information (recipes, designs, safety reports, etc.)
* Hardware
* Software
    - Could be on premis, SaaS, etc
* Network
* Personnel
* Physical Sites
* Organization's structure

## Procedure for asset management

When defining your inventory of assets for the purposes of your ISMS, you should define two lists.

* The **Primary** list is the high level summary that is necessary to perform the organisational risk assessment.  On this list, for example, you may have an asset known as _eCommerce Websites_.
* The **Secondary** list will be more detailed.  On this list, you will have the list of all websites.  The Primary list may also link to the secondary list to provide additional information on the specific assets in question.

In another example, when performing a risk assessment for your ISMS, you won't necessarily perform a risk assessment against a single server that may be hosted in your local computer room, instead, you'll do a risk assessment for all servers.

Consider for a moment that the risk of malware infecting your network.  It will be highly impractical if you were to perform the same risk assessment against every single server and workstation in your environment.  Instead, it makes a lot more sense to simply state _a risk of malware infection on all Windows servers can disrupt business operations._  Similarly, you can have _Windows Servers_ listed as an asset on your inventory of assets.  The _Secondary List_ can contain the specific list of every individual server.

## Classification

Every asset is different.  Some are more important than others.  Consider the [CIA](what-is-the-cia-in-the-isms.md) of the asset.  Some assets (like payroll data) may highly confidential, but do not need to be available all the time.  Your corporate website may not be confidential at all, but if suppliers can't access your information, you could lose potential sales, so the availability becomes critical.  Other information, like sales data being tramsitted over EDI, may not be very confidential, but the integrity of the data is crucial, as wrong data could result in incorrect orders being shipped (imagine someone changing an order for 10 new laptops to 10,000 new laptops -- that's a huge embarrasment if you were to sent 9,990 more machines to the customer than what they ordered, not to mention the revenue loss!)

When we summarize the CIA criticaility for each of the assets, we'll get a sense of where the importance of our assets are.  By using the highest rating, you end up with the organisation's result for the impact of the asset.

|**Asset**|**Confidential**|**Integrity**|**Availability**|**Result**|
|--|--|--|--|--|
|Payroll data|3|2|1|3|
|Corporate website|1|2|2|2|
|EDI Sales Order|1|3|2|3|

The result of your assessment can be captured in your inventory of assets.

## Asset Inventory Example

You can now create the inventory.  Feel free to expand on the fields if you believe you need to capture additional information.  Do not forget to follow the principles of [document management](document-management.md) when you create this important document.

|**Category**|**Identifier**|**Owner**|**Classification**|**Date Reviewed**|
|--|--|--|--|--|
|Hardware|Windows Servers (list to server list)|B.Gates|3|2022.01.30|
|Software|eCommerce websites|J.Bezos|2|2021.09.20|
|Hardware|Electric Vehicles|E.Musk|2|2022.02.20|





