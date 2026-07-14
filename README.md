# Boatrace Open API Mirror

[![v1](https://img.shields.io/badge/Boatrace_Open_API_Mirror-v1-blue)](https://github.com/boatraceopenapi/api-mirror/tree/gh-pages/docs/v1)
[![license](https://img.shields.io/badge/license-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![pages-build-deployment](https://github.com/boatraceopenapi/api-mirror/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/boatraceopenapi/api-mirror/actions/workflows/pages/pages-build-deployment)
[![sync-docs](https://github.com/boatraceopenapi/api-mirror/actions/workflows/sync-docs.yml/badge.svg)](https://github.com/boatraceopenapi/api-mirror/actions/workflows/sync-docs.yml)
[![keepalive](https://github.com/boatraceopenapi/api-mirror/actions/workflows/keepalive.yml/badge.svg)](https://github.com/boatraceopenapi/api-mirror/actions/workflows/keepalive.yml)
[![dependabot-updates](https://github.com/boatraceopenapi/api-mirror/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/boatraceopenapi/api-mirror/actions/workflows/dependabot/dependabot-updates)

---

## ⚠️ 注意事項

**本 API を利用する前に、以下の内容をご確認ください。**

- **このリポジトリは [boatraceopenapi/api](https://github.com/boatraceopenapi/api) の docs/ を毎日ミラーリングした GitHub Pages 配信用リポジトリです。ドキュメント・仕様・注意事項などは本家をご確認ください。**
- **本リポジトリの内容は 1 日 1 回の同期のため、本家 [boatraceopenapi/api](https://github.com/boatraceopenapi/api) と比べて反映が遅いです。リアルタイム性が必要な場合は本家のエンドポイントをご利用ください。**

---

## 🌐 エンドポイント

```bash
https://boatraceopenapi.github.io/api-mirror/v1/YYYY/YYYYMMDD.json
```

- `YYYY` → 年
- `YYYYMMDD` → 年月日
- 日付は日本標準時（JST / UTC+9）基準

> データが存在しない日付（対応期間外・未来日付など）を指定した場合、GitHub Pages の仕様により HTTP 404 が返されます。

---

## 📄 ライセンス

Boatrace Open API Mirror は [MIT license](LICENSE) の元で公開されています。
