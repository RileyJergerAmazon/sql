opensearch-sql 3.2.0 Release Notes

# OpenSearch SQL 3.2.0 Release Notes

## Features
* Add ClickBench IT Suite ([#3860](https://github.com/RileyJergerAmazon/sql/pull/3860))
* Add big5 to IT Suite ([#3822](https://github.com/RileyJergerAmazon/sql/pull/3822))
* Add compare_ip operator udfs ([#3821](https://github.com/RileyJergerAmazon/sql/pull/3821))
* Support Sort pushdown ([#3620](https://github.com/RileyJergerAmazon/sql/pull/3620))
* Support filter push down for Sarg value ([#3840](https://github.com/RileyJergerAmazon/sql/pull/3840))
* Support pushdown physical sort operator to speedup SortMergeJoin ([#3864](https://github.com/RileyJergerAmazon/sql/pull/3864))
* Support relevance query functions pushdown implementation in Calcite ([#3834](https://github.com/RileyJergerAmazon/sql/pull/3834))
* Support span push down ([#3823](https://github.com/RileyJergerAmazon/sql/pull/3823))
* Support struct field with dynamic disabled ([#3829](https://github.com/RileyJergerAmazon/sql/pull/3829))

## Enhancements
* Allow warning header for yaml test ([#3846](https://github.com/RileyJergerAmazon/sql/pull/3846))
* Change compare logical when comparing date related fields with string literal ([#3798](https://github.com/RileyJergerAmazon/sql/pull/3798))
* Correct null order for `sort` command with Calcite ([#3835](https://github.com/RileyJergerAmazon/sql/pull/3835))
* Push down QUERY_SIZE_LIMIT ([#3880](https://github.com/RileyJergerAmazon/sql/pull/3880))
* Skipping codegen and compile for Scan only plan ([#3853](https://github.com/RileyJergerAmazon/sql/pull/3853))

## Bug Fixes
* Fix flaky tests of week/yearweek in CalcitePPLDateTimeBuiltinFunctionIT ([#3815](https://github.com/RileyJergerAmazon/sql/pull/3815))
* Translate JSONException to 400 instead of 500 ([#3833](https://github.com/RileyJergerAmazon/sql/pull/3833))
* Fix incorrect push down for Sarg with nullAs is TRUE ([#3882](https://github.com/RileyJergerAmazon/sql/pull/3882))
* Fix relevance query function over optimization issue in ReduceExpressionsRule ([#3851](https://github.com/RileyJergerAmazon/sql/pull/3851))

## Infrastructure
* Add enforce-labels action ([#3816](https://github.com/RileyJergerAmazon/sql/pull/3816))
* Add explain ITs with Calcite without pushdown ([#3786](https://github.com/RileyJergerAmazon/sql/pull/3786))
* Update the maven snapshot publish endpoint and credential ([#3886](https://github.com/RileyJergerAmazon/sql/pull/3886))

## Documentation
* Update ppl documentation index for new functions ([#3868](https://github.com/RileyJergerAmazon/sql/pull/3868))
* Update the limitation docs ([#3801](https://github.com/RileyJergerAmazon/sql/pull/3801))