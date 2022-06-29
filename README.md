<style>
th{ background-color: #343a98!important; color: #fff!important; }
</style> 

![Tax Agile Logo](docs/Tax-Agile-Short.png)

[Home](../README.md) \| [Getting started](docs/getting-started.md) \|  [Postman](docs/postman.md) \| [Swagger](docs/swagger/index.html)

# Developer Hub
The Tax Agile Developer Hub contains resources for developers integrating with Tax Agile. 

It includes [API Swagger OAS3 docs](docs/swagger/index.html), [sample API requests](docs/postman.md) and documentation to [get started](docs/getting-started.md).

The Hub is hosted on GitHub and you can report issues to us using the GitHub Issues functionality.

# Overview of the API
[![Generic badge](https://img.shields.io/badge/Version-v1.0.1-green.svg)](https://shields.io/)

In this version of the API you have methods to authenticate and invoke the VAT Determination API.

```mermaid
    flowchart TD;
        A[deploy] --> B(foo);
     
```


```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```