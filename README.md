# MPC Server プロジェクト

このリポジトリには、ClaudeやClineなどのAIアシスタントが外部サービスと連携するためのModel Context Protocol (MCP) サーバーが含まれています。

## 含まれるMCPサーバー

### 1. Filesystem MCP Server

ファイルシステムとの対話を可能にするMCPサーバーです。AIアシスタントがファイルの読み書きやディレクトリ操作を行うことができます。

#### 主な機能

- ファイルの読み書き
- ディレクトリの作成・一覧表示・削除
- ファイル/ディレクトリの移動
- ファイル検索
- ファイルメタデータの取得

### 2. Notion MCP Server

NotionのAPIを利用して、AIアシスタントがNotionワークスペースと対話できるようにするMCPサーバーです。

#### 主な機能

- Notionページやデータベースの作成・取得・更新・削除
- ブロックの追加・取得・削除
- データベースのクエリ
- コメントの作成・取得
- ユーザー情報の取得
- 検索機能

### 3. MCP Compass

自然言語クエリを使用してMCPサーバーを検索・推奨するためのサービスです。AIアシスタントが特定のタスクに適したMCPサービスを見つけるのを支援します。
