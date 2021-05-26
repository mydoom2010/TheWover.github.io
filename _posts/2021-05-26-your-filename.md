---
published: true
---
---
layout: post
title: New
---

*TLDR: One of the ways to load .NET Assemblies through unmanaged code is to use C++/CLI. What is that, you may ask? It is Visual C++ that can be compiled to CIL rather than native machine code. You may specify that code is either managed or native. Native code is written the same as normal C++. The managed version, however, uses a different syntax. To compile managed C++, you must use the /clr option on the Visual Studios compiler. This repo provides some code samples that demonstrate how to do this. Warning, the code is a bit wonky. That is partly because I've never gotten around to cleaning it up and also because this is just meant to make you aware that C++/CLI is a thing.*

Note: This project is not presented with my usual quality. :-) I got it working a while ago and have never got around to finishing it. Rather than leave it around collecting dust, I have cleaned it up a bit and put together an explanation. Hopefully it helps.

# Advancing Tradecraft - Context
