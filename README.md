# Azure Static Web AppsでWebサイト公開（学習記録）

## 概要

Azureの学習として、簡単なWebページを作成し公開しました。

---

## 使用技術

* HTML
* GitHub
* Azure Static Web Apps（Freeプラン）

---

## 手順

### ① HTMLファイル作成

index.htmlを作成

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>はじめてのAzure</title>
</head>
<body>
  <h1>Azureで公開できた！</h1>
  <p>これがポートフォリオの第一歩</p>
</body>
</html>
```

---

### ② GitHubにアップロード

* 新しいリポジトリ作成
* index.htmlをアップロード
* Commitして保存

---

### ③ Azureで公開

* Static Web Appsを作成
* GitHubと連携
* リポジトリとmainブランチを選択
* 自動デプロイ実行

---

### ④ 公開確認

発行されたURLにアクセスして表示確認

---

## 学んだこと

* GitHubの基本操作（commit）
* Azureでのデプロイの流れ
* CI/CDの仕組み（自動で更新される）

---

## 改善・今後やること

* ボタン操作を追加
* API（Azure Functions）と連携
* データ保存機能を追加
