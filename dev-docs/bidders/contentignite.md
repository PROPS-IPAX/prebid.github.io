---
layout: bidder
title: Content Ignite
description: Prebid Contnent Ignite Adaptor
top_nav_section: dev_docs
nav_section: reference
hide: true
biddercode: contentignite
biddercode_longer_than_12: true
prebid_1_0_supported : true
---


### bid params

{: .table .table-bordered .table-striped }
| Name        | Scope    | Description                          | Example      | Type     |
|-------------|----------|--------------------------------------|--------------|----------|
| `accountID` | required | Account ID                           | `'168237'`   | `string` |
| `zoneID`    | required | Zone ID                              | `'299680'`   | `string` |
| `keyword`   | optional | Keyword(s) used for custom targeting | `'business'` | `string` |
| `minCPM`    | optional | Minimum CPM value to accept          | `'0.10'`     | `string` |
| `maxCPM`    | optional | Maximum CPM value to accept          | `'5.00'`     | `string` |
