---
title: strings.Replace
description: Returns a copy of INPUT, replacing all occurrences of OLD with NEW.
categories: []
keywords: []
params:
  functions_and_methods:
    aliases: [replace]
    returnType: string
    signatures: ['strings.Replace INPUT OLD NEW [LIMIT]']
aliases: [/functions/replace]
---

```go-html-template
{{ $s := "Batman and Robin" }}
{{ replace $s "Robin" "Catwoman" }} → Batman and Catwoman
```

Limit the number of replacements using the `LIMIT` argument:

```go-html-template
{{ replace "aabbaabb" "a" "z" 2 }} → zzbbaabb
```
