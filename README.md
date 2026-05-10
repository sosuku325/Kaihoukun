# kaihoukun1

UPnP を使ってポート開放/閉鎖をGUIでやるやつです。  
毎回ルーター設定開くの面倒だったので作りました。

TCP/UDP の単体開放と、複数ポート一括開放に対応しています。

## 機能

- ローカルIP取得
- グローバルIP取得
- ポート開放
- ポート閉鎖
- 外部到達性テスト（TCP）
- 複数ポート一括開放
- IPコピー

## 必要なもの

- Windows
- Python 3.x

## ライブラリ

```bash
pip install -r requirements.txt