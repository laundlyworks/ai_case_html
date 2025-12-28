# タグ説明機能

## 変更内容

### 機能追加

- タグ選択時に説明を表示する機能
- タグ一覧の下部に説明エリアを追加

### 新規ファイル

- `data/tags.js`: タグ説明データ（100以上のタグ定義）

### 実装詳細

#### HTML

- `<div class="tag-description" id="tagDescription">` 要素を追加
- `<script src="data/tags.js"></script>` でデータ読み込み

#### CSS

- `.tag-description`: グラデーション背景、左ボーダー
- `.tag-description .tag-name`: タグ名のスタイル
- ダークモード対応スタイル

#### JavaScript

- `showTagDescription()`: タグの説明を検索・表示
- `handleTagClick()`: タグ選択時に説明表示を呼び出し

### データ構造

```javascript
const TAGS = [
    {
        "tag": "#タグ名",
        "explanation": "タグの説明文"
    },
    // ...
];
```
