---
layout: page
title: Existing opening balance
permalink: /opening_balance/existing_balance
parent: Opening balance
nav_order: 2
---

## Opening balance when you already have an administration

It is important that from the moment you transfer your administration to GnuCash, you will only enter things in GnuCash and not in
your other programs that you used until then. This goes for all invoices, all mutations and payments from that moment.

Everything before that date should be entered in the old system.

### Trial balance
Create a report similar to the Trial balance in your old program per the chosen date.
You will use this trial balance to enter the opening balance in GnuCash.
For this example we use the following Trial balance.


| Account name                                    | Account type     | Debet | Credit |
|:------------------------------------------------|:-----------------|------:|-------:|
| 010 Company buildings and terrains              | Assets           |   220 |        |
| 020 Machines and installations                  | Assets           |   180 |        |
| 040 Private equity                              | Equity           |       |  1550  |
| 041 Private deposits                            | Equity           |       |   150  |
| 042 Private withdrawals                         | Equity           |    50 |        |
| 070 Debts                                       | Equity           |       |   160  |
| 100 Cash                                        | Cash             |    60 |        |
| 110 Bank                                        | Bank             |   200 |        |
| 130 Accounts Receivable                         | A/Receivable     |   800 |        |
| 140 Accounts Payable                            | A/Payable        |       |    440 |
| 180 VAT Receivable                              | Assets           |   140 |        |
| 185 VAT Payable 21%                             | Equity           |       |     90 |
| 186 VAT Payable 9%                              | Equity           |       |     45 |
| 187 VAT Payable other (not 0%)                  | Equity           |       |     15 |
| 188 VAT Payable 0%                              | Equity           |       |      0 |
| 189 VAT Payable transferred to me               | Equity           |       |     50 |
| 400 Expenses of materials and stock             | Expense          |  1800 |        |
| 410 Expenses of outsourced work                 | Expense          |  1200 |        |
| 430 Depreciation buildings and terrains         | Expense          |    10 |        |
| 440 Depreciation machines and installations     | Expense          |    25 |        |
| 450 Expenses Auto and transport                 | Expense          |   170 |        |
| 460 Accomodation expenses                       | Expense          |    60 |        |
| 470 Maintenance expenses                        | Expense          |    85 |        |
| 480 Expenses sales + ads + marketing            | Expense          |   125 |        |
| 490 Expenses other                              | Expense          |   145 |        |
| 495 Expenses bank and interest                  | Expense          |    30 |        |
| 700 Stock                                       | Assets           |  1200 |        |
| 800 Revenue 21% VAT                             | Income           |       |   2700 |
| 801 Revenue 9% VAT                              | Income           |       |    850 |
| 802 Revenue 0% VAT                              | Income           |       |    450 |
|-------------------------------------------------|------------------| ----- | ------ |
|                                                 |                  |  6500 |   6500 |

Now open GnuCash and select on the tab Accounts the account for which you want to enter the 
opening balance. We now choose the first account "Company buildings and terrains". This should get 
an opening balance of € 220. 

Choose the option "Reconcile" from the menu "Actions".


![menu Acties, optie Afstemmen]({{site.baseurl}}/assets/menu_acties_afstemmen.png)

Enter the € 220 in the field "Ending balance".

![Afstemmen bedrijfsgebouwen dialoogvenster]({{site.baseurl}}/assets/bedrijfsgebouwen_afstemmen_dialog.png)

The window Reconcile is still empty. In the right bottom corner you will see the ending balance we just entered.
Click on "Balance".

![Bedrijfsgebouwen afstemmen]({{site.baseurl}}/assets/bedrijfsgebouwen_afstemmen.png)

The account "Company buildings and terrains" will now be opened. Enter the date in the field "Date", "Opening balance" as "Description"
and choose the account "Private Equity" in the column "Transfer". Always use the account "Private equity"!
You can leave the rest unchanged. Click on "Enter".


![Bedrijfsgebouwen beginbalans]({{site.baseurl}}/assets/bedrijfsgebouwen_beginbalans.png)

Now go back to the window "Reconcile". This is very likely still open, behind the main window of GnuCash.
If not, select the account on the tab "Accounts" and again choose "Reconcile" from the "Actions" menu.

Now mark the incoming money stream. You will see now that the difference in the right bottom corner has become € 0.

![Bedrijfsgebouwen afstemmen met geldstroom]({{site.baseurl}}/assets/bedrijfsgebouwen_geldstroom.png)

The opening balance should be right now, and there should be no difference. Choose "Finish" in the menu "Reconcile" or through the "&#9662;"-menu.

Now select the account "Private equity" and also choose here the option "Reconcile" from the "Actions" menu.
You will see that the opening balance here is also still € 0 en the ending balance is already filled in. Choose OK.

![Dialoogvenster afstemmen Eigen vermogen]({{site.baseurl}}/assets/eigenvermogen_afstemmen_dialog.png)

Mark in the window Reconcile the opening balance. The different in the right bottom corner should now be € 0.

![Eigenvermogen afstemmen]({{site.baseurl}}/assets/eigenvermogen_afstemmen.png)

As the opening balance is right now and there is no more difference, you choose "Finish" in the "Reconcile" menu or in the "&#9662;"-menu.

If you now select the account again and choose "Reconcile", you will see that the opening balance is now also right 
and there is nothing left in the window "Reconcile".

Repeat the steps above for every account of the opening balance, with the only exception being the Private Equity account.
You don't enter the € 1550 as it is the total of all other records together (debit and credit).
Take care that you enter the amount on the account "Private withdrawals" as a negative number, in order for it to appear on the debet side of the balance.


### Accounts Receivable
The accounts receivable of in total € 800 consists of two unpaid invoices, being customer Hopman for € 450 and customer Petersen for € 350.

Open now the account "Accounts Receivable" and enter for every invoice the following:

* **Date**: The date of the opening balance
* **Customer**: The name of the customer
* **Transfer**: The account "Private equity"
* **Invoice**: The amount on the invoice

You won't be able to enter something in the field "Expiry Date" and also leave the other fields untouched.
Click on Enter.

![Invullen van openstaande facturen in Debiteuren]({{site.baseurl}}/assets/debiteuren_openstaande_facturen.png)

#### Payment of invoices from opening balance Accounts Receivable
When the unpaid invoices are paid by the customer, you select the account "Bank" from the tab "Accounts".
Doubleclick the account Bank and enter the received amounts.


![Bank debiteuren betaling]({{site.baseurl}}/assets/bank_debiteuren_betaling.png)

For the remaining steps you can follow the steps of the page ["Process bank statements"]({{site.baseurl}}/paying/manual).


### Accounts payable
The value on the account Accounts Payable of € 440 consists of two unpaid bills, one from vendor "Wholesale dealer The Lamp" of € 180 and one from "Garden center Garden, Pet and Pond" of € 260.

Open the account "Accounts Payable" and enter for every unpaid bill the following:

* **Date**: The date of the opening balance
* **Vender**: The name of the vendor
* **Transfer**: The account "Private Equity"
* **Bill**: The value of the bill

You cannot fill in the field "Expiry date" and you can leave the rest of the fields empty.
Click on Enter.

![Invoeren openstaande facturen in Crediteuren]({{site.baseurl}}/assets/crediteuren_invoeren_openstaande_inkoopfacturen.png)


#### Paying bills from opening balance Accounts Payable
When the unpaid bills are paid by bank to the vendor, you select the account Bank in the Accounts overview.
Doubleclick on the account and enter the paid amounts.

TODO: Verification: In the original Accoo.nl manual an image is used where the payments are entered as deposits on the bank account.
I assume this is a mistake, so in the image below they are entered as a withdrawal.

![Invoeren betaling openstaande facturen in Bank]({{site.baseurl}}/assets/bank_verwerking_crediteuren_betaling.png)

For the remaining steps you can follow the steps of the page ["Process bank statements"]({{site.baseurl}}/paying/manual).

## Trial balance
After you enter the opening balance, all amounts in the example above should be visible in the Trial balance generated by GnuCash.
Open the Trial balance through choosing the menu "Reports", the option "Income & Expense" and the suboption "Trial Balance".

![Weergave proefbalans]({{site.baseurl}}/assets/proefbalans_prefilled.png)

The dates of the report can be adjusted through the "Options" button in the toolbar. After clicking that button, navigate to the tab "General".

![Algemene opties van het rapport proefbalans]({{site.baseurl}}/assets/proefbalans_options_general.png)

## Concluding
Entering the opening balance is a step that will be very helpful using a bookkeeping program. You now know the details and the steps you need to 
perform to setup an opening balance.
