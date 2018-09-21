+++
date = "Fri Jun  8 13:46:49 MSK 2018"
title = "Go AVX-512 support"
tags = [
    "[go]",
    "[asm]",
    "[avx-512]",
]
description = "Your guide in Go AVX-512 world. Links to docs, articles and so on."
draft = false
+++

## About this document

This article is going to be up-to-date source of AVX-512 information in Go context.  
It references other posts, official documentation and other useful resources.

It's short. By purpose.  
Only English content is referenced (original + translated).

## Documentation

* [AVX-512 support in Go assembler](https://github.com/golang/go/wiki/AVX-512-support-in-Go-assembler):
  short reference that focuses on Go-specific implementation of AVX-512.
  It describes how to use all AVX-512 special features in Go assembly syntax as well as some encoder details.
  Contains some examples.

* [Disassembling Go AVX-512](/blog/post/disassembling-go-avx512):
  how to disassemble and inspect AVX-512 machine code (given that `go tool objdump` can't do it).

* [Hardware counters collector](https://github.com/intel-go/avx512counters):
  a program that runs all supported AVX-512 instructions on your machine and records turbo state perf events.
  There are pre-built example tables like [avx512_core_i9_7900x.csv](https://github.com/intel-go/avx512counters/blob/master/avx512_core_i9_7900x.csv).
