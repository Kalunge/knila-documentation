---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell
  - ruby
  - python
  - javascript

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true

code_clipboard: true

meta:
  - name: description
    content: Documentation for the Kittn API
---

# Introduction

Welcome to the Line 5 API! You can use our API to access Line 5  API endpoints, which can get information loans.

Line 5 partners with dealers like you to fully fund vehicle protection plans for Automobiles, SUVs, Trucks and more. With guaranteed approvals and zero down payment requirements, your customers get the coverage they want at a payment they can afford. You sell more products and make more money.


## Get All loans

This endpoint retrieves all kittens.

### HTTP Request

`GET https://staging.line5.com/admin/quotes`

> The above command returns JSON structured like this:

```json
[
  {
    "id": 1,
    "name": "Titus",
    "dare": "02/05/2022",
    "Total amount": 6000,
    "MOnthly payment": 7,
    "APR" : 45.00,
    "Term": "10 mo",
    "products" : 1
  },
  {
    "id": 2,
    "name": "Arul",
    "dare": "02/05/2022",
    "Total amount": 6000,
    "MOnthly payment": 7,
    "APR" : 45.00,
    "Term": "10 mo",
    "products" : 1
  },
]
```


