JSON at Work: Search and Transform
==================================

## Description
Most modern Web APIs prefer JSON because of its interoperability. All modern languages have excellent JSON support, but large-scale environments often require more than simple serialization/de-serialization. This tutorial shows how to leverage JSON Search and Transform to help developers consume and work with the content generated by RESTful JSON-based APIs.

## Abstract
Most front-end developers interact with JSON by making an AJAX call and processing the results. Backend developers wrestle with serializing/de-serializing objects to/from JSON. But JSON has so much more to offer to Developers and Architects to help design and build large-scale systems of APIs.

### JSON Search
Web APIs aren't always well-designed, and can generate data that is too complex or voluminous to be useful. Sometimes consuming applications only want to access a portion of an API’s JSON response. There are several ways to search through a JSON document, including:
* JSONPath
* jsoniq
* JSON Pointer
* JSONQuery
* json:select
* JPath
* jaql

### JSON Transform
Sometimes an API Consumer may need to change the JSON data returned by an API. 

#### JSON to JSON
There are a couple techniques to modify a JSON document, including:
* JSON T
* JSON 2 JSON
* JSON Patch

#### Other Formats to JSON
In other cases, a developer may need to convert from other formats to JSON, including:
* CSV (Comma-Seprated Values)
* XML

#### JSON to HTML
Finally, we'll look at [Mustache.js](https://github.com/janl/mustache.js/) to convert JSON to HTML.

## What Do I Get Out of It?
This session will show practical JSON Search and Transform development tools and techniques to improve overall application design.

## Prerequisites
Prior knowledge of JavaScript and familiarity with JSON and Node.js.

## Required Installs
Before coming to this session, please install the following:
* [Node.js](https://github.com/tmarrs/json-at-work/blob/master/appendix-a/Appendix-A-README.md#installing-nodejs)
* [Yeoman](https://github.com/tmarrs/json-at-work/blob/master/appendix-a/Appendix-A-README.md#installing-yeoman)
* [Yeoman `webapp` generator](https://github.com/tmarrs/json-at-work/blob/master/appendix-a/Appendix-A-README.md#installing-the-webapp-yeoman-generator)

## Session Length
60 minutes