# clavis-password-manager

ID・パスワード・URL・メモを AES-256-GCM でローカルに暗号化保存するパスワードマネージャ。

- 公式サイト: <https://informanellica.github.io/clavis-password-manager/>
- マニュアル: <https://informanellica.github.io/clavis-password-manager/manual.html>
- 更新履歴: <https://github.com/informanellica/clavis-password-manager/releases>
- 最新版ダウンロード: <https://github.com/informanellica/clavis-password-manager/releases/latest>

## 主な機能

- マスターパスワード保護の金庫ファイル (AES-256-GCM + PBKDF2-310000)
- ID Manager 風のグループ階層ツリー (ドラッグ&ドロップで並べ替え・移動・マージ)
- CSV / XML / JSON のインポート (Shift-JIS / UTF-8 自動判定) と CSV / JSON エクスポート
- 強力なパスワード生成器 (大小英字・数字・記号・長さ指定、crypto.randomBytes)
- 30 秒で自動消去されるクリップボードコピー
- 名前 / ID / URL / メモの横断検索
- データはすべてローカル (`%APPDATA%\Clavis Password Manager\vault.enc`)、外部送信なし

## ライセンス

本ソフトウェアは [フリーソフト利用規約](https://informanellica.github.io/clavis-password-manager/#フリーソフト利用規約) に基づき提供されます。
再配布・第三者への提供等は禁止されています。詳細は規約をご確認ください。

## このリポジトリの構成

- `docs/` — 公式サイトのソース (GitHub Pages から配信)

## 不具合・誤植の連絡

サイトの誤植、リンク切れ、アプリの不具合、機能要望などがあれば
[Issues](https://github.com/informanellica/clavis-password-manager/issues) でお知らせください。
