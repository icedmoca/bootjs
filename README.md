# bootjs

>UEFI boot environment providing a fully programmable JavaScript interface at firmware stage. Built on a minimal kernel, custom framebuffer compositor, and embedded QuickJS engine, it supports a component-driven, declarative UI with animation, theming, and real input handling before any operating system loads. This architecture is the first to introduce a full scripting runtime into pre-OS execution space, enabling a flexible interface model that surpasses traditional static bootloaders.

*Prototype architecture. Core kernel, framebuffer API, and JS runtime integration under active development.*

## Goals

Declarative UI defined entirely in JavaScript

React-style component model

Real-time animation and event handling

Cross-OS chainloading

Extensible theming and layout system
