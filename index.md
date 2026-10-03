---
layout: default
title: ホーム
description: Google アカウントでサインインできるsu9ai専用個人向けサービスの公式ホームページです。
---

<div class="hero">
  <h1>{{ site.title }}</h1>
  <p>{{ site.description }}</p>
</div>

## サービスについて

このサイトは、Google アカウントを利用してサインインできる **{{ site.title }}** の公式ページです。

本サービスは、個人（{{ site.author.name }}）によって運営されており、法人ではありません。

- 個人開発者による小規模サービスとして運営
- 私（{{ site.author.name }}）以外は利用できません
- 簡単に Google アカウントでログイン
- 取得する情報は必要最低限に留めています
- サービスの利用規約とプライバシーポリシーをご確認のうえご利用ください

## この認証を利用しているサービス

本サービスは、Google アカウント認証を以下の su9ai 専用システムで利用しています。

- **cloudflare os** — su9ai 専用の個人運用システム
- **rclone** — su9ai 専用のデータ同期・管理用途で利用

これらのシステムも含め、本サービスは su9ai 以外が利用することはできません。

## リンク

- [プライバシーポリシー](/privacy-policy/)
- [利用規約](/terms-of-service/)
- [お問い合わせ](/contact/)

## 運営者情報

- 運営者名：{{ site.author.name }}
- 問い合わせ先：[{{ site.author.email }}](mailto:{{ site.author.email }})
