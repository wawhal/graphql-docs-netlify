---
description: |
  This is a test query to my own fork
contributedBy: "@wawhal"
variables: ""
title: "GetUsers"
result: |
  null
---

```graphql
query GetTenUsers ($limit: Int = 10) {
  user (limit:$limit) {
    id
  }
}
```
