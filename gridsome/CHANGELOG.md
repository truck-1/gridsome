# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

<a name="0.4.5"></a>
## [0.4.5](https://github.com/gridsome/gridsome/compare/gridsome@0.4.4...gridsome@0.4.5) (2019-01-26)


### Bug Fixes

* **app:** custom favicon path ([#149](https://github.com/gridsome/gridsome/issues/149)) ([f6b6b3d](https://github.com/gridsome/gridsome/commit/f6b6b3d)), closes [#138](https://github.com/gridsome/gridsome/issues/138)
* **g-image:** bind custom classes to object ([#151](https://github.com/gridsome/gridsome/issues/151)) ([10150ca](https://github.com/gridsome/gridsome/commit/10150ca))





<a name="0.4.4"></a>
## [0.4.4](https://github.com/gridsome/gridsome/compare/gridsome@0.4.3...gridsome@0.4.4) (2019-01-15)


### Bug Fixes

* **graphql:** merge ref fields correctly ([#128](https://github.com/gridsome/gridsome/issues/128), [#129](https://github.com/gridsome/gridsome/issues/129)) ([ffb29ee](https://github.com/gridsome/gridsome/commit/ffb29ee))
* **webpack:** cache graphql loader results ([6e794ab](https://github.com/gridsome/gridsome/commit/6e794ab))
* **webpack:** transpile custom blocks ([#130](https://github.com/gridsome/gridsome/issues/130)) ([c81fee4](https://github.com/gridsome/gridsome/commit/c81fee4))





<a name="0.4.3"></a>
## [0.4.3](https://github.com/gridsome/gridsome/compare/gridsome@0.4.2...gridsome@0.4.3) (2019-01-09)


### Bug Fixes

* **webpack:** fix config for IE support ([e403f4c](https://github.com/gridsome/gridsome/commit/e403f4c))





<a name="0.4.2"></a>
## [0.4.2](https://github.com/gridsome/gridsome/compare/gridsome@0.4.1...gridsome@0.4.2) (2019-01-07)


### Bug Fixes

* **route:** allow node props as route params ([1658fde](https://github.com/gridsome/gridsome/commit/1658fde))
* **store:** update node content and excerpt ([637e0e4](https://github.com/gridsome/gridsome/commit/637e0e4))





<a name="0.4.1"></a>
## [0.4.1](https://github.com/gridsome/gridsome/compare/gridsome@0.4.0...gridsome@0.4.1) (2019-01-03)


### Bug Fixes

* **config:** customizing host and port ([bc44a64](https://github.com/gridsome/gridsome/commit/bc44a64))
* **config:** use host and port from project config ([7936aa7](https://github.com/gridsome/gridsome/commit/7936aa7))
* **graphql:** fix deprecated references api ([cb6f245](https://github.com/gridsome/gridsome/commit/cb6f245))
* **image:** don’t re-render when parent updates ([#93](https://github.com/gridsome/gridsome/issues/93)) ([c813d70](https://github.com/gridsome/gridsome/commit/c813d70))
* **pathPrefix:** don’t create subfolder ([#85](https://github.com/gridsome/gridsome/issues/85)) ([96bfbed](https://github.com/gridsome/gridsome/commit/96bfbed))
* **router:** add leading slash to routes ([4024ace](https://github.com/gridsome/gridsome/commit/4024ace))





<a name="0.4.0"></a>
# [0.4.0](https://github.com/gridsome/gridsome/compare/gridsome@0.3.6...gridsome@0.4.0) (2018-12-19)


### Bug Fixes

* **app:** use default link behavior if 404 ([f9aeed7](https://github.com/gridsome/gridsome/commit/f9aeed7))
* **g-link:** customizable active classes ([#65](https://github.com/gridsome/gridsome/issues/65)) ([0ee5273](https://github.com/gridsome/gridsome/commit/0ee5273))
* **g-link:** link to local files ([ece2de5](https://github.com/gridsome/gridsome/commit/ece2de5))
* **graphql:** include empty string type in schema ([44b68b2](https://github.com/gridsome/gridsome/commit/44b68b2))
* **graphql:** return null for missing images ([39c5a92](https://github.com/gridsome/gridsome/commit/39c5a92))
* **graphql:** warn when missing reference ([a6f7857](https://github.com/gridsome/gridsome/commit/a6f7857))
* **router:** fetch data for paths with hash ([19a0c78](https://github.com/gridsome/gridsome/commit/19a0c78))
* **store:** dont process null value as an object ([a05bb5a](https://github.com/gridsome/gridsome/commit/a05bb5a))


### Features

* **build:** image processing cache ([#57](https://github.com/gridsome/gridsome/issues/57)) ([0a9e449](https://github.com/gridsome/gridsome/commit/0a9e449))
* **graphql:** add custom metadata ([#54](https://github.com/gridsome/gridsome/issues/54)) ([7b35378](https://github.com/gridsome/gridsome/commit/7b35378))
* **graphql:** reference with multiple node types ([#50](https://github.com/gridsome/gridsome/issues/50)) ([185297f](https://github.com/gridsome/gridsome/commit/185297f))
* **image:** crop by width and height ([#78](https://github.com/gridsome/gridsome/issues/78)) ([001aa0b](https://github.com/gridsome/gridsome/commit/001aa0b))
* **router:** custom fields as params ([#53](https://github.com/gridsome/gridsome/issues/53)) ([f53f67f](https://github.com/gridsome/gridsome/commit/f53f67f))
* **webpack:** runtimeCompiler config ([cdb676f](https://github.com/gridsome/gridsome/commit/cdb676f))
* **webpack:** transpileDependencies config ([36e4932](https://github.com/gridsome/gridsome/commit/36e4932))





<a name="0.3.6"></a>
## [0.3.6](https://github.com/gridsome/gridsome/compare/gridsome@0.3.5...gridsome@0.3.6) (2018-12-10)


### Bug Fixes

* **graphql:** dont infer filename as file type ([3a04df9](https://github.com/gridsome/gridsome/commit/3a04df9))
* **image:** exclude unecessary data ([574928c](https://github.com/gridsome/gridsome/commit/574928c))





<a name="0.3.5"></a>
## [0.3.5](https://github.com/gridsome/gridsome/compare/gridsome@0.3.4...gridsome@0.3.5) (2018-12-05)


### Bug Fixes

* **api:** pass graphql object to addSchemaField ([#64](https://github.com/gridsome/gridsome/issues/64)) ([f6fd2a8](https://github.com/gridsome/gridsome/commit/f6fd2a8))
* **build:** fix beforeProcessAssets hook name ([8eafe68](https://github.com/gridsome/gridsome/commit/8eafe68))
* **favicon:** set mime type for icons in head ([bface4d](https://github.com/gridsome/gridsome/commit/bface4d))
* **graphql:** do not use file type for urls ([fd14b44](https://github.com/gridsome/gridsome/commit/fd14b44))
* **graphql:** fix order argument for collections ([3e6a1fa](https://github.com/gridsome/gridsome/commit/3e6a1fa))
* **graphql:** get node by id ([ba83545](https://github.com/gridsome/gridsome/commit/ba83545))
* **graphql:** transform nested invalid field names ([5555354](https://github.com/gridsome/gridsome/commit/5555354))
* **touchicon:** use correct sizes when custom icon ([db1c349](https://github.com/gridsome/gridsome/commit/db1c349))





<a name="0.3.4"></a>
## [0.3.4](https://github.com/gridsome/gridsome/compare/gridsome@0.3.3...gridsome@0.3.4) (2018-11-22)


### Bug Fixes

* **graphql:** do not use file type if no extension ([3b1fb7c](https://github.com/gridsome/gridsome/commit/3b1fb7c))
* **webpack:** allow async chainWebpack ([a0caa84](https://github.com/gridsome/gridsome/commit/a0caa84))





<a name="0.3.3"></a>
## [0.3.3](https://github.com/gridsome/gridsome/compare/gridsome@0.3.2...gridsome@0.3.3) (2018-11-16)


### Bug Fixes

* re-create routes after a node.path change ([b6e16c9](https://github.com/gridsome/gridsome/commit/b6e16c9))





<a name="0.3.2"></a>
## [0.3.2](https://github.com/gridsome/gridsome/compare/gridsome@0.3.1...gridsome@0.3.2) (2018-11-16)


### Bug Fixes

* **graphql:** merge nested object fields ([f2e9d4a](https://github.com/gridsome/gridsome/commit/f2e9d4a))
* **webpack:** absolute path to 404 fallback ([97e5e36](https://github.com/gridsome/gridsome/commit/97e5e36)), closes [#43](https://github.com/gridsome/gridsome/issues/43)
* **webpack:** load local babel config files ([975bfea](https://github.com/gridsome/gridsome/commit/975bfea))





<a name="0.3.1"></a>
## [0.3.1](https://github.com/gridsome/gridsome/compare/gridsome@0.3.0...gridsome@0.3.1) (2018-11-14)


### Bug Fixes

* **graphql:** get sub fields from object fields ([039a532](https://github.com/gridsome/gridsome/commit/039a532))
* **graphql:** return correct dates ([1965091](https://github.com/gridsome/gridsome/commit/1965091))
* **ssr:** render body scripts from vue-meta ([b4b50bd](https://github.com/gridsome/gridsome/commit/b4b50bd))
* **webpack:** run chainWebpack after all plugins ([2cc5850](https://github.com/gridsome/gridsome/commit/2cc5850))





<a name="0.3.0"></a>
# [0.3.0](https://github.com/gridsome/gridsome/compare/gridsome@0.2.5...gridsome@0.3.0) (2018-11-11)


### Bug Fixes

* clear errors in terminal when resolved ([832e7de](https://github.com/gridsome/gridsome/commit/832e7de))
* dont fail when missing favicon.png ([829091b](https://github.com/gridsome/gridsome/commit/829091b))
* handle urls in process queue ([60623ee](https://github.com/gridsome/gridsome/commit/60623ee))
* **image:** render fallback as html string ([738ef23](https://github.com/gridsome/gridsome/commit/738ef23))
* **store:** warn and skip when duplicate path detected ([215b3e9](https://github.com/gridsome/gridsome/commit/215b3e9))
* keep hash when resolving raw html links ([87860ab](https://github.com/gridsome/gridsome/commit/87860ab))
* lazy load external image urls ([4f7f867](https://github.com/gridsome/gridsome/commit/4f7f867))
* send context to transformer ([7b50bae](https://github.com/gridsome/gridsome/commit/7b50bae))
* send graphql to createSchema api ([86363c3](https://github.com/gridsome/gridsome/commit/86363c3))
* update routes when source path changes ([85171cf](https://github.com/gridsome/gridsome/commit/85171cf))


### Features

* addReference and addSchemaField ([c159ee5](https://github.com/gridsome/gridsome/commit/c159ee5))
* build hooks ([32774f0](https://github.com/gridsome/gridsome/commit/32774f0))
* cleaner graphql schema ([#31](https://github.com/gridsome/gridsome/issues/31)) ([98420a2](https://github.com/gridsome/gridsome/commit/98420a2))
* client plugin api ([caa6a17](https://github.com/gridsome/gridsome/commit/caa6a17))
* copy linked files ([7dd26f2](https://github.com/gridsome/gridsome/commit/7dd26f2))
* plugin api ([7a7889b](https://github.com/gridsome/gridsome/commit/7a7889b))
* **contentful:** use new plugin api ([eaf6092](https://github.com/gridsome/gridsome/commit/eaf6092))
* **graphql:** createSchema api [wip] ([c5d6d6b](https://github.com/gridsome/gridsome/commit/c5d6d6b))
* **graphql:** date field type ([d9f8335](https://github.com/gridsome/gridsome/commit/d9f8335))
* **graphql:** file type ([05f6c98](https://github.com/gridsome/gridsome/commit/05f6c98))
* **graphql:** image arguments ([e38b243](https://github.com/gridsome/gridsome/commit/e38b243))
* **graphql:** image type ([#25](https://github.com/gridsome/gridsome/issues/25)) ([316c91d](https://github.com/gridsome/gridsome/commit/316c91d))
* **graphql:** merge third party schemas ([1f33169](https://github.com/gridsome/gridsome/commit/1f33169))
* resolve file paths ([#26](https://github.com/gridsome/gridsome/issues/26)) ([a4baf68](https://github.com/gridsome/gridsome/commit/a4baf68))
* store api ([15d1c97](https://github.com/gridsome/gridsome/commit/15d1c97))
* **store:** set content and excerpt on node ([43c4236](https://github.com/gridsome/gridsome/commit/43c4236))
* support local plugins ([#22](https://github.com/gridsome/gridsome/issues/22)) ([568207f](https://github.com/gridsome/gridsome/commit/568207f))





<a name="0.2.5"></a>
## [0.2.5](https://github.com/gridsome/gridsome/compare/gridsome@0.2.4...gridsome@0.2.5) (2018-10-30)


### Bug Fixes

* prioritize static files ([6326958](https://github.com/gridsome/gridsome/commit/6326958))
* **image:** add more attributes to markup ([5c5052d](https://github.com/gridsome/gridsome/commit/5c5052d))
* send context to transofmers ([0b5840e](https://github.com/gridsome/gridsome/commit/0b5840e))


<a name="0.2.4"></a>
## [0.2.4](https://github.com/gridsome/gridsome/compare/gridsome@0.2.3...gridsome@0.2.4) (2018-10-22)


### Bug Fixes

* **build:** clear cached data files ([909caa0](https://github.com/gridsome/gridsome/commit/909caa0))
* **build:** use correct path for pagination ([e8a642c](https://github.com/gridsome/gridsome/commit/e8a642c))


<a name="0.2.3"></a>
## [0.2.3](https://github.com/gridsome/gridsome/compare/gridsome@0.2.2...gridsome@0.2.3) (2018-10-20)


### Bug Fixes

* don’t create routes for missing content types ([9eb216e](https://github.com/gridsome/gridsome/commit/9eb216e))
* **image:** send quality attr to worker ([4fd5151](https://github.com/gridsome/gridsome/commit/4fd5151))


<a name="0.2.2"></a>
## [0.2.2](https://github.com/gridsome/gridsome/compare/gridsome@0.2.1...gridsome@0.2.2) (2018-10-17)


### Bug Fixes

* forward slash component file path ([5c8e0d6](https://github.com/gridsome/gridsome/commit/5c8e0d6))
* hot reload page-query in windows ([f1ab80a](https://github.com/gridsome/gridsome/commit/f1ab80a))
* make paths in loaders work in windows ([7e27ca1](https://github.com/gridsome/gridsome/commit/7e27ca1))


<a name="0.2.1"></a>
## [0.2.1](https://github.com/gridsome/gridsome/compare/gridsome@0.2.0...gridsome@0.2.1) (2018-10-16)


### Bug Fixes

* ensure cache dir exists ([f243338](https://github.com/gridsome/gridsome/commit/f243338))
* use correct paths on windows ([fd624df](https://github.com/gridsome/gridsome/commit/fd624df))


<a name="0.2.0"></a>
# [0.2.0](https://github.com/gridsome/gridsome/compare/gridsome@0.1.2...gridsome@0.2.0) (2018-10-15)


### Bug Fixes

* **app:** use pathPrefix option ([7edfb79](https://github.com/gridsome/gridsome/commit/7edfb79))
* **build:** adjustments for better render times ([290e92d](https://github.com/gridsome/gridsome/commit/290e92d))
* **build:** check if static dir exists ([e42ca05](https://github.com/gridsome/gridsome/commit/e42ca05))
* **build:** keep leading slash for paged paths ([a2abccc](https://github.com/gridsome/gridsome/commit/a2abccc))
* **build:** show error stack form render failures ([5ba558e](https://github.com/gridsome/gridsome/commit/5ba558e))
* freeze base config object to prevent changes ([5fad26f](https://github.com/gridsome/gridsome/commit/5fad26f))
* replace path prefix correctly in links ([90dc133](https://github.com/gridsome/gridsome/commit/90dc133))
* **build:** use correct manifest path ([7a204be](https://github.com/gridsome/gridsome/commit/7a204be))
* **develop:** exclude dev middleware for playground route ([cff46b9](https://github.com/gridsome/gridsome/commit/cff46b9))
* **graphql:** hot reload page-query changes ([017aa95](https://github.com/gridsome/gridsome/commit/017aa95))
* **image:** hot reload after changes ([b4d83e7](https://github.com/gridsome/gridsome/commit/b4d83e7)), closes [#3](https://github.com/gridsome/gridsome/issues/3)
* **webpack:** page data importer in separate chunk ([34b8244](https://github.com/gridsome/gridsome/commit/34b8244))


### Features

* dir for static files ([4185564](https://github.com/gridsome/gridsome/commit/4185564))


<a name="0.1.2"></a>
## [0.1.2](https://github.com/gridsome/gridsome/compare/gridsome@0.1.1...gridsome@0.1.2) (2018-09-27)


### Bug Fixes

* show system info at startup ([de9793e](https://github.com/gridsome/gridsome/commit/de9793e))
* stop worker if any errors ([9890a26](https://github.com/gridsome/gridsome/commit/9890a26))
* **build:** better error if render fails ([7158300](https://github.com/gridsome/gridsome/commit/7158300))
* **build:** dont prefetch data chunks ([46e80a4](https://github.com/gridsome/gridsome/commit/46e80a4))
* **build:** output paths for html and data ([d167e8e](https://github.com/gridsome/gridsome/commit/d167e8e))
* **critical:** use htmlOutput ([c2c9670](https://github.com/gridsome/gridsome/commit/c2c9670))
* **webpack:** alias to gridsome app ([3891e87](https://github.com/gridsome/gridsome/commit/3891e87))


<a name="0.1.1"></a>
## [0.1.1](https://github.com/gridsome/gridsome/compare/gridsome@0.1.0...gridsome@0.1.1) (2018-09-26)


### Bug Fixes

* **cli:** show stack when failing ([7507051](https://github.com/gridsome/gridsome/commit/7507051))
* **data:** strip trailing slash before import ([35fc653](https://github.com/gridsome/gridsome/commit/35fc653))
* **renderer:** protect agains failing ssr vue-meta ([c9ad300](https://github.com/gridsome/gridsome/commit/c9ad300))


<a name="0.1.0"></a>
# [0.1.0](https://github.com/gridsome/gridsome/compare/gridsome@0.0.6...gridsome@0.1.0) (2018-09-26)


### Bug Fixes

* **app:** dont sanitize inline styles and scripts ([eaac209](https://github.com/gridsome/gridsome/commit/eaac209))
* **babel:** dont load config files ([c891593](https://github.com/gridsome/gridsome/commit/c891593))
* **cli:** stop if not in a gridsome dir ([8c29072](https://github.com/gridsome/gridsome/commit/8c29072))
* **graphql:** dont run empty page query ([9cc7176](https://github.com/gridsome/gridsome/commit/9cc7176))
* **image:** dont add lazy class when no srcset ([f3e4257](https://github.com/gridsome/gridsome/commit/f3e4257))
* **image:** init observer in client only ([4c4dad9](https://github.com/gridsome/gridsome/commit/4c4dad9))
* **image:** re-observe after hot-reload ([dfeeb90](https://github.com/gridsome/gridsome/commit/dfeeb90))


### Features

* GRIDSOME_MODE env variable ([561e72c](https://github.com/gridsome/gridsome/commit/561e72c))
* **app:** send isServer and isClient to main.js ([fe01c8e](https://github.com/gridsome/gridsome/commit/fe01c8e))
* **cli:** gridsome serve ([a91c7fc](https://github.com/gridsome/gridsome/commit/a91c7fc))
* **env:** rename to isClient and isServer ([90880c6](https://github.com/gridsome/gridsome/commit/90880c6))
* **graphql:** rename graphql block to page-query ([8bf5e1a](https://github.com/gridsome/gridsome/commit/8bf5e1a))
* **image:** generate blured inline svg ([bd54dfe](https://github.com/gridsome/gridsome/commit/bd54dfe))


<a name="0.0.6"></a>
## [0.0.6](https://github.com/gridsome/gridsome/compare/gridsome@0.0.5...gridsome@0.0.6) (2018-09-18)


### Bug Fixes

* **worker:** set jpeg quality ([31f8929](https://github.com/gridsome/gridsome/commit/31f8929))


<a name="0.0.5"></a>
## [0.0.5](https://github.com/gridsome/gridsome/compare/gridsome@0.0.4...gridsome@0.0.5) (2018-09-18)


### Bug Fixes

* **app:** prevent duplicate router.push ([508dd58](https://github.com/gridsome/gridsome/commit/508dd58))
* **image:** resize by width attribute + test ([7ac63a7](https://github.com/gridsome/gridsome/commit/7ac63a7))
* **worker:** resize images correctly ([61d2e74](https://github.com/gridsome/gridsome/commit/61d2e74))


### Features

* **app:** browser field in package json ([3e87581](https://github.com/gridsome/gridsome/commit/3e87581))
* **app:** gen favicon and touchicon sizes [#4](https://github.com/gridsome/gridsome/issues/4) ([3448301](https://github.com/gridsome/gridsome/commit/3448301))
* **webpack:** alias ~ to src dir ([81c1a5f](https://github.com/gridsome/gridsome/commit/81c1a5f))


<a name="0.0.4"></a>
## [0.0.4](https://github.com/gridsome/gridsome/compare/gridsome@0.0.3...gridsome@0.0.4) (2018-09-17)

**Note:** Version bump only for package gridsome


<a name="0.0.3"></a>
## [0.0.3](https://github.com/gridsome/gridsome/compare/142896c2454016dc989a7872faffec7263fc658c...gridsome@0.0.3) (2018-09-17)


### Bug Fixes

* webpack progress in tty only ([bab7e8a](https://github.com/gridsome/gridsome/commit/bab7e8a))



<a name="0.0.2"></a>
## [0.0.2](https://github.com/gridsome/gridsome/compare/142896c2454016dc989a7872faffec7263fc658c...gridsome@0.0.3) (2018-09-16)


### Bug Fixes

* add local bin to core package ([0bab302](https://github.com/gridsome/gridsome/commit/0bab302))
