# Changelog

## [v0.3.0](https://github.com/napari/superqt/tree/v0.3.0) (2022-02-16)

[Full Changelog](https://github.com/napari/superqt/compare/v0.2.5-1...v0.3.0)

**Implemented enhancements:**

- Qthrottler and debouncer [\#62](https://github.com/napari/superqt/pull/62) ([tlambert03](https://github.com/tlambert03))
- add edgeLabelMode option to QLabeledSlider [\#59](https://github.com/napari/superqt/pull/59) ([tlambert03](https://github.com/tlambert03))

**Fixed bugs:**

- Fix nested threadworker not starting [\#63](https://github.com/napari/superqt/pull/63) ([tlambert03](https://github.com/tlambert03))
- Add missing signals on proxy sliders  [\#54](https://github.com/napari/superqt/pull/54) ([tlambert03](https://github.com/tlambert03))
- Ugly but functional workaround for pyside6.2.1 breakages [\#51](https://github.com/napari/superqt/pull/51) ([tlambert03](https://github.com/tlambert03))

**Tests & CI:**

- add napari test to CI [\#67](https://github.com/napari/superqt/pull/67) ([tlambert03](https://github.com/tlambert03))
- add gh-release action [\#65](https://github.com/napari/superqt/pull/65) ([tlambert03](https://github.com/tlambert03))
- fix xvfb tests [\#61](https://github.com/napari/superqt/pull/61) ([tlambert03](https://github.com/tlambert03))

**Refactors:**

- Use qtpy, deprecate superqt.qtcompat, drop support for Qt \<5.12 [\#39](https://github.com/napari/superqt/pull/39) ([tlambert03](https://github.com/tlambert03))

## [v0.2.5-1](https://github.com/napari/superqt/tree/v0.2.5-1) (2021-11-23)

[Full Changelog](https://github.com/napari/superqt/compare/v0.2.5...v0.2.5-1)

**Merged pull requests:**

- typing-extensions version pinning [\#46](https://github.com/napari/superqt/pull/46) ([AhmetCanSolak](https://github.com/AhmetCanSolak))

## [v0.2.5](https://github.com/napari/superqt/tree/v0.2.5) (2021-11-22)

[Full Changelog](https://github.com/napari/superqt/compare/v0.2.4...v0.2.5)

**Implemented enhancements:**

- add support for python 3.10 [\#42](https://github.com/napari/superqt/pull/42) ([tlambert03](https://github.com/tlambert03))
- QCollapsible for Collapsible Section Control [\#37](https://github.com/napari/superqt/pull/37) ([MosGeo](https://github.com/MosGeo))
- Threadworker [\#31](https://github.com/napari/superqt/pull/31) ([tlambert03](https://github.com/tlambert03))
- Add font icons [\#24](https://github.com/napari/superqt/pull/24) ([tlambert03](https://github.com/tlambert03))

**Fixed bugs:**

- Fix some small linting issues. [\#41](https://github.com/napari/superqt/pull/41) ([tlambert03](https://github.com/tlambert03))
- Use functools.wraps insterad of \_\_wraped\_\_ and manual proxing \_\_name\_\_ [\#29](https://github.com/napari/superqt/pull/29) ([Czaki](https://github.com/Czaki))
- Propagate function name in `ensure_main_thread` and `ensure_object_thread` [\#28](https://github.com/napari/superqt/pull/28) ([Czaki](https://github.com/Czaki))

**Tests & CI:**

- reskip test\_object\_thread\_return on ci [\#43](https://github.com/napari/superqt/pull/43) ([tlambert03](https://github.com/tlambert03))

**Refactors:**

- refactoring qtcompat [\#34](https://github.com/napari/superqt/pull/34) ([tlambert03](https://github.com/tlambert03))

**Merged pull requests:**

- Fix-manifest, move font tests [\#44](https://github.com/napari/superqt/pull/44) ([tlambert03](https://github.com/tlambert03))
- update deploy [\#33](https://github.com/napari/superqt/pull/33) ([tlambert03](https://github.com/tlambert03))
- move to src layout [\#32](https://github.com/napari/superqt/pull/32) ([tlambert03](https://github.com/tlambert03))

## [v0.2.4](https://github.com/napari/superqt/tree/v0.2.4) (2021-09-13)

[Full Changelog](https://github.com/napari/superqt/compare/v0.2.3...v0.2.4)

**Implemented enhancements:**

- Add type stubs for ensure\_thread decorator [\#23](https://github.com/napari/superqt/pull/23) ([tlambert03](https://github.com/tlambert03))
- Add `ensure_main_tread` and `ensure_object_thread` [\#22](https://github.com/napari/superqt/pull/22) ([Czaki](https://github.com/Czaki))
- Add QMessageHandler context manager [\#21](https://github.com/napari/superqt/pull/21) ([tlambert03](https://github.com/tlambert03))

**Merged pull requests:**

- add changelog for 0.2.4 [\#25](https://github.com/napari/superqt/pull/25) ([tlambert03](https://github.com/tlambert03))

## [v0.2.3](https://github.com/napari/superqt/tree/v0.2.3) (2021-08-25)

[Full Changelog](https://github.com/napari/superqt/compare/v0.2.2...v0.2.3)

**Fixed bugs:**

- Fix warnings on eliding label for 5.12, test more qt versions [\#19](https://github.com/napari/superqt/pull/19) ([tlambert03](https://github.com/tlambert03))

## [v0.2.2](https://github.com/napari/superqt/tree/v0.2.2) (2021-08-17)

[Full Changelog](https://github.com/napari/superqt/compare/v0.2.1...v0.2.2)

**Implemented enhancements:**

- Add QElidingLabel [\#16](https://github.com/napari/superqt/pull/16) ([tlambert03](https://github.com/tlambert03))
- Enum ComboBox implementation [\#13](https://github.com/napari/superqt/pull/13) ([Czaki](https://github.com/Czaki))

**Documentation updates:**

- fix broken link [\#18](https://github.com/napari/superqt/pull/18) ([haesleinhuepf](https://github.com/haesleinhuepf))

## [v0.2.1](https://github.com/napari/superqt/tree/v0.2.1) (2021-07-10)

[Full Changelog](https://github.com/napari/superqt/compare/v0.2.0rc0...v0.2.1)

**Fixed bugs:**

- Fix QLabeledRangeSlider API \(fix slider proxy\) [\#10](https://github.com/napari/superqt/pull/10) ([tlambert03](https://github.com/tlambert03))
- Fix range slider with negative min range [\#9](https://github.com/napari/superqt/pull/9) ([tlambert03](https://github.com/tlambert03))

## [v0.2.0rc0](https://github.com/napari/superqt/tree/v0.2.0rc0) (2021-06-26)

[Full Changelog](https://github.com/napari/superqt/compare/v0.2.0...v0.2.0rc0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
