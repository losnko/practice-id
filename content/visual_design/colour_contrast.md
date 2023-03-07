---
weight: 2000
title: "Colour Contrast"
description: "Descriptions and examples of accessible colour contrast information."
titleIcon: "fa-solid fa-circle-half-stroke"
categories: ["Visual design"]
tags: ["Content management"]
---
# Colour contrast

## Additionally, this project features callouts:
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
