# データ構造

## master.js

事例データを格納するファイル。パス: `data/master.js`

```javascript
const DATA = [
    {
        id: 1,
        title: "事例タイトル",
        subtitle: "サブタイトル",
        challenge_primary: "課題（主）",
        challenge_secondary: "課題（副）",
        solution_primary: "ソリューション（主）",
        solution_secondary: "ソリューション（副）",
        outcome_primary: "成果（主）",
        outcome_secondary: "成果（副）",
        voice: "ユーザーの声",
        tags: ["タグ1", "タグ2"]
    },
    // ...
];
```

## process.js

プロセスデータを格納するファイル。パス: `data/process.js`

```javascript
const PROCESS = [
    {
        "001": [
            {"1.ステップ名": "ステップの説明"},
            {"2.ステップ名": "ステップの説明", "prompt": "プロンプト例（AIを使うステップのみ）"},
            // ...
        ]
    },
    // ...
];
```

### promptフィールド

- AIを活用するステップにのみ付与
- 具体的なプロンプト例を記載
- 詳細ページでステップ説明の下に表示される

## tags.js

タグ説明データを格納するファイル。パス: `data/tags.js`

```javascript
const TAGS = [
    {
        "tag": "#タグ名",
        "explanation": "タグの説明文"
    },
    // ...
];
```

## 画像ファイル

- ディレクトリ: `data/images/`
- 命名規則: `tips{番号}.jpeg`（例: tips001.jpeg）
