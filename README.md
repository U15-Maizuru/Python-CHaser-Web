# CHaserWeb（一関大会版）

このプロジェクトは、**[函館大会](https://sites.google.com/view/u16procon-hakodate/)向けに開発された[CHaserWebシステム](https://github.com/shin3391/CHaserWeb)をベースに、[一関大会](https://www.u15-ichinoseki.org/)向けにカスタマイズしたWebアプリケーション**です。
  一関大会で推奨している[CHaserクライアントライブラリ](https://github.com/U15-Ichinoseki/python-chaser) に準拠しています。

> ⚠️ 本アプリは公式CHaserサーバーとの完全な互換性を保証するものではありません。
 
---

## 主な変更点

- [一関大会推奨ライブラリ](https://github.com/U15-Ichinoseki/python-chaser) に対応
- 対戦用AIのロジックを強化
- ゲームボードのデザインを一関大会のデザインに変更

---

## 主な機能

- Pythonコードをブラウザ上で編集・実行
- ゲームの進行状況をリアルタイムで表示
- プログラムのアップロード・ダウンロード

---

## 使用ライブラリ

| ライブラリ名                                  | 用途                                   | ライセンス               |
|----------------------------------------------|----------------------------------------|---------------------------|
| [Pyodide](https://github.com/pyodide/pyodide) | Pythonコードをブラウザ上で実行するため   | Mozilla Public License 2.0 |
| [CodeMirror](https://codemirror.net/)         | ブラウザベースのコードエディタ           | MIT License               |

---

## ライセンス

このプロジェクトは、[MIT License](LICENSE) のもとで公開されています。
詳細は、[LICENSE](LICENSE) ファイルをご覧ください。
