---
title: Code samples
permalink: /docs/code_samples/
---

[Provide a few complete code samples or snippets that users can copy and paste for common use cases. The idea is that your code samples will help users understand how to write their own code for your API.

You can start with cURL command line code samples, but you should add samples in other languages to address common needs, such as JavaScript for web browser code and Java and Swift for mobile developers.

## Code syntax

To specify language for your code blocks, follow the [Markdown code and syntax highlighting](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code-and-syntax-highlighting) section in Adam Pritchard's Markdown cheatsheet.]


Visualize.js
============

Visualize.js is a JavaScript API framework used to embed JasperReport Server reports & visualizations inside web applications.
It comes bundled with the commercial editions of TIBCO JasperReports® Server, specifically Jaspersoft AWS, Enterprise or
Professional (and as an add-on with Jaspersoft Reporting).

> In this guide you will find a full listing of Visualize.js API code samples.

> For greater detail also view the full [Visualize.js API reference guide].

[Download Jaspersoft >][Download JRS]

Installing Jaspersoft
----------------------
 
 *Note: All fiddles in this guide are live and available to view before install*
 
 * Download the commercial edition of [JasperReport Server]
 * Use our [quick start guide] for installation and configuration

Getting Started
---------------
 
 ### Live Fiddles
 
 View and reuse the live Visualize.js API samples in this guide and(or) reference to your own [installation]
 
 To use your own install change the following HTML in the fiddles... 
 
 ``` html
 <script src="http://visualizejsdemo.jaspersoft.com/jasperserver-pro/client/visualize.js"></script>
 ```
 
 and reference the location of your JasperReport Server installation...
 
  ``` html
 <script src="[myserver]/jasperserver-pro/client/visualize.js"></script>
 ```
 
 ### Video Tutorials
 
 * Need a jump start? Watch our [API video tutorials] for more information on Visualize.js and embedding inside your application.
 
 ### Via GitHub
 
 * Fork this Visualize.js API [sample set and guide] for your own use
 * Download our [sample application] on GitHub featuring Visualize.js

[Visualize.js API reference guide]: https://community.jaspersoft.com/documentation/tibco-jasperreports-server-visualizejs-guide/v62/api-reference-visualizejs
[JasperReport Server]: https://jaspersoft.com/download
[installation]: https://jaspersoft.com/download
[quick start guide]: https://jaspersoft.com/jaspersoft-quick-start-guide
[API video tutorials]: https://community.jaspersoft.com/wiki/visualizejs-tutorials
[sample set and guide]: https://github.com/TIBCOSoftware/JS-visualize
[sample application]: https://github.com/TIBCOSoftware/JS-FDSample

[Download JRS]: https://jaspersoft.com/download


Report Samples
=======

### Basic Embed

Try it:

<b>[Simple report rendering], [from a list]</b>

Initialization of the visualize.js library with simple rendering of an HTML report using plain text authentication. See full authentication samples in this guide for securing data and reports with the JasperReports Server and Visualize.js.

>You can easily change the resource to embed a different report from the JasperReport Server.

>For example:

``` javascript
        resource: "/public/Samples/Reports/SalesByMonthReport"
``` 

Try it:

<b>[Load multiple reports]</b>

Use a common configuration to load multiple reports.

### Pagination

Try it:

<b>[Next/previous]</b>, <b>[enter range]</b>, <b>[pagination events]</b>

Provide control for report pagination with either individual selectors or a directly inputed range. Also, see pagination with events for full control of inputs.

Try it:

<b>[Anchors]</b>, <b>[range with anchor]</b>, <b>[anchor and page search]</b>

Provide the ability to move quickly through reports with direct page anchors. Also see an anchor with a range of rendered pages and an example of searching both an anchor and page/range with an event to callout the current selection.
