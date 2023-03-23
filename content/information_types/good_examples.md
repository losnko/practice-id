---
weight: 11000
title: "Examples"
description: "Some excellent examples of information architecture"
titleIcon: "fa-solid fa-file-circle-plus"
categories: ["Information types"]
tags: ["Content management"]
---

# Examples of Information Types: 

When compiling information, there are specific examples of information types that a designer can follow, for instance:

## Site Mapping:

Refers to the process of creating a visual representation of a website’s structure, layout, and content.

{{< alert >}} Tap **+** to explore the interactive map of this site  {{< /alert >}}

{{< treeview
    rootpath="/"
    display="tree"
    init="collapse"
/>}}



## Inventory/Audit:

Refers to the process of examining and cataloguing a set of items or resources, usually to determine their value or quantity.

| Variable | Value | Description |
|---|---|---|
|A |123| This is an item|
|B |456| This is also an item|
|C |789| This was an item| 

## Diagram:

Refers to a visual representation of a system, process, or structure, usually using symbols or diagram to represent different components.

```mermaid
graph LR
    subgraph Activity 3
    c1(Action 3.0) --> c2(Action 3.1)
    a3 --> c1 
    c1 --> a3
    end
    subgraph Activity 2
    b1(Action 2.1) --> b2(Action 2.2)
    b3(Action 2.0) --> b2
    b2 --> a3
    end
    subgraph Activity 1
    a1(Action 1.1) --> a2(Action 1.2)
    a1 --> a3(Action 1.3)
    a2 --> a4(Finished)
    end
```

## Tree Structure:

Refers to a hierarchical structure, usually represented as a tree, with nodes and branches that represent different elements or categories.

For example, a treeview of this website:
{{< treeview rootpath="/" display="graph" />}}
