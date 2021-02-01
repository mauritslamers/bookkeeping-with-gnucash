---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Welcome
permalink: /
nav_order: 0
---

_**Warning:** This manual is far from complete. All remarks as well as proposals for improvements are very welcome._
_Also, this is a quick translate from the Dutch version, so all screen shots will be in Dutch initially._
_Please use the [GitHub Issues](https://github.com/mauritslamers/bookkeeping-with-gnucash/issues) or send a pull request!_

_Thanks in advance!_

<hr>

## Bookkeeping with GnuCash

Welcome to this manual of GnuCash, an open source computer program which enables you to do your own bookkeeping.

This manual is intended specifically for one-person-businesses in the Dutch environment. At the same time, European countries use similar 
approaches, so many things might also be applicable in other European countries. We will look at how to deal with VAT and how GnuCash can do most if not
all calculations for you, and even do your invoice layout..

## Accounting scheme: Invoice or Cash
Before we go any further, it is important to establish whether your company should keep an Invoice scheme or a Cash scheme for the VAT.
In the Dutch environment there are two types of VAT-schemes.

The Invoice scheme is a scheme in which you send invoices for products or services. You need to keep an administration in which you need to keep the amount of VAT you need to pay, or get back. In this situation it doesn't matter whether the customer already paid the invoice: as soon as you write the invoice, you are obliged to pay the VAT on it.

The Invoice scheme works fine for many companies, but very impractical for companies who work mainly with direct selling, such as supermarkets or market salesmen. That is why these companies in the Dutch system are required to use the Cash scheme. These companies only have to pay VAT on the products they actually sold. Have a look on the Dutch website for the Tax Services for more information (Dutch only):

[Belastingdienst: Voor wie geldt het kasstelsel](https://www.belastingdienst.nl/wps/wcm/connect/bldcontentnl/belastingdienst/zakelijk/btw/btw_aangifte_doen_en_betalen/bereken_het_bedrag/hoe_berekent_u_het_btw_bedrag/kasstelsel/voor_wie_geldt_het_kasstelsel)

This manual assumes you are using the invoice scheme.

### Bookkeeping? Why?

If this is the first time you ever do something with bookkeeping, you better read the page [Why bookkeeping]({{site.baseurl}}/why_bookkeeping) first.
Additionally, it is good to read the [short introduction]({{ site.baseurl}}/double_bookkeeping) about the how and why of the so-called double bookkeeping system.

### To work
This manual uses a layout in which step by step both the actions as well as how to do these actions within GnuCash are being explained, as well as
giving you the opportunity to quickly look up things when you are already familiar with GnuCash.

If you are create a new bookkeeping or you want to transfer a current system, choose [Bookkeeping Setup]({{ site.baseurl}}/setup).

## Why this manual?

This manual is based on the Dutch GnuCash manual originally published as a set of blog posts at http://www.accoo.nl/handleiding-gnucash/.
I experience this manual as very useful, but the layout didn't offer much of an overview, and the content was a bit dated.
The purpose of this manual is to save the content of this Accoo-manual as well as improve on it by updating it and adding practical solutions.


## Licence
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons-License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International licence</a>.


<!-- Lees hier over veelvoorkomende handelingen. -->
<!-- [See configuration options]({{ site.baseurl }}{% link pages/test.md %}) -->