---
type: "docs/scenarios"
title: Installation Common
description: Details on how to install krkn and krkn-hub
categories: [Installation]
tags: [install, docs]
weight: 2
---
{{< foundation_tabs tabs-id="ruby-python-go-panel" >}}
  {{< foundation_tab active="true" panel-link="ruby-panel" tab-text="Ruby">}}
  {{< foundation_tab panel-link="python-panel" tab-text="Python" >}}
  {{< foundation_tab panel-link="golang-panel" tab-text="Go" >}}
{{< /foundation_tabs >}}

{{< foundation_tabs_panels tabs-id="ruby-python-go-panel" >}}
  {{< foundation_tabs_panel active="true" panel-id="ruby-panel" >}}
  ```ruby
  puts 'Hello, world!'
  ```
  {{< /foundation_tabs_panel >}}

  {{< foundation_tabs_panel panel-id="python-panel" >}}
  ```python
  print('Hello, world!')
  ```
  {{< /foundation_tabs_panel >}}
  {{< foundation_tabs_panel panel-id="golang-panel" >}}
  ```go
  package main

  import "fmt"

  func main() {
      fmt.Println("Hello, world!")
  }
  ```
  {{< /foundation_tabs_panel >}}
{{< /foundation_tabs_panels >}}