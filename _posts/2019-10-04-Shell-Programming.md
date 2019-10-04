---
title: Shell Programming
comments: true
tags: Technical
---

1. Hello World

```bash
#!/bin/bash
echo "Hello World!"
```

2. Creating Linux User and Password by using path variabls

```bash
#!/bin/bash
#$1 is the first variable,$2 is the second variable

useradd "$1"

echo "$2" | passwd ‐‐stdin "$1"
```








---

