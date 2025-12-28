# 技術要件

## 動作環境

- モダンブラウザ（Chrome, Firefox, Safari, Edge）
- JavaScript有効
- サーバー不要（静的ファイルのみで動作）

## ファイル構成

```
生成AI活用例/
├── index.html            # メインHTML
├── data/                 # 静的データ
│   ├── master.js         # 事例データ
│   ├── process.js        # プロセスデータ（プロンプト例含む）
│   ├── tags.js           # タグ説明データ
│   └── images/           # スライド画像
│       ├── tips001.jpeg
│       ├── tips002.jpeg
│       └── ...
└── docs/                 # ドキュメント
```

## 依存関係

- 外部ライブラリなし
- 純粋なHTML/CSS/JavaScriptで実装
