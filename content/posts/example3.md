---
date: "2021-08-03T11:11:11+01:00"
description: This is desc 3
draft: false
title: Example 3
type: post
---

```haskell
factorial n = go n 1
    where
    go n res
        | n > 1     = go (n - 1) (res * n)
        | otherwise = res
```