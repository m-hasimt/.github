---
name: Bug
about: Investigate and fix incorrect behavior
title: ""
labels: ""
assignees: ""
---

## Problem

<!-- 現在起きている問題を記載する -->

## Expected behavior

<!-- 本来期待される動作を記載する -->

## Reproduction

1.
2.
3.

## Evidence

<!-- ログ、エラー、発生条件、関連ファイル等を記載する -->

## Scope

- 原因を特定する
- 必要に応じて再現テストを追加する
- 原因に対する最小限の修正を行う

## Acceptance criteria

- [ ] 問題の原因が特定されている
- [ ] 修正後に問題を再現しない
- [ ] 適切な回帰テストが追加されている
- [ ] Existing tests pass
- [ ] Unrelated changesを含まない

## Stop conditions

以下の場合は推測で大規模変更せず状況を報告する。

- 問題を再現できない
- architecture変更が必要になる
- public APIやデータ形式の変更が必要になる
- 複数の原因候補があり仕様判断が必要になる
