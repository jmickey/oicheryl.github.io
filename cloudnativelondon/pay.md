---
layout: page
title: Payment methods for Cloud Native London
description: "Pay Cloud Native London by bank transfer, direct debit, credit or debit card."
---

Monthly sponsors usually pay through a direct debit. The payment goes out on the
15th of each month.

<button onclick="location.href='https://pay.gocardless.com/AL00022PZ8R1ZJ'" type="button">
         Set up direct debit</button>

For one-off payments, make the bank transfer to:

> **Amount:** £600.00  
> **Payee name:** Cloud Native London Ltd  
> **Sort code:** 60-83-71  
> **Account number:** 57049586  
> **IBAN:** GB33SRLG60837157049586  
> **SWIFT/BIC:** SRLGGB2L  
> **Reference:** See invoice   

We can also raise an invoice for 3/6/12 months (£1800/£3600/£7200) in one go.

Alternatively, you can make a card payment:

{% if jekyll.environment == "production" %}
{% include stripe.html %}
{% else %}
{% include stripe-test.html %}
{% endif %}
