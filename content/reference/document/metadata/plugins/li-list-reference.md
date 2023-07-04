---
title: li-list-reference
type: metadata-plugins
menus:
  reference:
    parent: Metadata Plugins
support:
  document: true
  media: false
  tableDashboard: false
  include: true
  displayFilter: false
  dynamicIndexing: true
  systemMetadata: false
  planningSystem: false
defaultUI: Selected list, or list selection dialog
storageFormat: |
  {
    $ref: 'list',
    reference: {
      id: <String>,
      count: <Integer>,
      priority: <Integer>
    }
  }
contentTypeConfig: |2
        handle: 'myHandle'
        type: 'li-list-reference',
        config: {
          // common
          hideFromForm: false,                     // optional, default: false
          required: true,                          // optional, default: false
          requiredErrorMessage: 'Provide a value',  // optional
          // specific
          defaultCount: true
        }
---