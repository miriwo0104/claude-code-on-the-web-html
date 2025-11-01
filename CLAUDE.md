# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## プロジェクト概要

このプロジェクトは、シンプルな静的HTMLページです。ビルドプロセスやパッケージマネージャーは不要で、ブラウザで直接開いて動作を確認できます。

## プロジェクト構成

- `index.html` - メインのHTMLファイル
- `styles.css` - スタイルシート（レスポンシブデザイン対応、グラデーション背景とアニメーション効果を含む）

## 開発方法

プレビューは以下のいずれかの方法で確認:

```bash
# Pythonを使用する場合
python3 -m http.server 8000

# Node.jsのhttp-serverを使用する場合（インストールが必要）
npx http-server -p 8000
```

その後、ブラウザで http://localhost:8000 にアクセス

## コードの特徴

- **レスポンシブデザイン**: 768px以下のデバイス向けにメディアクエリを実装
- **アニメーション**: ページロード時のフェードイン効果（fadeInアニメーション）
- **モダンなスタイル**: グラデーション背景、ボックスシャドウ、半透明の白背景
