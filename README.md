# BC Correspondence

**Lightweight online multiplayer networking SDK for JavaScript games.**  
Room creation, joining, state synchronization, reconnect and RESYNC — without building the networking layer from scratch.

**BC Correspondence（BC通信）は、個人開発・小規模ゲーム向けの軽量オンライン通信SDKです。**

既存のJavaScriptゲームに、オンライン対戦・協力プレイ用の通信機能を追加することを目的にしています。

## Features / 主な機能

- Room creation / join（ROOM作成・参加）
- Multiplayer event messaging（ゲームイベント送受信）
- State synchronization（状態同期）
- ACK / Retry
- Automatic reconnect（一時切断からの自動再接続）
- Replay / Snapshot based RESYNC
- WebSocket based communication
- Node.js server
- Designed for small multiplayer games

○×ゲーム、オセロ、カードゲーム、ボードゲーム、ターン制ゲームなど、小規模なオンラインゲームへの組み込みを想定しています。

## Simple integration

BC Correspondenceは、ゲーム本体と通信処理をできるだけ分離して扱えるように設計しています。

実際に**オフラインの○×ゲームへ後付けでBC Correspondenceを組み込み、2人オンライン対戦・勝敗同期・再接続・状態復旧まで動作確認**しています。

製品には、この○×ゲームの実装サンプルと日本語Quick Startが付属します。

## For AI-assisted development

BC Correspondenceには、AIへ組み込み作業を依頼するためのテンプレートも付属しています。

ChatGPTなどのAIコーディング支援を使いながらゲームを開発している個人開発者でも、既存ゲームへの通信機能追加を進めやすい構成を目指しています。

## Requirements

- JavaScript game / application
- Node.js environment capable of running the server
- WebSocket communication

特定のゲームエンジン専用ではありません。

## License

- Commercial use allowed
- No royalties
- Games using BC Correspondence may be sold
- One purchase can be used for game development under the included license terms
- Redistribution or resale of BC Correspondence itself is prohibited

## Price

**¥500 — one-time purchase**

No subscription.  
No royalty.

## Download / Purchase

BC Correspondence is available from BOOTH.

https://hiruto668.booth.pm/items/8917410

## Current version

**BC Correspondence v0.1**

Current release is intended for lightweight multiplayer games and small-scale projects.

Transient network disconnects can automatically reconnect and restore state.  
Full page reload / application restart session recovery is not included in the standard v0.1 behavior.

---

### Keywords

JavaScript multiplayer SDK / game networking SDK / WebSocket multiplayer / online game networking / state synchronization / reconnect / RESYNC / indie game development / オンライン対戦 / ゲーム通信 / 通信SDK / JavaScriptゲーム / 個人ゲーム開発
