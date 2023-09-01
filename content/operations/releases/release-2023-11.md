---
type: release-notes
title: November 2023 Release
description: Technical Release Notes for release-2023-11
excludeFromSearch: true
hideSectionTeaser: true
aliases:
  - /operations/releases/release-2023-11/
  - /operations/releases/release-2023-11/release-2023-11/
---

{{< release-header
  title="November 2023 Release"
  upcoming=true
  legacy=false
  current=false
  maintained=false
  branchHandle="release-2023-11"
>}}

## Caveat :fire:

These are the release notes of the upcoming release (pull requests merged to master).

- :information_source: this document is updated automatically by a bot (pr's to categorize section)
- :information_source: this document will be roughly updated manually once a week (put PRs + description to the right section)
- :fire: We don't guarantee stable APIs. They can still change until the official release
- :fire: Integration against the upcoming release (currently `master` branch) is at your own risk

## PRs to Categorize
* [Apply base filters in quick search](https://github.com/livingdocsIO/livingdocs-editor/pull/7399)
* [Fix comments parsing error](https://github.com/livingdocsIO/livingdocs-editor/pull/7383)
* [fix(deps): update dependency fastify from 4.22.0 to v4.22.1 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/6093)
* [fix(deps): update dependency fastify from 4.22.0 to v4.22.1 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/7395)
* [fix(deps): update dependency cypress from 12.17.4 to v13 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/7378)
* [Fix/editor scrolling #5028](https://github.com/livingdocsIO/livingdocs-editor/pull/7389)
* [Update references after running hooks](https://github.com/livingdocsIO/livingdocs-server/pull/6055)
* [Handle errors in custom getDocumentIds include functions](https://github.com/livingdocsIO/livingdocs-server/pull/6078)
* [Change supported browser versions as we're using newer apis](https://github.com/livingdocsIO/livingdocs-editor/pull/7388)
* [fix(deps): update dependency aws-sdk from 2.1444.0 to v2.1448.0 (master) - autoclosed](https://github.com/livingdocsIO/livingdocs-server/pull/6074)
* [fix(deps): update dependency @babel/preset-env from 7.22.10 to v7.22.14 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/7356)
* [Convert li-poster-image metadata plugin form to Vue](https://github.com/livingdocsIO/livingdocs-editor/pull/7344)
* [fix(deps): update dependency fastify from 4.21.0 to v4.22.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/6076)
* [fix(deps): update dependency @livingdocs/framework from 26.0.1 to v26.1.1 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/6088)
* [fix(deps): update dependency @livingdocs/framework from 26.0.1 to v26.1.1 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/7359)
* [Streamline when removed component label or removed text label is shown](https://github.com/livingdocsIO/livingdocs-editor/pull/7382)
* [Allow li-image metadata plugin to be used in media library metadata](https://github.com/livingdocsIO/livingdocs-editor/pull/7333)
* [Fix display filters erroring without store on multilist viewer](https://github.com/livingdocsIO/livingdocs-editor/pull/7384)
* [fix(editableCount): updated name](https://github.com/livingdocsIO/livingdocs-editor/pull/7379)
* [fix(viewEvents): make blur editable fire before blur component](https://github.com/livingdocsIO/livingdocs-editor/pull/7375)
* [Truncate document title on creation](https://github.com/livingdocsIO/livingdocs-server/pull/6084)
* [fix: pass image original dimensions for crop preview](https://github.com/livingdocsIO/livingdocs-editor/pull/7343)
* [Update `nzz` downstream branch to `release-2023-11`](https://github.com/livingdocsIO/livingdocs-editor/pull/7373)
* [Update `nzz` downstream branch to `release-2023-11`](https://github.com/livingdocsIO/livingdocs-server/pull/6083)


To get an overview about new functionality, read the [Release Notes](TODO).
To learn about the necessary actions to update Livingdocs to `release-2023-11`, read on.

**Attention:** If you skipped one or more releases, please also check the release-notes of the skipped ones.

## Webinar

* Feature Webinar Recording: **TODO**
* Feature Webinar Documentation: **TODO**
* Dev Webinar Recording: **TODO**
* Dev Webinar Slides: **TODO**
* [Release Newsletter Subscription](https://confirmsubscription.com/h/j/61B064416E79453D)

## System Requirements

### Suggested

TODO

### Minimal

TODO

## Breaking Changes 🔥

### Migrate the Postgres Database :fire:

It's a simple/fast migration with no expected data losses.

```sh
# run `livingdocs-server migrate up` to update to the newest database scheme
livingdocs-server migrate up
```

TODO: check migration

## Deprecations

## APIs :gift:

## Features

TODO (featureset not 100% defined yet)

## Vulnerability Patches

We are constantly patching module vulnerabilities for the Livingdocs Server and Livingdocs Editor as module fixes are available. Below is a list of all patched vulnerabilities included in the release.

### Livingdocs Server

### Livingdocs Editor


## Patches

Here is a list of all patches after the release has been announced.

### Livingdocs Server Patches

### Livingdocs Editor Patches


  ---
  **Icon Legend**
  * Breaking changes: :fire:
  * Feature: :gift:
  * Bugfix: :beetle:
  * Chore: :wrench: