# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### 0.7.2 (2025-08-26)


### Features

* Add data-link-path attribute ([a11724c](https://github.com/erfur/obsidian-supercharged-links/commit/a11724c9a962c88e3ffb86b1b15ffb9f3a010172))
* Aliases and single-link types ([42f665c](https://github.com/erfur/obsidian-supercharged-links/commit/42f665c03953ced7ff5a47aebb3baa7b78479d29))
* Changed icon css class to data-link-icon to prevent confusion ([d5e290a](https://github.com/erfur/obsidian-supercharged-links/commit/d5e290a7522d9c0df5dfdf9385705412d03632ce))
* Incremental updates on live preview for improved performance ([6dce400](https://github.com/erfur/obsidian-supercharged-links/commit/6dce4004bf4a932d3dcd41225d5104a51b7eaabc))
* Much better live-preview support with CM6 extensions ([754d173](https://github.com/erfur/obsidian-supercharged-links/commit/754d173b2e1b6bd7749a8225bce6ec08108bc3da))
* Now also supercharges aliased links in editor and live preview ([5ea91b0](https://github.com/erfur/obsidian-supercharged-links/commit/5ea91b0f427b6dce6de2bc1694aca226a1ba7fc0))
* Now also supercharges the Live Preview mode ([6882200](https://github.com/erfur/obsidian-supercharged-links/commit/68822004939553f90b9e5a73825643232f2738b8)), closes [#54](https://github.com/erfur/obsidian-supercharged-links/issues/54)
* Now automatically activates CSS snippet ([e547cd0](https://github.com/erfur/obsidian-supercharged-links/commit/e547cd00f8ff3a7018adce7644c9e7071f9f4d84))
* Setting for quick switcher supercharge ([931c4e6](https://github.com/erfur/obsidian-supercharged-links/commit/931c4e699c73496268b31375c7b3072a4c666cda))
* Style setting support for after emojis and backgrounds ([cb0313a](https://github.com/erfur/obsidian-supercharged-links/commit/cb0313a3ba4afd39b7fe919f37f411e99ac34705))
* Supercharge link autocompleter ([89511e4](https://github.com/erfur/obsidian-supercharged-links/commit/89511e47c706dd8596d4cb1c2268edcf738c32fe))
* Supercharge quick switcher ([6ce1005](https://github.com/erfur/obsidian-supercharged-links/commit/6ce10055d14aa9204f64cecf96cc0e8b1de1a76b)), closes [#76](https://github.com/erfur/obsidian-supercharged-links/issues/76)
* Supercharge tab headers ([e257050](https://github.com/erfur/obsidian-supercharged-links/commit/e257050d0099067becc83c14aab0dcefd497f894)), closes [#136](https://github.com/erfur/obsidian-supercharged-links/issues/136)
* Support Another Quick Switcher ([9e9a3e7](https://github.com/erfur/obsidian-supercharged-links/commit/9e9a3e7a822ac4576e3a9d45cca5cbfd085d77cf))
* Support backlinks in document ([18d00fd](https://github.com/erfur/obsidian-supercharged-links/commit/18d00fd4f730823644522c2fc8cdc93e239d4a4e)), closes [#52](https://github.com/erfur/obsidian-supercharged-links/issues/52)
* support data links as URLs for inline images ([3269888](https://github.com/erfur/obsidian-supercharged-links/commit/32698884eea43ec64f8694ed33811ce02c7a8fd7))
* Support recent files plugin ([0266a6c](https://github.com/erfur/obsidian-supercharged-links/commit/0266a6cc5e155ff5bff8057f8c605c5098f5d57e)), closes [#72](https://github.com/erfur/obsidian-supercharged-links/issues/72)


### Bug Fixes

* Adhere to the final CM6 API ([48d8dcb](https://github.com/erfur/obsidian-supercharged-links/commit/48d8dcbf72dcf98743c4d5e49ae84e34023b1399))
* Aliases are not supercharged in Live Preview ([36b7f25](https://github.com/erfur/obsidian-supercharged-links/commit/36b7f25fa9af31acb3d6f95d876716f0b8b3a561))
* Better performance by stopping forcing redraws on updates ([e79691e](https://github.com/erfur/obsidian-supercharged-links/commit/e79691eb093acd0f8984c56aa439da21233e36ff))
* Breadcrumbs V4 sidebar support ([1cb603d](https://github.com/erfur/obsidian-supercharged-links/commit/1cb603dc4596e807449cb3026122f9f01e374177))
* Broken suggestion models in insider ([5130708](https://github.com/erfur/obsidian-supercharged-links/commit/51307080e41a845509cd51037445ae1d60912fc8))
* Catch null FileCache in editor ([ed651a0](https://github.com/erfur/obsidian-supercharged-links/commit/ed651a0eaf3a43ee09ceea6e9dcbb6b2924e2505)), closes [#56](https://github.com/erfur/obsidian-supercharged-links/issues/56)
* Crash if no active file ([db02a5d](https://github.com/erfur/obsidian-supercharged-links/commit/db02a5d049116e45a53b5b6395bd1959265e8d86))
* Crash on internal links trying to get supercharged ([bd7fefb](https://github.com/erfur/obsidian-supercharged-links/commit/bd7fefb8ec6a8904ead6577335c7f17672ac72f7))
* Crashes when handling supercharging properties ([8c445f9](https://github.com/erfur/obsidian-supercharged-links/commit/8c445f9a4065dc118330e0fefaeca928caa85c4c))
* Cursor jump bugs after inserting a link ([070490e](https://github.com/erfur/obsidian-supercharged-links/commit/070490e4e80116a5a73c8998771df96b7d2f3b2b)), closes [#96](https://github.com/erfur/obsidian-supercharged-links/issues/96)
* Didn't update links when typing ([12ce2c3](https://github.com/erfur/obsidian-supercharged-links/commit/12ce2c3e79082e2f2e97f67b6935134adaf0782a))
* Disabled edit-mode supercharge on mobile to prevent bugs ([97d61c8](https://github.com/erfur/obsidian-supercharged-links/commit/97d61c8861a274093ecd1f4f6fe5e7ff68f2194c))
* Does not generate snippet if snippet folder does not exist ([a151ff9](https://github.com/erfur/obsidian-supercharged-links/commit/a151ff942b406a40a6ba5e66617534fb0a53d6c6))
* Doesnt properly observe multiple markdown panes ([166ad00](https://github.com/erfur/obsidian-supercharged-links/commit/166ad009a669f0a2a553a20928a174e7974d2ff6)), closes [#86](https://github.com/erfur/obsidian-supercharged-links/issues/86)
* File browser does not immediately update ([9fe8642](https://github.com/erfur/obsidian-supercharged-links/commit/9fe86424e58558f488fe9125dd5fac48d1775a5a))
* Generated snippets are not automatically enabled (v0.16.0+) ([46960e8](https://github.com/erfur/obsidian-supercharged-links/commit/46960e87c57b56d99fc998c402ee4d9cf84ce933))
* Handling exceptions where the href attribute of a link does not exist ([6ec0778](https://github.com/erfur/obsidian-supercharged-links/commit/6ec0778e8dbf32859bced8d4cd9e0675244da776))
* Immediately supercharge tab header on opening file in new tab ([1411343](https://github.com/erfur/obsidian-supercharged-links/commit/1411343fdabd01f5c97a5bdfab4c380d7206dd05))
* Improper default color in style settings ([1a51ca8](https://github.com/erfur/obsidian-supercharged-links/commit/1a51ca87cd1dc44361c47691a745a493e6237c88))
* Improper manifest file ([bc101c3](https://github.com/erfur/obsidian-supercharged-links/commit/bc101c31c26cfecc41a8a300d6cabaae112be168))
* Improve tab header supercharging updating ([f78cc76](https://github.com/erfur/obsidian-supercharged-links/commit/f78cc76b5c4a3a1e7d45dec73e503960cf453219))
* Inconsistencies with empty attribute values ([060078e](https://github.com/erfur/obsidian-supercharged-links/commit/060078e87944c9bab39f048f938dd9e5fde200ed))
* Live preview does not work for markdown links ([831361e](https://github.com/erfur/obsidian-supercharged-links/commit/831361e8e001ed9b3a789e0efc88c3ba3340166d)), closes [#80](https://github.com/erfur/obsidian-supercharged-links/issues/80)
* Markdown links do not work with paths ([15ff8e3](https://github.com/erfur/obsidian-supercharged-links/commit/15ff8e33f98bb3bd65581c5c6c5d283983af92bb)), closes [#80](https://github.com/erfur/obsidian-supercharged-links/issues/80)
* Multiple emojis when using ::before annotations ([14cdc93](https://github.com/erfur/obsidian-supercharged-links/commit/14cdc9385c73ac371590733ea5a695c09304b45f))
* No colouring on live preview on new versions ([9293ef6](https://github.com/erfur/obsidian-supercharged-links/commit/9293ef6d722bd04329453c3125ae90e08f1a1751))
* No colouring on live preview on new versions ([386b5ad](https://github.com/erfur/obsidian-supercharged-links/commit/386b5ada937bcaff358fc35e9ee92a07ce490ba8))
* No updates on scrolling ([230ca97](https://github.com/erfur/obsidian-supercharged-links/commit/230ca9788a85622bd7abe5d45d3b57fd5869f2ce))
* Obsidian reload crash ([82b02b5](https://github.com/erfur/obsidian-supercharged-links/commit/82b02b54a34cdbd18b02b3d2efed2455be7e9d57)), closes [#66](https://github.com/erfur/obsidian-supercharged-links/issues/66)
* Pane links don't update on change ([673f67b](https://github.com/erfur/obsidian-supercharged-links/commit/673f67b955408920a44824527ff93a1d39758c8d))
* Performance issues with backlinks panel ([8ded121](https://github.com/erfur/obsidian-supercharged-links/commit/8ded121d94cad1b3f50cc9b82d0287e835ab8679)), closes [#74](https://github.com/erfur/obsidian-supercharged-links/issues/74)
* Performance much worse in latest version ([7976687](https://github.com/erfur/obsidian-supercharged-links/commit/79766873c390e975156928b0757b5c7ee5b875cc)), closes [#75](https://github.com/erfur/obsidian-supercharged-links/issues/75)
* Possible null crash ([2fdea76](https://github.com/erfur/obsidian-supercharged-links/commit/2fdea7602a7a4bba7cfba01cd6a454ac7b4952d2))
* Properly set up settings for tab headers ([51ed676](https://github.com/erfur/obsidian-supercharged-links/commit/51ed676f46d277da6b7575c593112674451d113e))
* Properly unload events ([4f40ce5](https://github.com/erfur/obsidian-supercharged-links/commit/4f40ce5e5e15c155208ee0888d53fd9c3e6415b5))
* Slightly improved ordering of DOM elements to make background easier ([65aab7b](https://github.com/erfur/obsidian-supercharged-links/commit/65aab7bc63d8e4feb21e29fffc890dc16ff493f1))
* Small memory leak ([742f3ad](https://github.com/erfur/obsidian-supercharged-links/commit/742f3addfef8cb90a502e26e21349d27eb852f58))
* standard-version argument ([783b461](https://github.com/erfur/obsidian-supercharged-links/commit/783b461e975b0137d8094c13ddafb958a47d3810))
* Style settings doesn't render prepend text ([26331a0](https://github.com/erfur/obsidian-supercharged-links/commit/26331a0e5cc43ffe65172e7adccc0cf8a68ee966))
* supercharged-links-gen.css is not created when not present ([fbe2e1f](https://github.com/erfur/obsidian-supercharged-links/commit/fbe2e1f7eb9a693766ee709f7ae269ff811b3b2f))
* support modals in pop-out windows ([8725b26](https://github.com/erfur/obsidian-supercharged-links/commit/8725b2669cb7ff6a75223bce40e8dcdaaea67488))

### [0.4.4](https://github.com/HEmile/obsidian_supercharged_links/compare/0.4.3...0.4.4) (2022-01-17)

### [0.4.3](https://github.com/HEmile/obsidian_supercharged_links/compare/0.4.2...0.4.3) (2022-01-17)


### Features

* Support recent files plugin ([0266a6c](https://github.com/HEmile/obsidian_supercharged_links/commit/0266a6cc5e155ff5bff8057f8c605c5098f5d57e)), closes [#72](https://github.com/HEmile/obsidian_supercharged_links/issues/72)


### Bug Fixes

* File browser does not immediately update ([9fe8642](https://github.com/HEmile/obsidian_supercharged_links/commit/9fe86424e58558f488fe9125dd5fac48d1775a5a))

### [0.4.1](https://github.com/HEmile/obsidian_supercharged_links/compare/v0.4.4...v0.4.1) (2022-01-12)


### Bug Fixes

* standard-version argument ([783b461](https://github.com/HEmile/obsidian_supercharged_links/commit/783b461e975b0137d8094c13ddafb958a47d3810))

### [0.4.4](https://github.com/HEmile/obsidian_supercharged_links/compare/v0.4.3...v0.4.4) (2022-01-12)

### [0.4.3](https://github.com/HEmile/obsidian_supercharged_links/compare/v0.4.2...v0.4.3) (2022-01-12)

### [0.4.2](https://github.com/HEmile/obsidian_supercharged_links/compare/v0.4.1...v0.4.2) (2022-01-12)

### 0.4.1 (2022-01-12)


### Features

* Changed icon css class to data-link-icon to prevent confusion ([d5e290a](https://github.com/HEmile/obsidian_supercharged_links/commit/d5e290a7522d9c0df5dfdf9385705412d03632ce))
* Much better live-preview support with CM6 extensions ([754d173](https://github.com/HEmile/obsidian_supercharged_links/commit/754d173b2e1b6bd7749a8225bce6ec08108bc3da))
* Now also supercharges aliased links in editor and live preview ([5ea91b0](https://github.com/HEmile/obsidian_supercharged_links/commit/5ea91b0f427b6dce6de2bc1694aca226a1ba7fc0))
* Now also supercharges the Live Preview mode ([6882200](https://github.com/HEmile/obsidian_supercharged_links/commit/68822004939553f90b9e5a73825643232f2738b8)), closes [#54](https://github.com/HEmile/obsidian_supercharged_links/issues/54)


### Bug Fixes

* Aliases are not supercharged in Live Preview ([36b7f25](https://github.com/HEmile/obsidian_supercharged_links/commit/36b7f25fa9af31acb3d6f95d876716f0b8b3a561))
* Catch null FileCache in editor ([ed651a0](https://github.com/HEmile/obsidian_supercharged_links/commit/ed651a0eaf3a43ee09ceea6e9dcbb6b2924e2505)), closes [#56](https://github.com/HEmile/obsidian_supercharged_links/issues/56)
* Disabled edit-mode supercharge on mobile to prevent bugs ([97d61c8](https://github.com/HEmile/obsidian_supercharged_links/commit/97d61c8861a274093ecd1f4f6fe5e7ff68f2194c))
* Multiple emojis when using ::before annotations ([14cdc93](https://github.com/HEmile/obsidian_supercharged_links/commit/14cdc9385c73ac371590733ea5a695c09304b45f))
* Obsidian reload crash ([82b02b5](https://github.com/HEmile/obsidian_supercharged_links/commit/82b02b54a34cdbd18b02b3d2efed2455be7e9d57)), closes [#66](https://github.com/HEmile/obsidian_supercharged_links/issues/66)
* Properly unload events ([4f40ce5](https://github.com/HEmile/obsidian_supercharged_links/commit/4f40ce5e5e15c155208ee0888d53fd9c3e6415b5))
* Slightly improved ordering of DOM elements to make background easier ([65aab7b](https://github.com/HEmile/obsidian_supercharged_links/commit/65aab7bc63d8e4feb21e29fffc890dc16ff493f1))
