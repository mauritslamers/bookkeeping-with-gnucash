---
layout: page
title: Create VAT rates
permalink: /vat_tariffs/
parent: Setup
nav_order: 2
---

### Create VAT rates

Now we create the accounts, it is time to create the VAT rates. In order to do that, we go to the menu "Business" and choose the option
`Sales Tax Table`.

![Menu Business / Sales Tax Table]({{ site.baseurl}}/assets/menu_mkb_btw.png)

You will get the following dialog:

![Tax Tables]({{ site.baseurl}}/assets/btw_dialog.png)

First create a new tax rate by clicking the "New" button below the list `Tax Tables`.
You will get another dialog: 

![Create Tax Table]({{ site.baseurl}}/assets/new_btw_tariff_dialog.png)

Create an entry for every tax rate:

| Name tax table    | Type      | Value  | Account              |
|:------------------|:----------|-------:|:---------------------|
| VAT Sales 0%      | Percent % | 0      | 188 VAT Payable 0%   |
| VAT Expenses 21%  | Percent % | 21     | 180 VAT Receivable   |
| VAT Sales 21%     | Percent % | 21     | 185 VAT Payable 21%  |
| VAT Expenses 9%   | Percent % | 9      | 180 VAT Receivable   |
| VAT Sales 9%      | Percent % | 9      | 186 VAT Payable 9%   |


```
NB. In the original Accoo-manual the percentages were the first item in the name. In this manual they are the last item in the name.
The reason is that when entering invoices or bills the tax column is usually rather narrow, and in that way the percentages will be always visible.
```

In the dialog of the Tax Tables we now see the relation between the tax rate table and the corresponding account.

![Complete Tax table](/assets/existing_btw_tariffs.png)

