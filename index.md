@def title = "MyFranklin Sandbox"
@def hasmath = true
@def hascode = true

# Set up
## Update title
- All modification should be in index.md file
## Update config.md
- where to modify blog variable that affect the whole blog
- The footnote is store @ _layout/page_foot.html
  - the fd_mtime_raw show the time last modify time GMT.
    using fd_mtime_raw to change time format to ISO 8601 format
- Modify the author, site
- For github site add the repository name here

## Create a table of content
## Upload with Github desktop app
## Example
## How to insert a table from CSV file
## How to insert image
## How to insert clickable thumbnail to Youtube
## How ot inject raw html




<!-- 
# Franklin syntax sandbox

This page is meant as a sandbox for Franklin Syntax so that you can quickly practice or experience things.

## Sandbox

Write whatever you want here to practice Franklin Syntax:

```julia:./ex1
using LinearAlgebra, Random
Random.seed!(135)
a, b = randn(50), randn(50)
println(dot(a, b))
println(sum(ai * bi for (ai, bi) ∈ zip(a, b)))
```

\output{./ex1}

(yet another example that floating point arithmetics can be complicated).

$$ \forall x \in \R:\quad \scal{x, x} \ge 0 $$

\newcommand{\E}{\mathbb E}

Surely some people remember the ordering, but I always forget:

$$ \varphi(\E[X]) \le \E[\varphi(X)] $$

for $\varphi$ convex. -->
