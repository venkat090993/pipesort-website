---
title: HOW TO WRITE AN INITIAL PRODUCT REQUIREMENT DOCS (2019-12-02)
date: 2019-09-16T12:51:00.000Z
---

Last week, I had a client who wanted a web app. He sent me an elaborate documentation including what framework I should use, what name I should give it to the component names. I told him, I couldn’t get an overview about what the app does because it had too much information. Either it is nothing or too much.

I’ll give a simple format that works best for me as a developer or consultant to understand the product or the idea of someone.

As a consultant I have turned down many jobs because we won’t be able to do it as it wasn’t our expertise or refer them to SAAS products like shopify, zohoCRM, etc. I have also had clients who wanted mobile app or web app, to whom I have suggested to go for a different medium (web/mobile/plugin).

The objective of the first email or the first call of mine is always to understand the product in simple terms without getting bogged down by too much information, so I can:

1.decide if we are the best fit for the client, if not suggest some other existing tool or someone else.

2.suggest what best medium, approach to use based on the little experience I have.

What I don’t need: There would be plenty of feature requests like notifying user on something happening, search, filter, many different add-on features. Also there would be flow on onboarding a certain user. Too much details — no!

What I need: There will always be a core or main element like the sun in a solar system. Most of the actions would be around it. There can be typically one or two main elements, maximum of 3.

Here is a sample initial product requirement docs:

## <a name="top"></a> Table of Contents

* [Business overview](#Businessoverview)
* [Primary elements](#Primaryelements)
* [My Goals](#Goals)
* [Other requirements](#Otherrequirements)
* [Inline elements](#Inline)

***

# <a name="Businessoverview"></a>Business overview

Arokiya is an e-commerce app. It helps the customers order groceries online.

<b>Users</b>: customers, admin, staff

Medium: PWA for customer. Web app for admin.

# <a name="Primaryelements"></a>Primary elements

<h3>Product</h3>

<p>Product is the grocery item listed by admin which can will be brought by the item.</p>

<b>Creation</b>: Creation: Admin creates the order

<h4>Life cycle:</h4>
<ul>
<li>Admin adds the product</li>
<li>Customer purchases the product through order</li>
<li>Admin updates the details and availability</li>
<li>Admin marks it “out of stock” if not available.</li>
</ul>

<h3>Order</h3>

<p>Order is a list of products chosen by the customer to be home delivered to them.</p>

<b>Creation</b>: Customer places the order

<h4>Life cycle:</h4>
<ul>
<li>Customer selects the items and adds them to their cart.</li>
<li>Customer provides the address, card details and makes the payment.</li>
<li>Staff delivers the product and marks the order “completed”.</li>
<li>Customer can return the product and get a refund if there are any issues.</li>
</ul>


# <a name="Goals"></a>My Goals

<h4>Life cycle:</h4>
<ul>
<li>To be the top online grocery shopping app in UK</li>
<li>Customers can purchase groceries at reasonable price, delivered at doorstep</li>
<li>To have an efficient order processing system.</li>
</ul>

# <a name="Otherrequirements"></a>Other requirements
<p>Build the front end as gatsbyjs static pages.</p>
<a href="https://www.notion.so/Initial-product-requirement-docs-274049163b4a4580ad6b71dc3952581a" target="_blank" >For more sample editable docs: https://www.notion.so/Initial-product-requirement-docs-274049163b4a4580ad6b71dc3952581a</a>


