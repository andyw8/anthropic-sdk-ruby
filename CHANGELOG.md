# Changelog

## 1.3.0 (2025-07-28)

Full Changelog: [v1.2.0...v1.3.0](https://github.com/anthropics/anthropic-sdk-ruby/compare/v1.2.0...v1.3.0)

### Features

* **api:** removed older deprecated models ([47de6c2](https://github.com/anthropics/anthropic-sdk-ruby/commit/47de6c2860fabd344374aed733df1bcb17988454))
* **client:** add beta stream implementation and fine grained tool streaming example ([2856b81](https://github.com/anthropics/anthropic-sdk-ruby/commit/2856b8119b99e6487093df3f49216ecc8d1bd3e3))
* **client:** add beta stream implementation and fine grained tool streaming example ([bc87fd4](https://github.com/anthropics/anthropic-sdk-ruby/commit/bc87fd4afd94a48301fec548a0e7b21f44a24a59))


### Bug Fixes

* **internal:** ensure sorbet test always runs serially ([0b39a19](https://github.com/anthropics/anthropic-sdk-ruby/commit/0b39a1908587597ca5836872333541307f24bdf2))
* **internal:** ensure vertex client test ordering ([#667](https://github.com/anthropics/anthropic-sdk-ruby/issues/667)) ([d7439fa](https://github.com/anthropics/anthropic-sdk-ruby/commit/d7439fa58664d9a533cacca6a299b3dbbe43ec7f))


### Chores

* add basic tool use example ([#107](https://github.com/anthropics/anthropic-sdk-ruby/issues/107)) ([4452119](https://github.com/anthropics/anthropic-sdk-ruby/commit/445211929b09ff0be9406aad1b3f3604d8bf3794))
* add Darwin to PLATFORMS in Gemfile.lock ([#104](https://github.com/anthropics/anthropic-sdk-ruby/issues/104)) ([aa5bcbe](https://github.com/anthropics/anthropic-sdk-ruby/commit/aa5bcbedc48cc9a49ba14050fa3ad934a6f95c99))
* **internal:** run formatter ([87ce979](https://github.com/anthropics/anthropic-sdk-ruby/commit/87ce979a06108f980e8c867d43166fbeeff02ec3))
* update contribute.md ([aa928a0](https://github.com/anthropics/anthropic-sdk-ruby/commit/aa928a09f08250c9e6e93b884761eb35a9d5b6b4))

## 1.2.0 (2025-07-18)

Full Changelog: [v1.1.1...v1.2.0](https://github.com/anthropics/anthropic-sdk-ruby/compare/v1.1.1...v1.2.0)

### Features

* **api:** add support for Search Result Content Blocks ([158a7ce](https://github.com/anthropics/anthropic-sdk-ruby/commit/158a7ced1013c3af956554caf41ee08ec5d1db3c))
* **api:** api update ([cd22765](https://github.com/anthropics/anthropic-sdk-ruby/commit/cd2276536c7960a4f7276ceb9baba8ba5aec196e))
* **api:** manual updates ([7f51b33](https://github.com/anthropics/anthropic-sdk-ruby/commit/7f51b336943422d230d8704583f42dc6f8a3ac62))
* **client:** add breaking change detection to CI ([52e342f](https://github.com/anthropics/anthropic-sdk-ruby/commit/52e342fe8c8231ad6b6b6ff68ed522033cd503c7))
* **client:** add support for new text_editor_20250429 tool ([9049af2](https://github.com/anthropics/anthropic-sdk-ruby/commit/9049af2f634f88d867104f2dc0ddc6396f5f8031))
* streaming helpers ([#627](https://github.com/anthropics/anthropic-sdk-ruby/issues/627)) ([43fbbf8](https://github.com/anthropics/anthropic-sdk-ruby/commit/43fbbf8a39ac1d99920845ba19da43d7419a5e73))
* **vertex:** support global region endpoint ([da8c452](https://github.com/anthropics/anthropic-sdk-ruby/commit/da8c452a22c56780f311f4f1ab3477a48ac46891))


### Bug Fixes

* `to_sorbet_type` should not return branded types ([2658903](https://github.com/anthropics/anthropic-sdk-ruby/commit/2658903f13178a133ca679f4b87615e9cddcd813))
* **ci:** release-doctor — report correct token name ([e30183e](https://github.com/anthropics/anthropic-sdk-ruby/commit/e30183e5561070dfd3dfe041f48e76765975cb3b))
* **client:** deprecate BetaBase64PDFBlock in favor of BetaRequestDocumentBlock ([f75705b](https://github.com/anthropics/anthropic-sdk-ruby/commit/f75705bfb4af3160b2fa7208adfad10719cd17a7))
* default content-type for text in multi-part formdata uploads should be text/plain ([0a91592](https://github.com/anthropics/anthropic-sdk-ruby/commit/0a915925fc93ca7ad191bab33dba8c72b6c48a2a))
* **internal:** fix: should publish to ruby gems when a release is created ([cc88c6c](https://github.com/anthropics/anthropic-sdk-ruby/commit/cc88c6c7c164c5bb1937e12cefb4d91f05fec157))
* issue where we cannot mutate arrays on base model derivatives ([446c8be](https://github.com/anthropics/anthropic-sdk-ruby/commit/446c8be0eb77a29641d472ea36cbaf6f786f7e3a))


### Chores

* add `license` to the gemspec ([#101](https://github.com/anthropics/anthropic-sdk-ruby/issues/101)) ([af509a7](https://github.com/anthropics/anthropic-sdk-ruby/commit/af509a735c0e985e615f9279bc070dc090874df8))
* add RBS types for helpers/streaming ([#631](https://github.com/anthropics/anthropic-sdk-ruby/issues/631)) ([0d7941d](https://github.com/anthropics/anthropic-sdk-ruby/commit/0d7941df6628b1500f7e7e8def88f613d7bcf2fa))
* **api:** mark claude-3-opus-20240229 as deprecated ([1edd9bd](https://github.com/anthropics/anthropic-sdk-ruby/commit/1edd9bdf0bf508f5467daf92c4b1db11128d70ea))
* **api:** update BetaCitationSearchResultLocation ([b294f7e](https://github.com/anthropics/anthropic-sdk-ruby/commit/b294f7e2bfd44d01504eeb7e30b37926ca7200e2))
* **ci:** enable for pull requests ([31bbb43](https://github.com/anthropics/anthropic-sdk-ruby/commit/31bbb43d02cc56505ad5ec8d737801b73f9f5fd8))
* **ci:** link to correct github repo ([37b5902](https://github.com/anthropics/anthropic-sdk-ruby/commit/37b59027a26268ad5bb20ee6530c7f0c630bc5b5))
* **ci:** only run for pushes and fork pull requests ([8d3c942](https://github.com/anthropics/anthropic-sdk-ruby/commit/8d3c9425afe873a49e403c7a8a36f14642191a89))
* **internal:** allow streams to also be unwrapped on a per-row basis ([a271d21](https://github.com/anthropics/anthropic-sdk-ruby/commit/a271d21d2f01a9f7c9c2d126b1f3d9b0611dd8cd))
* **internal:** codegen related update ([8b12fd6](https://github.com/anthropics/anthropic-sdk-ruby/commit/8b12fd6e8ec1c06d3cbf7d20c63c6933538d0983))
* remove workaround for updating arrays in place in streaming ([#643](https://github.com/anthropics/anthropic-sdk-ruby/issues/643)) ([e0a30b8](https://github.com/anthropics/anthropic-sdk-ruby/commit/e0a30b8128624566f673ac77f97c305953b11c63))


### Documentation

* model in examples ([18ba0b6](https://github.com/anthropics/anthropic-sdk-ruby/commit/18ba0b62bd8f87b84766265726090ca2265a64b7))
* update documentation in MessageStream ([#630](https://github.com/anthropics/anthropic-sdk-ruby/issues/630)) ([4795c73](https://github.com/anthropics/anthropic-sdk-ruby/commit/4795c73f0628d2bc710f77bd0868be18c53ec31a))
* update models and non-beta ([a4ea04e](https://github.com/anthropics/anthropic-sdk-ruby/commit/a4ea04eaf88e608612512d39d07051842beaf500))

## 1.1.1 (2025-05-28)

Full Changelog: [v1.1.0...v1.1.1](https://github.com/anthropics/anthropic-sdk-ruby/compare/v1.1.0...v1.1.1)

### Bug Fixes

* prevent rubocop from mangling `===` to `is_a?` check ([303ad55](https://github.com/anthropics/anthropic-sdk-ruby/commit/303ad550c542c726b2ce8bc3d53e01108af634d5))
* sorbet types for enums, and make tapioca detection ignore `tapioca dsl` ([fb289a1](https://github.com/anthropics/anthropic-sdk-ruby/commit/fb289a1be37379cea207b024e0fb4503ea174639))


### Chores

* add more examples ([e14665e](https://github.com/anthropics/anthropic-sdk-ruby/commit/e14665e4e236cce4a17de06507d1b855d1d153d2))
* image example ([#621](https://github.com/anthropics/anthropic-sdk-ruby/issues/621)) ([9bdc648](https://github.com/anthropics/anthropic-sdk-ruby/commit/9bdc6487d77d856c87d658917f53faa6f12bc38f))
* **internal:** fix release workflows ([fffb4b8](https://github.com/anthropics/anthropic-sdk-ruby/commit/fffb4b8eeff759ac98e9cfb5d778b014336e2956))
* more examples ([#619](https://github.com/anthropics/anthropic-sdk-ruby/issues/619)) ([e14665e](https://github.com/anthropics/anthropic-sdk-ruby/commit/e14665e4e236cce4a17de06507d1b855d1d153d2))

## 1.1.0 (2025-05-22)

Full Changelog: [v1.0.0...v1.1.0](https://github.com/anthropics/anthropic-sdk-ruby/compare/v1.0.0...v1.1.0)

### Features

* **api:** add claude 4 models, files API, code execution tool, MCP connector and more ([5dd465d](https://github.com/anthropics/anthropic-sdk-ruby/commit/5dd465dac56891b5f21e51e73edac15131d04453))


### Chores

* use fully qualified names for yard annotations and rbs aliases ([80332a0](https://github.com/anthropics/anthropic-sdk-ruby/commit/80332a019ae8bb49d839516256fc4314db7648b9))

## 1.0.0 (2025-05-21)

Full Changelog: [v0.1.0-beta.9...v1.0.0](https://github.com/anthropics/anthropic-sdk-ruby/compare/v0.1.0-beta.9...v1.0.0)

### Chores

* force utf-8 locale via `RUBYOPT` when formatting ([55bfa9d](https://github.com/anthropics/anthropic-sdk-ruby/commit/55bfa9d146b9f983d20a01b180f968c0649d171b))
* **internal:** version bump ([595b2c8](https://github.com/anthropics/anthropic-sdk-ruby/commit/595b2c8221b79acb4814384a32f3beea822e3a8d))

## 0.1.0-beta.9 (2025-05-21)

Full Changelog: [v0.1.0-beta.8...v0.1.0-beta.9](https://github.com/anthropics/anthropic-sdk-ruby/compare/v0.1.0-beta.8...v0.1.0-beta.9)

### Features

* **api:** manual updates ([c68662a](https://github.com/anthropics/anthropic-sdk-ruby/commit/c68662a15bab31a97e332a3d667ec3b580276f7a))


### Bug Fixes

* correctly instantiate sorbet type aliases for enums and unions ([e79b78d](https://github.com/anthropics/anthropic-sdk-ruby/commit/e79b78def9c79c6602bdd05ae87022682255769d))


### Chores

* **internal:** version bump ([6d1c2e6](https://github.com/anthropics/anthropic-sdk-ruby/commit/6d1c2e6d8f50b1b4352af9cb27851f37127855ec))
* refine Yard and Sorbet types and ensure linting is turned on for examples ([530daaf](https://github.com/anthropics/anthropic-sdk-ruby/commit/530daaf8161c18635324a839bc0ba7a8d74204d6))
* remove beta message for GA release ([#613](https://github.com/anthropics/anthropic-sdk-ruby/issues/613)) ([e7cee11](https://github.com/anthropics/anthropic-sdk-ruby/commit/e7cee11d280381a5832917b984b1cf9598893eb7))
* remove legacy bedrock example ([#609](https://github.com/anthropics/anthropic-sdk-ruby/issues/609)) ([256fa36](https://github.com/anthropics/anthropic-sdk-ruby/commit/256fa36937ef642db16d126ee908f9760844b418))
* use sorbet union aliases where available ([a21753a](https://github.com/anthropics/anthropic-sdk-ruby/commit/a21753ab23550944f299c7deada3cbb03d12ad66))
* whitespaces ([f622e39](https://github.com/anthropics/anthropic-sdk-ruby/commit/f622e39936d338caa833bff46786d72a1855624a))


### Documentation

* README updates for GA release ([#602](https://github.com/anthropics/anthropic-sdk-ruby/issues/602)) ([6cdf0c3](https://github.com/anthropics/anthropic-sdk-ruby/commit/6cdf0c335642b64dd13825f8b3367d6f70990b3e))

## 0.1.0-beta.8 (2025-05-19)

Full Changelog: [v0.1.0-beta.7...v0.1.0-beta.8](https://github.com/anthropics/anthropic-sdk-ruby/compare/v0.1.0-beta.7...v0.1.0-beta.8)

### Chores

* **internal:** version bump ([8d8501b](https://github.com/anthropics/anthropic-sdk-ruby/commit/8d8501bc3b2f24c3519574c3f04d72720c599f15))

## 0.1.0-beta.7 (2025-05-15)

Full Changelog: [v0.1.0-beta.6...v0.1.0-beta.7](https://github.com/anthropics/anthropic-sdk-ruby/compare/v0.1.0-beta.6...v0.1.0-beta.7)

### ⚠ BREAKING CHANGES

* rename Vertex::Client and Bedrock::Client to VertexClient and BedrockClient

### Features

* bump default connection pool size limit to minimum of 99 ([5170cb6](https://github.com/anthropics/anthropic-sdk-ruby/commit/5170cb6172644012bb6f2580a6789c965088a01a))
* **client:** enable setting base URL from environment variable ([9cb10b1](https://github.com/anthropics/anthropic-sdk-ruby/commit/9cb10b1491761bb101269b92f4229183355ff77b))
* expose base client options as read only attributes ([2813fa7](https://github.com/anthropics/anthropic-sdk-ruby/commit/2813fa78dbc68c7c38cf0b00141f758fda2ff7c3))
* expose recursive `#to_h` conversion ([386a6a7](https://github.com/anthropics/anthropic-sdk-ruby/commit/386a6a78e1ca1f28841a6883d7a72433a9bd40a9))
* implement `#hash` for data containers ([f289994](https://github.com/anthropics/anthropic-sdk-ruby/commit/f2899941f30d6ce62414a1a866a5c9b47d54c340))
* rename Vertex::Client and Bedrock::Client to VertexClient and BedrockClient ([0506c4f](https://github.com/anthropics/anthropic-sdk-ruby/commit/0506c4f850ed6e289766ebcef7780aeee078398f))
* support sorbet aliases at the runtime ([239b6bb](https://github.com/anthropics/anthropic-sdk-ruby/commit/239b6bb99ad9a6549d30e15dfa7dffe7748fca3f))
* support specifying content-type with FilePart class ([d81f97d](https://github.com/anthropics/anthropic-sdk-ruby/commit/d81f97d27b72fcb30813d037c420657878f78c54))
* support webmock for testing ([91c3d67](https://github.com/anthropics/anthropic-sdk-ruby/commit/91c3d6748c9ead461bbffcd2fac8c621a357160c))


### Bug Fixes

* always send idempotency header when specified as a request option ([c53396e](https://github.com/anthropics/anthropic-sdk-ruby/commit/c53396ea8e8b3afdb572c338af34f7bb0a712151))
* **client:** send correct HTTP path ([4ff371b](https://github.com/anthropics/anthropic-sdk-ruby/commit/4ff371b538e07f3a2ab6c7c4be72616bf425789b))
* ensure gem release is unaffected by renaming ([9dbcb33](https://github.com/anthropics/anthropic-sdk-ruby/commit/9dbcb339381980f9e3e809dda6e9f9fe7133463e))
* **internal:** ensure formatting always uses c.utf-8 locale ([8cdaf4e](https://github.com/anthropics/anthropic-sdk-ruby/commit/8cdaf4ec891bb4b52af12f194d83a8a65d20f72d))
* **internal:** fix formatting script for macos ([acf7bb0](https://github.com/anthropics/anthropic-sdk-ruby/commit/acf7bb0313f4ead5b714864fcd8ca65e9a7a5999))
* **internal:** update gemspec name ([6e1994d](https://github.com/anthropics/anthropic-sdk-ruby/commit/6e1994d2742d7915aceec13b51e25c700c9b82c2))
* make a typo for `FilePart.content` ([8dee858](https://github.com/anthropics/anthropic-sdk-ruby/commit/8dee858a316df5faa7e9e9153f79eee8c558c4d3))
* vertex and bedrock sorbet types ([de4bf33](https://github.com/anthropics/anthropic-sdk-ruby/commit/de4bf3384ee0047e570baee5c7dfe13a2d53aa2b))


### Chores

* accept all nd-json mimetype variants ([1a0c3e3](https://github.com/anthropics/anthropic-sdk-ruby/commit/1a0c3e350ac480539d84fe11edb8bc8a7bde75ba))
* add generator safe directory ([cbaa546](https://github.com/anthropics/anthropic-sdk-ruby/commit/cbaa54667b544ac6afbe182fa88a59f4dda51b80))
* always check if current page is empty in `next_page?` ([ef41b35](https://github.com/anthropics/anthropic-sdk-ruby/commit/ef41b35500600a1c1f02f201832855762d49e2e2))
* amend Gemfile.lock SHA for git dependency ([617d7df](https://github.com/anthropics/anthropic-sdk-ruby/commit/617d7df30d5eec60d4c7af63a2954b6a945c4277))
* broadly detect json family of content-type headers ([eb41428](https://github.com/anthropics/anthropic-sdk-ruby/commit/eb41428c85973c2e664e053415e2777f0d2f39a7))
* **ci:** add timeout thresholds for CI jobs ([ea76f5c](https://github.com/anthropics/anthropic-sdk-ruby/commit/ea76f5c57dc556b094630150248b63a1ae7f431e))
* **ci:** only use depot for staging repos ([213392b](https://github.com/anthropics/anthropic-sdk-ruby/commit/213392bb8c4b3765684a68de2a6aea1e59c0692b))
* **ci:** run on more branches and use depot runners ([b85caa6](https://github.com/anthropics/anthropic-sdk-ruby/commit/b85caa6b9ccb6074a446f195d04b6e2eca07482d))
* consistently use string in examples, even for enums ([2f6528e](https://github.com/anthropics/anthropic-sdk-ruby/commit/2f6528e4f6b4b6317e3f1903bd1381423f0aa8eb))
* documentation improvements ([e479e74](https://github.com/anthropics/anthropic-sdk-ruby/commit/e479e7423fd7db99723af7e000af7915d9025128))
* explicitly mark apis public under `Internal` module ([5adf74c](https://github.com/anthropics/anthropic-sdk-ruby/commit/5adf74c6032dd6bc304f936968d1f90391fc8654))
* fix misc linting / minor issues ([753f93a](https://github.com/anthropics/anthropic-sdk-ruby/commit/753f93acc061764313883e12c3e2c21a65c89344))
* **internal:** always run post-processing when formatting when syntax_tree ([6b66ae9](https://github.com/anthropics/anthropic-sdk-ruby/commit/6b66ae9b0b7bcb695a531ea37242b6ab666490b7))
* **internal:** annotate request options with type aliases in sorbet ([78301c8](https://github.com/anthropics/anthropic-sdk-ruby/commit/78301c845d2f19ca67af13310443699801ca715b))
* **internal:** codegen related update ([c8424fb](https://github.com/anthropics/anthropic-sdk-ruby/commit/c8424fb051fdd61fa9ea747acb3df264409b01e7))
* **internal:** codegen related update ([ea9c02e](https://github.com/anthropics/anthropic-sdk-ruby/commit/ea9c02ed98b2db9103353d5a427daa2fe5531782))
* **internal:** codegen related update ([e60bcc4](https://github.com/anthropics/anthropic-sdk-ruby/commit/e60bcc4b11cd93720300277d28302d86d8566762))
* **internal:** codegen related update ([453af53](https://github.com/anthropics/anthropic-sdk-ruby/commit/453af530dea415d610566e2f8a88f317b5950c0f))
* **internal:** contribute.md and contributor QoL improvements ([c48b418](https://github.com/anthropics/anthropic-sdk-ruby/commit/c48b418733b923bf8d470004df4a179aba989e96))
* **internal:** improve response envelope unwrap functionality ([b807072](https://github.com/anthropics/anthropic-sdk-ruby/commit/b8070726b4d2b2d2612e4141a4c5122935715f76))
* **internal:** loosen internal type restrictions ([7675f8e](https://github.com/anthropics/anthropic-sdk-ruby/commit/7675f8efad31278d372ac1d778fe542202706681))
* **internal:** minor sync ([14829b1](https://github.com/anthropics/anthropic-sdk-ruby/commit/14829b1c97379325af6c716fd25eec7cf75eb7bc))
* **internal:** minor touch ups on sdk internals ([3b4a873](https://github.com/anthropics/anthropic-sdk-ruby/commit/3b4a873177d9cdddcb6c07440619da007615c0bd))
* **internal:** minor type annotation improvements ([e493aef](https://github.com/anthropics/anthropic-sdk-ruby/commit/e493aef841e1c86ef2954c24e029fd3719d5982d))
* **internal:** mostly README touch ups ([b29f388](https://github.com/anthropics/anthropic-sdk-ruby/commit/b29f3887bd12df092cd8398ac6fb82b327c7d2b1))
* **internal:** protect SSE parsing pipeline from broken UTF-8 characters ([74056ed](https://github.com/anthropics/anthropic-sdk-ruby/commit/74056edcb149d9237db1ef83f6afab46ce489689))
* **internal:** remove unnecessary `rbi/lib` folder ([f238fa8](https://github.com/anthropics/anthropic-sdk-ruby/commit/f238fa8af1c36616dfb87ee102165183684898a9))
* **internal:** version bump ([8478780](https://github.com/anthropics/anthropic-sdk-ruby/commit/8478780254d9ea6b489baccefe0b4a33c314e0c8))
* make internal types pretty print ([99c01e4](https://github.com/anthropics/anthropic-sdk-ruby/commit/99c01e43cceeebd97875bdfa8551352076dfb69f))
* make sorbet enums easier to read ([1909c6e](https://github.com/anthropics/anthropic-sdk-ruby/commit/1909c6ed7049fcf0d3b05a32318bd142f8116af7))
* migrate away from deprecated `JSON#fast_generate` ([80308a9](https://github.com/anthropics/anthropic-sdk-ruby/commit/80308a9b311a0a2b9ee1311fdebce93e0aa0427e))
* more accurate type annotations and aliases ([54c04df](https://github.com/anthropics/anthropic-sdk-ruby/commit/54c04df8f8f760aa9eed2466e1af1712a41f8c69))
* move bedrock and vertex under anthropic/helpers ([#574](https://github.com/anthropics/anthropic-sdk-ruby/issues/574)) ([c2f3554](https://github.com/anthropics/anthropic-sdk-ruby/commit/c2f355403be66637d615ff9e8f2f79f27eb35af8))
* re-export top level models under library namespace ([41a5161](https://github.com/anthropics/anthropic-sdk-ruby/commit/41a516134b3a9f4ac62d02a033369fee00162e36))
* refine `#inspect` and `#to_s` for model classes ([de00260](https://github.com/anthropics/anthropic-sdk-ruby/commit/de002609060018c1f61ec5ed84cc497b6a0ef7bb))
* remove Gemfile.lock during bootstrap ([7d671aa](https://github.com/anthropics/anthropic-sdk-ruby/commit/7d671aa814ff52569a8a372691a8964924a6e30c))
* reorganize type aliases ([94c0258](https://github.com/anthropics/anthropic-sdk-ruby/commit/94c0258dc85df0094da63365021f1301c5700a7a))
* revert ignoring Gemfile.lock ([47413aa](https://github.com/anthropics/anthropic-sdk-ruby/commit/47413aa7cae463b941b59f4b963b0d3d12eb60eb))
* show truncated parameter docs in yard ([679c27b](https://github.com/anthropics/anthropic-sdk-ruby/commit/679c27b578b746360f92e778c48c9e9bb105174c))
* simplify yard annotations by removing most `@!parse` directives ([5b23af5](https://github.com/anthropics/anthropic-sdk-ruby/commit/5b23af5a32f8317576e1f37e2685fead060956a6))
* update README with recommended editor plugins ([0c706bb](https://github.com/anthropics/anthropic-sdk-ruby/commit/0c706bbcc23d6affe8223cdf7ec06cc75a241859))
* use `@!method` instead of `@!parse` for virtual method type definitions ([2834dd6](https://github.com/anthropics/anthropic-sdk-ruby/commit/2834dd6f8bcb7ac7fbf2319c3ca948a8ecaa6c07))
* validate request option coercion correctness ([cd89ec5](https://github.com/anthropics/anthropic-sdk-ruby/commit/cd89ec570f37d602b594de786863e6d146d98833))


### Documentation

* fix misplaced coming soon snippet in README.md ([6979aae](https://github.com/anthropics/anthropic-sdk-ruby/commit/6979aae6105c9a26557e756f3a62963c59f9c742))
* illustrate environmental defaults for auth variables ([3f295d8](https://github.com/anthropics/anthropic-sdk-ruby/commit/3f295d8348e7e1c841b99911aa28e49a1b13a3cc))
* **readme:** fix typo ([6effd14](https://github.com/anthropics/anthropic-sdk-ruby/commit/6effd148a3510980e40ecada7b05dd4b856ef5e4))
* rewrite much of README.md for readability ([aaf7e8c](https://github.com/anthropics/anthropic-sdk-ruby/commit/aaf7e8c5ff69c1e209b7af078e3723418ec25b3c))
* update documentation links to be more uniform ([6b95412](https://github.com/anthropics/anthropic-sdk-ruby/commit/6b95412c1193c99bd7f1c701929e76a021f6e39e))

## 0.1.0-beta.6 (2025-04-11)

Full Changelog: [v0.1.0-beta.5...v0.1.0-beta.6](https://github.com/anthropics/anthropic-sdk-ruby/compare/v0.1.0-beta.5...v0.1.0-beta.6)

### Bug Fixes

* inaccuracies in the README.md ([9fa4a77](https://github.com/anthropics/anthropic-sdk-ruby/commit/9fa4a7772cfd01ec0c7d2ec20205740390984d27))
* outdated examples ([c82c0e3](https://github.com/anthropics/anthropic-sdk-ruby/commit/c82c0e3eb1cb9e56f6bb2ff7fbbdd98afae15bed))


### Chores

* fix lsp configuration file for local development ([2928009](https://github.com/anthropics/anthropic-sdk-ruby/commit/2928009aecdcf522fcf2d2f71e82eb4b72e4693a))
* **internal:** update readme with pinned issue thread ([4ef25a4](https://github.com/anthropics/anthropic-sdk-ruby/commit/4ef25a4c1a5a8e3a1a03daf6c614d6da6fd9acba))
* **internal:** version bump ([b12584c](https://github.com/anthropics/anthropic-sdk-ruby/commit/b12584c4f49946c81bc067339d9627ba8b32763b))

## 0.1.0-beta.5 (2025-04-09)

Full Changelog: [v0.1.0-beta.4...v0.1.0-beta.5](https://github.com/anthropics/anthropic-sdk-ruby/compare/v0.1.0-beta.4...v0.1.0-beta.5)

### Chores

* **internal:** reduce CI branch coverage ([52ba9ab](https://github.com/anthropics/anthropic-sdk-ruby/commit/52ba9ab8d17bd798fdfbdcdaeb7765500c6a35c6))
* **internal:** version bump ([5eed725](https://github.com/anthropics/anthropic-sdk-ruby/commit/5eed725fbe49fe86a7bf85331c40880a7f9ac3e7))

## 0.1.0-beta.4 (2025-04-09)

Full Changelog: [v0.1.0-beta.3...v0.1.0-beta.4](https://github.com/anthropics/anthropic-sdk-ruby/compare/v0.1.0-beta.3...v0.1.0-beta.4)

### Chores

* **internal:** version bump ([e539946](https://github.com/anthropics/anthropic-sdk-ruby/commit/e539946a885564f7197ae0f869d28d59095de410))

## 0.1.0-beta.3 (2025-04-09)

Full Changelog: [v0.1.0-beta.2...v0.1.0-beta.3](https://github.com/anthropics/anthropic-sdk-ruby/compare/v0.1.0-beta.2...v0.1.0-beta.3)

### Chores

* add release trigger to publish-gem.yml ([660d3a0](https://github.com/anthropics/anthropic-sdk-ruby/commit/660d3a04a4db23ffa900c8ed8c46abb65fb2a202))
* **internal:** version bump ([ff3effe](https://github.com/anthropics/anthropic-sdk-ruby/commit/ff3effe91c77f2f9adfca40f57031d4a7a01c4fb))

## 0.1.0-beta.2 (2025-04-09)

Full Changelog: [v0.1.0-alpha.1...v0.1.0-beta.2](https://github.com/anthropics/anthropic-sdk-ruby/compare/v0.1.0-alpha.1...v0.1.0-beta.2)

### Features

* **api:** manual updates ([#75](https://github.com/anthropics/anthropic-sdk-ruby/issues/75)) ([5a6b5cc](https://github.com/anthropics/anthropic-sdk-ruby/commit/5a6b5cc8d49083a7ebc28d48d9bb8d7c214c8a0a))
* use Pathname alongside raw IO handles for file uploads ([#68](https://github.com/anthropics/anthropic-sdk-ruby/issues/68)) ([a900382](https://github.com/anthropics/anthropic-sdk-ruby/commit/a9003825c9b4f377dba511f4d00aa0e834728f08))


### Bug Fixes

* **internal:** update release-please to use ruby strategy for README.md ([#73](https://github.com/anthropics/anthropic-sdk-ruby/issues/73)) ([f0466d1](https://github.com/anthropics/anthropic-sdk-ruby/commit/f0466d1b15f68d822df6bc73c6d9c80c7a330d4f))
* raise connection error for errors that result from HTTP transports ([#70](https://github.com/anthropics/anthropic-sdk-ruby/issues/70)) ([0885db3](https://github.com/anthropics/anthropic-sdk-ruby/commit/0885db3f4c0ec1b43e91231a8ed922ab9c4a428e))


### Chores

* add README docs for using solargraph when installing gem from git ([#67](https://github.com/anthropics/anthropic-sdk-ruby/issues/67)) ([bf8e537](https://github.com/anthropics/anthropic-sdk-ruby/commit/bf8e5371a291e1fe0b335e734a7208ff8b3d739c))
* ensure readme.md is bumped when release please updates versions ([#72](https://github.com/anthropics/anthropic-sdk-ruby/issues/72)) ([99323d0](https://github.com/anthropics/anthropic-sdk-ruby/commit/99323d08371ecc5b494fd0604619d5815410202f))
* **internal:** expand CI branch coverage ([#74](https://github.com/anthropics/anthropic-sdk-ruby/issues/74)) ([a058c31](https://github.com/anthropics/anthropic-sdk-ruby/commit/a058c31e98cd5920705380539f69222321d2a1b7))
* **internal:** version bump ([0d1f04a](https://github.com/anthropics/anthropic-sdk-ruby/commit/0d1f04a5ac2f8a323e3590d43bd7a6e550115fdc))
* loosen const and integer coercion rules ([#71](https://github.com/anthropics/anthropic-sdk-ruby/issues/71)) ([6fcb07c](https://github.com/anthropics/anthropic-sdk-ruby/commit/6fcb07c70a269a362afc6ead4b670ce2f8b03470))
* update readme sorbet example ([5fee7e7](https://github.com/anthropics/anthropic-sdk-ruby/commit/5fee7e7484ca3c7587137804cbafe1afabe49364))

## 0.1.0-alpha.1 (2025-04-08)

Full Changelog: [v0.0.1-alpha.0...v0.1.0-alpha.1](https://github.com/anthropics/anthropic-sdk-ruby/compare/v0.0.1-alpha.0...v0.1.0-alpha.1)

### ⚠ BREAKING CHANGES

* bump min supported ruby version to 3.1 (oldest non-EOL) ([#46](https://github.com/anthropics/anthropic-sdk-ruby/issues/46))
* remove top level type aliases to relocated classes ([#44](https://github.com/anthropics/anthropic-sdk-ruby/issues/44))
* use tagged enums in sorbet type definitions ([#5](https://github.com/anthropics/anthropic-sdk-ruby/issues/5))
* support `for item in stream` style iteration on `Stream`s ([#1](https://github.com/anthropics/anthropic-sdk-ruby/issues/1))
* encode objects in multipart encoding as JSON
* base page should be module instead of class
* breaking change - improved request options signatures
* breaking change: support const enums
* (breaking change) flatter error hierarchy

### Features

* ! (breaking change) introduce nesting for models under deeply nested resources ([f5e32b6](https://github.com/anthropics/anthropic-sdk-ruby/commit/f5e32b6890b4b97d6ef555565d63fd8a233fc0b1))
* ! (breaking change) pull path params not in the last position into the params argument ([0f8f0d3](https://github.com/anthropics/anthropic-sdk-ruby/commit/0f8f0d3b22c9f3efed74e3a7fe2fb1adb877ba87))
* (breaking change) flatter error hierarchy ([a825225](https://github.com/anthropics/anthropic-sdk-ruby/commit/a825225707d55f91176b903c363b5e76a7f1e906))
* add basic usage examples ([ecd4278](https://github.com/anthropics/anthropic-sdk-ruby/commit/ecd427858454f61628667499ecc8994e60f085ba))
* add deprecation notice to enum members and resources ([3782933](https://github.com/anthropics/anthropic-sdk-ruby/commit/3782933604daed0ac4b2072dedab212b722e23f0))
* add jsonl support ([aaf602d](https://github.com/anthropics/anthropic-sdk-ruby/commit/aaf602d1795a06a01bd1c849b6f8ca541676f5db))
* add reference links in yard ([#33](https://github.com/anthropics/anthropic-sdk-ruby/issues/33)) ([8bda0cb](https://github.com/anthropics/anthropic-sdk-ruby/commit/8bda0cb09407884f6b9a828845348d46cf1119d9))
* add SKIP_BREW env var to ./scripts/bootstrap ([59df81e](https://github.com/anthropics/anthropic-sdk-ruby/commit/59df81e0517dd658d4b885c87a88dec8f88603d4))
* allow all valid `JSON` types to be encoded ([#55](https://github.com/anthropics/anthropic-sdk-ruby/issues/55)) ([3dfe51b](https://github.com/anthropics/anthropic-sdk-ruby/commit/3dfe51b4832b47a36b22007c4480d75114f8dae1))
* **api:** add citations ([7fc3326](https://github.com/anthropics/anthropic-sdk-ruby/commit/7fc33265423046e2eb66c2623f84d788cf01068e))
* **api:** add claude-3.7 + support for thinking ([1c92c58](https://github.com/anthropics/anthropic-sdk-ruby/commit/1c92c583868b09a6c13ac02bfad5d7a92d0de1f7))
* **api:** add message batch delete endpoint ([ffc84eb](https://github.com/anthropics/anthropic-sdk-ruby/commit/ffc84eb557b65b7408c9f34aa66d5bc0fc55768e))
* **api:** add message batches api ([f8bef83](https://github.com/anthropics/anthropic-sdk-ruby/commit/f8bef83e309e6f54d29e4f00268dc344241f8032))
* **api:** add message token counting & PDFs support ([979744f](https://github.com/anthropics/anthropic-sdk-ruby/commit/979744f4b520a341ea1508e44e5b33f9362d1029))
* **api:** add new haiku model ([69c38f7](https://github.com/anthropics/anthropic-sdk-ruby/commit/69c38f74e4af30eff3d9bfd77a657b1e8a02f88e))
* **api:** add new model and `computer-use-2024-10-22` beta ([742f2a7](https://github.com/anthropics/anthropic-sdk-ruby/commit/742f2a78ee1b82457af4c7582033d87d9f38283f))
* **api:** add support for disabling tool calls ([06330df](https://github.com/anthropics/anthropic-sdk-ruby/commit/06330dffe22ab456bd075e3513b095ca5fe60605))
* **api:** add URL source blocks for images and PDFs ([8f6cc00](https://github.com/anthropics/anthropic-sdk-ruby/commit/8f6cc00894c42886de43c451595338b503f1ff44))
* **api:** extract ContentBlockDelta events into their own schemas ([#34](https://github.com/anthropics/anthropic-sdk-ruby/issues/34)) ([e5bbcc4](https://github.com/anthropics/anthropic-sdk-ruby/commit/e5bbcc45983bbdff009b9db9ff5b0d5ab6af2483))
* **api:** general availability updates ([a7111aa](https://github.com/anthropics/anthropic-sdk-ruby/commit/a7111aaa0f9e21b40278d7d2557ac2a81ca63ef6))
* **api:** manual updates ([236007c](https://github.com/anthropics/anthropic-sdk-ruby/commit/236007c1813c01b8b23c4d5265bded60598dc4ca))
* **api:** manual updates ([#40](https://github.com/anthropics/anthropic-sdk-ruby/issues/40)) ([54a5afd](https://github.com/anthropics/anthropic-sdk-ruby/commit/54a5afd80dd8edcdfb9e536d35a9d5a892c07e8b))
* **api:** manual updates ([#45](https://github.com/anthropics/anthropic-sdk-ruby/issues/45)) ([bfd23d7](https://github.com/anthropics/anthropic-sdk-ruby/commit/bfd23d79ed884676839762e836342da869f5e1e5))
* breaking change - improved request options signatures ([90fd7b0](https://github.com/anthropics/anthropic-sdk-ruby/commit/90fd7b001899800ffa717715ddcfaa3e3dcc7fc4))
* breaking change: support const enums ([b68ff43](https://github.com/anthropics/anthropic-sdk-ruby/commit/b68ff43484498d3715daa46da014a24f3a506442))
* bump min supported ruby version to 3.1 (oldest non-EOL) ([#46](https://github.com/anthropics/anthropic-sdk-ruby/issues/46)) ([360c3e3](https://github.com/anthropics/anthropic-sdk-ruby/commit/360c3e3a5fd455fd7c2217173b685503331e8aeb))
* bundle typing manifests with gem release ([cc7ce7e](https://github.com/anthropics/anthropic-sdk-ruby/commit/cc7ce7ef3f3fca39a8766f8c8b141f73c8118aaa))
* **client:** configurable timeouts ([3907f0b](https://github.com/anthropics/anthropic-sdk-ruby/commit/3907f0b22be2fc9eac8f61482046f0d8800cf624))
* **client:** improved .inspect output ([20b9526](https://github.com/anthropics/anthropic-sdk-ruby/commit/20b9526bb8503d9692753950650fefb455df8a92))
* **client:** send `X-Stainless-Read-Timeout` header ([8077201](https://github.com/anthropics/anthropic-sdk-ruby/commit/80772011e1b01b871bf1f35e21d83155ee917f76))
* **client:** support results endpoint ([84aee14](https://github.com/anthropics/anthropic-sdk-ruby/commit/84aee14d4da446e19a937757b3090b6508284a00))
* **client:** support rightward assignment ([037d377](https://github.com/anthropics/anthropic-sdk-ruby/commit/037d377178c216c7284b7a808a5bf6a683040450))
* consistently accept `AnyHash` types in parameter positions in sorbet ([#10](https://github.com/anthropics/anthropic-sdk-ruby/issues/10)) ([5b87e3a](https://github.com/anthropics/anthropic-sdk-ruby/commit/5b87e3a45085ce9564852411ff6bd9a00f2f680f))
* elide anonymous enums into unions ([cda05e9](https://github.com/anthropics/anthropic-sdk-ruby/commit/cda05e9aa0dd0484a45b4694735db558618843b0))
* enable type annotations ([8efbf84](https://github.com/anthropics/anthropic-sdk-ruby/commit/8efbf84e789cd434a3d6e32b4d4e629983b3c28b))
* escape path params ([7d95a65](https://github.com/anthropics/anthropic-sdk-ruby/commit/7d95a6551ae2af350b2aad5308e58db95e530751))
* escape path params ([20323f4](https://github.com/anthropics/anthropic-sdk-ruby/commit/20323f4dcb37aa8686eccd8d4ab2350172c8c8bd))
* examples for working with discriminated unions ([815f6f1](https://github.com/anthropics/anthropic-sdk-ruby/commit/815f6f11698e10950dc2115b1de288dc3d4a8f65))
* exercise connection pool in tests ([4758f2f](https://github.com/anthropics/anthropic-sdk-ruby/commit/4758f2f69bfbf8491b76f491bde6fa4f24a671e7))
* explicitly mark more internal methods with `private` ([c3e2c09](https://github.com/anthropics/anthropic-sdk-ruby/commit/c3e2c09d295b6ce365ec3a0311f86e5e2ba57f47))
* fix `to_enum` and `enum_for` built-ins for pagination classes ([1e8f0d7](https://github.com/anthropics/anthropic-sdk-ruby/commit/1e8f0d72e00907060b9df8f5f490754ff2f42218))
* generate enum examples ([6707fde](https://github.com/anthropics/anthropic-sdk-ruby/commit/6707fdea9040664f1010794aaf86b2b21bf6f414))
* generate params classes ([b63d653](https://github.com/anthropics/anthropic-sdk-ruby/commit/b63d6536fd5dd18d6383773e1b3453bfe15e0a23))
* generate some omitted class names in doc comments ([cf3d9cd](https://github.com/anthropics/anthropic-sdk-ruby/commit/cf3d9cd398495f253ce1421861ed5f37c97e36f0))
* implement `to_json` for base model ([#39](https://github.com/anthropics/anthropic-sdk-ruby/issues/39)) ([2b8090e](https://github.com/anthropics/anthropic-sdk-ruby/commit/2b8090eae10fd136f98f3221d5908656b9b40693))
* implement subsumption operator for base classes ([83e9ed4](https://github.com/anthropics/anthropic-sdk-ruby/commit/83e9ed4201cdc3f0ead4f522bbcc6e54705d9557))
* implement unions ([ede8afc](https://github.com/anthropics/anthropic-sdk-ruby/commit/ede8afc02bd630c4b87047400e1e7577ce14503c))
* implement unions ([7079e3b](https://github.com/anthropics/anthropic-sdk-ruby/commit/7079e3b7ee61fc09f8a6880b3932dd4c6901d5d4))
* improve `ArrayOf` DSL to use `:[]` instead of `.new` ([8f1a061](https://github.com/anthropics/anthropic-sdk-ruby/commit/8f1a06136c031fb71d5d17d7943f2cb060513f42))
* improve interface readability, especially in `*.rbi` ([5db7d5c](https://github.com/anthropics/anthropic-sdk-ruby/commit/5db7d5c21a6e7225f4c0fecdd7d624c360947823))
* improve sorbet attribute signatures ([3d137b9](https://github.com/anthropics/anthropic-sdk-ruby/commit/3d137b9241e491fdb2d260080db7364774652c72))
* inline sorbet type aliases ([7219236](https://github.com/anthropics/anthropic-sdk-ruby/commit/7219236159271fa797f92c91b3b563ae5eb204b5))
* **internal:** converter interface should recurse without schema ([#24](https://github.com/anthropics/anthropic-sdk-ruby/issues/24)) ([0d86d2b](https://github.com/anthropics/anthropic-sdk-ruby/commit/0d86d2bc685322f794db6f1d07e66a0e970d9049))
* **internal:** modified tests for thread and fiber safety ([e4d8d96](https://github.com/anthropics/anthropic-sdk-ruby/commit/e4d8d96649c891c8d232cb26fad9398aac94d725))
* isolate platform headers ([52ab4f8](https://github.com/anthropics/anthropic-sdk-ruby/commit/52ab4f8415472508b6e34e9faab54387e150b90c))
* link response models to their methods in yard doc ([#36](https://github.com/anthropics/anthropic-sdk-ruby/issues/36)) ([25b5673](https://github.com/anthropics/anthropic-sdk-ruby/commit/25b5673b479eb282d8972f19a3745d043518403f))
* make `build_request` overridable ([29e3135](https://github.com/anthropics/anthropic-sdk-ruby/commit/29e313539d6227c9e3a11236fc2fbebeddf1bc3d))
* make enum classes thread safe ([203ea8e](https://github.com/anthropics/anthropic-sdk-ruby/commit/203ea8ef2e94df101ed3f451c16e6dc969fe5e77))
* modernize sdk internals ([63e1284](https://github.com/anthropics/anthropic-sdk-ruby/commit/63e1284ece645a08e2d692440204d1ea118f2244))
* more consistent ArrayOf and HashOf DSL with re: lambda usage ([bd9c771](https://github.com/anthropics/anthropic-sdk-ruby/commit/bd9c771e4885f5fed1d5a143e4321c3738ef8f32))
* more consistent ArrayOf and HashOf DSL with re: lambda usage ([ae072d7](https://github.com/anthropics/anthropic-sdk-ruby/commit/ae072d7ea84e706b7526b3f22fac55eb6e31ac2d))
* prevent tapioca from introspecting the gem internals ([#9](https://github.com/anthropics/anthropic-sdk-ruby/issues/9)) ([3d7f0a8](https://github.com/anthropics/anthropic-sdk-ruby/commit/3d7f0a8ca9700bc20c894567c0652dfebc95e590))
* rb: render kwargs in constructors ([67e0961](https://github.com/anthropics/anthropic-sdk-ruby/commit/67e0961aa1cf5c9b84aa376f8a0c8d2609e3eda6))
* remove top level type aliases to relocated classes ([#44](https://github.com/anthropics/anthropic-sdk-ruby/issues/44)) ([41cbf0b](https://github.com/anthropics/anthropic-sdk-ruby/commit/41cbf0b7e05bf87a574bf79c617309757f5d818a))
* rename fields when they collide with ruby internals ([67f68dc](https://github.com/anthropics/anthropic-sdk-ruby/commit/67f68dc59e2e0f58061ce2afb4a320c0d65a7eba))
* render yard docs with hash and nil? info ([5626317](https://github.com/anthropics/anthropic-sdk-ruby/commit/56263177532d4bccc8229d051ea05ed1fe682e6c))
* ruby add nilability annotations ([8a7bf3e](https://github.com/anthropics/anthropic-sdk-ruby/commit/8a7bf3e18085a4b3345ea2aac3bb210f9e8656c6))
* run rubocop in multiple processes when formatting ([0291b49](https://github.com/anthropics/anthropic-sdk-ruby/commit/0291b49a288d313b85c2c21c157f42c1b42701a5))
* seal private constructors ([bf74451](https://github.com/anthropics/anthropic-sdk-ruby/commit/bf74451cc475989c3338b2d8198650c78162e8d6))
* support `for item in stream` style iteration on `Stream`s ([#1](https://github.com/anthropics/anthropic-sdk-ruby/issues/1)) ([404600c](https://github.com/anthropics/anthropic-sdk-ruby/commit/404600caa127d8db3d3b2c27a1283122f48f69c4))
* support client level methods ([b190c00](https://github.com/anthropics/anthropic-sdk-ruby/commit/b190c009c19d5279276ae04db80ead48c26bd624))
* support jsonl uploads ([b1c36cf](https://github.com/anthropics/anthropic-sdk-ruby/commit/b1c36cf854cf87cc2abd6121541175ee37aba12a))
* support overlapping HTTP requests in same Fiber ([8884a36](https://github.com/anthropics/anthropic-sdk-ruby/commit/8884a36938be24f84e2dc839f61668f7da0b9dfb))
* support query, header, and body params that have identical names ([#54](https://github.com/anthropics/anthropic-sdk-ruby/issues/54)) ([0a47d58](https://github.com/anthropics/anthropic-sdk-ruby/commit/0a47d58d360b6b42f9fb397cee22bae32d52bb70))
* support solargraph generics ([#49](https://github.com/anthropics/anthropic-sdk-ruby/issues/49)) ([e2f8051](https://github.com/anthropics/anthropic-sdk-ruby/commit/e2f8051311e2ed5dde2f99a88bfcdf8ee5be7e01))
* support streaming uploads ([54cd6e7](https://github.com/anthropics/anthropic-sdk-ruby/commit/54cd6e739e6154fd3f8a366dbf755ecc800724bc))
* switch to yard `@!parse` directive for init signatures instead of dummy methods ([30e430a](https://github.com/anthropics/anthropic-sdk-ruby/commit/30e430a1891c263932a353cac9f4385a1f21e773))
* unify param & return types in yard ([5c33a30](https://github.com/anthropics/anthropic-sdk-ruby/commit/5c33a3048ffb561f7f90a5be66373bd58586cd9e))
* use pattern matching in parsing pagination responses ([132f23a](https://github.com/anthropics/anthropic-sdk-ruby/commit/132f23a2c56155d618c20eca7accb4abf85e39a2))
* use tagged enums in sorbet type definitions ([#5](https://github.com/anthropics/anthropic-sdk-ruby/issues/5)) ([ebdf7bc](https://github.com/anthropics/anthropic-sdk-ruby/commit/ebdf7bc2e14c9e29287ae85de541fde54f6b22c8))


### Bug Fixes

* base client type annotations ([1514045](https://github.com/anthropics/anthropic-sdk-ruby/commit/15140450700479fb0aa738768cdcb4fbb41fc525))
* base page should be module instead of class ([b95df92](https://github.com/anthropics/anthropic-sdk-ruby/commit/b95df92d0fb45ae6f85c5d509c5bbc7da9eaffaf))
* **beta:** merge betas param with the default value ([c16fa7c](https://github.com/anthropics/anthropic-sdk-ruby/commit/c16fa7c64da11469705caa1bc831f385e3d96486))
* **beta:** merge betas param with the default value ([217f24b](https://github.com/anthropics/anthropic-sdk-ruby/commit/217f24bd034281d52a45b7fa8391a4207f2eec96))
* better support header parameters ([f6fa0d5](https://github.com/anthropics/anthropic-sdk-ruby/commit/f6fa0d5d1056e37c9a8988619a500f3e4fb29838))
* **client:** deduplicate stop reason type ([#18](https://github.com/anthropics/anthropic-sdk-ruby/issues/18)) ([2688c3b](https://github.com/anthropics/anthropic-sdk-ruby/commit/2688c3bbfec6365057ac01cb01efee377b0dc53f))
* **client:** point accessors to the correct keys ([7f4152d](https://github.com/anthropics/anthropic-sdk-ruby/commit/7f4152d13445a044bd4bb1c2301adc6be16cd61f))
* **client:** various items, including keying connection pool by origin, not host ([ec36fe1](https://github.com/anthropics/anthropic-sdk-ruby/commit/ec36fe126bf160d285c0c4f0ccda134ff7e87fc1))
* converter now rejects unexpected arguments correctly ([7a4e479](https://github.com/anthropics/anthropic-sdk-ruby/commit/7a4e479d298bcc2243d159a8c23ffc2607944fbc))
* converter should transform stringio into string where applicable ([#57](https://github.com/anthropics/anthropic-sdk-ruby/issues/57)) ([f295fc0](https://github.com/anthropics/anthropic-sdk-ruby/commit/f295fc03d5718209ff5e77d84906ae71b3676a3a))
* correctly annotate nil values in yard ([b2a17dc](https://github.com/anthropics/anthropic-sdk-ruby/commit/b2a17dc2e586ca85525bb05418664a5e4fc40bd2))
* correctly geneate array and map schemas with models ([1943720](https://github.com/anthropics/anthropic-sdk-ruby/commit/194372003c37f9a22975f4a0c780afbecdee4438))
* correctly mark optional arrays and hashes as nullable ([c189028](https://github.com/anthropics/anthropic-sdk-ruby/commit/c1890281149d1afae26917e4be142c87946012c8))
* correctly mark some error values as optional ([e49c40b](https://github.com/anthropics/anthropic-sdk-ruby/commit/e49c40ba9a4db9226d179bc9ce419a017e27fe3f))
* encode objects in multipart encoding as JSON ([5474b7c](https://github.com/anthropics/anthropic-sdk-ruby/commit/5474b7cd63526f19f83fa240bc800056d42a4360))
* enums should only coerce matching symbols into strings ([4d61b49](https://github.com/anthropics/anthropic-sdk-ruby/commit/4d61b49f895392832daa8a015df58568f1686a13))
* error classes did not call `.to_s` on error uri ([3ac9239](https://github.com/anthropics/anthropic-sdk-ruby/commit/3ac92395e1de0f40d6ca30957a176f153b6d2daf))
* exclude duplicate streaming determinant fields ([db212db](https://github.com/anthropics/anthropic-sdk-ruby/commit/db212dbcd10b70f899f890c58c15aa8f677c5676))
* fix union variant duplication ([2e32e31](https://github.com/anthropics/anthropic-sdk-ruby/commit/2e32e3181cfd76314185de62589499c8dbdcf8fa))
* pages should be able to accept non-converter models ([#13](https://github.com/anthropics/anthropic-sdk-ruby/issues/13)) ([7f3f1b9](https://github.com/anthropics/anthropic-sdk-ruby/commit/7f3f1b91293e679e0ce527747d9f146dbae33a58))
* path interpolation template strings ([#32](https://github.com/anthropics/anthropic-sdk-ruby/issues/32)) ([04f7783](https://github.com/anthropics/anthropic-sdk-ruby/commit/04f7783acce776833722c05abb10635bf827cbf7))
* pre-release version string should match ruby, not semver conventions ([#48](https://github.com/anthropics/anthropic-sdk-ruby/issues/48)) ([872c0b0](https://github.com/anthropics/anthropic-sdk-ruby/commit/872c0b0421903354f14eb89bbc59fe923430528d))
* rectify a mistake where wrong lines were chosen during rebase ([b94b0d0](https://github.com/anthropics/anthropic-sdk-ruby/commit/b94b0d07ee177cc95afb98093f9d3fcc12f3c0b3))
* remove unnecessary indirection for some ArrayOf and HashOf types ([51ee769](https://github.com/anthropics/anthropic-sdk-ruby/commit/51ee76983abf2bac28fb139f5c1638909f23e92f))
* resolve tapioca derived sorbet errors ([#4](https://github.com/anthropics/anthropic-sdk-ruby/issues/4)) ([3b99fb9](https://github.com/anthropics/anthropic-sdk-ruby/commit/3b99fb9921a61c98b215d407be2033be9e783c4c))
* restore accidently removed optional dependencies ([f749376](https://github.com/anthropics/anthropic-sdk-ruby/commit/f74937681f7c724974c74bc4aca503495dbef326))
* run bundle install before publishing ruby gems ([ff4c067](https://github.com/anthropics/anthropic-sdk-ruby/commit/ff4c0674a5ef8d6658b015e52b4a02edf3e1004b))
* sorbet request method signatures should support default values ([004072a](https://github.com/anthropics/anthropic-sdk-ruby/commit/004072a79bc916503885e919f0c196393c6989c6))
* ssl timeout not required when TCP socket open timeout specified ([a032e01](https://github.com/anthropics/anthropic-sdk-ruby/commit/a032e015c2cca5283aa33a98bda34950c8ccc7d2))
* switch to github compatible markdown engine ([#29](https://github.com/anthropics/anthropic-sdk-ruby/issues/29)) ([009c43d](https://github.com/anthropics/anthropic-sdk-ruby/commit/009c43d8c47b18c56193d24354b041bbcf736dbe))
* temporarily run CI without bundler cache ([82f8fe0](https://github.com/anthropics/anthropic-sdk-ruby/commit/82f8fe0a4b73bfb54b23db179da9353f8daa137f))
* **type signature:** remove extraneous `params` from resource methods ([46f31db](https://github.com/anthropics/anthropic-sdk-ruby/commit/46f31db2d528096f6a4e2c95890c6dc1e364ea7c))
* **types:** add missing token-counting-2024-11-01 ([6fae646](https://github.com/anthropics/anthropic-sdk-ruby/commit/6fae6460a3e83a0683e3182cc90085eb39681a26))
* **types:** correct claude-3-5-haiku-20241022 name ([67ef9e8](https://github.com/anthropics/anthropic-sdk-ruby/commit/67ef9e81c38683180cfc570a41921b4e9390a911))
* **types:** remove anthropic-instant-1.2 model ([b09f15f](https://github.com/anthropics/anthropic-sdk-ruby/commit/b09f15f86879bc710a8fc37d484dbfd089cb6eb5))
* update outdated examples ([b3668b7](https://github.com/anthropics/anthropic-sdk-ruby/commit/b3668b7fcb3c80c17d21127154d05dc0569e8517))
* yard example tag formatting ([#7](https://github.com/anthropics/anthropic-sdk-ruby/issues/7)) ([13c0a7d](https://github.com/anthropics/anthropic-sdk-ruby/commit/13c0a7daa1b3fa8a6fe6780a55e991750e21c2ec))


### Chores

* `BaseModel` fields that are `BaseModel` typed should also accept `Hash` ([#6](https://github.com/anthropics/anthropic-sdk-ruby/issues/6)) ([29bb24a](https://github.com/anthropics/anthropic-sdk-ruby/commit/29bb24a5a24e61dd3d2089e9389744922ef99506))
* accept `BaseClient` where `Client` were accepted ([ee8dc80](https://github.com/anthropics/anthropic-sdk-ruby/commit/ee8dc80005908f785510b33762436e9677300880))
* add `sorbet` section to README ([e86eeb4](https://github.com/anthropics/anthropic-sdk-ruby/commit/e86eeb48f752f09a66e2fb4dc6fe594790dc51cd))
* add hash of OpenAPI spec/config inputs to .stats.yml ([#17](https://github.com/anthropics/anthropic-sdk-ruby/issues/17)) ([a217e5a](https://github.com/anthropics/anthropic-sdk-ruby/commit/a217e5aaa1d33ed3f01f50bdf3d9ca37fbd34d47))
* add more examples to README.md ([a66b0be](https://github.com/anthropics/anthropic-sdk-ruby/commit/a66b0be1761825b1a3dcd3f870f20d4c2492e7d2))
* add more private yard doc annotations ([1fbbf09](https://github.com/anthropics/anthropic-sdk-ruby/commit/1fbbf098c85efa67c777ffd7e7ca70eaf1e3f5e3))
* add most doc strings to rbi type definitions ([4b4eb5d](https://github.com/anthropics/anthropic-sdk-ruby/commit/4b4eb5d79ccdb9ab6dec3f54949b797967537818))
* add stub methods for higher level stream helpers ([4d86623](https://github.com/anthropics/anthropic-sdk-ruby/commit/4d8662300256d9c995be88d9f41a2fdae364f0f3))
* add type annotations for enum and union member listing methods ([#8](https://github.com/anthropics/anthropic-sdk-ruby/issues/8)) ([e26a2b4](https://github.com/anthropics/anthropic-sdk-ruby/commit/e26a2b499a5bb7de4fa4ff5e2627179bd8e0bccd))
* add type annotations for requester ([4c4001d](https://github.com/anthropics/anthropic-sdk-ruby/commit/4c4001d5b0ba44469719f2823cc48d44a51a5df5))
* adjust method param class position in yard doc for convenience ([d4799c9](https://github.com/anthropics/anthropic-sdk-ruby/commit/d4799c923a6949b40fdb5f06ad59ad827b7682df))
* adjust whitespace in comments ([545f35f](https://github.com/anthropics/anthropic-sdk-ruby/commit/545f35f993bec8f63a7557fd13c78d2aee88c5ac))
* always fold up method bodies in sorbet type definitions ([#61](https://github.com/anthropics/anthropic-sdk-ruby/issues/61)) ([b77b1a7](https://github.com/anthropics/anthropic-sdk-ruby/commit/b77b1a73101e793309f496e4b53d28d017146da9))
* **api:** add title ([b82e233](https://github.com/anthropics/anthropic-sdk-ruby/commit/b82e2336c27fa8ee9984a83e51ed6a3da765ac31))
* **api:** update openapi spec url ([2fab4c1](https://github.com/anthropics/anthropic-sdk-ruby/commit/2fab4c1d7768b2057f306fde3399638b23ab6544))
* **api:** update spec version ([90e3e26](https://github.com/anthropics/anthropic-sdk-ruby/commit/90e3e26ee15715739f04feb98f92d1cf748a4801))
* **api:** update spec version ([a7f4b77](https://github.com/anthropics/anthropic-sdk-ruby/commit/a7f4b7763091c10ce3fdf243309aa75069e5aedb))
* attempt to clean up underlying transport when streams are GC'd ([#66](https://github.com/anthropics/anthropic-sdk-ruby/issues/66)) ([f562b62](https://github.com/anthropics/anthropic-sdk-ruby/commit/f562b6240c6d775cc054e6668830fd0d0aa1fa3a))
* be consistent and use lower case headers everywhere ([359050a](https://github.com/anthropics/anthropic-sdk-ruby/commit/359050a4a639c15c9d549924a500b60e7f5826b1))
* bump lockfile ([44d371d](https://github.com/anthropics/anthropic-sdk-ruby/commit/44d371dd9ad95d8620c0f0e1d09bafff123e12c6))
* bump lockfile ([c7b4556](https://github.com/anthropics/anthropic-sdk-ruby/commit/c7b455617080dcbf1c000efc1fba3df43ff614bb))
* bump sorbet ([796e654](https://github.com/anthropics/anthropic-sdk-ruby/commit/796e65499903e1ba89e11b813157e7d7f977cf2e))
* clamp timeout to range of positive floats ([042cdbb](https://github.com/anthropics/anthropic-sdk-ruby/commit/042cdbb6f577e4c59dbefc59e8218b5ce113bdc9))
* clean up client tests ([ca6fefb](https://github.com/anthropics/anthropic-sdk-ruby/commit/ca6fefbd2afb24362d15a8948ab69d7b3bb6e9ff))
* **client:** ensure streaming methods are suffixed with `_streaming` ([#43](https://github.com/anthropics/anthropic-sdk-ruby/issues/43)) ([875abed](https://github.com/anthropics/anthropic-sdk-ruby/commit/875abed8a8e7d356a6218fa1086df55e94e8f2e8))
* **client:** extract out client agnostic code into utils ([9c6e7e6](https://github.com/anthropics/anthropic-sdk-ruby/commit/9c6e7e615fbba8676ed2d89ac4c5ddb1fae36efd))
* **client:** refactor to use RFC3986_PARSER for URL handling ([702735e](https://github.com/anthropics/anthropic-sdk-ruby/commit/702735e13fffe8ce79fa2fcd5214c6212f2c4ffb))
* consolidate imports ([1acdd2b](https://github.com/anthropics/anthropic-sdk-ruby/commit/1acdd2b1d6e3b51c169f17ce102d3f1718c93822))
* demonstrate how to make undocumented requests in README ([#47](https://github.com/anthropics/anthropic-sdk-ruby/issues/47)) ([48bb3df](https://github.com/anthropics/anthropic-sdk-ruby/commit/48bb3df6d82f6bee69c298af39d5eb710907cdde))
* disable dangerous rubocop auto correct rule ([#15](https://github.com/anthropics/anthropic-sdk-ruby/issues/15)) ([4e2c7b1](https://github.com/anthropics/anthropic-sdk-ruby/commit/4e2c7b11b48827c2dddbeed3e2119ab1391e7d22))
* do not git ignore `bin/` ([c4c8a4b](https://github.com/anthropics/anthropic-sdk-ruby/commit/c4c8a4bcd6e00c98066ab07c6300f84cf5d979df))
* do not label modules as abstract ([a662c5a](https://github.com/anthropics/anthropic-sdk-ruby/commit/a662c5a2bd2a0bc546d76d9710fdbef4c324474c))
* do not use literals for version in type definitions ([#50](https://github.com/anthropics/anthropic-sdk-ruby/issues/50)) ([5248f18](https://github.com/anthropics/anthropic-sdk-ruby/commit/5248f1865a098790f8553618e008f04fa779d8d8))
* **docs:** updates ([215c716](https://github.com/anthropics/anthropic-sdk-ruby/commit/215c716c41714aad1649c3e8c074ae8cedda053a))
* document LSP support in read me ([#53](https://github.com/anthropics/anthropic-sdk-ruby/issues/53)) ([c1141ae](https://github.com/anthropics/anthropic-sdk-ruby/commit/c1141ae7ad75a26b56f0193302209452b18a5ff6))
* document union variants in yard doc ([6d46142](https://github.com/anthropics/anthropic-sdk-ruby/commit/6d4614204d5bfe5c2bbe6b5079c1afc35c50db9c))
* easier to read examples in README.md ([#64](https://github.com/anthropics/anthropic-sdk-ruby/issues/64)) ([d33a5d4](https://github.com/anthropics/anthropic-sdk-ruby/commit/d33a5d4f8aa6491778617b243f699d641db0098d))
* enable full pagination tests ([0461ff1](https://github.com/anthropics/anthropic-sdk-ruby/commit/0461ff1c622d4a749e697ce86867237bc3a8de02))
* ensure doc strings for rbi method arguments ([7e1c01e](https://github.com/anthropics/anthropic-sdk-ruby/commit/7e1c01ede9b18b0cfe18e6f42722b23c8246538a))
* error fields are now mutable in keeping with rest of SDK ([7e05b0a](https://github.com/anthropics/anthropic-sdk-ruby/commit/7e05b0aa0c09927260e59338f3fd47133518ef63))
* extract error classes into own module ([#41](https://github.com/anthropics/anthropic-sdk-ruby/issues/41)) ([bd071ab](https://github.com/anthropics/anthropic-sdk-ruby/commit/bd071ab57962aba3ecc3eb73459c7d04d218c687))
* fix a yard doc comment ([9ba259f](https://github.com/anthropics/anthropic-sdk-ruby/commit/9ba259f38d13765edc44f2a502022a96b5100aa2))
* fix misc rubocop errors ([#30](https://github.com/anthropics/anthropic-sdk-ruby/issues/30)) ([da01798](https://github.com/anthropics/anthropic-sdk-ruby/commit/da01798506fd1c8873d5331fc149c5c31125b755))
* formatting change for `*.rbi` files ([465bf0b](https://github.com/anthropics/anthropic-sdk-ruby/commit/465bf0b65bfd05d01b01f3bbaf45070ae80c12cc))
* formatting consistency update ([e1845c3](https://github.com/anthropics/anthropic-sdk-ruby/commit/e1845c338d966ab5cd9254b9ab1988875a3d96bb))
* fully qualify `Array` and `Hash` in rbs files to avoid collisions ([ed20454](https://github.com/anthropics/anthropic-sdk-ruby/commit/ed204542c7414452d58c6e88e0422351f80cbd2b))
* fully qualify class name for inheritance ([780ccfe](https://github.com/anthropics/anthropic-sdk-ruby/commit/780ccfecae00c632bb678726ce9fe5a3b97f3d01))
* fused enum should use faster internal iteration by default ([9b8f6b6](https://github.com/anthropics/anthropic-sdk-ruby/commit/9b8f6b6f924dd351d0b69bad380036cbb6d9084e))
* generate better supported rbi signatures ([b3d1d0f](https://github.com/anthropics/anthropic-sdk-ruby/commit/b3d1d0f2a492ce820bb24f2a923be2dc5969ddf2))
* generate params class initializers ([b6ade22](https://github.com/anthropics/anthropic-sdk-ruby/commit/b6ade22118bffcf1b51f098ffe6410daa02ff83f))
* generate yard docs on page classes ([633147d](https://github.com/anthropics/anthropic-sdk-ruby/commit/633147d2f482e15bc16f61ef77c9fd9249d23b31))
* improve doc comment readability ([7926d77](https://github.com/anthropics/anthropic-sdk-ruby/commit/7926d77e8205b8cb81f3115eb330634a0723f83f))
* improve doc comment readability ([c390289](https://github.com/anthropics/anthropic-sdk-ruby/commit/c390289347c64d51b9f8abcd0dace801b1d63bf2))
* improve documentation ([999b642](https://github.com/anthropics/anthropic-sdk-ruby/commit/999b642a7a086e652ee50783ee46fd10ec7bbd0a))
* improve rbi typedef for page classes ([c15f0f9](https://github.com/anthropics/anthropic-sdk-ruby/commit/c15f0f9c3bf1aa5af6d055ba8aa1acbeb0a2fb50))
* improve uri interpolation internals ([dc68ceb](https://github.com/anthropics/anthropic-sdk-ruby/commit/dc68cebaee5b7c4bbc02214559c96b563bfccfa2))
* improve yard doc folding and reduce repetition ([fc89d13](https://github.com/anthropics/anthropic-sdk-ruby/commit/fc89d13a94cd9940482a905c620fb87424fc34dd))
* improve yard docs readability ([#35](https://github.com/anthropics/anthropic-sdk-ruby/issues/35)) ([9f938ae](https://github.com/anthropics/anthropic-sdk-ruby/commit/9f938aee6c682f4d6f5d22a0541b2d0fda03870a))
* **internal:** add back release workflow ([f96d786](https://github.com/anthropics/anthropic-sdk-ruby/commit/f96d7866a0ca6b1978450f6d6800d8ab050e7ffc))
* **internal:** add utils methods for parsing SSE ([4384987](https://github.com/anthropics/anthropic-sdk-ruby/commit/4384987f369ce97881433630ba79759f616a223f))
* **internal:** bump dependencies ([b8d2f75](https://github.com/anthropics/anthropic-sdk-ruby/commit/b8d2f75ae9d4830633e58c4fa71045f743e8ca66))
* **internal:** bump dependencies ([992a146](https://github.com/anthropics/anthropic-sdk-ruby/commit/992a146f76e9f3b304aebddd7650348c03eb69ce))
* **internal:** bump dependencies ([fd5d65f](https://github.com/anthropics/anthropic-sdk-ruby/commit/fd5d65f8ba819b5d60af587b702df616d11befee))
* **internal:** formatting ([a44a2cf](https://github.com/anthropics/anthropic-sdk-ruby/commit/a44a2cfaae3d4ded594560d8f745b086e52fd0ae))
* **internal:** group related utils together ([cf14545](https://github.com/anthropics/anthropic-sdk-ruby/commit/cf145453ec75dc7ce7158173540e4a584f66277a))
* **internal:** improve sdk internal docs / types ([8e10e1e](https://github.com/anthropics/anthropic-sdk-ruby/commit/8e10e1e53cca77f8467e7fda059c61bba7c21a18))
* **internal:** minor refactoring of utils ([#23](https://github.com/anthropics/anthropic-sdk-ruby/issues/23)) ([ebb85fe](https://github.com/anthropics/anthropic-sdk-ruby/commit/ebb85fe8b8764c09be4c24325ebfafc8050dffc8))
* **internal:** misc small improvements ([#58](https://github.com/anthropics/anthropic-sdk-ruby/issues/58)) ([f888187](https://github.com/anthropics/anthropic-sdk-ruby/commit/f888187862639e9869e9333668c95446e1550663))
* **internal:** more concise handling of parameter naming conflicts ([#63](https://github.com/anthropics/anthropic-sdk-ruby/issues/63)) ([4a573cd](https://github.com/anthropics/anthropic-sdk-ruby/commit/4a573cd6c5926ac4e92ab8aa48a2ad3d09ba06bb))
* **internal:** prune unused `extern` references ([6ba7331](https://github.com/anthropics/anthropic-sdk-ruby/commit/6ba73310ec87d18cfdb8a64ebdb7cafe57beba10))
* **internal:** refactor request stack ([af9c6fa](https://github.com/anthropics/anthropic-sdk-ruby/commit/af9c6fa698e10e249f286dd9d166a7d28c407446))
* **internal:** remove CI condition ([#22](https://github.com/anthropics/anthropic-sdk-ruby/issues/22)) ([b89b4e3](https://github.com/anthropics/anthropic-sdk-ruby/commit/b89b4e3d6cd7b402affe0c0ed545be95675422fd))
* **internal:** remove extra empty newlines ([2b8f3f9](https://github.com/anthropics/anthropic-sdk-ruby/commit/2b8f3f94b3b3b30a5dbd7064a91b67c650bb2d5a))
* **internal:** reorder model constants ([aee0601](https://github.com/anthropics/anthropic-sdk-ruby/commit/aee0601a7410743d0424cf33da6804e7cf0b036d))
* **internal:** rubocop rules ([#60](https://github.com/anthropics/anthropic-sdk-ruby/issues/60)) ([032f3e7](https://github.com/anthropics/anthropic-sdk-ruby/commit/032f3e7442fca2d6ca4301220c02e28023e2341a))
* **internal:** run rubocop linter in parallel ([#59](https://github.com/anthropics/anthropic-sdk-ruby/issues/59)) ([70c29d1](https://github.com/anthropics/anthropic-sdk-ruby/commit/70c29d1f6c9eb08357a4d37dec89bb80165013ad))
* **internal:** update config ([#21](https://github.com/anthropics/anthropic-sdk-ruby/issues/21)) ([6407fd1](https://github.com/anthropics/anthropic-sdk-ruby/commit/6407fd1a961209c62fb676942d64ccfc1e87f06f))
* **internal:** update dependencies ([e7d6f17](https://github.com/anthropics/anthropic-sdk-ruby/commit/e7d6f17c083f0e73f59e24b7dc8d5a7254cab574))
* **internal:** update dependencies ([5372f72](https://github.com/anthropics/anthropic-sdk-ruby/commit/5372f721c6324b9fc6760d13c9bd17249beaac3d))
* **internal:** update lock file ([35393a0](https://github.com/anthropics/anthropic-sdk-ruby/commit/35393a0e9e31b1f027874cbad0931c5dee797f7d))
* **internal:** update lock file ([7f320b2](https://github.com/anthropics/anthropic-sdk-ruby/commit/7f320b23bea26d3d17ca20bcebb4456ef6b51dde))
* **internal:** update lock file ([b86e9ec](https://github.com/anthropics/anthropic-sdk-ruby/commit/b86e9ec19cdd6bb82dfcbe193ad5f48f1b585dae))
* **internal:** update spec ([b44172f](https://github.com/anthropics/anthropic-sdk-ruby/commit/b44172f02a80c9a5bcef1beb27e0daa303b25b44))
* **internal:** update spec ([31530cc](https://github.com/anthropics/anthropic-sdk-ruby/commit/31530cc7bc3be027f87f8c2867e37fdb8dfed5a7))
* **internal:** update spec URL ([96a52f8](https://github.com/anthropics/anthropic-sdk-ruby/commit/96a52f8230c608738e9cc4af2e1872440c4569a8))
* **internal:** update spec version ([b37e786](https://github.com/anthropics/anthropic-sdk-ruby/commit/b37e786e38172700a40b316b0e9e6d541d39377d))
* link to param model in method yard docs ([99f6930](https://github.com/anthropics/anthropic-sdk-ruby/commit/99f693069981d3131f8a266f39525adb571a057b))
* make client tests look prettier ([#65](https://github.com/anthropics/anthropic-sdk-ruby/issues/65)) ([7550298](https://github.com/anthropics/anthropic-sdk-ruby/commit/7550298d31b7b7d95835f598ab64f5cc28487890))
* make MFA optional depending on token ([0705343](https://github.com/anthropics/anthropic-sdk-ruby/commit/070534338ab367dc42ed682384ca12431456db08))
* mark non-inheritable SDK internal classes as final ([2f466f1](https://github.com/anthropics/anthropic-sdk-ruby/commit/2f466f1aa87dec750618e130151db0937c1c7433))
* migrate to pattern matching for testing ([e1eb80f](https://github.com/anthropics/anthropic-sdk-ruby/commit/e1eb80f90a0053d60da08d12c268147382aaa3d7))
* minor formatting changes ([8ee908a](https://github.com/anthropics/anthropic-sdk-ruby/commit/8ee908ac1bf58d19a96dfd817a93216b994d9494))
* minor improvements to param type yard doc ([d3ec6af](https://github.com/anthropics/anthropic-sdk-ruby/commit/d3ec6af0fb1d858193c256f34257fb08f09a405f))
* minor refactorings on base client ([4aa03f1](https://github.com/anthropics/anthropic-sdk-ruby/commit/4aa03f1c69e387f5adeb5d63b13c356c2bbeaf89))
* minor scripting improvements ([9fa1667](https://github.com/anthropics/anthropic-sdk-ruby/commit/9fa1667b6fef8f5d9bb454e9fa7c2071dde91cdc))
* misc code formatting changes ([f480392](https://github.com/anthropics/anthropic-sdk-ruby/commit/f4803921ccfb95db91613dc5ee05f34ab01e7b50))
* misc sdk polish ([#52](https://github.com/anthropics/anthropic-sdk-ruby/issues/52)) ([559e927](https://github.com/anthropics/anthropic-sdk-ruby/commit/559e927e9396343681d2c88630ebb533b3c0f70f))
* modify sorbet initializers to better support auto-completion ([06657ca](https://github.com/anthropics/anthropic-sdk-ruby/commit/06657ca0879eb5d9f53803a572a6820cff3bee6b))
* more accurate generic params for stream classes ([00638c2](https://github.com/anthropics/anthropic-sdk-ruby/commit/00638c22862256b1ca328e9a00a7ef67a4ad9762))
* more accurate type annotations for SDK internals ([#27](https://github.com/anthropics/anthropic-sdk-ruby/issues/27)) ([894f4d6](https://github.com/anthropics/anthropic-sdk-ruby/commit/894f4d6f90cd4d5a0e1f710d1af3c0c59bbc044e))
* more aggressive tapioca detection logic for skipping compiler introspection ([#19](https://github.com/anthropics/anthropic-sdk-ruby/issues/19)) ([eeb1f1b](https://github.com/anthropics/anthropic-sdk-ruby/commit/eeb1f1b912be1b8d06f160524685342300dfa9b0))
* more detailed yard docs for base client ([572b2c7](https://github.com/anthropics/anthropic-sdk-ruby/commit/572b2c7b8befe771cb63e6997e59add22b4612a8))
* more detailed yard docs for sdk utils ([75435e2](https://github.com/anthropics/anthropic-sdk-ruby/commit/75435e24a394f0b72b9324c9ac88d9f375860145))
* more explicit privacy annotations ([5dd26ad](https://github.com/anthropics/anthropic-sdk-ruby/commit/5dd26ad3129594ee6955106198793dcba56bca87))
* more readable output when tests fail ([#16](https://github.com/anthropics/anthropic-sdk-ruby/issues/16)) ([83aa368](https://github.com/anthropics/anthropic-sdk-ruby/commit/83aa36887352f46ea611acc3942ebb9655702b22))
* move basemodel examples into tests ([0cf72d1](https://github.com/anthropics/anthropic-sdk-ruby/commit/0cf72d161afd1cd6e6716f1342931adc0d3fa7e1))
* move examples into tests ([9658760](https://github.com/anthropics/anthropic-sdk-ruby/commit/9658760f3370f6920074906adf5845e6801a345c))
* move private classes into internal module ([#42](https://github.com/anthropics/anthropic-sdk-ruby/issues/42)) ([6627f51](https://github.com/anthropics/anthropic-sdk-ruby/commit/6627f51aab8f7289e51c99e43fdbb4b9b614f489))
* order client variables by "importance" ([#38](https://github.com/anthropics/anthropic-sdk-ruby/issues/38)) ([2fc8233](https://github.com/anthropics/anthropic-sdk-ruby/commit/2fc8233bd34737ad45bb7729efbaead33e2660fd))
* re-arrange request-options method definitions ([43da888](https://github.com/anthropics/anthropic-sdk-ruby/commit/43da888b43719fc9477876ea61936d1ac9c8cd62))
* re-order assignment lines to make unions easier to read ([#20](https://github.com/anthropics/anthropic-sdk-ruby/issues/20)) ([fa776d0](https://github.com/anthropics/anthropic-sdk-ruby/commit/fa776d0a85cd23a6a02593d2f71a8c9861609f0e))
* re-order init params in accordance with their optionality ([e6d54b5](https://github.com/anthropics/anthropic-sdk-ruby/commit/e6d54b5d6afba0035f422e5f5313fc90b3908bf5))
* re-order resource classes constructor position ([1dfecdf](https://github.com/anthropics/anthropic-sdk-ruby/commit/1dfecdfd96eb85b449b8abb5281293816754f8be))
* recursively accept `AnyHash` for `BaseModel`s in arrays and hashes ([#11](https://github.com/anthropics/anthropic-sdk-ruby/issues/11)) ([9794ce4](https://github.com/anthropics/anthropic-sdk-ruby/commit/9794ce4cef30beae0c7ae09a19fd3e5fcc0cdf4a))
* reduce test verbosity ([f55e130](https://github.com/anthropics/anthropic-sdk-ruby/commit/f55e1309589874988b5afd6f3bacfe5facdbd030))
* reduce verbosity in type declarations ([#14](https://github.com/anthropics/anthropic-sdk-ruby/issues/14)) ([f92b511](https://github.com/anthropics/anthropic-sdk-ruby/commit/f92b5119be9c95ff26f7b278dc4cacbfa223294f))
* refactor base client internals ([d44a188](https://github.com/anthropics/anthropic-sdk-ruby/commit/d44a188adf96d994c997db9ffa25b005d0e3f34c))
* refactor base client methods ([c220090](https://github.com/anthropics/anthropic-sdk-ruby/commit/c220090382da588ca376642945b067142a7c86e6))
* refactor base client methods ([b0fde06](https://github.com/anthropics/anthropic-sdk-ruby/commit/b0fde06c0c7f287e9c0b6a8dfd1dcbe5538071dd))
* refactor BasePage to have initializer ([0f72312](https://github.com/anthropics/anthropic-sdk-ruby/commit/0f723122b85858f3665b098f4a8ed0547366e4fa))
* refactor util method signatures ([aec6d2b](https://github.com/anthropics/anthropic-sdk-ruby/commit/aec6d2b18c9bff2e7bc72799a5787ee547c01683))
* **refactor:** improve requester internals ([5e026ed](https://github.com/anthropics/anthropic-sdk-ruby/commit/5e026ede2b6fd6430a2068b631dfd0251681d5c5))
* relax sorbet enum parameters to allow `String` in addition to `Symbol` ([#37](https://github.com/anthropics/anthropic-sdk-ruby/issues/37)) ([4084602](https://github.com/anthropics/anthropic-sdk-ruby/commit/4084602f8cd7436ea696fbdb3994a1068159063a))
* relocate internal modules ([#26](https://github.com/anthropics/anthropic-sdk-ruby/issues/26)) ([eeedd82](https://github.com/anthropics/anthropic-sdk-ruby/commit/eeedd82e860a067dc6ce0ddabac5ed20f337cf3d))
* remove stale thread local checks ([2cdb176](https://github.com/anthropics/anthropic-sdk-ruby/commit/2cdb176ba5d685cf92246d80c615dd182bd94d69))
* remove unnecessary & confusing module ([#25](https://github.com/anthropics/anthropic-sdk-ruby/issues/25)) ([1743ccc](https://github.com/anthropics/anthropic-sdk-ruby/commit/1743cccb7f80d75bd3034d32e6f9bb501096c81b))
* rename confusing `Type::BooleanModel` to `Type::Boolean` ([#56](https://github.com/anthropics/anthropic-sdk-ruby/issues/56)) ([2fe7368](https://github.com/anthropics/anthropic-sdk-ruby/commit/2fe7368a11d74f9e141510df8a2c1931a5e6915c))
* rename internal type aliases ([8b319e3](https://github.com/anthropics/anthropic-sdk-ruby/commit/8b319e3b4934812507f2c0a99ff22001e121d589))
* rename internal variable ([25c089f](https://github.com/anthropics/anthropic-sdk-ruby/commit/25c089fe52e898b0c6430c1688701d3c57604528))
* rename misleading variable ([e5e2b07](https://github.com/anthropics/anthropic-sdk-ruby/commit/e5e2b07c58209a985b8de233bc51915cf8596b20))
* reorganize import ordering ([47f8d21](https://github.com/anthropics/anthropic-sdk-ruby/commit/47f8d21eb21042199fb9edce52ba9d3c263699d9))
* reorganize request construction hash to mirror HTTP semantics ([255af2c](https://github.com/anthropics/anthropic-sdk-ruby/commit/255af2c3848579ea85f8bd72d0917c283853906c))
* sdk client internal refactoring ([e19893f](https://github.com/anthropics/anthropic-sdk-ruby/commit/e19893fe66ce157e998639933480a481e0078451))
* sdk internal updates ([5dbeb61](https://github.com/anthropics/anthropic-sdk-ruby/commit/5dbeb6159c03f4a2bbf1c339bb1b68d8cf1d1eb5))
* simplify internal utils ([#51](https://github.com/anthropics/anthropic-sdk-ruby/issues/51)) ([42e6f89](https://github.com/anthropics/anthropic-sdk-ruby/commit/42e6f891ff2a40877ebb8e6711f66eb02081285e))
* slightly more consistent type definition layout ([11e35e7](https://github.com/anthropics/anthropic-sdk-ruby/commit/11e35e752fe555f6e9332a906ddb8922d4ca41c0))
* slightly more robust utils ([77f7f35](https://github.com/anthropics/anthropic-sdk-ruby/commit/77f7f35786f2f0b61e088649cba29bf5140eab39))
* slightly more robust utils ([a456b92](https://github.com/anthropics/anthropic-sdk-ruby/commit/a456b92fda2a3e0abb1d0055decd007d4c78e074))
* sort imports via topological dependency & file path ([647f324](https://github.com/anthropics/anthropic-sdk-ruby/commit/647f3248ba989abfbebd6380741e51ef40225f15))
* styling improvements in doc strings ([2c01db4](https://github.com/anthropics/anthropic-sdk-ruby/commit/2c01db4a8c6f83b44d7564ab716dd9e727520514))
* support (deprecated) ruby 3.0 as well ([31885ce](https://github.com/anthropics/anthropic-sdk-ruby/commit/31885ceb0c8c079ffbe80231ac52c878b05c900b))
* support different EOLs in streaming ([20173b9](https://github.com/anthropics/anthropic-sdk-ruby/commit/20173b93ba996f9f2e81dc78c51836f0470d8607))
* switch over to relative requires for gem locals ([064113e](https://github.com/anthropics/anthropic-sdk-ruby/commit/064113e6bebfd523cb3a51e89c1faa113c804453))
* switch to prettier looking sorbet annotations ([#12](https://github.com/anthropics/anthropic-sdk-ruby/issues/12)) ([3a98172](https://github.com/anthropics/anthropic-sdk-ruby/commit/3a98172528f03b4d0dd66f61c06ed96047413522))
* **tests:** limit array example length ([df006e2](https://github.com/anthropics/anthropic-sdk-ruby/commit/df006e2cba144280b8c402f7d27b3e3314559c67))
* **tests:** support overriding base url with an env var ([6c0135b](https://github.com/anthropics/anthropic-sdk-ruby/commit/6c0135b87c12b3eb83060688e218fe32f7c613dd))
* **tests:** support overriding base url with an env var ([4c88087](https://github.com/anthropics/anthropic-sdk-ruby/commit/4c880871e1e87758b6298e5830513de5cd692a02))
* touch up sdk usage examples ([1bd00b5](https://github.com/anthropics/anthropic-sdk-ruby/commit/1bd00b51e17412c40e4091b5d8624d1e3de4a045))
* touch up yard docs with more spec compliant syntax ([dc157ab](https://github.com/anthropics/anthropic-sdk-ruby/commit/dc157ab4157fd29aea5b229a277b6d90766c3f08))
* **types:** add types for Model#initialize ([5a2123b](https://github.com/anthropics/anthropic-sdk-ruby/commit/5a2123b581711ed40c929534dce645279b55c6b2))
* unknown commit message ([796e654](https://github.com/anthropics/anthropic-sdk-ruby/commit/796e65499903e1ba89e11b813157e7d7f977cf2e))
* unknown commit message ([ed20454](https://github.com/anthropics/anthropic-sdk-ruby/commit/ed204542c7414452d58c6e88e0422351f80cbd2b))
* unknown commit message ([cc7ce7e](https://github.com/anthropics/anthropic-sdk-ruby/commit/cc7ce7ef3f3fca39a8766f8c8b141f73c8118aaa))
* unknown commit message ([c4c8a4b](https://github.com/anthropics/anthropic-sdk-ruby/commit/c4c8a4bcd6e00c98066ab07c6300f84cf5d979df))
* unknown commit message ([82f8fe0](https://github.com/anthropics/anthropic-sdk-ruby/commit/82f8fe0a4b73bfb54b23db179da9353f8daa137f))
* unknown commit message ([465bf0b](https://github.com/anthropics/anthropic-sdk-ruby/commit/465bf0b65bfd05d01b01f3bbaf45070ae80c12cc))
* unknown commit message ([7219236](https://github.com/anthropics/anthropic-sdk-ruby/commit/7219236159271fa797f92c91b3b563ae5eb204b5))
* unknown commit message ([b3668b7](https://github.com/anthropics/anthropic-sdk-ruby/commit/b3668b7fcb3c80c17d21127154d05dc0569e8517))
* unknown commit message ([31885ce](https://github.com/anthropics/anthropic-sdk-ruby/commit/31885ceb0c8c079ffbe80231ac52c878b05c900b))
* unknown commit message ([1514045](https://github.com/anthropics/anthropic-sdk-ruby/commit/15140450700479fb0aa738768cdcb4fbb41fc525))
* unknown commit message ([e7d6f17](https://github.com/anthropics/anthropic-sdk-ruby/commit/e7d6f17c083f0e73f59e24b7dc8d5a7254cab574))
* unknown commit message ([042cdbb](https://github.com/anthropics/anthropic-sdk-ruby/commit/042cdbb6f577e4c59dbefc59e8218b5ce113bdc9))
* unknown commit message ([8077201](https://github.com/anthropics/anthropic-sdk-ruby/commit/80772011e1b01b871bf1f35e21d83155ee917f76))
* unknown commit message ([5474b7c](https://github.com/anthropics/anthropic-sdk-ruby/commit/5474b7cd63526f19f83fa240bc800056d42a4360))
* unknown commit message ([7f320b2](https://github.com/anthropics/anthropic-sdk-ruby/commit/7f320b23bea26d3d17ca20bcebb4456ef6b51dde))
* unknown commit message ([46f31db](https://github.com/anthropics/anthropic-sdk-ruby/commit/46f31db2d528096f6a4e2c95890c6dc1e364ea7c))
* unknown commit message ([2fab4c1](https://github.com/anthropics/anthropic-sdk-ruby/commit/2fab4c1d7768b2057f306fde3399638b23ab6544))
* unknown commit message ([c189028](https://github.com/anthropics/anthropic-sdk-ruby/commit/c1890281149d1afae26917e4be142c87946012c8))
* unknown commit message ([5db7d5c](https://github.com/anthropics/anthropic-sdk-ruby/commit/5db7d5c21a6e7225f4c0fecdd7d624c360947823))
* unknown commit message ([3d137b9](https://github.com/anthropics/anthropic-sdk-ruby/commit/3d137b9241e491fdb2d260080db7364774652c72))
* unknown commit message ([8efbf84](https://github.com/anthropics/anthropic-sdk-ruby/commit/8efbf84e789cd434a3d6e32b4d4e629983b3c28b))
* unknown commit message ([aee0601](https://github.com/anthropics/anthropic-sdk-ruby/commit/aee0601a7410743d0424cf33da6804e7cf0b036d))
* unknown commit message ([b95df92](https://github.com/anthropics/anthropic-sdk-ruby/commit/b95df92d0fb45ae6f85c5d509c5bbc7da9eaffaf))
* unknown commit message ([1e748e8](https://github.com/anthropics/anthropic-sdk-ruby/commit/1e748e8e7804b644daec5b40eb5d98e0b4117b92))
* unknown commit message ([5c33a30](https://github.com/anthropics/anthropic-sdk-ruby/commit/5c33a3048ffb561f7f90a5be66373bd58586cd9e))
* unknown commit message ([aec6d2b](https://github.com/anthropics/anthropic-sdk-ruby/commit/aec6d2b18c9bff2e7bc72799a5787ee547c01683))
* unknown commit message ([9ba259f](https://github.com/anthropics/anthropic-sdk-ruby/commit/9ba259f38d13765edc44f2a502022a96b5100aa2))
* unknown commit message ([90fd7b0](https://github.com/anthropics/anthropic-sdk-ruby/commit/90fd7b001899800ffa717715ddcfaa3e3dcc7fc4))
* unknown commit message ([b68ff43](https://github.com/anthropics/anthropic-sdk-ruby/commit/b68ff43484498d3715daa46da014a24f3a506442))
* unknown commit message ([215c716](https://github.com/anthropics/anthropic-sdk-ruby/commit/215c716c41714aad1649c3e8c074ae8cedda053a))
* unknown commit message ([7fc3326](https://github.com/anthropics/anthropic-sdk-ruby/commit/7fc33265423046e2eb66c2623f84d788cf01068e))
* unknown commit message ([fc89d13](https://github.com/anthropics/anthropic-sdk-ruby/commit/fc89d13a94cd9940482a905c620fb87424fc34dd))
* unknown commit message ([f5c2dc1](https://github.com/anthropics/anthropic-sdk-ruby/commit/f5c2dc1d21dc3e3696c14774a5b177f75c5d2f12))
* unknown commit message ([84aee14](https://github.com/anthropics/anthropic-sdk-ruby/commit/84aee14d4da446e19a937757b3090b6508284a00))
* unknown commit message ([572b2c7](https://github.com/anthropics/anthropic-sdk-ruby/commit/572b2c7b8befe771cb63e6997e59add22b4612a8))
* unknown commit message ([75435e2](https://github.com/anthropics/anthropic-sdk-ruby/commit/75435e24a394f0b72b9324c9ac88d9f375860145))
* unknown commit message ([8ee908a](https://github.com/anthropics/anthropic-sdk-ruby/commit/8ee908ac1bf58d19a96dfd817a93216b994d9494))
* unknown commit message ([8a7bf3e](https://github.com/anthropics/anthropic-sdk-ruby/commit/8a7bf3e18085a4b3345ea2aac3bb210f9e8656c6))
* unknown commit message ([e6d54b5](https://github.com/anthropics/anthropic-sdk-ruby/commit/e6d54b5d6afba0035f422e5f5313fc90b3908bf5))
* unknown commit message ([dc157ab](https://github.com/anthropics/anthropic-sdk-ruby/commit/dc157ab4157fd29aea5b229a277b6d90766c3f08))
* unknown commit message ([1dfecdf](https://github.com/anthropics/anthropic-sdk-ruby/commit/1dfecdfd96eb85b449b8abb5281293816754f8be))
* unknown commit message ([0291b49](https://github.com/anthropics/anthropic-sdk-ruby/commit/0291b49a288d313b85c2c21c157f42c1b42701a5))
* unknown commit message ([dc68ceb](https://github.com/anthropics/anthropic-sdk-ruby/commit/dc68cebaee5b7c4bbc02214559c96b563bfccfa2))
* unknown commit message ([ae072d7](https://github.com/anthropics/anthropic-sdk-ruby/commit/ae072d7ea84e706b7526b3f22fac55eb6e31ac2d))
* unknown commit message ([815f6f1](https://github.com/anthropics/anthropic-sdk-ruby/commit/815f6f11698e10950dc2115b1de288dc3d4a8f65))
* unknown commit message ([51ee769](https://github.com/anthropics/anthropic-sdk-ruby/commit/51ee76983abf2bac28fb139f5c1638909f23e92f))
* unknown commit message ([ee8dc80](https://github.com/anthropics/anthropic-sdk-ruby/commit/ee8dc80005908f785510b33762436e9677300880))
* unknown commit message ([2e32e31](https://github.com/anthropics/anthropic-sdk-ruby/commit/2e32e3181cfd76314185de62589499c8dbdcf8fa))
* unknown commit message ([e49c40b](https://github.com/anthropics/anthropic-sdk-ruby/commit/e49c40ba9a4db9226d179bc9ce419a017e27fe3f))
* unknown commit message ([8e10e1e](https://github.com/anthropics/anthropic-sdk-ruby/commit/8e10e1e53cca77f8467e7fda059c61bba7c21a18))
* unknown commit message ([9fa1667](https://github.com/anthropics/anthropic-sdk-ruby/commit/9fa1667b6fef8f5d9bb454e9fa7c2071dde91cdc))
* unknown commit message ([545f35f](https://github.com/anthropics/anthropic-sdk-ruby/commit/545f35f993bec8f63a7557fd13c78d2aee88c5ac))
* unknown commit message ([b2a17dc](https://github.com/anthropics/anthropic-sdk-ruby/commit/b2a17dc2e586ca85525bb05418664a5e4fc40bd2))
* unknown commit message ([3ac9239](https://github.com/anthropics/anthropic-sdk-ruby/commit/3ac92395e1de0f40d6ca30957a176f153b6d2daf))
* unknown commit message ([4758f2f](https://github.com/anthropics/anthropic-sdk-ruby/commit/4758f2f69bfbf8491b76f491bde6fa4f24a671e7))
* unknown commit message ([203ea8e](https://github.com/anthropics/anthropic-sdk-ruby/commit/203ea8ef2e94df101ed3f451c16e6dc969fe5e77))
* unknown commit message ([7079e3b](https://github.com/anthropics/anthropic-sdk-ruby/commit/7079e3b7ee61fc09f8a6880b3932dd4c6901d5d4))
* unknown commit message ([20323f4](https://github.com/anthropics/anthropic-sdk-ruby/commit/20323f4dcb37aa8686eccd8d4ab2350172c8c8bd))
* unknown commit message ([5626317](https://github.com/anthropics/anthropic-sdk-ruby/commit/56263177532d4bccc8229d051ea05ed1fe682e6c))
* unknown commit message ([1943720](https://github.com/anthropics/anthropic-sdk-ruby/commit/194372003c37f9a22975f4a0c780afbecdee4438))
* unknown commit message ([e1eb80f](https://github.com/anthropics/anthropic-sdk-ruby/commit/e1eb80f90a0053d60da08d12c268147382aaa3d7))
* unknown commit message ([8f1a061](https://github.com/anthropics/anthropic-sdk-ruby/commit/8f1a06136c031fb71d5d17d7943f2cb060513f42))
* unknown commit message ([6707fde](https://github.com/anthropics/anthropic-sdk-ruby/commit/6707fdea9040664f1010794aaf86b2b21bf6f414))
* unknown commit message ([bf74451](https://github.com/anthropics/anthropic-sdk-ruby/commit/bf74451cc475989c3338b2d8198650c78162e8d6))
* unknown commit message ([132f23a](https://github.com/anthropics/anthropic-sdk-ruby/commit/132f23a2c56155d618c20eca7accb4abf85e39a2))
* unknown commit message ([cf3d9cd](https://github.com/anthropics/anthropic-sdk-ruby/commit/cf3d9cd398495f253ce1421861ed5f37c97e36f0))
* unknown commit message ([b44172f](https://github.com/anthropics/anthropic-sdk-ruby/commit/b44172f02a80c9a5bcef1beb27e0daa303b25b44))
* unknown commit message ([83e9ed4](https://github.com/anthropics/anthropic-sdk-ruby/commit/83e9ed4201cdc3f0ead4f522bbcc6e54705d9557))
* unknown commit message ([90e3e26](https://github.com/anthropics/anthropic-sdk-ruby/commit/90e3e26ee15715739f04feb98f92d1cf748a4801))
* unknown commit message ([43da888](https://github.com/anthropics/anthropic-sdk-ruby/commit/43da888b43719fc9477876ea61936d1ac9c8cd62))
* unknown commit message ([5dd26ad](https://github.com/anthropics/anthropic-sdk-ruby/commit/5dd26ad3129594ee6955106198793dcba56bca87))
* unknown commit message ([b6ade22](https://github.com/anthropics/anthropic-sdk-ruby/commit/b6ade22118bffcf1b51f098ffe6410daa02ff83f))
* unknown commit message ([c390289](https://github.com/anthropics/anthropic-sdk-ruby/commit/c390289347c64d51b9f8abcd0dace801b1d63bf2))
* unknown commit message ([a456b92](https://github.com/anthropics/anthropic-sdk-ruby/commit/a456b92fda2a3e0abb1d0055decd007d4c78e074))
* unknown commit message ([99f6930](https://github.com/anthropics/anthropic-sdk-ruby/commit/99f693069981d3131f8a266f39525adb571a057b))
* unknown commit message ([2c01db4](https://github.com/anthropics/anthropic-sdk-ruby/commit/2c01db4a8c6f83b44d7564ab716dd9e727520514))
* unknown commit message ([ec36fe1](https://github.com/anthropics/anthropic-sdk-ruby/commit/ec36fe126bf160d285c0c4f0ccda134ff7e87fc1))
* unknown commit message ([9c6e7e6](https://github.com/anthropics/anthropic-sdk-ruby/commit/9c6e7e615fbba8676ed2d89ac4c5ddb1fae36efd))
* unknown commit message ([25c089f](https://github.com/anthropics/anthropic-sdk-ruby/commit/25c089fe52e898b0c6430c1688701d3c57604528))
* unknown commit message ([b63d653](https://github.com/anthropics/anthropic-sdk-ruby/commit/b63d6536fd5dd18d6383773e1b3453bfe15e0a23))
* unknown commit message ([bacbf53](https://github.com/anthropics/anthropic-sdk-ruby/commit/bacbf534fc9d91cb9ebd52211d8a0dfe2fafbae8))
* unknown commit message ([f55e130](https://github.com/anthropics/anthropic-sdk-ruby/commit/f55e1309589874988b5afd6f3bacfe5facdbd030))
* unknown commit message ([702735e](https://github.com/anthropics/anthropic-sdk-ruby/commit/702735e13fffe8ce79fa2fcd5214c6212f2c4ffb))
* unknown commit message ([236247b](https://github.com/anthropics/anthropic-sdk-ruby/commit/236247b370cfd126baa9399cfbb1b1b02b7a2af0))
* unknown commit message ([992a146](https://github.com/anthropics/anthropic-sdk-ruby/commit/992a146f76e9f3b304aebddd7650348c03eb69ce))
* unknown commit message ([fd5d65f](https://github.com/anthropics/anthropic-sdk-ruby/commit/fd5d65f8ba819b5d60af587b702df616d11befee))
* unknown commit message ([f480392](https://github.com/anthropics/anthropic-sdk-ruby/commit/f4803921ccfb95db91613dc5ee05f34ab01e7b50))
* unknown commit message ([a825225](https://github.com/anthropics/anthropic-sdk-ruby/commit/a825225707d55f91176b903c363b5e76a7f1e906))
* unknown commit message ([1e8f0d7](https://github.com/anthropics/anthropic-sdk-ruby/commit/1e8f0d72e00907060b9df8f5f490754ff2f42218))
* unknown commit message ([f5e32b6](https://github.com/anthropics/anthropic-sdk-ruby/commit/f5e32b6890b4b97d6ef555565d63fd8a233fc0b1))
* unknown commit message ([255af2c](https://github.com/anthropics/anthropic-sdk-ruby/commit/255af2c3848579ea85f8bd72d0917c283853906c))
* unknown commit message ([0f8f0d3](https://github.com/anthropics/anthropic-sdk-ruby/commit/0f8f0d3b22c9f3efed74e3a7fe2fb1adb877ba87))
* unknown commit message ([c815c7f](https://github.com/anthropics/anthropic-sdk-ruby/commit/c815c7f17c6bc7f8019791ce62bc54d221b64664))
* unknown commit message ([67f68dc](https://github.com/anthropics/anthropic-sdk-ruby/commit/67f68dc59e2e0f58061ce2afb4a320c0d65a7eba))
* unknown commit message ([7a4e479](https://github.com/anthropics/anthropic-sdk-ruby/commit/7a4e479d298bcc2243d159a8c23ffc2607944fbc))
* unknown commit message ([df006e2](https://github.com/anthropics/anthropic-sdk-ruby/commit/df006e2cba144280b8c402f7d27b3e3314559c67))
* unknown commit message ([a7f4b77](https://github.com/anthropics/anthropic-sdk-ruby/commit/a7f4b7763091c10ce3fdf243309aa75069e5aedb))
* unknown commit message ([7546811](https://github.com/anthropics/anthropic-sdk-ruby/commit/7546811d6d177d27f2ba09e28cbe44fa959c3eb8))
* unknown commit message ([7699572](https://github.com/anthropics/anthropic-sdk-ruby/commit/769957257171548b0a06d98d3ebfc419aa7a4fd1))
* unknown commit message ([b09f15f](https://github.com/anthropics/anthropic-sdk-ruby/commit/b09f15f86879bc710a8fc37d484dbfd089cb6eb5))
* unknown commit message ([fefdaf2](https://github.com/anthropics/anthropic-sdk-ruby/commit/fefdaf26152537af76bc4fc97fa471bf16948e3d))
* unknown commit message ([d44a188](https://github.com/anthropics/anthropic-sdk-ruby/commit/d44a188adf96d994c997db9ffa25b005d0e3f34c))
* unknown commit message ([c3e2c09](https://github.com/anthropics/anthropic-sdk-ruby/commit/c3e2c09d295b6ce365ec3a0311f86e5e2ba57f47))
* unknown commit message ([780ccfe](https://github.com/anthropics/anthropic-sdk-ruby/commit/780ccfecae00c632bb678726ce9fe5a3b97f3d01))
* unknown commit message ([633147d](https://github.com/anthropics/anthropic-sdk-ruby/commit/633147d2f482e15bc16f61ef77c9fd9249d23b31))
* unknown commit message ([69c38f7](https://github.com/anthropics/anthropic-sdk-ruby/commit/69c38f74e4af30eff3d9bfd77a657b1e8a02f88e))
* unknown commit message ([213172e](https://github.com/anthropics/anthropic-sdk-ruby/commit/213172e4cef378fc280fee3429b6e449b33efdb0))
* unknown commit message ([ff4c067](https://github.com/anthropics/anthropic-sdk-ruby/commit/ff4c0674a5ef8d6658b015e52b4a02edf3e1004b))
* unknown commit message ([b0fde06](https://github.com/anthropics/anthropic-sdk-ruby/commit/b0fde06c0c7f287e9c0b6a8dfd1dcbe5538071dd))
* unknown commit message ([6fae646](https://github.com/anthropics/anthropic-sdk-ruby/commit/6fae6460a3e83a0683e3182cc90085eb39681a26))
* unknown commit message ([979744f](https://github.com/anthropics/anthropic-sdk-ruby/commit/979744f4b520a341ea1508e44e5b33f9362d1029))
* unknown commit message ([4aa03f1](https://github.com/anthropics/anthropic-sdk-ruby/commit/4aa03f1c69e387f5adeb5d63b13c356c2bbeaf89))
* unknown commit message ([4e4523e](https://github.com/anthropics/anthropic-sdk-ruby/commit/4e4523ec5cbdb95704580a2d8b3d9b6b92164656))
* unknown commit message ([63e1284](https://github.com/anthropics/anthropic-sdk-ruby/commit/63e1284ece645a08e2d692440204d1ea118f2244))
* unknown commit message ([e3f3559](https://github.com/anthropics/anthropic-sdk-ruby/commit/e3f355964dafb934fbef49bf94bc0b7cd5e64423))
* unknown commit message ([b37e786](https://github.com/anthropics/anthropic-sdk-ruby/commit/b37e786e38172700a40b316b0e9e6d541d39377d))
* unknown commit message ([d3ec6af](https://github.com/anthropics/anthropic-sdk-ruby/commit/d3ec6af0fb1d858193c256f34257fb08f09a405f))
* unknown commit message ([1acdd2b](https://github.com/anthropics/anthropic-sdk-ruby/commit/1acdd2b1d6e3b51c169f17ce102d3f1718c93822))
* unknown commit message ([064113e](https://github.com/anthropics/anthropic-sdk-ruby/commit/064113e6bebfd523cb3a51e89c1faa113c804453))
* unknown commit message ([742f2a7](https://github.com/anthropics/anthropic-sdk-ruby/commit/742f2a78ee1b82457af4c7582033d87d9f38283f))
* unknown commit message ([31530cc](https://github.com/anthropics/anthropic-sdk-ruby/commit/31530cc7bc3be027f87f8c2867e37fdb8dfed5a7))
* unknown commit message ([b82e233](https://github.com/anthropics/anthropic-sdk-ruby/commit/b82e2336c27fa8ee9984a83e51ed6a3da765ac31))
* unknown commit message ([20b9526](https://github.com/anthropics/anthropic-sdk-ruby/commit/20b9526bb8503d9692753950650fefb455df8a92))
* unknown commit message ([7f4152d](https://github.com/anthropics/anthropic-sdk-ruby/commit/7f4152d13445a044bd4bb1c2301adc6be16cd61f))
* unknown commit message ([30e430a](https://github.com/anthropics/anthropic-sdk-ruby/commit/30e430a1891c263932a353cac9f4385a1f21e773))
* unknown commit message ([e1845c3](https://github.com/anthropics/anthropic-sdk-ruby/commit/e1845c338d966ab5cd9254b9ab1988875a3d96bb))
* unknown commit message ([037d377](https://github.com/anthropics/anthropic-sdk-ruby/commit/037d377178c216c7284b7a808a5bf6a683040450))
* unknown commit message ([5a2123b](https://github.com/anthropics/anthropic-sdk-ruby/commit/5a2123b581711ed40c929534dce645279b55c6b2))
* unknown commit message ([217f24b](https://github.com/anthropics/anthropic-sdk-ruby/commit/217f24bd034281d52a45b7fa8391a4207f2eec96))
* unknown commit message ([96a52f8](https://github.com/anthropics/anthropic-sdk-ruby/commit/96a52f8230c608738e9cc4af2e1872440c4569a8))
* unknown commit message ([4c88087](https://github.com/anthropics/anthropic-sdk-ruby/commit/4c880871e1e87758b6298e5830513de5cd692a02))
* unknown commit message ([3907f0b](https://github.com/anthropics/anthropic-sdk-ruby/commit/3907f0b22be2fc9eac8f61482046f0d8800cf624))
* unknown commit message ([f8bef83](https://github.com/anthropics/anthropic-sdk-ruby/commit/f8bef83e309e6f54d29e4f00268dc344241f8032))
* update basic usage examples ([d573682](https://github.com/anthropics/anthropic-sdk-ruby/commit/d573682cf78c7347059fa306e2b3cbee7dedfdf9))
* update custom timeout header name ([c4c9870](https://github.com/anthropics/anthropic-sdk-ruby/commit/c4c987007a36a34c100e48383efdd29d33bc43ca))
* update deps ([4736fe3](https://github.com/anthropics/anthropic-sdk-ruby/commit/4736fe3b24fafff748257cd21db8c265dfe4f707))
* update deps ([73f1827](https://github.com/anthropics/anthropic-sdk-ruby/commit/73f1827fa9b4cde920df59249a0c8fc27d978b06))
* update lockfile ([92c697d](https://github.com/anthropics/anthropic-sdk-ruby/commit/92c697d2db8f48f45ddae69e1c7fca7c713b2662))
* update readme ([#28](https://github.com/anthropics/anthropic-sdk-ruby/issues/28)) ([6f56971](https://github.com/anthropics/anthropic-sdk-ruby/commit/6f56971455470f4bfd59b5035a765cab35a6c1d8))
* update sorbet annotations for vertex and bedrock clients ([5310e3b](https://github.com/anthropics/anthropic-sdk-ruby/commit/5310e3b18c7c2f804e947419eb2abcec79633bec))
* update sorbet examples ([0a55362](https://github.com/anthropics/anthropic-sdk-ruby/commit/0a55362427a4d1f2f0bcf590d50d2a3356be8f64))
* update yard comment formatting ([#62](https://github.com/anthropics/anthropic-sdk-ruby/issues/62)) ([f3f4c25](https://github.com/anthropics/anthropic-sdk-ruby/commit/f3f4c25b8fe2bfe39d0362541ac76a912cdf3b49))
* updated lockfile ([187ea67](https://github.com/anthropics/anthropic-sdk-ruby/commit/187ea67c171d3ada873fc316ed6fcaf1443e694e))
* use `has_more` for pagination ([4e238c5](https://github.com/anthropics/anthropic-sdk-ruby/commit/4e238c5ad7f77069dcd16265c801bddcec5fd935))
* use concise syntax for pattern matching ([c1947ac](https://github.com/anthropics/anthropic-sdk-ruby/commit/c1947ac4cbc343a6e81f7eba678314e33385127a))
* use fully qualified name in sorbet README example ([#31](https://github.com/anthropics/anthropic-sdk-ruby/issues/31)) ([47a4d11](https://github.com/anthropics/anthropic-sdk-ruby/commit/47a4d11c13630c10f742998ea11d28f68c54ffc1))
* use generics instead of overloading for sorbet type definitions ([6ea42de](https://github.com/anthropics/anthropic-sdk-ruby/commit/6ea42dee14dc4b9086bcc1a79dcd2987da790c74))
* use more descriptive rubocop output format ([f5c2dc1](https://github.com/anthropics/anthropic-sdk-ruby/commit/f5c2dc1d21dc3e3696c14774a5b177f75c5d2f12))
* yard doc improvements ([e3f3559](https://github.com/anthropics/anthropic-sdk-ruby/commit/e3f355964dafb934fbef49bf94bc0b7cd5e64423))


### Documentation

* update URLs from stainlessapi.com to stainless.com ([2ac10de](https://github.com/anthropics/anthropic-sdk-ruby/commit/2ac10decee796a6b8222da70023e235a74877a7a))
* use latest sonnet in example snippets ([236247b](https://github.com/anthropics/anthropic-sdk-ruby/commit/236247b370cfd126baa9399cfbb1b1b02b7a2af0))


### Refactors

* avoid unnecessary setter invocation ([c815c7f](https://github.com/anthropics/anthropic-sdk-ruby/commit/c815c7f17c6bc7f8019791ce62bc54d221b64664))
* clean up base client send_request method ([213172e](https://github.com/anthropics/anthropic-sdk-ruby/commit/213172e4cef378fc280fee3429b6e449b33efdb0))
* client constructor ([7699572](https://github.com/anthropics/anthropic-sdk-ruby/commit/769957257171548b0a06d98d3ebfc419aa7a4fd1))
* **client:** extract ContentBlockParam type ([7546811](https://github.com/anthropics/anthropic-sdk-ruby/commit/7546811d6d177d27f2ba09e28cbe44fa959c3eb8))
* **client:** impose consistent sdk internals layout ([1e748e8](https://github.com/anthropics/anthropic-sdk-ruby/commit/1e748e8e7804b644daec5b40eb5d98e0b4117b92))
* extract out url handling functions into utils ([4e4523e](https://github.com/anthropics/anthropic-sdk-ruby/commit/4e4523ec5cbdb95704580a2d8b3d9b6b92164656))
* extract some base client internals into utils ([3a2d596](https://github.com/anthropics/anthropic-sdk-ruby/commit/3a2d596e223eb8e9ea8244468963076e15e79db4))
* private base client internals ([fefdaf2](https://github.com/anthropics/anthropic-sdk-ruby/commit/fefdaf26152537af76bc4fc97fa471bf16948e3d))
* remove special testing only request header ([bacbf53](https://github.com/anthropics/anthropic-sdk-ruby/commit/bacbf534fc9d91cb9ebd52211d8a0dfe2fafbae8))
