# Rikuchu-corporatesite — コーポレートサイト制作リポジトリ

陸中建設株式会社コーポレートサイト（https://rikuchu.co.jp/ ）のデザイン改善・ページ制作を管理するリポジトリ。

## 前提（重要）

- 現サイトは **STUDIO（有料プラン）** で構築・公開されている（編集権限：及川さん）。
- STUDIOはHTMLの直接アップロードができないため、**このリポジトリのHTMLはそのまま本番反映されない**。
- 運用方針は **「方針A」**：Claude がデザイン案・構成案・原稿・プロトタイプHTML（見本）を作成し、
  及川さんが STUDIO 上で再現して公開する。

## ディレクトリ構成

| パス | 用途 |
|---|---|
| `assets/brand/` | ロゴ・ブランド素材の置き場（**素材はここに集約する**） |
| `docs/` | ブランドガイド・サイト構成などのドキュメント |
| `prototypes/` | ページごとのプロトタイプHTML（1ページ＝1フォルダ。例：`prototypes/recruit/`） |

## 制作フロー

1. 目的・ターゲット・締切を確認（`docs/site-structure.md` の現状構成を参照）
2. 構成案を提示 → 合意
3. `prototypes/<ページ名>/index.html` にプロトタイプを作成（単一HTML・CSS内包・レスポンシブ）
4. 公開前チェック（表示崩れPC/スマホ・リンク切れ・正式表記・title/description）
5. 及川さんが STUDIO で再現 → 公開

## 関連

- 品質基準：`Claude-code-personalized/knowledge/quality-standards.md`「コーポレートサイト（HTML）」
- ブランド情報：`docs/brand-guide.md`
