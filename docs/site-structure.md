# 現サイトの構成（sitemap より・2026-07-09 取得）

構築基盤：STUDIO（Studio.Design／Nuxt レンダリング）。CMS機能で「お知らせ（news）」「施工実績（case）」を運用。

## 静的ページ一覧

| URL | 想定内容 |
|---|---|
| `/` | トップ |
| `/company` | 会社情報 |
| `/company/history` | 沿革 |
| `/company/social`・`/company/social-1` | 社会貢献（無印＝制作中のプレースホルダ、`-1`＝制作中の本体。及川さん確認済み 2026-07） |
| `/business` | 事業内容トップ |
| `/business/architecture` | 建築 |
| `/business/civilengineering` | 土木 |
| `/business/realestate`・`/business/realestate-1` | 不動産（無印＝制作中のプレースホルダ、`-1`＝制作中の本体。及川さん確認済み 2026-07） |
| `/business/crushedstone` | 砕石 |
| `/business/industrialwaste` | 産業廃棄物 |
| `/business/others` | その他 |
| `/case` | 施工実績（CMS） |
| `/news` | お知らせ（CMS） |
| `/hole-3` | 〔要確認：URLから内容不明。採用ページ？〕 |
| `/contact` | お問い合わせ |
| `/contact-thanks` | 送信完了 |
| `/privacypolicy` | プライバシーポリシー |

## 気づき（リニューアル検討の材料）

- social / realestate の2組は重複ではなく制作中（無印＝プレースホルダ、`-1`＝制作中の本体）→ 完成時にURLの一本化を検討
- `/hole-3` は意味の取れないスラッグ → 内容確認のうえ、リネームか整理を検討
- 採用専用ページ・セクションが見当たらない → 高校新卒採用に力を入れているため、**採用ページ新設は有力候補**
