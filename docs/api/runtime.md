---
title: "@messageformat/runtime"
parent: API Reference
has_children: true
has_toc: false
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->



# runtime package

A collection of runtime utility functions

## Remarks

This package should be marked as a dependency for any package that publishes the output of [compileModule()](./core.compilemodule.md)<!-- -->, as it may be included in its ES module source output as a dependency.

For applications that bundle their output using e.g. Webpack this is not necessary.

The `Messages` accessor class is a completely optional addition. See also [@messageformat/react](./react.md) for a React-specific solution.

## Classes

|  Class | Description |
|  --- | --- |
|  [Messages](./runtime.messages.md) | Accessor class for compiled message functions generated by [compileModule()](./core.compilemodule.md) |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [MessageData](./runtime.messagedata.md) | Hierarchical message object |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [MessageFunction](./runtime.messagefunction.md) | A message function, as generated by [MessageFormat.compile()](./core.messageformat.compile.md) |
