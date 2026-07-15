
# 福井大学 半導体集積デバイス工学研究室

**Semiconductor Integrated Device Engineering Laboratory, Fukui University**

福井大学・文京キャンパスの半導体集積デバイス工学研究室の公式ウェブサイトです。GaN HEMT、N極性GaNのプロセス技術、電流コラプス解析、酸化ガリウム結晶の抵抗率評価に取り組んでいます。

公開サイト：<https://uf-side-lab.github.io/>

## ページ構成

| ページ | 内容 |
| --- | --- |
| トップ | 研究室の概要、研究テーマ、ニュース |
| 研究紹介 | HEMTの基礎と4つの研究テーマ |
| メンバー | 教員・学生と担当テーマ |
| 業績・論文・ニュース・設備紹介 | 最新情報（準備中の項目を含む） |
| アクセス | 所在地、交通案内、地図 |

## ファイル構成

```text
├── index.html              # トップページ
├── research.html           # 研究紹介
├── members.html            # メンバー
├── achievements.html       # 業績
├── publications.html       # 論文
├── news.html               # ニュース
├── facilities.html         # 設備紹介
├── access.html             # アクセス
└── assets/
    ├── css/style.css       # 共通スタイル
    └── js/main.js          # モバイルメニューなどの共通操作
```

## 更新方法

各ページの内容は対応するHTMLファイルを編集します。デザインの共通調整は `assets/css/style.css`、メニューなどの操作は `assets/js/main.js` で行います。

`main` ブランチへ変更を反映すると、GitHub Pagesにより公開サイトへ自動で反映されます。静的サイトのため、追加のビルド作業や依存パッケージのインストールは不要です。

## 技術構成

- HTML / CSS / JavaScriptのみ
- レスポンシブ対応
- SEO・アクセシビリティを考慮したマークアップ
- 外部フレームワークに依存しない軽量構成
