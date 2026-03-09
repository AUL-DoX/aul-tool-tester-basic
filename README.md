# AUL Tool Tester Basic

AIで作ったHTMLツールを、公開前にチェックするための簡易チェッカーです。

インストール不要。ブラウザで開くだけで使えます。

---

## 🚀 使ってみる

**👉 [ブラウザで開く](https://aul-dox.github.io/aul-tool-tester-basic/tool-tester-basic.html)**

---

## できること

- 基本構造のチェック（DOCTYPE・文字コード・viewportなど）
- セキュリティチェック（XSS・eval使用・デバッグログの残留など）
- コード品質チェック（console.log残留・エラーハンドリングなど）
- UI / UXチェック（ボタン・フォーム・alt属性など）
- 依存関係チェック（外部CDN・Webフォントの使用）
- 手動確認チェックリスト（10項目）
- チェック結果を VERIFIED.md 形式で出力

---

## 使い方

1. 上のリンクをブラウザで開く
2. HTMLファイルをドロップ、またはURLを入力
3. `▶ RUN QA CHECK` を実行
4. 結果を確認して VERIFIED.md を出力

詳しくは [取扱説明書](./aul-tool-tester-basic-manual.md) をご覧ください。

---

## 動作環境

- Chrome 最新版
- Edge 最新版

---

## AUL Tool Tester Pro との違い

| | Basic（本ツール） | Pro |
|---|---|---|
| 動作環境 | ブラウザのみ | Node.js + ターミナル |
| チェック方法 | 静的解析 | 実ブラウザ動作（Playwright） |
| インストール | 不要 | 必要 |
| GAS対応 | URLのみ | ◎ |
| 向いている人 | 誰でも | 開発者 |

---

※proは有料ツールのため、noteにて販売しています。

本ツールは AUL Tool Tester Basic v1.0.0 にて自己チェック済みです。
詳細は [VERIFIED.md](./VERIFIED.md) をご参照ください。

---

## 開発者

[AUL-DoX](https://aul-dox.jp)
