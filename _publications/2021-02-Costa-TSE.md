---
title: "Breaking Type-Safety in Go: An Empirical Study on the Usage of the unsafe Package"
collection: publications
authors: 'Diego Costa,  Suhaib Mujahid,  Rabe Abdalkareem,  Emad Shihab'
permalink: /publication/2021-02-Costa-TSE
date: 2021-02-01
venue: 'IEEE Transactions on Software Engineering Journal (TSE)'
series: 'TSE&apos;21'
preprent: '/papers/Costa_TSE2021.pdf'
---
 **Abstract:**  A decade after its first release, the Go programming language has become a major programming language in the development landscape. While praised for its clean syntax and C-like performance, Go also contains a strong static type-system that prevents arbitrary type casting and arbitrary memory access, making the language type-safe by design. However, to give developers the possibility of implementing low-level code, Go ships with a special package called unsafe that offers developers a way around the type-safety of Go programs. The package gives greater flexibility to developers but comes at a higher risk of runtime errors, chances of non-portability, and the loss of compatibility guarantees for future versions of Go. In this paper, we present the first large-scale study on the usage of the unsafe package in 2,438 popular Go projects. Our investigation shows that unsafe is used in 24% of Go projects, motivated primarily by communicating with operating systems and C code but is also commonly used as a source of performance optimization. Developers are willing to use unsafe to break language specifications (e.g., string immutability) for better performance and 6% of analyzed projects that use unsafe perform risky pointer conversions that can lead to program crashes and unexpected behavior. Furthermore, we report a series of real issues faced by projects that use unsafe, from crashing errors and non-deterministic behavior to having their deployment restricted from certain popular environments. Our findings can be used to understand how and why developers break type-safety in Go and help motivate further tools and language development that could make the usage of unsafe in Go even safer.

DOI: [10.1109/TSE.2021.3057720](https://doi.org/10.1109/TSE.2021.3057720){:target="_blank"}
