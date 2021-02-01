---
layout: page
title: Create Accounts
permalink: /accounts_setup/
parent: Setup
nav_order: 1
has_children: yes
---

## Accounts

As soon as you installed GnuCash and run it for the first time, you will be asked to create a Account Hierarchy.
For a beginner it is actually better to do this manually. In that way you will have encountered all accounts and form an idea what these accounts are for.

If you already performed this operation a few times, or you are in a hurry, you can also import an existing tree.
You can find more information on [Quick Setup]({{ site.baseurl}}/quick_accounts_setup)

In the wizard, click "Cancel" to create the account tree manually.

You arrive on the empty tab `Accounts`. Choose the menu `Actions` and then `New Account`.

![Menu-actie voor nieuwe rekening]({{ site.baseurl}}/assets/new_account_nl.png)

You will see the following dialog:

![Dialog for a new account]({{ site.baseurl}}/assets/new_account_dialog_nl.png)

### Create ledger accounts.
Fill in the name of the account, the code, account type and parent account.
If you want, you can enter a description, but it is not required.
Do this for every account in the table below. It is possible that some accounts are not useful for your company.
Create them anyhow, they won't be in the way much.
If something goes wrong, you can edit the account afterwards. More about that below the table.

```
NB. The accounts in the table will be appropriate for almost all self-employed people and one-person-businesses.
This schema was chosen because it matches the Dutch VAT declaration and Income tax declaration the most.
That way, you don't have to start searching which numbers to fill in where. That saves time and limits the possibility of errors.
```

In the account overview, you will see 9 different account types. It is useful to know what these types are, because it will help you making overviews and reports later.

* **Assets**: Assets or means that are being used actively (Dutch: Activa)
* **Equity**: Assets or means that have value and will create value when sold (Dutch: Eigen vermogen)
* **Liability**: Assets or means of others that are maintained by the company, usually in the form of credits (Dutch: Vreemd vermogen)
* **Cash**: Account for cash (Dutch Contanten)
* **Bank**: Account at the bank
* **Accounts Receivable**: Account to track what has been sold (Dutch: Debiteuren)
* **Accounts Payable**: Account to track what has been bought (Dutch: Crediteuren)
* **Expense**: Account to track costs (Dutch: Kosten)
* **Income**: Account to track proceeds / revenue. (Dutch: opbrengsten)

After creating the accounts, please continue with [Setting up VAT rates]({{ site.baseurl}}/vat_tariffs).

##### Account tree

| Account name                                     | Account number | Account type    | Parent account        | Description                     |
|:-------------------------------------------------|:---------------|:----------------|:----------------------|----------------------------------|
| 010 Company buildings and terrains               | 010            | Assets          | New top level account | Value of real estate             |
| 020 Machines and installations                   | 020            | Assets          | New top level account | Value of machines                |
| 040 Private equity                               | 040            | Equity          | New top level account | Private equity                   |
| 041 Private deposits                             | 041            | Equity          | New top level account | Private deposits                 |
| 042 Private withdrawals                          | 042            | Equity          | New top level account | Private withdrawals              |
| 070 Debts                                        | 070            | Equity          | New top level account | Credits of investments           |
| 100 Cash                                         | 100            | Cash            | New top level account | Cash register                    |
| 110 Bank                                         | 110            | Bank            | New top level account | Bank account                     |
| 130 Accounts Receivable                          | 130            | A/Receivable    | New top level account | Invoices                         |
| 140 Accounts Payable                             | 140            | A/Payable       | New top level account | Bills                            |
| 180 VAT Receivable                               | 180            | Assets          | New top level account | VAT paid when buying             |
| 185 VAT Payable 21%                              | 185            | Equity          | New top level account | VAT on sales, high rate          |
| 186 VAT Payable 9%                               | 186            | Equity          | New top level account | VAT on sales, low rate           |
| 187 VAT Payable other (not 0%)                   | 187            | Equity          | New top level account | VAT on sales, other rates not 0%  |
| 188 VAT Payable 0%                               | 188            | Equity          | New top level account | VAT on sales, 0% rate             |
| 189 VAT Payable transferred to me                | 189            | Equity          | New top level account | VAT on sales, transferred         |
| 400 Expenses of materials and stock              | 400            | Expense         | New top level account | Costs made of creating stock     |
| 410 Expenses of outsourced work                  | 410            | Expense         | New top level account | Costs made when outsourcing work |
| 430 Depreciation buildings and terrains          | 430            | Expense         | New top level account | Depreciation real estate         |
| 440 Depreciation machines and installations      | 440            | Expense         | New top level account | Depreciation machines            |
| 450 Expenses Auto and transport                  | 450            | Expense         | New top level account | Costs made for transport         |
| 460 Accomodation expenses                        | 460            | Expense         | New top level account | Costs for accomodation and rent  |
| 470 Maintenance expenses                         | 470            | Expense         | New top level account | Maintenance costs                |
| 480 Expenses sales + ads + marketing             | 480            | Expense         | New top level account | Costs for sales / adv            |
| 490 Expenses other                               | 490            | Expense         | New top level account | Other expenses                   |
| 495 Expenses bank and interest                   | 495            | Expense         | New top level account | Costs of interest and bank services |
| 700 Stock                                        | 700            | Assets          | New top level account | Value of stock                   |
| 800 Revenue 21% VAT                              | 800            | Income          | New top level account | Revenue 21% VAT                  |
| 801 Revenue 9% VAT                               | 801            | Income          | New top level account | Revenue 9% VAT                   |
| 802 Revenue 0% VAT                               | 802            | Income          | New top level account | Revenue without VAT              |

### Editing ledger accounts

You can edit the settings of an account. Select the account you want to edit and choose in the Edit menu the option "Edit account"
You will get the same dialog that was used to create the account. Change what you need to change and click OK to save.


