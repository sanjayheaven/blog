---
title: "Go 语言之 context"
date: "2024-01-16T14:33:44+08:00"
draft: true
---

# Go 语言之 context

## 什么是 context

context 是 Go 语言中的一个标准库，主要用于在多个 goroutine 之间传递上下文信息，它是线程安全的。

### emptyCtx

这个是 context 的零值，也就是说当我们没有显式的创建 context 的时候，就会使用这个值。
