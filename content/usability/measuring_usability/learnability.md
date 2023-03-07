---
weight: 16000
title: "Learnability"
description: "How learnability impacts measuring usability"
titleIcon: "fa-solid fa-plug"
categories: ["Usability"]
tags: ["User experience"]
---
# Headings

The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Paragraph

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

#### Blockquote without attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use *Markdown syntax* within a blockquote.

#### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

Tables aren't part of the core Markdown spec, but Hugo supports them out-of-the-box.

   Name | Age
--------|------
    Bob | 27
  Alice | 23

#### Inline Markdown within tables

| Italics   | Bold     | Code   |
| --------  | -------- | ------ |
| *italics* | **bold** | `code` |

## List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

* List item
* Another item
* And another item

#### Nested list

* Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese

## Code Blocks

#### Code block with backticks

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```
Additionally, this project features callouts:
{{< alert type="info" >}} This an example of **info** type callout/alert{{< /alert >}}
{{< alert type="success" >}} This an example of **success** type callout/alert{{< /alert >}}
{{< alert type="warning" >}} This an example of **warning** type callout/alert{{< /alert >}}
{{< alert type="error" >}} This an example of **error** type callout/alert{{< /alert >}}

### Blockquotes

{{< blockquote source="Santa Clause" >}}Ho, ho, ho! Information Architecture{{< /blockquote >}}

### Drawers

{{< collapsible >}}These collapsible blocks help reduce information displayed on screen at one time{{< /collapsible >}} 

### Data visualizations
{{< highcharts
  id="highcharts1"
  assets=""
  source="/highcharts/example-default.json"
>}}

### Project management

{{< highcharts
  id="highcharts2"
  assets="js/external/highcharts/modules/gantt.min.js"
  source="/highcharts/example-gantt.json"
>}}

### Information tree

{{< treeview
    display="tree"
>}}
[{
    "kind": "dir",
    "label": "***Directory***",
    "content": [{
            "kind": "archive",
            "label": "***Archive***",
            "content": [{
                    "kind": "dir",
                    "label": "***Directory** in an archive*",
                    "content": [{
                            "kind": "file",
                            "label": "***Flat file** in a directory in an archive*"
                        }]
                },{
                    "kind": "file",
                    "label": "***Flat file** in an archive*"
                }]
        },{
            "kind": "file",
            "label": "***Flat file** in a directory*"
        }]
},{
    "kind": "default",
    "label": "***Default***"
},{
    "kind": "dir",
    "label": "***Directory***"
},{
    "kind": "file",
    "label": "***File***"
},{
    "kind": "home",
    "label": "***Home***"
},{
    "kind": "page",
    "label": "***Page***"
},{
    "kind": "section",
    "label": "***Section***"
},{
    "kind": "taxonomy",
    "label": "***Taxonomy***"
},{
    "kind": "term",
    "label": "***Taxonomy's term***"
},{
    "kind": "archive",
    "label": "***Archive***"
},{
    "kind": "image",
    "label": "***Image file***"
},{
    "kind": "video",
    "label": "***Video file***"
},{
    "kind": "script",
    "label": "***Script***"
},{
    "kind": "dockerfile",
    "label": "***Dockerfile***"
},{
    "kind": "pdf",
    "label": "***PDF file***"
},{
    "kind": "powerpoint",
    "label": "***PowerPoint file***"
},{
    "kind": "excel",
    "label": "***Excel file***"
},{
    "kind": "csv",
    "label": "***CSV file***"
},{
    "kind": "word",
    "label": "***Word file***"
}]
{{< /treeview >}}
