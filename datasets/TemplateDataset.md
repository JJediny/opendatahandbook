---
layout: wrapper_text
category: datasets

# Basic
identifier: "100,766"
title: "Travel Warnings"
describedBy: "http://travel.state.gov/_res/rss/TWs.xml"
description: "Travel Warnings are issued to describe long-term, protracted conditions that make a country dangerous or unstable. A Travel Warning is also issued when the U.S. Government's ability to assist American citizens is constrained due to the closure of an embassy or consulate or because of a drawdown of its staff."
programCode: "014:003"
bureauCode: "014:00"

# Dates
modified: "2009-08-07"

# POC
poc:
  type: ""
  fn: ""
  hasEmail: ""

# Publisher
publisher:
  type: "org:Organization"
  name: "U.S. Department of State"

# Spatiotemporal
spatial: "World"
temporal: "2007-01-01T00:00:01Z/2013-10-01T23:59:59Z"

# Distribution
distribution:
  - type: dcat:Distribution
    downloadURL: "http://travel.state.gov/_res/rss/TWs.xml"
    mediaType: "text/XML"
  - type: dcat:Distribution
    accessURL: "http://travel.state.gov/_res/rss/TWs.xml"
    format: "text/XML"

# Keywords
keywords:
  - "-"

published: true
layout: dataset
type: datasets
# NOTE see https://project-open-data.cio.gov/v1.1/metadata-resources/#field-mappings for HELP
modified: YYYY-MM-DD
title: "Dataset Title"
lead: "Introduction Text"
# NOTE description should = lead
description: "Abstract"
identifier: "UniqueID or Permalink"
license: "http://creativecommons.org/publicdomain/mark/1.0/"
rights: "Attribution"
spatial: "Place/WKT/GeoJSON/BBOX"
modified: YYYY-MM-DD
keywords: [one, two, three]
themes: [one, two, three]
references: [URL, URL, URL]
bureauCode: 000:00
programCode: 000:00
# NOTE see http://goals.performance.gov/sites/default/files/images/FederalProgramInventory_FY13_MachineReadable_091613.xls
accessLevel: public
#publisher:
officeName: Office
programName: Service/Bureau/Program
agencyName: Agency/Department
govName: U.S. Government
contactPoints:
  - name: Name
    email: Email
    role: Title
distributions:
  - downloadURL: "/_data/redirect.html"
    format: HTML
    mediaType: text/html
  - downloadURL: "/_data/linkto.csv"
    format: CSV
    mediaType: text/csv  
  - downloadURL: "/_data/linkto.zip"
    format: ZIP
    mediaType: application/zip
  - downloadURL: "/_data/linkto.json"
    format: JSON
    mediaType: application/json
  - downloadURL: "/_data/linkto.xls"
    format: XLS
    mediaType: application/vnd.ms-excel
  - downloadURL: "/_data/linkto.pdf"
    format: PDF
    mediaType: application/pdf
  - downloadURL: "/permalink.json"
    format: API
    mediaType: application/+json
    accessURL: "https://project-open-data.cio.gov/v1.1/api/"
    description: ""
    conformsTo: "URL"
    describedBy: "URL"
    describedByType: "URL"

## Optional Fields ##
#isPartOf: "@Collection"
#See https://github.com/project-open-data/project-open-data.github.io/blob/master/v1.1/collections.md"
#temporal: YYYY-MM-DDT12:00:00Z/YYYY-MM-DDT12:00:00Z
#issued: YYYY-MM-DD
#conformsTo: "Data Standard"
#describedBy: "Data Dictionary"
#describedByType: "Data Dictionary Type"

## Optional Default Overrides ##
#landingPage: "/_dataset/thispost.md"
#dataQuality: true
#systemOfRecords: "URL"
#language: en
#primaryITInvestmentUII: "#"
#accrualPeriodicity: "R/P1Y"

# NOTE accessURL/conformsTo/describedBy/describedByType/description/title are optional for common mediaTypes http://www.iana.org/assignments/media-types/media-types.xhtml

# NOTE `format` should be based on mediaType
# NOTE where is `attribution` field?
# NOTE `publisher` names should be dynamic based on converting `bureauCode` & `programCode`
---
