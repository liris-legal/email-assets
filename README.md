# email-assets

メール配信用の画像アセットを管理するリポジトリです。

## フォルダ構成

| フォルダ | 内容 |
|---------|------|
| `logos/` | LIRISロゴ画像 |
| `seminar/` | セミナー案内画像 |
| `covers/` | カバー・製品画像 |

## 画像の追加方法

画像素材は [Google Drive - 画像素材の共有フォルダ](https://drive.google.com/drive/u/0/folders/1YAiFnPNs2RWihoNvV-0-oTz4AV-Wm1MM) で共有されています。メールで使用する画像はこのフォルダからダウンロードし、適切なフォルダに配置してPushしてください。

> **注意**: ファイル名は日本語を避け、英数字とハイフンを使用してください。

## 画像の参照方法

HTMLメールから参照する場合、以下の形式のURLを使用してください。

```
https://raw.githubusercontent.com/liris-legal/email-assets/master/{フォルダ名}/{ファイル名}
```

例:
```html
<img src="https://raw.githubusercontent.com/liris-legal/email-assets/master/logos/liris-logo_horizontal_blue.png" alt="LIRISロゴ" width="200px" />
```
