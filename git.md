[ローカルで作業した git リポジトリを GitHub にアップする手順 \| Tomohiro Furukawa](https://hirofurukawa.com/push-local-repos-to-github/)
## 1) 要約（3点以内）

- ローカルのGitリポジトリを「GitHub上の空リポジトリ」に紐づけて `push` する手順。([Tomohiro Furukawa](https://hirofurukawa.com/push-local-repos-to-github/ "ローカルで作業した git リポジトリを GitHub にアップする手順 | Tomohiro Furukawa"))
    
- 事前に「ローカルはコミット済みでクリーン」「GitHub側にリポジトリ作成」「SSH URLをコピー」が要点。([Tomohiro Furukawa](https://hirofurukawa.com/push-local-repos-to-github/ "ローカルで作業した git リポジトリを GitHub にアップする手順 | Tomohiro Furukawa"))
    
- あとは `git remote add origin <SSH_URL>` → `git push origin <branch>` で完了。([Tomohiro Furukawa](https://hirofurukawa.com/push-local-repos-to-github/ "ローカルで作業した git リポジトリを GitHub にアップする手順 | Tomohiro Furukawa"))
    

## 2) 前提・仮定（1〜3文）

前提：ローカルの作業ディレクトリは既に `git init` 済みで、コミットまで終わっていると仮定します。([Tomohiro Furukawa](https://hirofurukawa.com/push-local-repos-to-github/ "ローカルで作業した git リポジトリを GitHub にアップする手順 | Tomohiro Furukawa"))  
前提：GitHubアカウント作成済みで、SSH接続を使う想定（HTTPSでも可能）。([Tomohiro Furukawa](https://hirofurukawa.com/push-local-repos-to-github/ "ローカルで作業した git リポジトリを GitHub にアップする手順 | Tomohiro Furukawa"))

## 3) 推奨（優先度付き）／アクションプラン（ステップ）

- **最優先**：ローカルを「コミット済み・変更なし」にしてから作業する（事故率が下がる）。([Tomohiro Furukawa](https://hirofurukawa.com/push-local-repos-to-github/ "ローカルで作業した git リポジトリを GitHub にアップする手順 | Tomohiro Furukawa"))
    
- **優先**：GitHub側で空リポジトリを作成し、**SSH URL** をコピーして使う。([Tomohiro Furukawa](https://hirofurukawa.com/push-local-repos-to-github/ "ローカルで作業した git リポジトリを GitHub にアップする手順 | Tomohiro Furukawa"))
    
- **次点**：既定ブランチ名が `main` の場合が多いので、`master` と食い違うならブランチ名を合わせる（下に対処を書きます）。
    

## 4) 根拠・出典（URL含む）

- 「ローカルで作業した git リポジトリを GitHub にアップする手順」（Tomohiro Furukawa, 2025-08-28）([Tomohiro Furukawa](https://hirofurukawa.com/push-local-repos-to-github/ "ローカルで作業した git リポジトリを GitHub にアップする手順 | Tomohiro Furukawa"))
    

## 5) 未検証箇所・リスクと対策

- [未検証] GitHubの既定ブランチが `main` か `master` かは、あなたのリポジトリ設定・作成時期で変わります（出典なし）。**検証方法**：`git branch` でローカルのブランチ名を確認し、GitHub側の初期画面の案内（またはSettings → Branches）を確認。
    
- [未検証] SSH未設定だと `git push` 時に認証で詰まります（出典なし）。**検証方法**：`ssh -T git@github.com` を実行して疎通確認（成功ならメッセージが出る）。
    

## 6) 実行上の注意点（Obsidianコピペ用テンプレ）

````md
---
title: ローカルGitリポジトリをGitHubへpushする手順
date: 2026-02-01
tags: [git, github, howto]
source: Tomohiro Furukawa「ローカルで作業した git リポジトリを GitHub にアップする手順」
---

# ローカルGitリポジトリをGitHubへpushする（SSH）

## 0. 事前チェック（ローカル）
- ローカルの作業がコミット済みで、変更が残っていない状態にする（クリーン）。
  - 例：`git status` が "working tree clean" になる状態

## 1. GitHub側で空リポジトリを作成
- GitHubで新規リポジトリを作成（空でOK）
- リポジトリ画面から **SSH URL** をコピーして控える

## 2. ローカルで remote を追加して push
### 2-1) remote の状態確認
```bash
git remote -v
````

### 2-2) origin を追加（SSH URLを貼り付け）

```bash
git remote add origin git@github.com:YOUR_NAME/YOUR_REPO.git
```

### 2-3) remote 登録を確認

```bash
git remote -v
# origin ... (fetch)
# origin ... (push)
```

### 2-4) push する

> 元記事例は master。あなたのブランチ名に合わせること。

```bash
git push origin master
```

# つまずきメモ

## A) ブランチが main の場合

### ローカルのブランチ確認

```bash
git branch
```

### main で push

```bash
git push origin main
```
