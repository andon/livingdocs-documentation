---
title: li-named-crops
type: metadata-plugins
menus:
  reference:
    parent: Metadata Plugins
summary: Define Named Crops on a Media Library Image.
support:
  document: false
  media: true
  tableDashboard: false
  include: false
  displayFilter: false
  dynamicIndexing: false
  systemMetadata: false
  planningSystem: false
description: Define Named Crops on a Media Library Image.
defaultUI: Crop management
storageFormat: |
  {
    crops: [
      {
        name: <String>,
        x: <Integer>,
        y: <Integer>,
        width: <Integer>,
        height: <Integer>,
        isAutomatic: <Boolean>
      }
    ],
    focalPoint: {
      x: <Integer>,
      y: <Integer>
    }
  }
contentTypeConfig: |2
        handle: 'myHandle'
        type: 'li-named-crops'
---