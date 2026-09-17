---
name: Implementation task
about: Implement a scoped change with clear acceptance criteria
title: ""
labels: ""
assignees: ""
---

## Goal

<!-- このIssueで最終的に実現することを簡潔に記載する -->

## Background

<!-- 必要な背景を記載する。長期的な設計情報はdocs等への参照を優先する -->

## References

<!-- 実装前に確認すべきdocs、既存コード、関連Issue等を列挙する -->

-

## Scope

<!-- このIssueで実装する内容 -->

- [ ]

## Out of scope

<!-- 今回は変更しない範囲。不要なら削除してよい -->

-

## Design decisions

<!--
決定済みの重要な設計事項を記載する。
実装時に再検討させたくないarchitecture、interface、dependency等が対象。
不要なら削除してよい。
-->

-

## Acceptance criteria

<!-- 観測・検証可能な完了条件を記載する -->

- [ ]

## Verification

- [ ] Repository-standard tests pass
- [ ] Repository-standard lint/type checks pass where applicable
- [ ] New or modified behavior is appropriately tested
- [ ] Relevant documentation is updated where necessary

## Stop conditions

以下に該当する場合は、推測で大きな変更を行わず状況を報告する。

- Issueの要求と既存設計が矛盾する
- Scope外の変更が必要になる
- public APIやデータ形式の互換性を壊す必要がある
- 新規dependencyの追加が必要になる
- Acceptance criteriaを満たすために重要な設計判断が必要になる
