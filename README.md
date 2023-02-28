# DataAnalytics-PowerBI

Technical Challenge for the Global Sales Ops Warrior :)


In addition to this document, you will be provided with a data set that contains real data from our data warehouse. The technical challenges shown here are similar to the ones we solve on a daily basis. 

Some information before we start:
We recently started to sell a new product for clinics. To measure our sales flow we use a pipeline with the following stages:


1. INITIAL CONTACT - we contacted the clinic and requested successfully a meeting (if known please fill the Enterprise product and it’s amount on the corresponding property). 
2. 1ST MEETING (40% - probability of closing the deal) - we had our first meeting with the manager of the clinic. We know what parts of our value proposition will be interesting for them.
3. PROPOSAL SENT (60%) - We received verbal interest confirmation and we sent them the proposal indicating price of the proposal
4. CONTRACT SIGNED (90%) - We received a written confirmation of our proposal and onboarding of the clinic begins. 
5. CLOSED: WON. Contract signed by authorized people, the clinic provided a list of patients and doctors, we have all the data to open calendars (list of doctors + working hours), and we have established contact with the webmaster.
6. CLOSED: LOST - :( - The deal can be ‘lost’ only after meeting a customer. Before meeting a customer, do not change the status of the deal to lost with one exception. If you scheduled a meeting but the facility changed its mind and refused to meet you - change the stage to Closed Lost and put Lost Reason=First meeting cancelled. 
Mandatory properties: Lost Reason Enterprise
 
Some examples to show which stage to select in different cases:
• The customer had the 1st meeting but did not reply after that - this should stay in the 1st meeting stage and you should have notes inside explaining that you are not getting a reply and try to continue the process of selling.
 
Each stage is marked with a date property.
Please complete the following challenges. You should provide graphs, tables and written text to show the interpretation of your results.
 
1. When did we start selling this product?
2. How many sales did we close each month so far in each market? How many doctors did we win and how much revenue did we gain?
3. How long does it take us to close a deal? On which stage are we spending more time?
4. What’s the average price/doctor in each country?
