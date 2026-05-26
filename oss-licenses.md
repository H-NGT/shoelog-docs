# オープンソースライセンス / Open Source Licenses

ShoeLog は以下のオープンソースソフトウェアを利用しています。各パッケージのライセンス全文は [THIRD_PARTY_LICENSES.txt](./THIRD_PARTY_LICENSES.txt) を参照してください。

## ライセンス分布（本番依存 680 パッケージ）

| ライセンス | パッケージ数 |
| --- | --- |
| MIT | 572 |
| ISC | 41 |
| BSD-3-Clause | 16 |
| BSD-2-Clause | 15 |
| Apache-2.0 | 13 |
| BlueOak-1.0.0 | 9 |
| MPL-2.0 | 2 |
| その他（CC0, Unlicense 等） | 12 |

## 主要ライブラリ

| パッケージ | ライセンス | 用途 |
| --- | --- | --- |
| react | MIT | UI フレームワーク |
| react-native | MIT | クロスプラットフォーム実行基盤 |
| expo | MIT | 開発フレームワーク |
| expo-router | MIT | ファイルベースルーティング |
| expo-sqlite | MIT | ローカル DB |
| expo-image-picker | MIT | 写真選択／カメラ |
| expo-image-manipulator | MIT | 画像クロップ／回転 |
| expo-file-system | MIT | ファイル操作 |
| @react-native-async-storage/async-storage | MIT | 設定保存 |
| react-native-cloud-store | MIT | iCloud 同期 |
| react-native-reanimated | MIT | アニメーション |
| react-native-svg | MIT | SVG レンダリング |
| @gorhom/bottom-sheet | MIT | ボトムシート |
| @expo/vector-icons | MIT | アイコン |
| @react-native-community/datetimepicker | MIT | 日付ピッカー |

## ライセンス情報の再生成

依存追加・更新時にライセンス情報を再生成するには：

```bash
npx license-checker --production --excludePrivatePackages --json > /tmp/licenses.json
# その後、docs/ 配下の THIRD_PARTY_LICENSES.txt を作り直す
```
