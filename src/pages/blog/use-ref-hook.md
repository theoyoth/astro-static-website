---
id: 2
layout: "../../layouts/BlogPost.astro"
title: "useRef hook react"
description: "hook for managing state"
pubDate: "Oct 03 2022"
heroImage: "/useRef.jpg"
---

![useRef.jpg](/useRef.jpg)

useRef is a React Hook that lets you reference a value that’s not needed for rendering.

# Usage

## Referencing a value with a ref

#### Call useRef at the top level of your component to declare one or more refs.

```
import { useRef } from 'react';

function Stopwatch() {
const intervalRef = useRef(0);
// ...
```
