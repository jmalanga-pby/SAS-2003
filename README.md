# SAS-2003
OPs on SWOs saved as Service in ShopX, but Retail ("Over-the-Counter") in Legacy

Description
Some OPs created on an SWO are saved as "Retail" in Legacy.
If the payment type is "PCard", the request goes out to fund the PARTS card instead of the SVC card.

Success Criteria
When an OP in created in SWO, it is marked/tagged as an OP for SWO in both Shop-x and Legacy
When an OP is created in SWO, the SWO Pcard is opened for the transaction
