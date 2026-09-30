# 福井大学 半導体集積デバイス工学研究室 公式ウェブサイト

**Semiconductor Integrated Device Engineering Laboratory, University of Fukui**

福井大学 文京キャンパス「半導体集積デバイス工学研究室（SIDE LAB）」の公式ウェブサイトです。GaN HEMT、InP HEMT、Ga₂O₃（酸化ガリウム）を中心に、高周波・高耐圧・低雑音デバイスと集積回路技術に関する研究を紹介しています。

- 公開サイト（日本語）：<https://uf-side-lab.github.io/>
- English site: <https://uf-side-lab.github.io/en/>

## ページ構成

| ページ | 日本語 | English | 内容 |
| --- | --- | --- | --- |
| Home | `index.html` | `en/index.html` | 研究室概要、研究テーマ、ニュース |
| 研究紹介 / Research | `research.html` | `en/research.html` | GaN HEMT、InP HEMT、Ga₂O₃の研究内容 |
| 連携・展開 / Collaboration & Outlook | `collaboration.html` | `en/collaboration.html` | 今後の研究展開と共同研究分野 |
| 業績 / Achievements | `achievements.html` | `en/achievements.html` | 論文・学会発表などの研究業績 |
| ニュース / News | `news.html` | `en/news.html` | 研究室からのお知らせ |
| メンバー / Members | `members.html` | `en/members.html` | 教員・学生と研究テーマ |
| 経歴 / Profile | `career.html` | `en/career.html` | 教員の経歴・業績情報・共同研究実績 |
| アクセス / Access | `access.html` | `en/access.html` | 所在地、学内案内図、交通案内、Google Map |

## ディレクトリ構成

```text
├── index.html                    # 日本語トップページ
├── research.html                # 日本語各ページ
├── collaboration.html
├── achievements.html
├── news.html
├── members.html
├── career.html
├── access.html
├── en/                           # 英語版ページ
├── assets/
│   ├── css/style.css             # 共通スタイル
│   ├── js/                       # ナビゲーションなどの共通処理
│   └── images/                   # 研究写真・図・案内図
├── robots.txt                    # クローラー向け設定
├── sitemap.xml                   # 検索エンジン向けサイトマップ
└── .github/workflows/
    └── deploy-pages.yml          # GitHub Pagesへの自動公開
```

## 更新と公開

HTML、CSS、画像などを更新して`main`ブランチへ反映すると、GitHub ActionsからGitHub Pagesへ自動公開されます。静的サイトのため、ビルドコマンドや外部フレームワークは不要です。

## 検索エンジン向け設定

- 各ページに固有の`title`と`description`を設定
- canonical URLで`/`と`index.html`などの重複URLを整理
- `hreflang`で日本語版と英語版を関連付け
- `robots.txt`からルートの`sitemap.xml`を案内
- `sitemap.xml`に公開ページと最終更新日を記載
- トップページに研究組織の構造化データを設定

新規公開時や大きな更新後は、Google Search Consoleで`https://uf-side-lab.github.io/sitemap.xml`を送信し、トップページのURL検査からインデックス登録をリクエストしてください。

## 技術構成

- HTML / CSS / JavaScript
- 日本語・英語対応
- レスポンシブデザイン
- アクセシビリティとSEOを考慮した静的マークアップ
