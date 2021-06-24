Types of Credit Card Transactions
-----------------------------------
**Pre-Authorization** - It is also called as Pre-Auth or just authorization. It just reserves the money in Credit Card but doesn't complete the trasaction. A followup transaction is required to complete it.

**Post-Authorization** . It is also know as Post-Auth or Capture. It is used to complete the Pre-Auth transactions. 

**Void** . It is also know as Cancel. It is used to complete the Pre-Auth transactions. 

**Refund** . It is also know as Post-Auth or Capture. It is used to complete the Pre-Auth transactions. 

All transactions which we do online are called CNP - Card Not Present transactions.
All tranasctions with at done at SHOP with Termianls are called - Card Present tranctions.

High Level Payment process of Cards - Debit Cards, Credit Cards, Giro Cards
----------------------------------------------------------------------------

![image](https://user-images.githubusercontent.com/2181212/123215403-add69100-d4c8-11eb-8718-7dae49eebb45.png)

Fraud Detection, Financial Crime
--------------------------------------

As I understand there are two types of Fraud or Crime detection process
* Real Time - Which has to be really fast. For instance if we pay at Shop or Online Store we don't want to wait for very long. Credit Card Payments, Debit Card Payments, SPEA Instant Transfer.
* Normal  - Bank Transfer, SPEA Debit Transfer, Wire which ever doen't require to tranfer money instantly.

Why company do Fraud Detection or Financial Crime?
--------------------------------------------------
To prevent loss of customer asset, financial compliance, sancations and embargo. Companies does some background work using KYC(Know Your Customer) but that is not enough to tackel financial crimes. 

Methods Used to Detect Fraud
------------------------------

**Risk Assessment** 
---------------------
Over time we profile the payment pattern using machine learning and profilers and detect the pattern. For instance some Fraudster use transactions of 9999 $ over mutiple transactions to avoid the limit of 10000. 
  * Statistical Algorithm
  * Pattern Profiling over time
  * Pattern Recognistion - Evalution of risk pattern, suspocious associations and behaviors.
     *   Consumer buying patterns
     *   Behavioral analytics
     *   Payment trends
     *   The fraudster ecosystem
     *   Advanced fraud analytics

**Goverment Provided Data**
-------------------------------
It has details like Name, Address, Account Number, Country, Connections details.
* Global Negative Data
* OFAC - Office of Foreign Assets Control - Sanctions List
  * Sanctions can be applied to a Country, Person, Company, Organisations   
* SDN - Specially Designated Nationals List - Data Formats & Data Schemas

Note: Embargo is a ban on trade for all transactions without a license.
Note: Sanction is a prohibition on certain exports or activities without a license.

** Risk Decision Rules** 
-------------------------
Usually, company enforce these rules themselves.
  * Different for Different companies 
  * Payment limit
  * No of transactions limit
  * Some other rule.

**Expret Manual Review** - Sometimes system detect **false positive/ false declines** those cases should be reviewed manually by Merchant or Service provider. 

There are other Products in market Fraud Detect by First Data, HotScan by CGI,  Fraud Radar by Strip.


![image](https://user-images.githubusercontent.com/2181212/123222148-eded4200-d4cf-11eb-96e5-4fe591ca2111.png)

![image](https://user-images.githubusercontent.com/2181212/123222341-24c35800-d4d0-11eb-9f02-54457eedefcf.png)


