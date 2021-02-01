---
layout: page
title: New customer
permalink: /new_customer
parent: Sales invoice
nav_order: 1
---

## Create a customer

If you do not have any customers in your system, the first thing to do is to create one.
Choose the menu "Business", choose the option "Customer" and then the suboption "New Customer".

![Menu nieuwe klant]({{site.baseurl}}/assets/menu_new_customer.png)

Before you start to fill any fields, it is important that you know which customer number this customer is going to get.
If you already sent invoices before with customer numbers and you want the numbering to continue, choose "File", "Properties" and choose the 
tab "Counters". Here you fill in the last customer number you gave out. If this number is 4587, the first new customer will get number 4588 automatically.

If you do not have an administration yet, you can choose anumber yourself. If you don't fill in anything, GnuCash will start at 1.
The next customer will get number 2 etc.

Now fill in the following fields

* **Customer number**: If this customer is not a new customer to your company, you fill in the number of that customer. If it is a new customer, leave the field empty. GnuCash will fill it in when you save the customer.
* **Company name**: The name of the company of the customer
* **Active**: Indicates whether a customer is active. It is normally left marked.
* **Name**: Name of the contact person at this customer
* **Address**: Address of the customer
* **Phone**: Telephone number, can be left empty
* **Fax**: Fax number, usually left empty nowadays
* **E-mail**: E-mail address of the customer
* **Notes**: Usually left empty.

The fields "Customer Number", "Company Name", "Name", and "Address" are used for the printed invoice.

![Nieuwe klant]({{site.baseurl}}/assets/new_customer_dialog.png)

The second tab of this dialog consists of fields detailing billing options. 

![Nieuwe klant factuurgegevens]({{site.baseurl}}/assets/new_customer_invoice_properties_dialog.png)

* **Terms**: Used to determine default billing terms for this customer. We will look at this more specifically at [Create Billing terms]({{site.baseurl}}/sales_invoice/billing_terms).
* **Discount**: A way to set a default discount for a customer. You can also put a discount on every item separately when entering the invoice.
* **Credit Limit**: the maximum amount that this customer can have in unpaid invoices.
* **Tax included**: Is this customer exempt from VAT? If Yes, put No here.
* **Tax Table**: Predetermine the VAT rate this customer is going to pay. When entering the invoice, you can also decide this per item.

We can leave this empty now, and come back to this later.

The tab "Shipping address" can be used to register a shipping address. This will normally not be on the invoice.

Click OK to save the customer.

If you did not create any billing terms, continue at the page [Create Billing terms]({{site.baseurl}}/billing_terms).


