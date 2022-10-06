# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## 14.0.0 (2022-10-06)

### Features

- **coverage:** add coverage reports ([43e340a](https://github.com/material-extended/mde/commit/43e340ac814f35e2da05a59fce2bd33872c4412a))
- **coverage:** add coverage reports ([1cb6fef](https://github.com/material-extended/mde/commit/1cb6fef558c49b2891aa2cf8c578c2469fb74771))
- **demo:** add cdkFocusInitial ([5b530fd](https://github.com/material-extended/mde/commit/5b530fde67a1aa67e8e46e48d1cf80caf4d7e02a))
- **demo:** add mdePopoverBackdropCloseOnClick option ([eb4a881](https://github.com/material-extended/mde/commit/eb4a881b6ba8aaa79fd45a3014ae264d200c6841))
- **MdePopoverTrigger:** add mdePopoverBackdropCloseOnClick option, closes [#36](https://github.com/material-extended/mde/issues/36) ([9164650](https://github.com/material-extended/mde/commit/916465030a09b4db4c7a7e3990a3e9bdb3d24d23))
- **popover:** add disableAnimation option ([#46](https://github.com/material-extended/mde/issues/46)) ([76c4812](https://github.com/material-extended/mde/commit/76c48122488002648e7d31082dca4439e2648293))
- **popover:** add mdeFocusTrapAutoCaptureEnabled option ([4802a96](https://github.com/material-extended/mde/commit/4802a96f10e7c163167c9fe15b3e5e8379528c73))

### Bug Fixes

- **build:** fixed a problem with the UMD build, issue [#2](https://github.com/material-extended/mde/issues/2) ([e557e72](https://github.com/material-extended/mde/commit/e557e72a64766ad3e9970d1958fec8ddce0d3fa9))
- **build:** include secondary entry-points of the CDK package ([fa1bbf3](https://github.com/material-extended/mde/commit/fa1bbf3be9ce1394b3cf1d2c2fca9ade263cfbe7))
- **build:** include secondary entry-points of the CDK package ([2726c7b](https://github.com/material-extended/mde/commit/2726c7be7a85be711484f698f63a7d7e832269b1))
- **demo:** fix theme issue ([0834817](https://github.com/material-extended/mde/commit/08348171284818871b42c9032090a9fd57d4355b))
- **docs:** fix incorrect component name ([0939cb6](https://github.com/material-extended/mde/commit/0939cb63d8b5d2d000060b411cca278873f854c3))
- **docs:** update popover documentation link ([a2636f4](https://github.com/material-extended/mde/commit/a2636f421e68e017e556102c53f53553c91a012e))
- **export:** remove export causing problem ([5144b19](https://github.com/material-extended/mde/commit/5144b19aa98cac86a7c0db0bdfbcab84e37b4275))
- **exports:** export all ([1920ee8](https://github.com/material-extended/mde/commit/1920ee856f7d0f1fae6c2cbb183acba11e09ee4f))
- **library:** add missing peer dependency @angular/animations ([78ab045](https://github.com/material-extended/mde/commit/78ab04524242f2312a79d59e6bbaf28c06ecfadb))
- **MdePopoverTrigger:** change \_elementRef to public ([b5e9867](https://github.com/material-extended/mde/commit/b5e98676d3957278b6b53232198cbf6f2c64230c))
- **MdePopoverTrigger:** fix compile errors in 'fullTemplateTypeCheck' mode, closes [#25](https://github.com/material-extended/mde/issues/25) ([1fdf413](https://github.com/material-extended/mde/commit/1fdf413d7f992f758452723c9cd36bf1c2c85b0a))
- **MdePopoverTrigger:** remove mouseoverTimer on destroyPopover, closes [#34](https://github.com/material-extended/mde/issues/34) ([674b4e2](https://github.com/material-extended/mde/commit/674b4e2cc6ecd127c1ad9a33bacc7dc7c59b24cf))
- **overlay:** OverlayState has been renamed to OverlayConfig in CDK ([0103c0f](https://github.com/material-extended/mde/commit/0103c0f171f86c2d199e75fa232876fd05041886))
- **popover:** add markForCheck for onpush strategy fixes [#57](https://github.com/material-extended/mde/issues/57) ([3af3b62](https://github.com/material-extended/mde/commit/3af3b62bbb24ee5ea8d42883c9921b5100da94f9))
- **popover:** arrow orientation on first popover opening fix ([#45](https://github.com/material-extended/mde/issues/45)) ([488d556](https://github.com/material-extended/mde/commit/488d556ae881b39efa4656797d1ad3caabc5349b))
- **popover:** event undefined with \_handleMousedown [#26](https://github.com/material-extended/mde/issues/26) ([9eb7391](https://github.com/material-extended/mde/commit/9eb739149e30bcf0a88d1d84b9f8600d18aa89ce))
- **popover:** fix CdkTrapFocus issue [#48](https://github.com/material-extended/mde/issues/48) ([#52](https://github.com/material-extended/mde/issues/52)) ([03cd7f1](https://github.com/material-extended/mde/commit/03cd7f110e9be202182778ae6ccc2c324bb8753e))
- **popover:** fixed multiple popover issue [#4](https://github.com/material-extended/mde/issues/4) ([92c9f40](https://github.com/material-extended/mde/commit/92c9f409885af7d48d64cbc9bc344f6ddd7a9892))
- **popover:** fixed multiple popovers issue [#2](https://github.com/material-extended/mde/issues/2) ([0c474bc](https://github.com/material-extended/mde/commit/0c474bc00683a3ca239aa388ca7d2a353f4fd93c))
- **popover:** set \_classList to public issue [#21](https://github.com/material-extended/mde/issues/21) ([2d07731](https://github.com/material-extended/mde/commit/2d07731acef671ec772d722bbfbd42a460b8b265))
- **popover:** update to use panelClass ([204383e](https://github.com/material-extended/mde/commit/204383e9f80c5e223df18acd34c8fd83dd4a83f8))
- **propover-errors:** correct error messages with new API names ([0555468](https://github.com/material-extended/mde/commit/055546830facf5264910db86daca351ae76dc97b))
- **rxjs:** fix rxjs errors related to not exposed module ([4efbcd0](https://github.com/material-extended/mde/commit/4efbcd001f0c61fe5bce58e070bb66d096e99466))

### [3.0.3](https://github.com/material-extended/mde/compare/v3.0.1...v3.0.3) (2020-06-10)

### [3.0.1](https://github.com/material-extended/mde/compare/v3.0.0...v3.0.1) (2020-06-10)

## [3.0.0](https://github.com/material-extended/mde/compare/v2.3.1...v3.0.0) (2020-02-12)

### [2.3.1](https://github.com/material-extended/mde/compare/v2.3.0...v2.3.1) (2019-07-18)

### Bug Fixes

- **popover:** add markForCheck for onpush strategy fixes [#57](https://github.com/material-extended/mde/issues/57) ([3af3b62](https://github.com/material-extended/mde/commit/3af3b62))

## [2.3.0](https://github.com/material-extended/mde/compare/v2.2.2...v2.3.0) (2019-06-28)

### Bug Fixes

- **demo:** fix theme issue ([0834817](https://github.com/material-extended/mde/commit/0834817))
- **popover:** fix CdkTrapFocus issue [#48](https://github.com/material-extended/mde/issues/48) ([#52](https://github.com/material-extended/mde/issues/52)) ([03cd7f1](https://github.com/material-extended/mde/commit/03cd7f1))

### Features

- **demo:** add cdkFocusInitial ([5b530fd](https://github.com/material-extended/mde/commit/5b530fd))
- **popover:** add mdeFocusTrapAutoCaptureEnabled option ([4802a96](https://github.com/material-extended/mde/commit/4802a96))

### [2.2.2](https://github.com/material-extended/mde/compare/v2.2.0...v2.2.2) (2019-06-02)

### [2.2.1](https://github.com/material-extended/mde/compare/v2.2.0...v2.2.1) (2019-06-02)

### Update

- **popover:** Update to Angular 8 ([106b051](https://github.com/material-extended/mde/commit/106b051))

<a name="2.2.0"></a>

## [2.2.0](https://github.com/material-extended/mde/compare/v2.1.1...v2.2.0) (2019-05-14)

### Bug Fixes

- **popover:** arrow orientation on first popover opening fix ([#45](https://github.com/material-extended/mde/issues/45)) ([488d556](https://github.com/material-extended/mde/commit/488d556))

### Features

- **popover:** add disableAnimation option ([#46](https://github.com/material-extended/mde/issues/46)) ([76c4812](https://github.com/material-extended/mde/commit/76c4812))

<a name="2.1.1"></a>

## [2.1.1](https://github.com/material-extended/mde/compare/v2.1.0...v2.1.1) (2018-12-11)

<a name="2.1.0"></a>

# [2.1.0](https://github.com/material-extended/mde/compare/v2.0.3...v2.1.0) (2018-09-15)

### Features

- **demo:** add mdePopoverBackdropCloseOnClick option ([eb4a881](https://github.com/material-extended/mde/commit/eb4a881))
- **MdePopoverTrigger:** add mdePopoverBackdropCloseOnClick option, closes [#36](https://github.com/material-extended/mde/issues/36) ([9164650](https://github.com/material-extended/mde/commit/9164650))

<a name="2.0.3"></a>

## [2.0.3](https://github.com/material-extended/mde/compare/v1.0.0-alpha.10...v2.0.3) (2018-09-15)

### Bug Fixes

- **library:** add missing peer dependency [@angular](https://github.com/angular)/animations ([78ab045](https://github.com/material-extended/mde/commit/78ab045))
- **MdePopoverTrigger:** fix compile errors in 'fullTemplateTypeCheck' mode, closes [#25](https://github.com/material-extended/mde/issues/25) ([1fdf413](https://github.com/material-extended/mde/commit/1fdf413))
- **MdePopoverTrigger:** remove mouseoverTimer on destroyPopover, closes [#34](https://github.com/material-extended/mde/issues/34) ([674b4e2](https://github.com/material-extended/mde/commit/674b4e2))
- **popover:** event undefined with \_handleMousedown [#26](https://github.com/material-extended/mde/issues/26) ([9eb7391](https://github.com/material-extended/mde/commit/9eb7391))

<a name="2.0.2"></a>

## [2.0.2](https://github.com/material-extended/mde/compare/v2.0.1...v2.0.2) (2018-08-15)

### Bug Fixes

- **MdePopoverTrigger:** fix compile errors in 'fullTemplateTypeCheck' mode, closes [#25](https://github.com/material-extended/mde/issues/25) ([1fdf413](https://github.com/material-extended/mde/commit/1fdf413))

<a name="2.0.1"></a>

## [2.0.1](https://github.com/material-extended/mde/compare/v2.0.0...v2.0.1) (2018-05-24)

### Bug Fixes

- **library:** add missing peer dependency [@angular](https://github.com/angular)/animations ([78ab045](https://github.com/material-extended/mde/commit/78ab045))
- **popover:** event undefined with \_handleMousedown [#26](https://github.com/material-extended/mde/issues/26) ([9eb7391](https://github.com/material-extended/mde/commit/9eb7391))

<a name="2.0.0"></a>

# [2.0.0](https://github.com/material-extended/mde/compare/v1.0.0-alpha.10...v2.0.0) (2018-05-18)

<a name="1.0.0-alpha.10"></a>

# [1.0.0-alpha.10](https://github.com/material-extended/mde/compare/v1.0.0-alpha.9...v1.0.0-alpha.10) (2018-02-22)

<a name="1.0.0-alpha.9"></a>

# [1.0.0-alpha.9](https://github.com/material-extended/mde/compare/v1.0.0-alpha.8...v1.0.0-alpha.9) (2018-02-22)

<a name="1.0.0-alpha.8"></a>

# [1.0.0-alpha.8](https://github.com/material-extended/mde/compare/v1.0.0-alpha.7...v1.0.0-alpha.8) (2018-02-22)

<a name="1.0.0-alpha.7"></a>

# [1.0.0-alpha.7](https://github.com/material-extended/mde/compare/v1.0.0-alpha.6...v1.0.0-alpha.7) (2018-02-22)

### Bug Fixes

- **popover:** set \_classList to public issue [#21](https://github.com/material-extended/mde/issues/21) ([2d07731](https://github.com/material-extended/mde/commit/2d07731))
- **popover:** update to use panelClass ([204383e](https://github.com/material-extended/mde/commit/204383e))

<a name="1.0.0-alpha.6"></a>

# [1.0.0-alpha.6](https://github.com/material-extended/mde/compare/v1.0.0-alpha.5...v1.0.0-alpha.6) (2017-11-13)

### Bug Fixes

- **MdePopoverTrigger:** change \_elementRef to public ([b5e9867](https://github.com/material-extended/mde/commit/b5e9867))

<a name="1.0.0-alpha.5"></a>

# [1.0.0-alpha.5](https://github.com/material-extended/mde/compare/v1.0.0-alpha.4...v1.0.0-alpha.5) (2017-11-08)

<a name="1.0.0-alpha.4"></a>

# [1.0.0-alpha.4](https://github.com/material-extended/mde/compare/v1.0.0-alpha.3...v1.0.0-alpha.4) (2017-09-22)

### Bug Fixes

- **docs:** fix incorrect component name ([0939cb6](https://github.com/material-extended/mde/commit/0939cb6))
- **docs:** update popover documentation link ([a2636f4](https://github.com/material-extended/mde/commit/a2636f4))
- **overlay:** OverlayState has been renamed to OverlayConfig in CDK ([0103c0f](https://github.com/material-extended/mde/commit/0103c0f))

<a name="1.0.0-alpha.3"></a>

# [1.0.0-alpha.3](https://github.com/material-extended/mde/compare/v1.0.0-alpha.2...v1.0.0-alpha.3) (2017-09-04)

<a name="1.0.0-alpha.2"></a>

# [1.0.0-alpha.2](https://github.com/material-extended/mde/compare/v1.0.0-alpha.1...v1.0.0-alpha.2) (2017-09-04)

### Bug Fixes

- **build:** include secondary entry-points of the CDK package ([fa1bbf3](https://github.com/material-extended/mde/commit/fa1bbf3))

<a name="1.0.0-alpha.1"></a>

# [1.0.0-alpha.1](https://github.com/material-extended/mde/compare/v1.0.0-alpha.0...v1.0.0-alpha.1) (2017-09-04)

### Bug Fixes

- **build:** include secondary entry-points of the CDK package ([2726c7b](https://github.com/material-extended/mde/commit/2726c7b))

<a name="1.0.0-alpha.0"></a>

# [1.0.0-alpha.0](https://github.com/material-extended/mde/compare/v0.1.0-alpha.13...v1.0.0-alpha.0) (2017-08-31)

<a name="0.1.0-alpha.13"></a>

# [0.1.0-alpha.13](https://github.com/material-extended/mde/compare/v0.1.0-alpha.11...v0.1.0-alpha.13) (2017-08-31)

### Bug Fixes

- **export:** remove export causing problem ([5144b19](https://github.com/material-extended/mde/commit/5144b19))

<a name="0.1.0-alpha.12"></a>

# [0.1.0-alpha.12](https://github.com/material-extended/mde/compare/v0.1.0-alpha.11...v0.1.0-alpha.12) (2017-08-31)

### Bug Fixes

- **export:** remove export causing problem ([5144b19](https://github.com/material-extended/mde/commit/5144b19))

<a name="0.1.0-alpha.11"></a>

# [0.1.0-alpha.11](https://github.com/material-extended/mde/compare/v0.1.0-alpha.10...v0.1.0-alpha.11) (2017-08-08)

<a name="0.1.0-alpha.10"></a>

# [0.1.0-alpha.10](https://github.com/material-extended/mde/compare/v0.1.0-alpha.9...v0.1.0-alpha.10) (2017-08-07)

### Bug Fixes

- **exports:** export all ([1920ee8](https://github.com/material-extended/mde/commit/1920ee8))

<a name="0.1.0-alpha.9"></a>

# [0.1.0-alpha.9](https://github.com/material-extended/mde/compare/v0.1.0-alpha.8...v0.1.0-alpha.9) (2017-08-07)

<a name="0.1.0-alpha.8"></a>

# [0.1.0-alpha.8](https://github.com/material-extended/mde/compare/v0.1.0-alpha.7...v0.1.0-alpha.8) (2017-07-26)

### Bug Fixes

- **popover:** fixed multiple popover issue [#4](https://github.com/material-extended/mde/issues/4) ([92c9f40](https://github.com/material-extended/mde/commit/92c9f40))

<a name="0.1.0-alpha.7"></a>

# [0.1.0-alpha.7](https://github.com/material-extended/mde/compare/v0.1.0-alpha.6...v0.1.0-alpha.7) (2017-07-24)

### Bug Fixes

- **build:** fixed a problem with the UMD build, issue [#2](https://github.com/material-extended/mde/issues/2) ([e557e72](https://github.com/material-extended/mde/commit/e557e72))

<a name="0.1.0-alpha.6"></a>

# [0.1.0-alpha.6](https://github.com/material-extended/mde/compare/v0.1.0-alpha.5...v0.1.0-alpha.6) (2017-07-21)

### Bug Fixes

- **popover:** fixed multiple popovers issue [#2](https://github.com/material-extended/mde/issues/2) ([0c474bc](https://github.com/material-extended/mde/commit/0c474bc))

<a name="0.1.0-alpha.5"></a>

# [0.1.0-alpha.5](https://github.com/material-extended/mde/compare/v0.1.0-alpha.4...v0.1.0-alpha.5) (2017-07-20)

### Bug Fixes

- **propover-errors:** correct error messages with new API names ([0555468](https://github.com/material-extended/mde/commit/0555468))

<a name="0.1.0-alpha.4"></a>

# [0.1.0-alpha.4](https://github.com/material-extended/mde/compare/v0.1.0-alpha.3...v0.1.0-alpha.4) (2017-07-20)

### Bug Fixes

- **rxjs:** fix rxjs errors related to not exposed module ([4efbcd0](https://github.com/material-extended/mde/commit/4efbcd0))

### Features

- **coverage:** add coverage reports ([43e340a](https://github.com/material-extended/mde/commit/43e340a))
- **coverage:** add coverage reports ([1cb6fef](https://github.com/material-extended/mde/commit/1cb6fef))

<a name="0.1.0-alpha.3"></a>

# [0.1.0-alpha.3](https://github.com/material-extended/mde/compare/v0.1.0-alpha.2...v0.1.0-alpha.3) (2017-07-14)

<a name="0.1.0-alpha.2"></a>

# [0.1.0-alpha.2](https://github.com/material-extended/mde/compare/v0.1.0-alpha.1...v0.1.0-alpha.2) (2017-07-13)

<a name="0.1.0-alpha.1"></a>

# [0.1.0-alpha.1](https://github.com/material-extended/mde/compare/v0.1.0-alpha.0...v0.1.0-alpha.1) (2017-07-13)

<a name="0.1.0-alpha.0"></a>

# 0.1.0-alpha.0 (2017-07-13)
