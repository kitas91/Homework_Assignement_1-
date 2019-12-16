# Case Study Proposal Plaid 

## What Is It:
Plaid is a software company that provides API’s for application software to communicate with banksabout customer accounts via language agnostic JSON. Complicating such communications is the need todeal with identity verification, various kinds of error conditions, and the possibility that the samecustomer might have multiple accounts that need to be accessed simultaneously for aggregate balances,etc.

Banks have much more data about customers than most of us realize, and the Plaid API can get it. Plaidcan retrieve such things as the geolocation data for a given transaction and render it into intelligible form.As an example of the latter activity, called “cleaning”, the code “​SBXUSQ0112x” would be translated as“Starbucks Coffee, 41 Union Square, New York, New York in New York City”. The Plaid API can alsoretrieve the bank’s estimates of their customer incomes!

Plaid is in the early stages of using this data to help companies make better offers to customers, so theyare just getting into data science.

## Why This Matters: 

Banks do not provide an API for their customer data because there is no financial incentive or regulatoryrequirement that they do so. Yet this is precisely what is needed for third party fintech companies, such asBetterment and Venmo, who need to seamlessly link to customer bank accounts (To understand this needbetter, consider PayPal’s methodology for linking to a bank account: the customer must enter the accountinformation onto the PayPal web page and wait a few days while PayPal deposits, and then withdrawstwo amounts of less than a dollar. It is only after the customer enters the amount of those deposits that thelink with PayPal becomes operational. Not exactly seamless!).

And that is what 25% of Americans with bank accounts have asked various apps to do in 2018, up 13%from 2017. Yes, the banks have to agree to connect with Plaid, but more than 10,000 of them do,including the likes of JP Morgan Chase, Bank of America, CitiBank, and Wells Fargo. After Plaid’s lastfunding round, its market cap is over $2.7 billion, making it a start-up “unicorn”. An initial publicoffering (or IPO) in 2019 appears likely.

## Why This May Be Interesting:

Since Plaid is so deeply enmeshed in the fintech ecosystem, many people are likely to use thePlaid API, and many others will likely use similar Python-accessible API’s. Plaid itself has about300 employees in its San Francisco location at the moment. As a recent ​Forbes article ​states,“Plaid's founders know that they need to expand the uses of Plaid if they want to be a company
much larger than their predecessors”. In other words, they are in a “grow or die” situation, sothey will continue to hire rapidly.●Plaid also provides the web page ​fin.plaid.com​, which provides think pieces ​that take the pulse ofthe current fintech scene.

## Things to Keep in Mind for a Case Study:

An explanation of Plaid’s role in the fintech ecosystem●Explanation of PayPal’s clunky account verification algorithm o Walk-through of Plaid APImechanics as described in the ​Forbes article A demonstration of how to use Plaid’s API to grab customer data from a hypothetical bankaccount (Plaid allows prospective users to try such things for free in their “sandbox”.).

## Resources:
https://plaid.com​/ ​(Plaid website)

https://www.inc.com/jeff-pruitt/6-fintechs-disrupting-the-industry.html​​(Plaid is one of thesedisruptors, and this article explains more clearly than the Plaid website what Plaid actually does.).

https://www.forbes.com/plaid-fintech/#7d07821767f9​​(More detail about Plaid.).

https://security.stackexchange.com/questions/198005/is-plaid-a-service-which-collects-user-s-banking- login-information-safe-to-use​​(StackExchange page discussing Plaid’s security model. Itnotes that banks themselves do not provide API’s to access customer data, which is the ​raisond’être ​for Plaid).