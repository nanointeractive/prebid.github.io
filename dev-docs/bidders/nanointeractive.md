---
layout: bidder
title: Nanointeractive
description: Prebid Nanointeractive bidder adapter
top_nav_section: dev_docs
nav_section: reference
hide: true
biddercode: nanointeractive
biddercode_longer_than_12: true
---

### bid params

{: .table .table-bordered .table-striped } 

| Name | Scope    | Description        | Example  |
| :--- | :----    | :----------        | :------  |
| sec   | required | Security code | `"111111"` |
| dpid   | required | Data partner id  | `"22222"` |
| pid   | required | Pixel id  | `"33333"` |
| nq   | optional | Search query  | `"BMW"` |
| category   | optional | Category  | `"AUTO"` |
| name   | optional | Url query param name (&nq=BMW)  | `"nq"` |
