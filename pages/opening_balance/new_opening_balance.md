---
layout: page
title: New opening balance
permalink: /opening_balance/new_balance
parent: Opening balance
nav_order: 1
---

## Opening balance if you did not have an existing administration
In a few steps we are going to create and enter an opening balance in GnuCash.

Also if you already did start with your company but did not yet create an administration, we recommend you to follow this approach.

When you started your company, you probably transferred money and/or goods from your private posessions to your company.
A few common examples:
* You put your private car on your company
* You transferred your computer to your company
* You transferred money from your private bank account to the company bank account
* You started using privately owned tools for your company

The advantage of transferring privately owned to company owned brings the advantage that its value 
gets deducted from the company profits. You pay taxes on profit and if you have less profit, you will pay less taxes.
In many tax systems you need to depreciate goods. In the Dutch system you are required to depreciate goods with a value above € 450. 

Goods you transferred from private to company will get the value you would also get when you would sell it. This is called "real economic value".

Whether you would designate your car as company car or private car depends heavily on the value (original price and the value of the car on the moment of transfer)
of the car, the maintenance costs, fixed costs, its fuel consumption and the expected yearly revenue.
If you keep the car private and drive it for the company, you would need to keep an administration in order to get the maximum tax advantage from the travel compensation costs. 

The Dutch Tax Services will give you many good tips and information through their website and phone service on the choice betwen company or private car.

Make a list of goods and their value you transferred from your private ownership to your company when you started.
For example:

* Laptop: € 400
* Printer: € 120
* Van: € 2600
* Cellphone: € 90
* Tools: € 650
* Deposit company bank account: € 1000

De private contribution is € 4860 in total.

From the value of the private contribution you create the starting balance.
The private contribution € 4860 is the same as a private deposit. 
A private deposit will always be on the right (credit).
All goods and the deposit on the company bank account are now a company asset.
Assets are always on the left (debet).

The laptop, printer, van, cellphone and the tools fall into the category machines and installations.
The deposit on the bank account is bank.

Make sure that in a starting balance debet (left) and credit (right) should be the same in total.
In this example € 4860. Only enter a starting balance of which debet and credit are the same.

The opening balance looks then like this:

| Account name                                    | Account type    | Debet | Credit |
|:------------------------------------------------|:----------------|------:|-------:|
| 010 Company buildings and terrains              | Assets          |       |        |
| 020 Machines and installations                  | Assets          |  3860 |        |
| 040 Private equity                              | Equity          |       |        |
| 041 Private deposits                            | Equity          |       |  4860  |
| 042 Private withdrawals                         | Equity          |       |        |
| 070 Debts                                       | Equity          |       |        |
| 100 Cash                                        | Cash            |       |        |
| 110 Bank                                        | Bank            |  1000 |        |
| 130 Accounts Receivable                         | A/Receivable    |       |        |
| 140 Accounts Payable                            | A/Payable       |       |        |
| 180 VAT Receivable                              | Assets          |       |        |
| 185 VAT Payable 21%                             | Equity          |       |        |
| 186 VAT Payable 9%                              | Equity          |       |        |
| 187 VAT Payable other (not 0%)                  | Equity          |       |        |
| 188 VAT Payable 0%                              | Equity          |       |        |
| 189 VAT Payable transferred to me               | Equity          |       |        |
| 400 Expenses of materials and stock             | Expense         |       |        |
| 410 Expenses of outsourced work                 | Expense         |       |        |
| 430 Depreciation buildings and terrains         | Expense         |       |        |
| 440 Depreciation machines and installations     | Expense         |       |        |
| 450 Expenses Auto and transport                 | Expense         |       |        |
| 460 Accomodation expenses                       | Expense         |       |        |
| 470 Maintenance expenses                        | Expense         |       |        |
| 480 Expenses sales + ads + marketing            | Expense         |       |        |
| 490 Expenses other                              | Expense         |       |        |
| 495 Expenses bank and interest                  | Expense         |       |        |
| 700 Stock                                       | Assets          |       |        |
| 800 Revenue 21% VAT                             | Income          |       |        |
| 801 Revenue 9% VAT                              | Income          |       |        |
| 802 Revenue 0% VAT                              | Income          |       |        |
|-------------------------------------------------|-----------------| ----- | ------ |
|                                                 |                 |  4860 |   4860 |

### Opening balance private deposit

Open GnuCash and select in the Account overview of the tab "Accounts" the account for which 
you are doing to enter the opening balance.
In the example above the first account is "Machines and installations" which will get an opening balance of € 3860.


As the date choose a date earlier than the date you wrote your first invoice, or received your first bill, or made the first company costs.
In this example we will use January 1st 2019.

Choose the option "Reconcile" from the menu Actions.

![Menu Actions, option Reconcile]({{ site.baseurl }}/assets/menu_acties_afstemmen.png)

You will get the dialog "Reconcile". Enter the chosen date in the field "Statement Date", and in the "Ending Balance" field the amount.

![Reconciliation]({{ site.baseurl }}/assets/acties_afstemmen_dialog.png)

You now will get the "Reconcile" window, which is empty. In the right bottom corner you will see the Ending balance we just entered. 
Now click on Balance.

![Reconcile]({{ site.baseurl }}/assets/afstemmen_empty.png)

The account "Machines and installations" will now be opened.
Enter the chosen date in the Date field, "Opening Balance" in the description and select the account "Private deposit" in the column Transfer.
You can leave the rest unchanged. Click on Enter.

![Machines_opening_balance]({{ site.baseurl }}/assets/machines_beginbalans.png)

Now go back to the window "Reconcile" which is still open. It is possible it is hidden behind the main window. If this is not the case, select the
account again and open the dialog Reconcile through the "Reconcile" option in the "Actions" menu.

Mark the incoming money flow. You will see now that the difference in the right bottom corner has become 0.


![Afstemmen met selectie]({{ site.baseurl }}/assets/afstemmen_marked.png)

Now the opening balance is right and there is no more difference, you choose "Finish" in the "Reconcile" menu or through the "&#9662;"-menu.


Now we select the account "Private deposits" and choose for "Reconcile"
You will see that the opening balance is also on € 0 here and that the end balance has already been filled in.
To also get a opening balance on the account "Private deposits" we choose OK.

![Privéstortingen afstemmen dialoogvenster]({{site.baseurl}}/assets/privestortingen_afstemmen_dialog.png)

Mark in the Reconcile window the opening balance. The difference in the right bottom corner should be € 0 now.

![Privéstortingen afstemmen]({{site.baseurl}}/assets/privestortingen_afstemmen_window.png)

Now the opening balance is right and there is no more difference, we choose "Finish" through the menu or the pulldown menu.

If you now select the account again and choose for "Reconcile", you will see that the opening balance is right and there is nothing more in the window "Reconcile".

Repeat the steps above for every private deposit to complete the opening balance.
After you complete entering the private contributions, the three amounts from the example are visible in the Account overview.

![Rekeningoverzicht na afronding beginbalans]({{site.baseurl}}/assets/accounts_after_start_balance_complete.png)
