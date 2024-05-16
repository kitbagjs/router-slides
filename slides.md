---
title: Kitbag Router
author: Evan Sutherland
theme: apple-basic
layout: intro
---

# A New Vue Router
## @kitbag/router

<div class="intro__content">
  <div class="intro__logo-background" />
  <img class="intro__logo" src="/kitbag-logo.svg" />
</div>

---

# What I'll Cover

* Motivation
* Stretch Goals
* Developer Demo

---

# Motivation

* Add type safety
  * Worse case, route by paths `/somewhere/else`
  * Better, route by magic strings `{name: 'somewhere-else'}`
  * Best case, router has type for valid route names
* Include params in query
  * Treat params the same, regardless of where they live

---

# Stretch Goals

* Support different param types
  * Define params as `String`, `Number`, `Boolean`, `Regexp`, or your own custom type.
  * Only match routes when param type passes
* Built in rejection handling
  * Handle `notFound`, `authRequired`, or whatever other rejections you need.

---

# Developer Demo