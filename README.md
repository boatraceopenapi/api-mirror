# 🚤 Boatrace Open API Mirror

[![v1](https://img.shields.io/badge/Boatrace_Open_API-v1-blue)](https://github.com/boatraceopenapi/api/tree/gh-pages/docs/v1)
[![license](https://img.shields.io/badge/license-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![deploy-pages](https://github.com/boatraceopenapi/api/actions/workflows/deploy-pages.yml/badge.svg)](https://github.com/boatraceopenapi/api/actions/workflows/deploy-pages.yml)
[![test](https://github.com/boatraceopenapi/api/actions/workflows/test.yml/badge.svg)](https://github.com/boatraceopenapi/api/actions/workflows/test.yml)
[![psalm](https://github.com/boatraceopenapi/api/actions/workflows/psalm.yml/badge.svg)](https://github.com/boatraceopenapi/api/actions/workflows/psalm.yml)
[![audit](https://github.com/boatraceopenapi/api/actions/workflows/audit.yml/badge.svg)](https://github.com/boatraceopenapi/api/actions/workflows/audit.yml)
[![sync](https://github.com/boatraceopenapi/api/actions/workflows/sync.yml/badge.svg)](https://github.com/boatraceopenapi/api/actions/workflows/sync.yml)
[![sync-upcoming](https://github.com/boatraceopenapi/api/actions/workflows/sync-upcoming.yml/badge.svg)](https://github.com/boatraceopenapi/api/actions/workflows/sync-upcoming.yml)
[![keepalive](https://github.com/boatraceopenapi/api/actions/workflows/keepalive.yml/badge.svg)](https://github.com/boatraceopenapi/api/actions/workflows/keepalive.yml)
[![dependabot-updates](https://github.com/boatraceopenapi/api/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/boatraceopenapi/api/actions/workflows/dependabot/dependabot-updates)

## ⚠️ 注意事項

> **本 API を利用する前に、以下の内容をご確認ください。**
>
> - ⚡ **本 API は非公式です。**
>   BOATRACE 公式サイトおよび関連団体とは一切関係ありません。
>
> - 🕒 **データはリアルタイムではありません。**
>   GitHub Actions による約 3 分間隔の定期更新を行っています。リアルタイム配信ではないため、最新の情報が反映されるまで数分程度の遅れが生じる場合があります。
>
> - 📊 **データの正確性・完全性は保証していません。**
>   収集・変換の都合により、欠損や誤りが含まれる可能性があります。
>
> - 🚫 **公式な情報が必要な場合は、必ず BOATRACE 公式サイトをご確認ください。**
>
> - 🙇‍♂️ **本 API の利用は自己責任でお願いします。**

## 📌 概要

この API では、ボートレース（競艇）のデータを取得できます。<br>
データは GitHub Pages 上で公開されており、JSON 形式で提供されます。

- **対応レース場**: 全国 24 場すべてに対応しています。特定のレース場のみを取り出すエンドポイントはなく、1日分のデータに全場の情報が含まれます。
- **取得可能なデータ**: 出走表・直前情報・結果

## 🌐 エンドポイント

> 📅 対応期間: 2026年01月01日以降

```bash
https://boatraceopenapi.github.io/api-mirror/v1/YYYY/YYYYMMDD.json
```

📅 YYYY → 年<br>
📅 YYYYMMDD → 年月日<br>
（ 日付は日本標準時 JST〔UTC+9〕基準 ）

> **データが存在しない日付**（対応期間外・未来日付など）を指定した場合、GitHub Pages の仕様により **HTTP 404** が返されます。

## 📄 ライセンス

Boatrace Open API Mirror は [MIT license](LICENSE) の元で公開されています。
