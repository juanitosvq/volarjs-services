# Changelog

## 0.0.71 (2026-04-14)

- ci: create draft PR for version bump
- chore: upgrade tsslint to v3
- Refactor release workflow for push and dispatch triggers
- v0.0.70 (#116)
- refactor(pug): import parser from @vue/language-plugin-pug (#113)
- ci: add auto-version and release workflows (#115)
- v0.0.69
- bump yaml-language-server
- fix(pug): undo the merge operation on class/style attr
- chore: update pnpm-lock.yaml
- v0.0.68
- fix(typescript): correct getAutoImportFileExcludePatternsPreference return type
- refactor(pug): expose all options from HTML plugin
- v0.0.67
- chore(emmet): update @emmetio/css-parser to v0.4.1
- v0.0.66
- ci(lint): auto-fix
- chore: add dprint
- chore: update tsslint config
- chore: bump yaml-language-server to 1.19.2 (#111)
- v0.0.65
- refactor(typescript): export convertClassificationsToSemanticTokens
- chore: update pnpm-lock.yaml
- refactor(vetur): remove vetur package (#107)
- fix(html): pasting HTML code adds extra closing tag on first line
- v0.0.64
- fix(typescript): deep DiagnosticMessageChain is not processed
- chore: remove pkg.pr.new for now
- fix(emmet): use `ramya-rao-a/css-parser#vscode`
- v0.0.63
- fix(typescript): read `autoImportSpecifierExcludeRegexes` option newly added in TS5.6 (#108)
- chore: update tsslint to 1.5.0
- chore: remove importsNotUsedAsValues
- ci(lint): auto-fix
- lint: use `@johnsoncodehk/tsslint-config`
- chore(typescript): bump typescript-auto-import-cache
- chore(typescript): bump typescript-auto-import-cache
- v0.0.62
- feat(typescript): add option to disable auto import cache (#105)
- chore: fix @volar/language-service version
- v0.0.61
- v0.0.60
- chore: bump volar
- ci: add pkg.pr.new
- Add readme compatability note (#104)
- ci: bump actions
- Reapply "perf(typescript): try to insert new requests as needed before completing all CDN file requests"
- chore: `prerelease` script should be run before `release:next`
- v0.0.59
- Revert "perf(typescript): try to insert new requests as needed before completing all CDN file requests"
- chore: update package.json
- v0.0.58
- perf(typescript): try to insert new requests as needed before completing all CDN file requests
- v0.0.57
- chore: update to Volar 2.4.0-alpha.11
- perf(typescript): using `getProgram` to trigger CDN file synchronization
- v0.0.56
- chore: update to Volar 2.4.0-alpha.1
- chore: update package.json
- v0.0.55
- chore: update to Volar 2.4.0-alpha.0
- feat(markdown): add support for organizeLinkDefinitions (#101)
- feat(markdown): implement provideFileRenameEdits (#100)
- fix(pug): missing custom data synchronization logic (#99)
- v0.0.54
- chore: bump deps
- v0.0.53
- fix(typescript): move selection ranges provider to syntactic service
- fix(typescript): prune semanticTokens that are out of range
- fix(typescript): cannot update source scripts
- test(html): test `resolveReference`
- fix(typescript): define accurate SemanticTokensLegend
- v0.0.52
- chore: update to Volar 2.3.1
- chore(typescript): bump `typescript-auto-import-cache`
- chore: update to TS 5.5
- chore(pug): use `muggle-string` dep
- chore(yaml): update to yaml-language-server 1.15.0 (#98)
- feat(yaml): implement `onTypeFormattingEdits` (#97)
- lint: use `getDefaultRules()` from Volar TSSLint config
- v0.0.51
- feat: update to Volar 2.3.0
- lint: update tsslint and import config by URL
- feat(html, pug): add configurationSections option
- v0.0.50
- chore: bump volar
- ci(lint): auto-fix
- lint: update tsslint
- chore(pug): fix build
- v0.0.49
- fix(typescript): cannot convert extra file name to embedded uri
- chore: bump volar
- v0.0.48
- chore: update release scripts
- feat: upgrade to Volar 2.3 alpha (#96)
- v0.0.47
- fix(markdown): implement `getContainingDocument`
- v0.0.46
- feat(markdown): improve document synchronization
- chore(emmet): remove type annotation
- v0.0.45
- ci(lint): auto-fix
- feat(emmet): port VSCode emmet extension client logic (#95)
- chore: bump volar
- fix(css, html, json, yaml): failed to resolve relative path
- fix(typescript-twoslash-queries): fix invalid fileName
- v0.0.44
- chore: warning message format
- perf(typescript): check `command` resolve capability only for specific refactors (#94)
- fix(typescript): correct new file edit conversion
- fix(typescript): `allowTextChangesInNewFiles` never true for embedded documents
- feat(typescript): capture editor formatting options from the last formatting request
- feat(markdown): add hover support (#91)
- chore: specified pnpm version
- fix(typescript): tolerate non-existent file text span
- ci(lint): auto-fix
- v0.0.43
- fix(prettier): correctly resolve config for embedded document
- types(emmet): make options optional
- v0.0.42
- chore: update to volar 2.2
- v0.0.41
- feat(emmet): add `mappedModes` option
- chore(typescript): correct syntax only script version
- v0.0.40
- refactor(typescript): syntax only service context isolation
- chore: update package.json
- v0.0.39
- chore: use `@johnsoncodehk/vscode-html-languageservice`
- v0.0.38
- feat(html, pug, typescript): update auto insertion confition
- chore: bump volar and
- refactor(typescript): narrow `getUserPreferences` params
- v0.0.37
- fix(typescript): do not reuse snapshot
- v0.0.36
- chore: bump voalr
- refactor(typescript): reuse existing snapshots for the syntax language service
- chore: update release scripts
- v0.0.35
- chore: update release tag
- feat: upgrade to volar 2.2
- ci(lint): auto-fix
- chore(markdown): update vscode-markdown-languageservice to 0.5 alpha (#86)
- ci(lint): auto-fix
- feat(lint): add tsl
- v0.0.34
- chore: changelog
- fix(prettier): await isFormattingEnabled (#85)
- v0.0.33
- chore: changelog
- fix(typescript): code actions not working
- fix(typescript): options should be optional
- v0.0.32
- chore: changelog
- refactor(prettier): simplify plugin options (#84)
- refactor: consistent formatting options in language service plugins
- refactor(typescript): move plugins to `lib/plugins/`
- refactor(typescript): decoupled from `@volar/typescript`
- refactor(typescript): split into multiple ServicePlugins (#83)
- refactor(typescript): split syntactic, semantic services initialize into function
- fix(typescript): incorrectly identifying `jsx`/`tsx` as `ts`
- chore(html): remove unused option
- feat(prettier): Allow a Prettier instance to be optional (#81)
- chore: remove .DS_Store file (#80)
- v0.0.31
- chore: changelog
- chore: update pnpm-lock.yaml
- chore: remove unused tsconfig configs
- refactor: make all editor settings configurable (#78)
- chore: deprecate `volar-service-tsconfig`
- chore: deprecate `volar-service-pretty-ts-errors`
- feat(css, html, typescript): consume `initialIndentLevel` in embedded code formatting (#75)
- fix(html): script block format result inconsistent with vscode
- refactor(html): expose `getDocumentContext()`
- fix(typescript): semantic tokens result inconsistent with vscode
- feat(css, html, json, yaml): respect `ClientCapabilities.textDocument.foldingRange` option
- chore: update pnpm-lock.yaml
- fix(html): resolve reference behavior inconsistent with vscode
- chore: bump require volar version
- fix(pug): compatible with volar 2.0.4 types
- chore: release to `latest` and `volar-2.0` tags
- v0.0.30
- chore: changelog
- fix(typescript): `validate.enable` config not working for semantic check
- v0.0.29
- chore: changelog
- fix(html): autoClosingTags not working at first line
- v0.0.28
- chore: changelog
- fix(typescript): fix `fileNameToUri` regression
- feat(typescript): support for extra scripts (#74)
- chore: `~2.0.0` -> `~2.0.1`
- fix(typescript): only process `getScript()` result in semantic features (#73)
- chore(css): use `await`
- chore: fix compare link
- chore: `~2.0` -> `~2.0.0`
- v0.0.27
- chore: changelog
- chore: update tsconfig.json
- chore: upgrade to 2.0
- feat: implement definitions for markdown (#71)
- chore: remove `eslint`, `tslint` services (#72)
- chore: sync upstream types
- v0.0.26
- feat: sync 2.0.0-alpha.14 changes
- chore: update pnpm-lock.yaml
- feat: add markdown trigger characters (#70)
- chore: update pnpm-lock.yaml
- v0.0.25
- chore(typescript): bump `typescript-auto-import-cache`
- feat(prettier): add `getPrettier` option (#68)
- chore: update TypeScript imports
- v0.0.24
- feat: add name option
- v0.0.23
- fix(typescript): `*.suggest.enabled`, `*.validate.enable` configs not working
- feat(markdown): support user defined diagnostic options (#67)
- chore: add *.tgz to .gitignore
- chore: remove `main` field
- v0.0.22
- chore: fix package json include files
- refactor: no longer emit js files to `out` directory (#66)
- v0.0.21
- feat(typescript): consume `ReferenceContext` (#65)
- v0.0.20
- chore: pin volar version to next
- v0.0.19
- chore: update volar to 2.0.0-alpha.2
- v0.0.18
- feat: upgrade to 2.0 alpha (#64)
- chore: bump deps
- fix: add `@volar/language-service` for dev
- v0.0.17
- chore: upgrade require volar version
- v0.0.16
- fix: Avoid downstream need node polyfill for browser (#61)
- chore: bump deps
- chore: update pnpm-lock.yaml
- v0.0.15
- chore: disable `esModuleInterop`
- chore: bump deps
- fix(emmet, pug): browser stub missing create() function
- chore: no auto push release
- refactor(html): use the new `findDocumentSymbols2` API
- v0.0.14
- refactor(html): renaming options (#60)
- feat(html): add `useDefaultDataProvider` option (#58)
- chore: bump deps
- Configure GitHub action running TypeScript
- Add missing trailing newlines
- Update package metadata (#54)
- docs: consistent readmes
- Fix formatting issues (#53)
- Mark YAML Volar service options as optional
- chore: fix tsconfig extends paths
- refactor: simplify tsconfigs
- doc(yaml): remove formatting tick
- chore: typo
- chore: remove `@volar/source-map` from root deps
- chore: update pnpm-lock.yaml
- feat: add volar-service-markdown (#52)
- chore: remove `resolution-mode=highest` for pnpm 8.7.0
- v0.0.13
- chore: add yaml to tsconfig.build.json
- chore: hoist triggerCharacters
- v0.0.12
- refactor: export as `create()` for avoid interop problems
- fix(prettier): Properly pass filepath to resolveConfig (#51)
- Use module node16 (#47)
- Add volar-service-yaml (#45)
- chore: config workspace formatters
- v0.0.11
- chore: sync volar 1.10.0
- doc: plugins -> services
- v0.0.10
- chore(typescript): fix build
- [typescript] provide access to syntatic ls (#43)
- chore: sync volar 1.9.0
- chore(prettier): try don't to import prettier twice
- feat(prettier): Add support for Prettier 3 and passing an instance of Prettier (#42)
- fix: add missing DiagnosticSeverity
- v0.0.9
- chore: sync volar 1.8.0
- v0.0.8
- chore: sync volar 1.7.7
- chore: fix tsc
- chore: un-pin TS
- v0.0.7
- fix: services type missing in pnpm project
- v0.0.6
- chore: bump volar
- chore: pin typescript 5.0.4
- chore(typescript): use `getDocumentRegistry`
- fix(typescript): documentRegistry should not reuse between different root projects
- v0.0.5
- feat: Sync core for full web support (#40)
- chore: bump volar
- feat(prettier): Move config loading to format call (#38)
- refactor: sync core
- refactor(typescript): rename "services" folder to "features"
- doc: backend
- refactor(typescript): move tsconfig functionality to a separate service
- feat(css, html): use clientCapabilities
- v0.0.4
- chore: bump volar
- chore: update pnpm-lock.yaml
- refactor: decoupled from `vscode-languageserver-protocol`
- chore(pug): remove `vscode-languageserver-types` dep
- chore: fixed `unused-dependency` rule
- chore(typescript): make document optional for language service and host provider
- chore(pug): move volar deps from peerDependencies to dependencies
- chore: fixed `missing-dependency` rule
- chore: bump volar
- chore: bump volar
- chore: unused `satisfies`
- v0.0.3
- chore: bump volar
- refactor(html / pug): migrate service expose from function return to provide api
- refactor: update to type-only provide api
- chore: bump deps
- v0.0.2
- feat: update to 1.5.4 provide api
- v0.0.1
- chore: bump volar
- refactor: update rules api
- chore: bump volar
- chore: update header
- v0.0.0
- refactor: `@volar-plugins/` -> `volar-service-`
- chore: sync core 1.5.0-alpha.0
- fix(pug): failed to parse multi-line attribute value containing double quotes
- v2.0.0
- chore: bump volar
- fix(pretty-ts-errors): remove log
- chore(pretty-ts-errors): upgrade pretty-ts-errors-lsp
- v2.0.0-alpha.23
- feat: pretty-ts-errors plugin
- chore: bump volar
- doc: readme
- feat(prettier): Add a few bells and whistle to the Prettier plugin (#35)
- v2.0.0-alpha.22
- feat(typescript): support document links for tsconfig
- chore: upgrade volar
- chore: bump volar
- chore: no push on release
- chore: Lerna-Lite 2.0 publish & version are becoming optional commands
- chore: remove unused code
- v2.0.0-alpha.21
- perf(emmet): avoid parsing html document twice
- chore: update pnpm-lock.yaml
- v2.0.0-alpha.20
- chore: bump volar
- refactor: codeGen -> codes
- chore: update pnpm-lock.yaml for pnpm v8
- fix(html): add `<textarea>` to indent sensitive tags
- v2.0.0-alpha.19
- chore: bump volar
- fix(html): formatting push indent multi-line attribute value
- fix(html): formatting is pushing `<pre>` contents
- Fix regression: `labelDetails` in completions not processed (#31)
- chore: bump volar
- feat: set includePackageJsonAutoImports value (#32)
- feat: bump TS to 5.0
- v2.0.0-alpha.18
- Handle renameLocation from `getEditsForRefactor` (#29)
- v2.0.0-alpha.17
- chore: bump core
- chore: upgrade build target to es2021
- fix: emmet, pug web module export symbol incorrect
- v2.0.0-alpha.16
- feat: upgrade core to 1.4.0-alpha.0
- refactor: replace `export =` with `export default`
- feat: support for trigger characters registration
- v2.0.0-alpha.15
- refactor(pug): move `@volar/language-service` to peerDependencies
- chore: upgrade core
- v2.0.0-alpha.14
- chore: upgrade core
- v2.0.0-alpha.13
- chore: bump core
- feat(pug): consume mixin block
- feat: replace `SymbolInformation` with `DocumentSymbol`
- v2.0.0-alpha.12
- chore: bump core
- fix(typescript): document symbol range for arrow function declaration incorrect
- v2.0.0-alpha.11
- fix(typescript): response `DocumentSymbol[]` instead of `SymbolInformation[]`
- chore: bump core
- v2.0.0-alpha.10
- chore: bump core
- fix(pug): more reliable completion at empty lines
- v2.0.0-alpha.9
- chore: bump core
- v2.0.0-alpha.8
- chore: bump core
- feat(typescript): implement `getIndentSensitiveLines`
- feat(html): implement `getIndentSensitiveLines`
- v2.0.0-alpha.7
- chore: bump core
- fix(html): cannot rename html tags
- fix(typescript): syntactic features not working for .ts with takeover mode
- fix(emmet): completions appear inside self-closing tag
- v2.0.0-alpha.6
- chore: bump core
- chore: bump core
- chore: update pnpm-lock.yaml
- v2.0.0-alpha.5
- fix(emmet): completions appear inside open tag
- refactor(sass-formatter): remove insert new lines logic
- v2.0.0-alpha.4
- chore: bump framework to 1.2.0-alpha.11
- fix(typescript): onType format broken
- refactor: remove insert new lines logic
- refactor: remove initialIndent logic
- fix(typescript): cannot format for js code
- fix(typescript): syntax and format rules not working
- feat(typescript): syntax only language service
- refactor(typescript): reuse TextDocument from core
- chore: bump framework to 1.2.0-alpha.10
- chore: update package.json
- chore: remove ts module for rule context
- v2.0.0-alpha.3
- refactor(typescript): remove trigger characters into plugin scope
- feat(typescript): show warning if source file not found when prepare rules context
- refactor(typescript): share document condition
- refactor(typescript): remove createLanguageService.ts
- chore: remove rules context version
- feat: support for `initialIndent` format option
- v2.0.0-alpha.2
- chore: bump framework to 1.2.0-alpha.7
- doc: simplify plugin install sample
- feat(eslint): make config optional
- chore: bump deps
- chore: esModuleInterop
- refactor: move RuleContext type define to rules.d.ts
- v2.0.0-alpha.1
- chore: add @lerna-lite/cli
- chore: add release:next script
- fix(typescript): completion resolve missing labelDetails
- chore: typo
- chore(prettier): const languages
- chore: remove prepublishOnly
- refactor: rewrite expose
- doc: plugins capability table
- feat(typescript): show warning if tsdk missing
- refactor(prettier): make first param optional
- refactor: ignoreIDEOptions -> ignoreIdeOptions
- refactor(prettier): rebrand plugin interface (#23)
- release(prettier): v1.1.6
- fix: `useTabs` incorrect with `useVscodeIndentation` enabled
- chore: add vscode settings
- feat: upgrade framework to 1.2.0-alpha.5
- refactor: reduce dependencies
- feat: setup rule context for html, css, json, pug
- chore: add prepublishOnly script
- refactor(typescript): remove `@volar/shared` usages
- refactor(pug): remove `@volar/shared`
- refactor(typescript-twoslash-queries): remove `@volar/shared`
- fix(typescript): index.d.ts do not including to releases
- feat(typescript): expose types at root
- fix(typescript): handle for language client dropped insertText
- release(typescript): v1.2.0
- feat(typescript): support rules api
- fix: pug, emmet broken web
- release(core-plugins): v1.1.0
- chore: format
- refactor: `export default` -> `export =`
- refactor: move core plugins from volarjs/framework to repo (#22)
- chore: typo
- feat: update for v1.0.20 api
- release(eslint): v0.0.4
- fix(eslint): ignore project eslintrc.js
- fix(eslint): codeAction document uri comparison judgment incorrect
- release(eslint): v0.0.3
- feat(eslint): show config errors
- release(eslint): v0.0.2
- fix: diagnostics missing if lint result do not have `fix`
- doc: add missing @volar-plugins/eslint dep
- release(eslint): v0.0.1
- release(tslint): v0.0.1
- chore: bump deps
- chore: delete `vue-json` plugin
- refactor(vue-json): provide schema with Ls configure
- (prettier) use full text instead of text range
- release(vue-json): v1.0.1
- fix(vue-json): add simple check for add comma before `$schema` property
- chore: fix readme title
- feat: add vue-json plugin
- refactor: remove built-in plugins from repo
- refactor: combine `@volar/typescript-language-service`
- chore: add build script
- refactor: add packages from `plugins/*` of volar repo
- release(prettyhtml): v1.0.3
- fix(prettyhtml): range fomat result incorrect
- release(prettyhtml): v1.0.2
- fix(prettyhtml): handle newline
- release(prettyhtml): v1.0.1
- fix(prettyhtml): text edit range incorrect
- doc: vetur plugin features
- doc: add vetur plugin
- feat: component tag color
- feat: support `.vscode/vetur/snippets`
- feat: userSnippetDir
- feat: sfc block completion
- fix: events missing
- fix: ignore directives in v-bind
- feat: v-bind, v-on
- feat: component data support
- chore: simplify pkg names
- (Prettier plugin) update version
- update deps
- (Prettier plugin) better integration with VSCode
- update test cases
- update test cases
- doc: maintainers
- chore: update example code
- fix: `prettier-html` -> `prettyhtml`
- chore: format
- style(prettier): use tsconfig.json from tsc --init This will reduce JS errors.
- chore: add prepublishOnly script
- chore: move typescript to root devDependencies
- feat(prettier): update breakContentsFromTags regex
- release(sass-formatter): v1.0.1
- docs(prettier): publish to NPM of removed remnant
- release(sass-formatter): v1.0.0
- docs(prettier): remove remnant docs
- docs(prettier): remove unnecessary docs Also, only as far as I personally test.
- feat(prettier): use prettier's vue engine to parse <template> tags
- chore: fix typo
- release(prettier-html): v1.1.0
- style: more testing
- fix(prettier-html): move typescript to devDependencies
- refactor(prettier-html): import plugin without access default
- style: use gitattributes to exclude testCases from stats
- chore: correction module info
- fix: fix config merging with default
- doc: list plugins
- style: add keywords to prettier plugin
- add prepublish script
- chore: push to NPM
- fix: build using separate tsconfig.json
- feat: allow prettier to be installed separately
- style: move deps to devDeps
- style: move deps to devDeps
- doc: add README to @volar-plugins/prettier
- feat: make minimal prettier plugin that works well
- doc: readme
- release(prettier): v1.0.1
- fix: avoid prettier trimming
- chore: correction git url
- first commit

## 0.0.70 (2026-02-26)

- refactor(pug): import parser from @vue/language-plugin-pug (#113)
- ci: add auto-version and release workflows (#115)

## [0.0.34](https://github.com/volarjs/services/compare/v0.0.33...v0.0.34) (2024-03-14)

### Bug Fixes

- **prettier:** await isFormattingEnabled [#85](https://github.com/volarjs/services/issues/85)

## [0.0.33](https://github.com/volarjs/services/compare/v0.0.32...v0.0.33) (2024-03-14)

### Bug Fixes

- **typescript:** options should be optional
- **typescript:** coee actions not working

## [0.0.32](https://github.com/volarjs/services/compare/v0.0.31...v0.0.32) (2024-03-13)

### Features

- **prettier:** don't throw an error when no Prettier instance is available [#81](https://github.com/volarjs/services/issues/81)

### Bug Fixes

- **typescript:** can't format JSX/TSX document correctly (https://github.com/vuejs/language-tools/issues/3949)

### Refactors

- all package formatting options are now consistent
- **typescript:** split the main plugin into multiple plugins [#83](https://github.com/volarjs/services/issues/83)
- **typescript:** no longer depend on `@volar/typescript`
- **prettier:** simplify plugin options [#84](https://github.com/volarjs/services/issues/84)
- **html:** remove useCustomDataProviders option that is no longer used

## [0.0.31](https://github.com/volarjs/services/compare/v0.0.30...v0.0.31) (2024-02-26)

### Features

- Upgrade to Volar 2.1
- **css, html, typescript:** consume `initialIndentLevel` option for accurate embedded code formatting [#75](https://github.com/volarjs/services/issues/75)

### Refactors

- Deprecate `volar-service-tsconfig` package
- Deprecate `volar-service-pretty-ts-errors` package
- Make all editor settings configurable [#78](https://github.com/volarjs/services/issues/78)
	- Most services now expose `documentSelector` / `*DocumentSelector` option.
	- Services with formatting capabilities now expose the `isFormattingEnabled` option.
	- **css:** no longer has built-in support for `postcss` language. If necessary, you can configure `scssDocumentSelector: ['scss', 'postcss']` option.
	- **html:** if you need to update custom data, now you should implement the `onDidChangeCustomData` option instead of inject `'html/updateCustomData'` key.

### Bug Fixes

- **html:** reference resolving inconsistent with VSCode
- **html:** script block formatting inconsistent with VSCode
- **css, html, json, yaml:** respect `ClientCapabilities.textDocument.foldingRange` option
- **typescript:** semantic tokens return redundant invalid results

## [0.0.30](https://github.com/volarjs/services/compare/v0.0.29...v0.0.30) (2024-02-13)

### Bug Fixes

- **typescript:** `validate.enable` config not working for semantic check

## [0.0.29](https://github.com/volarjs/services/compare/v0.0.28...v0.0.29) (2024-02-10)

### Bug Fixes

- **html:** `autoClosingTags` not working at first line

## [0.0.28](https://github.com/volarjs/services/compare/v0.0.27...v0.0.28) (2024-02-05)

### Features

- **typescript:** support for extra scripts [#74](https://github.com/volarjs/services/issues/74)

### Bug Fixes

- **typescript:** only process `getScript()` result in semantic features [#73](https://github.com/volarjs/services/issues/73)

## [0.0.27](https://github.com/volarjs/services/compare/v0.0.17...v0.0.27) (2024-01-21)

### Features

- Upgrade to Volar 2.0
- **typescript:** consume `ReferenceContext` [#65](https://github.com/volarjs/services/issues/65)
- **markdown:** support user defined diagnostic options [#67](https://github.com/volarjs/services/issues/67)
- **prettier:** add `getPrettier` option [#68](https://github.com/volarjs/services/issues/68)
- **markdown:** add markdown trigger characters [#70](https://github.com/volarjs/services/issues/70)
- **markdown:** implement definitions for markdown [#71](https://github.com/volarjs/services/issues/71)

### Bug Fixes

- **typescript:** fix `*.suggest.enabled`, `*.validate.enable` config options not working (https://github.com/volarjs/services/commit/6f13b47fc01e9999f6fa46023f80225957f421f8)

### Breaking Changes

- `volar-service-eslint`, `volar-service-tslint` has been deprecated [#72](https://github.com/volarjs/services/issues/72)
