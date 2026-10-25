# 朝5分で読むGAFAMニュース

Google・Apple・Meta・Amazon・Microsoft の直近ニュースを、毎朝5分で読める日本語ダイジェストにまとめるスマホ向けアプリです。TomTom TOWNS の一員です。

- 公開URL: https://pecpec37-gift.github.io/GAFAM-News/
- 毎朝 5:48（日本時間）ごろ、Claude の定期タスクが新しい号を追加します。

## データの置き場所

- `data/index.json` … 号の一覧（新しい順、最大30号）
- `data/editions/YYYY-MM-DD.json` … 各号の本文

各号のJSONは `date / label / coverage / minutes / points / items / trend / calendar` を持ちます。`items[].co` は `google` `apple` `meta` `amazon` `microsoft` のいずれかです。
