---
title: Telerik.Web.UI.OrgChartGroupItemRendererLite
page_title: Telerik.Web.UI.OrgChartGroupItemRendererLite
description: Telerik.Web.UI.OrgChartGroupItemRendererLite
---

# Telerik.Web.UI.OrgChartGroupItemRendererLite

Represents the renderer of Telerik.Web.UI.OrgChartGroupItem OrgChartGroupItemin Lightweight render mode.

#### Remarks
Renders OrgChartGroupItem.
            All renderers are attached to the control's tree during PreRender stage.

## Inheritance Hierarchy

* System.Object
* System.Web.UI.Control
* System.Web.UI.WebControls.WebControl
* Telerik.Web.UI.OrgChartGroupItemRendererBase : INamingContainer, IOrgChartFieldsRenderer
* Telerik.Web.UI.OrgChartGroupItemRendererLite

## Properties

###  Collapsed `Boolean`

Gets or sets the Node collapsed state

#### Remarks
Determines what CSSClass to render on the Expand/Collapse Node

###  EnableCollapsing `Boolean`

Gets or sets if collapsing is enabled.

###  HasNodes `Boolean`

Gets or set whether the Node has nodes

#### Remarks
Used to determine if the Node is the last and not to render an expand/collapse arrow on it

###  HasNodesForLoad `Boolean`

Gets or set whether the Node has nodes for load

#### Remarks
Used to determine if the Node is the last and to render an expand/collapse arrow on it in web service binding

###  TagKey `HtmlTextWriterTag`

The default HtmlTextWriterTag is overrided to li or div(depends on if the item's GroupItemCollection is a group)

#### Remarks
The base HtmlTextWriterTag is span.

