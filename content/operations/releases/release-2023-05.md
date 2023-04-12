---
type: release-notes
title: May 2023 Release
description: Release notes for release-2023-05
excludeFromSearch: true
hideSectionTeaser: true
aliases:
  - /operations/releases/release-2023-05/
  - /operations/releases/release-2023-05/release-2023-05/
---

{{< release-header
  title="May 2023 Release"
  upcoming=true
  legacy=false
  current=false
  maintained=false
  branchHandle="release-2023-05"
>}}

## Caveat :fire:

These are the release notes of the upcoming release (pull requests merged to master).

- :information_source: this document is updated automatically by a bot (pr's to categorize section)
- :information_source: this document will be roughly updated manually once a week (put PRs + description to the right section)
- :fire: We don't guarantee stable APIs. They can still change until the official release
- :fire: Integration against the upcoming release (currently `master` branch) is at your own risk

## PRs to Categorize
* [fix(deps): update dependency @livingdocs/framework from 24.13.3 to v24.13.4 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5551)
* [Remove support for `search.host` server configuration](https://github.com/livingdocsIO/livingdocs-server/pull/5540)
* [Prevent syncing empty metadata title](https://github.com/livingdocsIO/livingdocs-editor/pull/6665)
* [fix(deps): update dependency semver from 7.3.8 to v7.4.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5549)
* [fix(deps): update dependency aws-sdk from 2.1353.0 to v2.1354.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5546)
* [fix(deps): update dependency lru-cache from 9.0.0 to v9.0.1 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5548)
* [fix(deps): update dependency lru-cache from 8.0.5 to v9 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5545)
* [fix(deps): update dependency aws-sdk from 2.1351.0 to v2.1353.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5542)
* [Account for missing width/height in image cropper](https://github.com/livingdocsIO/livingdocs-editor/pull/6667)
* [Introducing user stats per request done against server](https://github.com/livingdocsIO/livingdocs-server/pull/5533)
* [Working Title: Handle copy&paste and don't sanitize anymore](https://github.com/livingdocsIO/livingdocs-editor/pull/6664)
* [Working-Title improvements](https://github.com/livingdocsIO/livingdocs-editor/pull/6622)
* [Replace document scopes with document policies](https://github.com/livingdocsIO/livingdocs-editor/pull/6634)
* [fix(deps): update dependency aws-sdk from 2.1350.0 to v2.1351.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5539)
* [Deprecate `useAsTitle` sync](https://github.com/livingdocsIO/livingdocs-editor/pull/6652)
* [fix(deps): update dependency lru-cache from 8.0.4 to v8.0.5 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5538)
* [fix(deps): update dependency webpack from 5.76.3 to v5.78.0 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6661)
* [fix(deps): update dependency human-format from 1.0.0 to v1.1.0 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6660)
* [Fix documents filters query for editor](https://github.com/livingdocsIO/livingdocs-server/pull/5536)
* [Publish Control: allow manual publication date override before first publish & visual clarity](https://github.com/livingdocsIO/livingdocs-editor/pull/6643)
* [Fix menu drag and drop behaviour](https://github.com/livingdocsIO/livingdocs-editor/pull/6646)
* [Fix axios metadata and filters serialization](https://github.com/livingdocsIO/livingdocs-editor/pull/6647)
* [Cache access control user details by project](https://github.com/livingdocsIO/livingdocs-server/pull/5534)
* [Ensure mentioneeIds is on all comment schemas](https://github.com/livingdocsIO/livingdocs-server/pull/5531)
* [fix(deps): update dependency aws-sdk from 2.1349.0 to v2.1350.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5530)
* [Document Access Control Foundation](https://github.com/livingdocsIO/livingdocs-server/pull/5440)
* [fix(deps): update dependency aws-sdk from 2.1348.0 to v2.1349.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5524)
* [`rel` property was being overwritten by the `partialLinkAttributes`](https://github.com/livingdocsIO/livingdocs-editor/pull/6641)
* [Remove not used editing API endpoint /hugo/print/royalty-recipients](https://github.com/livingdocsIO/livingdocs-server/pull/5525)
* [Use remote metadata source when updating metadata](https://github.com/livingdocsIO/livingdocs-editor/pull/6633)
* [Add globally unique ID on Elasticsearch entries](https://github.com/livingdocsIO/livingdocs-server/pull/5465)
* [Use crop in getUpdatedAutomaticCrops() calculation](https://github.com/livingdocsIO/livingdocs-editor/pull/6624)
* [fix(deps): update dependency fast-json-stringify from 5.6.2 to v5.7.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5522)
* [fix(deps): update dependency ua-parser-js from 1.0.34 to v1.0.35 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5521)
* [extend airship log](https://github.com/livingdocsIO/livingdocs-server/pull/5391)
* [Fix error where links to other documents would fail to save the document](https://github.com/livingdocsIO/livingdocs-editor/pull/6625)
* [Include `target` property to LinkDirective schema](https://github.com/livingdocsIO/livingdocs-server/pull/5507)
* [Chore/tags numberdots labels and breadcrumbs](https://github.com/livingdocsIO/livingdocs-editor/pull/6628)
* [Fix "Has local changes" for editable teasers](https://github.com/livingdocsIO/livingdocs-editor/pull/6627)
* [Drop callback support in group queries](https://github.com/livingdocsIO/livingdocs-server/pull/5512)
* [fix(deps): update opentelemetry (master) (minor)](https://github.com/livingdocsIO/livingdocs-server/pull/5511)
* [fix(deps): update dependency aws-sdk from 2.1345.0 to v2.1347.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5510)
* [`li-meta-distribution-planning` design polish](https://github.com/livingdocsIO/livingdocs-editor/pull/6623)
* [fix(deps): update dependency @google-cloud/storage from 6.9.4 to v6.9.5 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5509)
* [feat(groups): Drop support for serverConfig.policies](https://github.com/livingdocsIO/livingdocs-server/pull/5505)
* [Enforce promises in menu api](https://github.com/livingdocsIO/livingdocs-server/pull/5503)
* [Prevent dashboard drag&drop error](https://github.com/livingdocsIO/livingdocs-editor/pull/6621)
* [Add `allowTitleEdit` component option for dashboard main cell](https://github.com/livingdocsIO/livingdocs-server/pull/5502)
* [Editable document title in dashboard main cell](https://github.com/livingdocsIO/livingdocs-editor/pull/6615)
* [Add `setTitle` patch operation on documents](https://github.com/livingdocsIO/livingdocs-server/pull/5496)
* [Sync document content types in afterProjectConfigChange hook](https://github.com/livingdocsIO/livingdocs-server/pull/5480)
* [Rotate npm read token](https://github.com/livingdocsIO/livingdocs-editor/pull/6616)
* [Add metadata search in publications](https://github.com/livingdocsIO/livingdocs-server/pull/5443)
* [fix(deps): update dependency exifreader from 4.11.1 to v4.12.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5494)
* [Dashboards: require componentOptions.allowQuickPublish to show publish button in dashboard](https://github.com/livingdocsIO/livingdocs-editor/pull/6602)
* [Design/color update](https://github.com/livingdocsIO/livingdocs-editor/pull/6610)
* [Replace simple metalman useage with schema API generator](https://github.com/livingdocsIO/livingdocs-server/pull/5490)
* [New title component in document edit toolbar](https://github.com/livingdocsIO/livingdocs-editor/pull/6600)
* [Add test case for corrupted image from imago](https://github.com/livingdocsIO/livingdocs-server/pull/5410)
* [Issue Navigation MVP](https://github.com/livingdocsIO/livingdocs-editor/pull/6548)
* [fix(deps): update dependency aws-sdk from 2.1343.0 to v2.1344.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5489)
* [feat(content-types): add `displayTitlePattern` to content type schema](https://github.com/livingdocsIO/livingdocs-server/pull/5488)
* [Fix undefined session console error in li-comment-mention component](https://github.com/livingdocsIO/livingdocs-editor/pull/6599)
* [Return complete document from /documents/:id/parent-issue endpoint](https://github.com/livingdocsIO/livingdocs-server/pull/5439)
* [fix(teasers): allow document drop with any param handle for the reference](https://github.com/livingdocsIO/livingdocs-editor/pull/6595)
* [Allow links that can not be parsed by iframely in li-tree](https://github.com/livingdocsIO/livingdocs-editor/pull/6603)
* [Dashboards: consider componentOptions.allowQuickPublish for publish state cell](https://github.com/livingdocsIO/livingdocs-editor/pull/6601)
* [Archive unused content and media types](https://github.com/livingdocsIO/livingdocs-server/pull/5475)
* [fix(deps): update dependency @livingdocs/framework from 24.13.2 to v24.13.3 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5482)
* [fix(deps): update dependency wait-on from 6.0.1 to v7 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6545)
* [Fix: show quick publish on dashboards only when reasonable](https://github.com/livingdocsIO/livingdocs-editor/pull/6585)
* [fix(dashboard): allow allowQuickPublish option for publish state dashboard cell](https://github.com/livingdocsIO/livingdocs-server/pull/5474)
* [fix(deps): update dependency moment-timezone from 0.5.41 to v0.5.42 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6591)
* [fix(deps): update dependency sass from 1.59.3 to v1.60.0 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6583)
* [fix(deps): update dependency sharp from 0.31.3 to ^0.32.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5479)
* [fix(deps): update dependency aws-sdk from 2.1342.0 to v2.1343.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5478)
* [Add `displayTitlePattern` to content type schema](https://github.com/livingdocsIO/livingdocs-server/pull/5471)
* [fix(li-integer): correctly treat 0 value](https://github.com/livingdocsIO/livingdocs-editor/pull/6587)
* [Test bundles](https://github.com/livingdocsIO/livingdocs-editor/pull/6575)
* [fix(deps): update dependency aws-sdk from 2.1341.0 to v2.1342.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5469)
* [Fix support for arrays in draft query sort option](https://github.com/livingdocsIO/livingdocs-server/pull/5468)
* [Buy-In: improve wording](https://github.com/livingdocsIO/livingdocs-editor/pull/6581)
* [Fix/Bundle-Thumbs](https://github.com/livingdocsIO/livingdocs-editor/pull/6580)
* [fix(deps): update dependency aws-sdk from 2.1339.0 to v2.1341.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5458)
* [Improve postgres transaction error handling](https://github.com/livingdocsIO/livingdocs-server/pull/5467)
* [Only query configured content types](https://github.com/livingdocsIO/livingdocs-server/pull/5454)
* [fix(deps): update dependency webpack from 5.76.2 to v5.76.3 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6576)
* [Wait for correct publish event in publication test](https://github.com/livingdocsIO/livingdocs-server/pull/5461)
* [Feat/Toolbar](https://github.com/livingdocsIO/livingdocs-editor/pull/6041)
* [Show ldNotify message for bundle actions](https://github.com/livingdocsIO/livingdocs-editor/pull/6573)
* [Improve bundle dashboard cells](https://github.com/livingdocsIO/livingdocs-editor/pull/6571)
* [fix(deps): update dependency fastify from 4.14.1 to v4.15.0 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6561)
* [Don't render hidden context-menu actions](https://github.com/livingdocsIO/livingdocs-editor/pull/6563)
* [Make the job queue waitNext more reliable](https://github.com/livingdocsIO/livingdocs-server/pull/5447)
* [Fix redis xtrimdelivered](https://github.com/livingdocsIO/livingdocs-server/pull/5449)
* [Bundle panel in article metadata](https://github.com/livingdocsIO/livingdocs-editor/pull/6562)
* [Support expectedOrActualPublicationDate filters in the search](https://github.com/livingdocsIO/livingdocs-server/pull/5448)
* [Apply menu list filters for table dashboards](https://github.com/livingdocsIO/livingdocs-editor/pull/6558)
* [fix(deps): update opentelemetry (master) (patch)](https://github.com/livingdocsIO/livingdocs-server/pull/5444)
* [fix(deps): update dependency aws-sdk from 2.1338.0 to v2.1339.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5445)
* [fix(deps): update dependency fs-extra from 11.1.0 to v11.1.1 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6560)
* [Do not close postgres pool clients on query errors](https://github.com/livingdocsIO/livingdocs-server/pull/5438)
* [fix(document selection): ensure filters are applied when using legacy dashboards](https://github.com/livingdocsIO/livingdocs-editor/pull/6550)
* [Don't hide table dashboard flyouts on mouseleave](https://github.com/livingdocsIO/livingdocs-editor/pull/6515)
* [Ignore test files in metadata plugin loader](https://github.com/livingdocsIO/livingdocs-server/pull/5434)
* [fix: add favicon.ico and apple-touch-icon](https://github.com/livingdocsIO/livingdocs-editor/pull/6551)
* [Hide download button when no crops are available](https://github.com/livingdocsIO/livingdocs-editor/pull/6541)
* [Fix content type changes on documents](https://github.com/livingdocsIO/livingdocs-server/pull/5432)
* [fix(deps): update dependency webpack from 5.76.1 to v5.76.2 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6543)
* [fix(deps): update dependency mini-css-extract-plugin from 2.7.3 to v2.7.5 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6526)
* [fix(deps): update dependency sass from 1.59.2 to v1.59.3 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6527)
* [fix(deps): update dependency style-loader from 3.3.1 to v3.3.2 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6538)
* [fix(deps): update dependency exifreader from 4.11.0 to v4.11.1 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5428)
* [fix(deps): update dependency aws-sdk from 2.1337.0 to v2.1338.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5430)
* [Don't show metadata button for legacy publication](https://github.com/livingdocsIO/livingdocs-editor/pull/6540)
* [Remove support of .documents and .publications properties on search results](https://github.com/livingdocsIO/livingdocs-server/pull/5427)
* [fix(deps): update babel (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6516)
* [Enable Publish Control for contentType `page` in project `magazine`](https://github.com/livingdocsIO/livingdocs-server/pull/5424)
* [Fix li-datetime filter date parsing](https://github.com/livingdocsIO/livingdocs-editor/pull/6531)
* [Search DSL](https://github.com/livingdocsIO/livingdocs-server/pull/5421)
* [Support caching for byIds dataloader](https://github.com/livingdocsIO/livingdocs-editor/pull/6528)
* [Fix/Scrollbar Issues](https://github.com/livingdocsIO/livingdocs-editor/pull/6522)
* [fix(creation flow): Allow content type boxes to text wrap their labels](https://github.com/livingdocsIO/livingdocs-editor/pull/6523)
* [Fix finite products config](https://github.com/livingdocsIO/livingdocs-server/pull/5417)
* [Issue navigation](https://github.com/livingdocsIO/livingdocs-server/pull/5413)
* [fix(deps): update dependency @fastify/reply-from from 9.0.0 to v9.0.1 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6517)
* [Remove app-level unnecessary scrollbar](https://github.com/livingdocsIO/livingdocs-editor/pull/6519)
* [fix(deps): update dependency @livingdocs/framework from 24.13.1 to v24.13.2 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5414)
* [fix(display filter): ensure custom vue display filters get the config object](https://github.com/livingdocsIO/livingdocs-editor/pull/6512)
* [fix(deps): update dependency @fastify/reply-from from 8.4.3 to v9 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6481)
* [Replace Generic error (5XX) used for Password verification with `validationError`](https://github.com/livingdocsIO/livingdocs-server/pull/5409)
* [Show distribution toolbar action on bundles](https://github.com/livingdocsIO/livingdocs-editor/pull/6514)
* [Also anonymise in changes calls](https://github.com/livingdocsIO/livingdocs-server/pull/5404)
* [fix(deps): update dependency aws-sdk from 2.1334.0 to v2.1335.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5405)
* [fix(create): correctly check if contentType is on defaultChannel](https://github.com/livingdocsIO/livingdocs-editor/pull/6510)
* [Add existing documents to bundle](https://github.com/livingdocsIO/livingdocs-editor/pull/6503)
* [Fix Desk-Net Schedule automatic placement errors due to schedule properties](https://github.com/livingdocsIO/livingdocs-editor/pull/6470)
* [fix(deps): update opentelemetry (master) (minor)](https://github.com/livingdocsIO/livingdocs-server/pull/5399)
* [fix: update framework version](https://github.com/livingdocsIO/livingdocs-server/pull/5400)
* [fix: bump framework version](https://github.com/livingdocsIO/livingdocs-editor/pull/6504)
* [fix(deps): update dependency @livingdocs/framework from 24.13.0 to v24.13.1 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5395)
* [fix(deps): update dependency @opentelemetry/api from 1.4.0 to v1.4.1 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5396)
* [Fix: contentType displayFilter works correctly with contentTypes not from the defaultChannel](https://github.com/livingdocsIO/livingdocs-editor/pull/6502)
* [Remove document from bundle](https://github.com/livingdocsIO/livingdocs-editor/pull/6497)
* [Shows scheduled doc tooltip ](https://github.com/livingdocsIO/livingdocs-editor/pull/6494)
* [Create and add documents to bundle](https://github.com/livingdocsIO/livingdocs-editor/pull/6488)
* [Use yyyy-MM-dd format date query parameter for Distribution Planning Schedule fixed date request](https://github.com/livingdocsIO/livingdocs-editor/pull/6471)
* [fix: remove 2nd line of buy-in empty state](https://github.com/livingdocsIO/livingdocs-editor/pull/6482)
* [fix(deps): update dependency webpack from 5.75.0 to v5.76.1 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6480)
* [chore(deps): update dependency eslint from 8.35.0 to v8.36.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5387)
* [Allow dashboard request to exclude revision content](https://github.com/livingdocsIO/livingdocs-server/pull/5382)
* [Don't load document content in table dashboards](https://github.com/livingdocsIO/livingdocs-editor/pull/6474)
* [fix(deps): update dependency aws-sdk from 2.1331.0 to v2.1332.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5383)
* [Fix Task List](https://github.com/livingdocsIO/livingdocs-editor/pull/6468)
* [Add `li-bundled-documents` metadata plugin](https://github.com/livingdocsIO/livingdocs-server/pull/5381)
* [Bundle panel with empty state](https://github.com/livingdocsIO/livingdocs-editor/pull/6467)
* [fix(deps): update opentelemetry (master) (minor)](https://github.com/livingdocsIO/livingdocs-server/pull/5375)
* [Upgrade sharp to fix Premature close error](https://github.com/livingdocsIO/livingdocs-server/pull/5376)
* [Transform pitch to bundle](https://github.com/livingdocsIO/livingdocs-editor/pull/6464)
* [Handle pitch and bundle independent of publish control](https://github.com/livingdocsIO/livingdocs-editor/pull/6463)
* [Deprecate Identifier](https://github.com/livingdocsIO/livingdocs-server/pull/5289)
* [Update framework](https://github.com/livingdocsIO/livingdocs-editor/pull/6451)
* [fix(deps): update dependency jose from 4.12.2 to v4.13.1 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5372)
* [fix(deps): update dependency cloudinary from 1.34.0 to v1.35.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5357)
* [fix(deps): update dependency @google-cloud/storage from 6.9.3 to v6.9.4 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5353)
* [fix(deps): update dependency lru-cache from 7.17.0 to v7.17.2 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5355)
* [`mediaIndex` normalisation, renamed to `indexing`](https://github.com/livingdocsIO/livingdocs-server/pull/5365)
* [Dynamic metadata for Publication indexing](https://github.com/livingdocsIO/livingdocs-server/pull/5362)
* [Feat/Component Icons V2](https://github.com/livingdocsIO/livingdocs-server/pull/5177)
* [Feat/Component Icons V2](https://github.com/livingdocsIO/livingdocs-editor/pull/6402)
* [Default Editor configuration](https://github.com/livingdocsIO/livingdocs-editor/pull/6446)
* [Fix flashing List Assignment](https://github.com/livingdocsIO/livingdocs-editor/pull/6453)
* [fix(deps): update dependency fastify from 4.13.0 to v4.14.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5358)
* [fix(deps): update dependency fastify from 4.13.0 to v4.14.0 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6450)
* [Dashboards: correctly apply stored display filter states on initial search](https://github.com/livingdocsIO/livingdocs-editor/pull/6440)
* [Fix distribution planning date range queries to use newsroom timezone](https://github.com/livingdocsIO/livingdocs-server/pull/5344)
* [Add `li-buy-in` planning system guard](https://github.com/livingdocsIO/livingdocs-editor/pull/6444)
* [Fix typos in localisation](https://github.com/livingdocsIO/livingdocs-editor/pull/6434)
* [Fix/distribution flyouts](https://github.com/livingdocsIO/livingdocs-editor/pull/6439)
* [Remove some internal yargs apis](https://github.com/livingdocsIO/livingdocs-server/pull/5346)
* [Fix `li-meta-integer` display filter error](https://github.com/livingdocsIO/livingdocs-editor/pull/6433)
* [Data Migration Log Improvement](https://github.com/livingdocsIO/livingdocs-server/pull/5298)
* [Refactoring: Document Migration V2](https://github.com/livingdocsIO/livingdocs-server/pull/5334)
* [Fix broken display filters in legacy dashboards](https://github.com/livingdocsIO/livingdocs-editor/pull/6431)
* [Update `@livingdocs/framework` to include fix for imgIX URL generation](https://github.com/livingdocsIO/livingdocs-editor/pull/6428)
* [Provides a server configuration to remove leading directory for ImgIX service](https://github.com/livingdocsIO/livingdocs-server/pull/5339)
* [Don't show unconfigured content types in distribution planning table dashboard](https://github.com/livingdocsIO/livingdocs-editor/pull/6417)
* [Handle import and webhook jobs immediately instead of using the waiting logic that requires less redis connections](https://github.com/livingdocsIO/livingdocs-server/pull/5333)
* [fix(deps): update dependency axios from 0.27.2 to v1 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6295)
* [Make foreign key constraints deferrable](https://github.com/livingdocsIO/livingdocs-server/pull/5308)
* [Restrict maximum postgres query parameters](https://github.com/livingdocsIO/livingdocs-server/pull/5327)
* [Fix axios 1 http querystring compatibility](https://github.com/livingdocsIO/livingdocs-server/pull/5325)
* [Fix renovate platformAutomerge](https://github.com/livingdocsIO/livingdocs-editor/pull/6415)
* [fix(deps): update dependency open from 8.4.1 to v8.4.2 (master)](https://github.com/livingdocsIO/livingdocs-editor/pull/6409)
* [fix(deps): update dependency pino from 8.10.0 to v8.11.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5324)
* [Fix renovate platformAutomerge](https://github.com/livingdocsIO/livingdocs-server/pull/5317)
* [fix(deps): update dependency lru-cache from 7.16.1 to v7.16.2 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5312)
* [fix(deps): update dependency @azure/storage-blob from 12.12.0 to v12.13.0 (master)](https://github.com/livingdocsIO/livingdocs-server/pull/5316)
* [Fix query performance with big tables](https://github.com/livingdocsIO/livingdocs-server/pull/5303)
* [Fix: Publish Control Button changes state after publish / draft creation](https://github.com/livingdocsIO/livingdocs-editor/pull/6403)
* [Fix/distribution dashboard layout](https://github.com/livingdocsIO/livingdocs-editor/pull/6407)
* [Fix queue waiting delay when a queue did not return results](https://github.com/livingdocsIO/livingdocs-server/pull/5301)
* [multipleServices apply defaultParams](https://github.com/livingdocsIO/livingdocs-editor/pull/6372)
* [Emit publication.update event for publishControl changes](https://github.com/livingdocsIO/livingdocs-server/pull/5299)

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


## Highlights

### Document Access Control

TODO: Description

* [Documentation](TODO)

### Planning System (Bundles)

TODO: Description

* [Documentation](TODO)

### Working Title

TODO: Description

* [Documentation](TODO)

### Publication/Draft Index

TODO: Description

* [Documentation](TODO)

### Home Screen - Part 2

TODO: Description

* [Documentation](TODO)

### Issue Management - Navigation

TODO: Description

* [Documentation](TODO)

### Metadata Preview

TODO: Description

* [Documentation](TODO)

### Concurrent License Model: Billing Report

TODO: Description

* [Documentation](TODO)


### Synced Table Dashboards

TODO: Description

* [Documentation](TODO)

### i18n - Editor available in German

TODO: Description

* [Documentation](TODO)








## Breaking Changes :fire:

:exclamation: Check the [Back to Standard Roadmap]({{< ref "/customising/back-to-standard" >}}) and inform you about important upcoming deprecations and breaking changes and reasons.

### Migrate the Postgres Database :fire:

It's a simple/fast migration with no expected data losses.

```sh
# run `livingdocs-server migrate up` to update to the newest database scheme
livingdocs-server migrate up
```

TODO: check migration


## Deprecations

:exclamation: Check the [Back to Standard Roadmap]({{< ref "/customising/back-to-standard" >}}) and inform you about important upcoming deprecations and breaking changes and reasons.



## Other Changes

### Features

### Improvements

### Bugfixes


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
