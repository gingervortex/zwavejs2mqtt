### Changelog

All notable changes to this project will be documented in this file. Dates are displayed in UTC.

Generated by [`auto-changelog`](https://github.com/CookPete/auto-changelog).

### [v2.0.0](https://github.com/robertsLando/Zwave2Mqtt/compare/v1.1.3...v2.0.0)

> 16 July 2019

- [fix] Better nodes event management. Fix #49 [`#49`](https://github.com/robertsLando/Zwave2Mqtt/issues/49)
- [feat] BETA: Hass mqtt discovery :tada: #27 [`6e124fa`](https://github.com/robertsLando/Zwave2Mqtt/commit/6e124fa4bc588bdfc9c19d2d8d55182068feeaf9)
- [feat] Hass devices JSON management in UI #27 #49 [`338c3ce`](https://github.com/robertsLando/Zwave2Mqtt/commit/338c3ce557560f4011e7c2265eb8537a258ca68f)
- [feat] HASS: support for devices like thermostats and fans with MQTT auto-discovery [`b26dcdf`](https://github.com/robertsLando/Zwave2Mqtt/commit/b26dcdfe04621fdc65a9788f84409cda75315f41)
- [feat] Breaking change: local nodes naming and location (#45). Now nodes name and location are stored in a JSON file and it will be imported/exported from the Control Panel UI instead of the zwcfg.xml file. This is back compatible as if there is no nodes.json configuration present the config is read from the existing xml file but the writeConfig button has been removed [`1f761d2`](https://github.com/robertsLando/Zwave2Mqtt/commit/1f761d2df6a043173999124b946733635812596c)
- [feat] Zwave scene and nodes events support #50 [`a7d80df`](https://github.com/robertsLando/Zwave2Mqtt/commit/a7d80dfb252cb344a0a02f213176103e324753bf)
- [refactor] Commented some code and clean up [`21102ad`](https://github.com/robertsLando/Zwave2Mqtt/commit/21102adf2a69a85d8033d03bac05e565d22a9d17)
- [feat] Persistent HASS devices and custom JSON editor [`1a92fed`](https://github.com/robertsLando/Zwave2Mqtt/commit/1a92fed3d683d484c9d19b4bbabe7a94fa1410a9)
- [feat] Hass Devices management UI [`7e16c7f`](https://github.com/robertsLando/Zwave2Mqtt/commit/7e16c7ffccf5f87384ed2089d08b9aa436cd16a2)
- [fix] Bug when using Object.assign not really cloning object at all [`dd72bf5`](https://github.com/robertsLando/Zwave2Mqtt/commit/dd72bf5449d3040b8973a096b99405763a7489bd)
- [fix] Set up light dimmer template for switch_multilevel [`e0662f7`](https://github.com/robertsLando/Zwave2Mqtt/commit/e0662f74a959a16cfc4c58982293c2888102674a)
- [fix] Node naming and location override (#45) [`d74588d`](https://github.com/robertsLando/Zwave2Mqtt/commit/d74588d2c3c89570aab72dbaea7e0dbd0e4a3307)
- [fix] Resolve close promise on mqtt client even with no client [`1c7abe1`](https://github.com/robertsLando/Zwave2Mqtt/commit/1c7abe19f45cc6c01eb3beecaceed3098ff5de29)
- Update issue templates [`1c43b56`](https://github.com/robertsLando/Zwave2Mqtt/commit/1c43b56961dbb69795b0fe631ef4ada5e8d81abf)
- Fix index for switch_multilevel [`ad00175`](https://github.com/robertsLando/Zwave2Mqtt/commit/ad001756723f84cd6536ad58f03c589b1e965dd2)
- [feat] Hass status management and mode fix [`c31446f`](https://github.com/robertsLando/Zwave2Mqtt/commit/c31446ff0933f8ffe7832ab31b4cccff20d2cc2a)
- [fix] Fix broken discovery #27 [`3b25dc7`](https://github.com/robertsLando/Zwave2Mqtt/commit/3b25dc74ba6a9f5c9e0be982d5e258058859bc28)
- [docs] Custom components with HASS [`b704f2e`](https://github.com/robertsLando/Zwave2Mqtt/commit/b704f2e1c7b4bfd870bf508b6a3521299d4c383f)
- [docs] Updated readme [`daa8e6b`](https://github.com/robertsLando/Zwave2Mqtt/commit/daa8e6b43eaf6da6f731716f1581c45711aae772)
- [fix] Better discovery topics update management [`ad01b9e`](https://github.com/robertsLando/Zwave2Mqtt/commit/ad01b9e5907cbec611a589058b740a7bc8d63934)
- [docs] Updated readme for hass [`2f32c09`](https://github.com/robertsLando/Zwave2Mqtt/commit/2f32c0994cfde57bfa5695ed97020b0d21558fa3)
- [fix] Broken scenes after deprecation with OZW 16 [`5a23372`](https://github.com/robertsLando/Zwave2Mqtt/commit/5a2337244f161ed8e1c5c119420a78f94787c42e)
- [feat] Flag in gateway settings to use node names in topics #45 [`e911579`](https://github.com/robertsLando/Zwave2Mqtt/commit/e911579b27a961dbd9c06ad9fe00e1badaf8293b)
- [docs] Updated docs [`ec40a40`](https://github.com/robertsLando/Zwave2Mqtt/commit/ec40a4031c9e8b2cfff493ae84435966070e76ff)
- [fix] Mode payload parsing for HASS [`e6d6e15`](https://github.com/robertsLando/Zwave2Mqtt/commit/e6d6e15804dfbf1be296fd8eb967a7db0fa17e2d)
- [fix] Add callback to Mqtt client end #49 [`1a67934`](https://github.com/robertsLando/Zwave2Mqtt/commit/1a679340c63b845b51249a0804740d9a70cbf550)
- [fix] Change setpoint when mode changes [`c75d088`](https://github.com/robertsLando/Zwave2Mqtt/commit/c75d0881f562b541ce26abed8a662323ba9b23c8)
- [feat] Custom icon for Hass devices [`042cace`](https://github.com/robertsLando/Zwave2Mqtt/commit/042cace4d39c7e7477c26cb79fcadff45af9dbee)
- [style] Better associations display and custom target node_id for groups associations (#47) [`6b9aae1`](https://github.com/robertsLando/Zwave2Mqtt/commit/6b9aae1c8e1a393ae5a69628f42831b0b414bdac)
- [feat] Auto detect failed nodes when calling replaceFailedNode function #34 [`843efee`](https://github.com/robertsLando/Zwave2Mqtt/commit/843efee18bb976fba7619f8e330530b1223e01ce)
- [fix] Value values list type write [`530f6c7`](https://github.com/robertsLando/Zwave2Mqtt/commit/530f6c76e5b4f37f9ee53d8c0deaa613a08f1d6e)
- [fix] Reverted change list type [`a3245fd`](https://github.com/robertsLando/Zwave2Mqtt/commit/a3245fd222c83e0d8bf2ee2fd97dbb8a60c762f5)
- [docs] Special topics [`c7f1cf7`](https://github.com/robertsLando/Zwave2Mqtt/commit/c7f1cf7837f48d7bc0d2cf9f51171d38fe276acc)
- [feat] Add node location to hass ids [`c7ebaee`](https://github.com/robertsLando/Zwave2Mqtt/commit/c7ebaeea73815cefa99fb38ca7e83f58400154aa)
- [docs] Hass componets management [`237a375`](https://github.com/robertsLando/Zwave2Mqtt/commit/237a37516ea191664f5b94bc0efb052ad9d30e3d)
- Update issue templates [`81f8081`](https://github.com/robertsLando/Zwave2Mqtt/commit/81f8081a6afc336cc5b722841e94cb530b5390ab)
- [feat] Hass door lock support [`c4d69bf`](https://github.com/robertsLando/Zwave2Mqtt/commit/c4d69bf22f8146bd95d6c7f6d853f3efd404226b)
- [feat] Added getNodeNeighbors missing node action [`67acc4c`](https://github.com/robertsLando/Zwave2Mqtt/commit/67acc4c9a9bf8d802a20e2f477895c524e068c08)
- [fix] Wrong value list values labels [`e19ee3f`](https://github.com/robertsLando/Zwave2Mqtt/commit/e19ee3f6fc396379555a8ff240d78fd08dc7105d)
- [fix] Get updated value object in parsePayload [`cd7bfdc`](https://github.com/robertsLando/Zwave2Mqtt/commit/cd7bfdc0ea5b622808d062e36943f7a8e98ef78a)
- [docs] Updated hass devices section [`fd6b5c8`](https://github.com/robertsLando/Zwave2Mqtt/commit/fd6b5c8978b70e826d9fb35b894b6d9a4a95ac28)
- [core] Updated to stable openzwave-shared 1.5.6 [`5f9fc89`](https://github.com/robertsLando/Zwave2Mqtt/commit/5f9fc898e96f4927cbb1c734e9f1b45a97484bb0)
- [fix] Import/Export nodes.json update hassDevices [`b913d93`](https://github.com/robertsLando/Zwave2Mqtt/commit/b913d93bdf014485aa495f89a9d74336ea3c482c)
- Delete FOUNDING.yml [`8c112ac`](https://github.com/robertsLando/Zwave2Mqtt/commit/8c112ac6b30781656fa8739894a77fbc8a177338)
- Added FOUNDING.yml [`09c8faf`](https://github.com/robertsLando/Zwave2Mqtt/commit/09c8faf1ea4fcdafda9c1451090cd3f627cd4198)
- Create FUNDING.yml [`f06f8db`](https://github.com/robertsLando/Zwave2Mqtt/commit/f06f8db27fec368e8e5759eeae9a930282a3ae75)
- [fix] Values not subscribed correctly when using custom gateway values topic [`02c0a41`](https://github.com/robertsLando/Zwave2Mqtt/commit/02c0a41cff208c51f855a9b078a672c9e9c138c8)
- [docs] Custom hass persistent componets [`3e6384d`](https://github.com/robertsLando/Zwave2Mqtt/commit/3e6384d45b3e32049a041aa7b45021413560896d)
- [docs] Updated readme with node name and loc [`8d6edb3`](https://github.com/robertsLando/Zwave2Mqtt/commit/8d6edb34eb1bb47d41478f7623237993adfb68ea)
- Update issue templates [`12e9f57`](https://github.com/robertsLando/Zwave2Mqtt/commit/12e9f5742af7e965bdddd1071db72f375aebaaa0)
- [docs] Updated readme [`c0719b0`](https://github.com/robertsLando/Zwave2Mqtt/commit/c0719b0494e9125c797349db1832e683438493ce)
- [fix] Back compatibility mqtt host url [`ea79b21`](https://github.com/robertsLando/Zwave2Mqtt/commit/ea79b21d2ccfc57edfd68c1f57d9f7c0fdfdebe7)
- Update issue templates [`0031ed5`](https://github.com/robertsLando/Zwave2Mqtt/commit/0031ed5c823d1d0413288a24bab90a34122381e0)
- [fix] Add value refreshed event  support (#42) [`9b954e1`](https://github.com/robertsLando/Zwave2Mqtt/commit/9b954e1301931847adfd5415a2d6279c61fcf97d)
- [docs] Slack channel :tada: [`3979364`](https://github.com/robertsLando/Zwave2Mqtt/commit/3979364868bc55cf4848b02c8fa72f891b758d8c)
- [fix] Enable discovery when node is ready [`4c2a428`](https://github.com/robertsLando/Zwave2Mqtt/commit/4c2a428b4c35099f8a97b78b64a382009f334187)
- [fix] Typo mode valueid parsing [`60858ef`](https://github.com/robertsLando/Zwave2Mqtt/commit/60858ef188d5d0608150ce03336731a869f50f5d)
- [fix] Attentnion message [`6fd0373`](https://github.com/robertsLando/Zwave2Mqtt/commit/6fd037382ee9a8ad53ab72e028b955b4374ee353)
- [docs] Added comment to device [`9ff1c73`](https://github.com/robertsLando/Zwave2Mqtt/commit/9ff1c732b11af411df835004282d320ce6f36a74)
- [fix] Typo [`ae41909`](https://github.com/robertsLando/Zwave2Mqtt/commit/ae41909217512ca16e4d6c5a04591694703441a6)
- [fix] Typo with sensor_gas caused crash #27 [`4d04076`](https://github.com/robertsLando/Zwave2Mqtt/commit/4d04076b7e26555a80ab03a76074c55079cfeec5)
- [fix] Bug when no node configuration present [`27d704b`](https://github.com/robertsLando/Zwave2Mqtt/commit/27d704b53c05ab391f0885303f1dfe541eb38e17)
- [build] Added hass folder to packaged binary [`c33bd71`](https://github.com/robertsLando/Zwave2Mqtt/commit/c33bd71d66e8163f2544307a737f5f598bd1e287)

#### [v1.1.3](https://github.com/robertsLando/Zwave2Mqtt/compare/v1.1.2...v1.1.3)

> 27 June 2019

- [fix] Now zwave options are updated correctly (fix #19 and #14) [`#19`](https://github.com/robertsLando/Zwave2Mqtt/issues/19)
- [fix] Removed auto-changelog and release-it deps, keep them global [`b7bcaf1`](https://github.com/robertsLando/Zwave2Mqtt/commit/b7bcaf1680ed7c39ae2975752718b82bb86a7fe5)
- [feat] Key Cert and Ca support for secured mqtt [`8f28258`](https://github.com/robertsLando/Zwave2Mqtt/commit/8f28258ed0ef5e50e1541ee6d97e11e00406d4ec)
- [chore] Better commits subject parsing for changelog [`1d1edc1`](https://github.com/robertsLando/Zwave2Mqtt/commit/1d1edc137e63bc5a6449aab48dd0574836d1a8ee)
- Release 1.1.3 [`508952d`](https://github.com/robertsLando/Zwave2Mqtt/commit/508952d24cfd593a848859284d7420463ea06b98)
- [fix] Nodes count when switching flag show hidden nodes (#37) [`2292fe6`](https://github.com/robertsLando/Zwave2Mqtt/commit/2292fe6a1268b2dc92bba188d60f1a41d23f93d1)
- [Fix] ENOENT error when deleting existing zwcfg (#31) [`5e9f0ff`](https://github.com/robertsLando/Zwave2Mqtt/commit/5e9f0ff9fb35054370ca6082c5135ff5ede2828a)
- [docs] Updated changelog [`eaa6592`](https://github.com/robertsLando/Zwave2Mqtt/commit/eaa659212dadbdf5b418ad5fce9d96d21211c307)
- [docs] Updated changelog [`0cb7573`](https://github.com/robertsLando/Zwave2Mqtt/commit/0cb75731ea896f132740115c9847035422b668a5)
- [style] More user friendly value select in gateway values table [`4a08767`](https://github.com/robertsLando/Zwave2Mqtt/commit/4a087674462353be9f28642855ac4be7107560db)
- [build] Removed useless sudo from pkg script [`9e1f23d`](https://github.com/robertsLando/Zwave2Mqtt/commit/9e1f23dc61e88b5e6a1c7066cf374eb3f8f25ade)
- [style] Added app version in title [`13f16c0`](https://github.com/robertsLando/Zwave2Mqtt/commit/13f16c0d8bd37bd187af1089011b8905fec403c0)
- [docs] Updated readme [`2adc2dd`](https://github.com/robertsLando/Zwave2Mqtt/commit/2adc2dd6eebcfa292817fada90afa115a240ab1e)
- [chore] Updated release script [`2143c9a`](https://github.com/robertsLando/Zwave2Mqtt/commit/2143c9a7f5eb1c705d34e24bafcf51dd9fb7eb03)
- [chore] Add replace text regex for better auto-changelog commits parsing [`84516d2`](https://github.com/robertsLando/Zwave2Mqtt/commit/84516d2b7b9d4496e55468693d9fa6047a5e6710)
- [chore] Ready for release [`779e54f`](https://github.com/robertsLando/Zwave2Mqtt/commit/779e54f1b9f9c6ebc3ef4256ce2f9fec3a6a5342)
- [fix] Secure mqtt wrong protocol option [`ecf66e9`](https://github.com/robertsLando/Zwave2Mqtt/commit/ecf66e9b343a5985ce87f732591f1f663a105cf6)
- Release 1.1.3 [`d31bf9f`](https://github.com/robertsLando/Zwave2Mqtt/commit/d31bf9fca31729b975b29d43f6ed6a8174996a91)
- [docs] Updated readme [`e3b75e8`](https://github.com/robertsLando/Zwave2Mqtt/commit/e3b75e8b979f8e80c26a6f1a24614b44bb1c2f4f)
- [chore] Release script [`f42b24c`](https://github.com/robertsLando/Zwave2Mqtt/commit/f42b24c9bc24c7a1bf2f9b0ed71e21a8b42dd605)
- [build] Fixed broken pkg script [`78b0861`](https://github.com/robertsLando/Zwave2Mqtt/commit/78b0861fc9efd8b50945e84e2c4d77e26dc293e4)
- [docs] Fixed auto-changelog script [`76f5a18`](https://github.com/robertsLando/Zwave2Mqtt/commit/76f5a18577876cad69520edf82899e361e47fdab)
- [chore] Auto-changelog script fix [`72ec7d0`](https://github.com/robertsLando/Zwave2Mqtt/commit/72ec7d05aec01e3acbf6ca5ba613fdfd6239c40a)

#### [v1.1.2](https://github.com/robertsLando/Zwave2Mqtt/compare/v1.1.1...v1.1.2)

> 15 May 2019

- [chore] fixed missing pkg script on release [`9133fba`](https://github.com/robertsLando/Zwave2Mqtt/commit/9133fbaba0d8540c71083dcdf9f0d184eba708c4)
- [chore] updated package script [`1bdd232`](https://github.com/robertsLando/Zwave2Mqtt/commit/1bdd2326e03650f4cbae36681de9e0fe193439ab)
- Release 1.1.2 [`5a6bc46`](https://github.com/robertsLando/Zwave2Mqtt/commit/5a6bc4636412d210d0d000f59322295aa7c8e690)
- [chore] `-s` option not allowed [`972e9c3`](https://github.com/robertsLando/Zwave2Mqtt/commit/972e9c39cc5c5cdc6b422785a031a3191dde3113)
- [chore] secure token read in release [`fb1a44b`](https://github.com/robertsLando/Zwave2Mqtt/commit/fb1a44b0d8f4e0ae4d4ba8affde0a1ea7e321d3c)

#### [v1.1.1](https://github.com/robertsLando/Zwave2Mqtt/compare/1.1.0...v1.1.1)

> 15 May 2019

- [chore] release and changelog helpers [`e460617`](https://github.com/robertsLando/Zwave2Mqtt/commit/e460617f2bb516c5c2511d2e10d54be464ad9242)
- Updated docker usage section [`d508cd9`](https://github.com/robertsLando/Zwave2Mqtt/commit/d508cd9561d6f29696066d80d423c9526887411c)
- Release 1.1.1 [`7e44934`](https://github.com/robertsLando/Zwave2Mqtt/commit/7e44934fd0ce995a6ac9f83eee1f0a651cc865af)
- [chore] updated release script [`9ae17d8`](https://github.com/robertsLando/Zwave2Mqtt/commit/9ae17d8050cc6887d997fb68aabf7e578b9220e5)
- Updated Readme with deprecation warning and HASS support feature [`c6cf4ef`](https://github.com/robertsLando/Zwave2Mqtt/commit/c6cf4ef80c66a63e07c83c72ab642ddf1f4c2160)
- Add script to start docker as a service [`81efb0a`](https://github.com/robertsLando/Zwave2Mqtt/commit/81efb0a2036b3161934b74ca5786bb56c511be64)
- [chore] updated build script [`9766d78`](https://github.com/robertsLando/Zwave2Mqtt/commit/9766d78d88fbca31762c3cb844dc3cfff0ff1b92)
- [chore] updated release script [`afdd0fe`](https://github.com/robertsLando/Zwave2Mqtt/commit/afdd0fea57fa0a1b7b0142d3b0b4b2fa623b54a6)
- [chore] updated release script [`4ee9d17`](https://github.com/robertsLando/Zwave2Mqtt/commit/4ee9d1794b88963790dfc39c01d820aefbaee8a3)
- Fixed typo [`68f881d`](https://github.com/robertsLando/Zwave2Mqtt/commit/68f881d0e9f5cbf977d93664798d1d05c1a404c9)

#### [1.1.0](https://github.com/robertsLando/Zwave2Mqtt/compare/1.0.1...1.1.0)

> 4 May 2019

- Bumped version 1.1.0 [`9cc3740`](https://github.com/robertsLando/Zwave2Mqtt/commit/9cc3740740b57f1e896139b5ffdb25be7576ad58)

#### [1.0.1](https://github.com/robertsLando/Zwave2Mqtt/compare/1.0.0...1.0.1)

> 4 May 2019

- Protocol support in host url [`474e0aa`](https://github.com/robertsLando/Zwave2Mqtt/commit/474e0aa9a87d067c52824554e4363949dfa4bdb2)
- Added 'verifyChanges' flag on gateway values [`1fd4ef0`](https://github.com/robertsLando/Zwave2Mqtt/commit/1fd4ef03f410ed162610ef4afc8515b6c8577b05)
- Moved all config files in store folder [`bfb07ff`](https://github.com/robertsLando/Zwave2Mqtt/commit/bfb07ff57f27daa2e35267cf16907bea8be3b135)
- Fixed Readme [`ab5eb19`](https://github.com/robertsLando/Zwave2Mqtt/commit/ab5eb19be8b2a0f745a6f23761d8f9ff492f2239)
- Removed  double closing tag [`0decf00`](https://github.com/robertsLando/Zwave2Mqtt/commit/0decf00634e3918cdfaa0be9061947926c64dc3a)
- Docker support :tada: [`dfc2c37`](https://github.com/robertsLando/Zwave2Mqtt/commit/dfc2c3713cf5677006eff5469c54cf6b61bba3c5)
- Option to allow self signed certs on mqtt clients [`d6a9362`](https://github.com/robertsLando/Zwave2Mqtt/commit/d6a93623647550d88ac89805f503b89ad69c4ca2)
- Fixed es-lint errors on www [`59bde82`](https://github.com/robertsLando/Zwave2Mqtt/commit/59bde82bd05a7260c8a1147e3b188c06530c6480)
- Update is_polled flag on valueids #18 [`29bba97`](https://github.com/robertsLando/Zwave2Mqtt/commit/29bba9716a3ddc05ae793a50e4a45a3b081d5c8f)
- Updated to openzwave-shared@1.4.8 [`0690bfd`](https://github.com/robertsLando/Zwave2Mqtt/commit/0690bfdea9c8d41b02b393bed84c57c62ed0cf1b)
- Fixed config xml import/export [`51038c7`](https://github.com/robertsLando/Zwave2Mqtt/commit/51038c7edf3fac0d5ab1a5ad7662ff4abacc1903)
- Added alpine build [`c451ca9`](https://github.com/robertsLando/Zwave2Mqtt/commit/c451ca95c8dfb38cb94cc3862843c1dfb9fc62e0)
- Updated Readme [`f000af1`](https://github.com/robertsLando/Zwave2Mqtt/commit/f000af17a455cd78ef8985d3f8e051904457401e)
- Updated github links after ownership transfer to Openzwave org [`91f54d9`](https://github.com/robertsLando/Zwave2Mqtt/commit/91f54d9715ae436920fdfbe8054432f27f4125b9)
- Added docker badges to readme [`667adae`](https://github.com/robertsLando/Zwave2Mqtt/commit/667adae2e1e8db4233e54c08d911e28454f77500)
- Bumped version 1.0.1 [`2f9da87`](https://github.com/robertsLando/Zwave2Mqtt/commit/2f9da876ff148aa5be5dece76a1cac0115dd0c54)
- Fixed typo in README [`30a5723`](https://github.com/robertsLando/Zwave2Mqtt/commit/30a5723b5bd96e307a40187b4b700421e3279383)
- Updated pkg link in README [`24e2f96`](https://github.com/robertsLando/Zwave2Mqtt/commit/24e2f96bcd883e94cf1958ff427d5a31bdd1a989)
- Updated package script to ignore duplicates .node files [`abdcc57`](https://github.com/robertsLando/Zwave2Mqtt/commit/abdcc57f484396304e77329f7bc1b95d3db333f9)
- Update script pkg [`2925390`](https://github.com/robertsLando/Zwave2Mqtt/commit/2925390dfac6d2d9f7b5e759835c4f031cbc49c3)
- Updated README with mqtt protocol help [`e3c63cc`](https://github.com/robertsLando/Zwave2Mqtt/commit/e3c63ccb10365667320561f17b699585e25d68ac)
- Better log of 404 errors [`e8029dc`](https://github.com/robertsLando/Zwave2Mqtt/commit/e8029dc38c6cbab98b6ea60259217584db6586e9)
- Remove unused require [`e048033`](https://github.com/robertsLando/Zwave2Mqtt/commit/e048033c7b08f7272ed426a82576f2b2e6cfd43b)
- Remove unused require [`2195d53`](https://github.com/robertsLando/Zwave2Mqtt/commit/2195d53146ae96d86892a1343f7532a4d411b393)

#### [1.0.0](https://github.com/robertsLando/Zwave2Mqtt/compare/v1.0.0-beta.1...1.0.0)

> 19 March 2019

- Added callback to close #17 [`#17`](https://github.com/robertsLando/Zwave2Mqtt/issues/17)
- Detect sleeping devices using `nodeAviable` event [`#11`](https://github.com/robertsLando/Zwave2Mqtt/issues/11)
- Added 'int' missing type on valueId.vue. Should fix #10 [`#10`](https://github.com/robertsLando/Zwave2Mqtt/issues/10)
- Fix #15: topic conflicts with named topics and multi-instance devices [`#15`](https://github.com/robertsLando/Zwave2Mqtt/issues/15)
- Drawer expand/collapse fix #8 [`#8`](https://github.com/robertsLando/Zwave2Mqtt/issues/8) [`#7`](https://github.com/robertsLando/Zwave2Mqtt/issues/7)
- Don't send error if SerialPort.list fails (Fixes #6) [`#6`](https://github.com/robertsLando/Zwave2Mqtt/issues/6)
- Added support for lot more controller commands [`82a59a9`](https://github.com/robertsLando/Zwave2Mqtt/commit/82a59a9d1c98c5072ea80752a6c9d0ed36957522)
- Custom config path option in zwave settings [`1840bef`](https://github.com/robertsLando/Zwave2Mqtt/commit/1840bef82ae786fd2adf6becb99619950cb5e356)
- Updated gateway logic. Now values table is always visible [`95bd0aa`](https://github.com/robertsLando/Zwave2Mqtt/commit/95bd0aaaeb0e2146ab82b7d9f57c3e85c14594e2)
- Convert value based on valueID type [`499ea83`](https://github.com/robertsLando/Zwave2Mqtt/commit/499ea83a286b5d8e09fed1cec9d5519ae1bbca61)
- Updated README.md [`312ddd1`](https://github.com/robertsLando/Zwave2Mqtt/commit/312ddd1860afad0814c6d885f1e6fe65318be9ee)
- Working on better support of broadcast commands [`1b52539`](https://github.com/robertsLando/Zwave2Mqtt/commit/1b525399a48a020ab580f3edb83abcb76a3a6fa9)
- Update groups on nodes added after scan complete event [`9811c67`](https://github.com/robertsLando/Zwave2Mqtt/commit/9811c674eb5ca7321941d2a4a11bc66ac8413af6)
- Added Test network and test node functions [`259b295`](https://github.com/robertsLando/Zwave2Mqtt/commit/259b2953dc5d0ebeff4beeb58862b3f2e125d5cb)
- Fixed duplicated messages when restarting client #17 [`f88f607`](https://github.com/robertsLando/Zwave2Mqtt/commit/f88f60773025ceb9d5891fa3a7c35906c44d9387)
- Parse value on Valueadded event (and little bug fix) [`1637b3a`](https://github.com/robertsLando/Zwave2Mqtt/commit/1637b3af46e75cd778a6b15b6a0d5deeda8202e9)
- Updated README [`2d25ac5`](https://github.com/robertsLando/Zwave2Mqtt/commit/2d25ac5ea9be155a1c3df616ac6d741ae5adbd6d)
- Show snackbar error if socket is disconnected when try to call api [`150981f`](https://github.com/robertsLando/Zwave2Mqtt/commit/150981facee262606ad5e1fefc14d5b0c1244361)
- Set disconnect timeout to 2 sec #17 [`c5057c6`](https://github.com/robertsLando/Zwave2Mqtt/commit/c5057c601d5b653f967bb0bf67a6217decae46a6)
- Send NIF frame when scan is completed to ndoes that are not ready [`ed6acb0`](https://github.com/robertsLando/Zwave2Mqtt/commit/ed6acb0929dde014d821fbcca32916e1677ae384)
- Added AssumeAwake option to zwave settings [`88698bd`](https://github.com/robertsLando/Zwave2Mqtt/commit/88698bdc1d7f77c7d8d256b829b69c85f1b2b58c)
- Added functions to controller for inclusion/exclusion [`c8c3ae2`](https://github.com/robertsLando/Zwave2Mqtt/commit/c8c3ae28a6fec0b35fee85900a74e54d0fa5d1b7)
- Removed NIF on scan complete and added event nodeAvailable [`bdc29ec`](https://github.com/robertsLando/Zwave2Mqtt/commit/bdc29ecb218476819556154393fc662432b73861)
- Eval operation even if no topic specified [`66272ad`](https://github.com/robertsLando/Zwave2Mqtt/commit/66272ad2664706480ebd7766693b784d71b776a7)
- Make dialogs peristent to prevent Vue error [`fde4211`](https://github.com/robertsLando/Zwave2Mqtt/commit/fde421176379400013ea1c920fb4e8cce8b46308)
- Updated README [`7b7a742`](https://github.com/robertsLando/Zwave2Mqtt/commit/7b7a7423f7ed60ff6199b4c3f6bbc157d50a1ea2)
- Updated readme with last pkg version [`0554eac`](https://github.com/robertsLando/Zwave2Mqtt/commit/0554eac8d86d602bff28ae8b3ba83786cb6a96a0)
- Fix error 'undefined' config.values (#5) [`24e9631`](https://github.com/robertsLando/Zwave2Mqtt/commit/24e963184dca9be1bce56323aaa6b52565da7a40)
- Removed date string from prefix on logs in UI [`a79c526`](https://github.com/robertsLando/Zwave2Mqtt/commit/a79c526f9fe3abe43a3759b8ef37ee170e8d3fe3)
- Removed blank lines [`8ae8438`](https://github.com/robertsLando/Zwave2Mqtt/commit/8ae84389261ef6ab461135ef9948e253f421001f)

#### v1.0.0-beta.1

> 30 January 2019

- Initial commit [`ed66c7a`](https://github.com/robertsLando/Zwave2Mqtt/commit/ed66c7a638c09b588c86332c32342ee9235dcf41)
- First working implementation of publish/subscribe [`834ae97`](https://github.com/robertsLando/Zwave2Mqtt/commit/834ae979cd0bc38b82766c3c5590630bdb4be20b)
- Control panel and socket management [`b7ec431`](https://github.com/robertsLando/Zwave2Mqtt/commit/b7ec4311d5e7db291636f4cd804ebd88921dec9d)
- Setting up main structure [`9d0c799`](https://github.com/robertsLando/Zwave2Mqtt/commit/9d0c79981e47d1999160b821632c9c9ff5924801)
- Check if value is polled before enable polling [`808d342`](https://github.com/robertsLando/Zwave2Mqtt/commit/808d3427fd23493cc6cd87ba583567352411f150)
- Updated icons [`1ea90bf`](https://github.com/robertsLando/Zwave2Mqtt/commit/1ea90bf1f760bb54d8506ec1e30e8bd1241cb477)
- Broadcast improvments and api calls via mqtt [`0e2647c`](https://github.com/robertsLando/Zwave2Mqtt/commit/0e2647cdb49823a6ce4afe3258cbc6f2eb96e75d)
- Scene support (need work) [`6d87d5f`](https://github.com/robertsLando/Zwave2Mqtt/commit/6d87d5f30d7eebcb3373f38db47c3864f2353365)
- Custom scene management with values timeout [`ea9fca5`](https://github.com/robertsLando/Zwave2Mqtt/commit/ea9fca5a24c88898c83e03da308c57dec1948561)
- Better logging with debug module [`869d3dc`](https://github.com/robertsLando/Zwave2Mqtt/commit/869d3dcbe4378fac27da86851926148d638bc56c)
- Import/Export scenes [`dc7a4fe`](https://github.com/robertsLando/Zwave2Mqtt/commit/dc7a4fe6018184a6748855e5d8334883e02c1962)
- Fixed scenes management and started refactoring code [`07e3838`](https://github.com/robertsLando/Zwave2Mqtt/commit/07e383817e1506baf42e51adf35db2e42891a61d)
- Updated README [`12af1ac`](https://github.com/robertsLando/Zwave2Mqtt/commit/12af1ac6811ff2030c89048654b52aca4f3d2994)
- Removed unused routes and starting pkg support [`2683e19`](https://github.com/robertsLando/Zwave2Mqtt/commit/2683e196c81702591c266dd21cbc32b7c29a3afe)
- Updated README [`ad297e0`](https://github.com/robertsLando/Zwave2Mqtt/commit/ad297e0597042a348b6bd1a9275e3b0c5eea7fb5)
- Initial commit [`db5c17d`](https://github.com/robertsLando/Zwave2Mqtt/commit/db5c17d542f717211172b3cc7011bdf5f5837fc0)
- Inited readme [`2807782`](https://github.com/robertsLando/Zwave2Mqtt/commit/2807782131900ee23f9f7ecd562126edcae4c625)
- Debug tab [`4392976`](https://github.com/robertsLando/Zwave2Mqtt/commit/4392976ac13b4ffadce2058398f5a6af40850e4c)
- Fix bug on start when no configuration is present [`4081147`](https://github.com/robertsLando/Zwave2Mqtt/commit/40811470c521836064d945837a97c14e68616daf)
- Fixed some typos in Readme and added some emojy [`937ea43`](https://github.com/robertsLando/Zwave2Mqtt/commit/937ea43f80d5dcd93ed57cf33dea3545cd0e6f3d)
- Fixed bug value not set correctly in payload [`20ced2e`](https://github.com/robertsLando/Zwave2Mqtt/commit/20ced2e6b8fa746d1f6aed3f12c287e782841580)
- Updated README [`00cea67`](https://github.com/robertsLando/Zwave2Mqtt/commit/00cea672d8705aa131011781546a3fe9700c760a)
- Handle value update [`948b39a`](https://github.com/robertsLando/Zwave2Mqtt/commit/948b39a1d781de7a84376eb650a5261dc4d4659c)
- Updated readme [`176aede`](https://github.com/robertsLando/Zwave2Mqtt/commit/176aede2219546b7bdbf21280323d57fd2c8308b)
- Better log colors and enabled debug by default [`20592b0`](https://github.com/robertsLando/Zwave2Mqtt/commit/20592b09181841fc36b2251647cebb62a57e4f1b)
- Updated webpack-dev-server and openzwave-shared packages [`0b56981`](https://github.com/robertsLando/Zwave2Mqtt/commit/0b56981bf30856db759a92ff106f67b4c252f1df)
- Updated README [`5ec5425`](https://github.com/robertsLando/Zwave2Mqtt/commit/5ec54253e4042d61f2a901140b1deffd5648948b)
- Updated Readme with new server dev start [`50ff268`](https://github.com/robertsLando/Zwave2Mqtt/commit/50ff2680948cb34460c49c4e5bae9a7c80d6cdaa)
- Added TODOs and fixed some typos [`8fdb485`](https://github.com/robertsLando/Zwave2Mqtt/commit/8fdb4859b203810f89463a2ac2e62ea2114c5fa3)
- Fixed markdown for TODOs [`f94313b`](https://github.com/robertsLando/Zwave2Mqtt/commit/f94313bf075b92460bb0011d2229f2cdfe806d56)
- Add debug on Gateway [`01d5afc`](https://github.com/robertsLando/Zwave2Mqtt/commit/01d5afce785305f3b9b553bdc89feed6fffa03b0)
- Updated README.md [`a75e280`](https://github.com/robertsLando/Zwave2Mqtt/commit/a75e280b88e7551395d68c5b87b33cb1fa0a18a4)
- Fixed typo in README [`b09ad26`](https://github.com/robertsLando/Zwave2Mqtt/commit/b09ad260d47a963c5be43258ecf40f33bfba9be5)
- Added TODOs section [`6e36951`](https://github.com/robertsLando/Zwave2Mqtt/commit/6e36951d239f73c7a55854eaaf2cc14ca1f37656)
- Updated wget link for pkg version [`8f20706`](https://github.com/robertsLando/Zwave2Mqtt/commit/8f20706cfee7d2f6cb7b7d00b44a3e5ac0d48c9d)
- Ignore pkg folder [`58076c6`](https://github.com/robertsLando/Zwave2Mqtt/commit/58076c66875ea0ea4d3d6ec7d1c199cb86ec393a)
- Ignore store folder [`2532ad3`](https://github.com/robertsLando/Zwave2Mqtt/commit/2532ad3e21f4dff6bab1ce3ec1190e478af06d59)
- Added developing note [`2d1579c`](https://github.com/robertsLando/Zwave2Mqtt/commit/2d1579c628eda49a0a29d8ff8a6d068687fd3b50)