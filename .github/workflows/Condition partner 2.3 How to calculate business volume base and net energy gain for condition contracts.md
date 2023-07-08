
 
# How to Create and Settle Condition Contracts with Customers in SAP S/4HANA
 
Condition contracts are a new feature in SAP S/4HANA that allow you to manage various types of conditions for both suppliers and customers, such as rebates, bonuses, commissions, and royalties. In this article, we will focus on how to create and settle condition contracts with customers as the contract partner.
 
**Download Zip ✸✸✸ [https://t.co/39eV0hRJdq](https://t.co/39eV0hRJdq)**


 
A condition contract is a central object that contains the conditions that apply to a specific customer or a group of customers. You can define different types of conditions, such as prices, discounts, surcharges, or rebates, that can either accompany an invoice or require subsequent settlement. You can also specify the validity periods, settlement dates, business volume selection criteria, and other details for each condition contract.
 
To create a condition contract with a customer as the contract partner, you need to use the transaction code WCOCO or the SAP Fiori app Manage Condition Contracts. You need to enter the following mandatory fields:
 
- Condition contract type: This defines the data source for settlement, for example, billing documents for sales rebate condition contracts[^1^].
- Contract partner: This is the customer number of the contract partner.
- Type of eligible partners: This specifies whether or not eligible partners play a role for the condition contract type[^1^]. Eligible partners are customers who are entitled to receive benefits from the condition contract.
- Validity period: This defines the start and end dates of the condition contract.

You can also enter optional fields, such as:

- Texts: You can add notes or comments to the condition contract.
- Conditions: You can add or edit the conditions that apply to the condition contract. For each condition type, you can enter the validity period, amount or percentage, scale basis, accrual indicator, and other details.
- Business volume selection criteria: You can define the scope for which the system determines the business volume that is relevant for settlement. For example, you can specify the sales organization, distribution channel, division, material group, or billing type.

After creating a condition contract, you need to settle it periodically to calculate and pay out the benefits to the eligible partners. You can settle condition contracts manually or automatically using transaction code WCCS or the SAP Fiori app Settle Condition Contracts. You need to enter the following mandatory fields:
 
Condition contract management with SAP S/4HANA,  Condition contract type and settings,  Condition contract settlement and accruals,  Condition contract partner customer or supplier,  Condition contract business volume calculation,  Condition contract score, credit limit and rating procedure,  Condition contract credit management configuration,  Condition contract credit segment and control area,  Condition contract credit group and check rule,  Condition contract credit release check for net value,  Condition contract active receivable per item category,  Condition contract external credit information query,  Condition contract rating procedure ID type Credisafe,  Condition contract logistics general settlement management,  Condition contract conditions accompanying an invoice,  Condition contract conditions requiring subsequent settlement,  Condition contract create and maintain condition contracts,  Condition contract real-time access to business volume data,  Condition contract advantages over traditional rebate agreements,  Condition contract single transaction code or SAP Fiori app,  Condition contract validity periods and text elements,  Condition contract settlement dates and information,  Condition contract create condition contracts with start date in the past,  Condition contract IMG menu path for customizing settings,  Condition contract BADI activation for S/4 HANA

- Settlement run ID: This is a unique identifier for each settlement run.
- Settlement period: This defines the start and end dates of the settlement period.
- Condition contract type: This defines the data source for settlement.

You can also enter optional fields, such as:

- Contract partner: You can limit the settlement run to a specific contract partner.
- Condition contract number: You can limit the settlement run to a specific condition contract.
- Simulation mode: You can run the settlement in simulation mode to check the results before posting them.

The system will then determine the business volume for each condition contract based on the selection criteria and calculate the settlement amount for each eligible partner. You can review and adjust the settlement results before posting them. The system will then create settlement documents, such as credit memos or debit memos, for each eligible partner.
 
In conclusion, condition contracts are a powerful tool in SAP S/4HANA that allow you to manage various types of conditions for both suppliers and customers. In this article, we have shown you how to create and settle condition contracts with customers as the contract partner. We hope you find this article helpful and informative.
 8cf37b1e13
 
