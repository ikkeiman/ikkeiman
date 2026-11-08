# Ikkei Miyata

約100名規模の組織で DX 推進部門の責任者として、業務システムの内製・RPA・全職員向け生成AI基盤を企画から設計・開発・運用まで一人で担当しています。
営業職から独学でプログラミングを身につけてシステム部門へ移り、「現場が毎日使う画面」と「安全に使える AI の仕組み」を作ってきました。
ポートフォリオ: https://ikkeiman.github.io/port_folio/

## リポジトリの位置づけ

| リポジトリ | 何か | 状態 |
|---|---|---|
| [llm-guard-gateway](https://github.com/ikkeiman/llm-guard-gateway) | LLM への入力を3段階（ルール → 固有表現抽出 → ローカル LLM 判定）で検査し、個人情報を止めてから外部 LLM に転送する OpenAI 互換プロキシ。合成データで見逃し率・止めすぎ率・応答時間を測る評価ハーネス付き | 公開中。テストと CI あり。ローカル LLM 判定の評価値は未計測 |
| [secure-mcp-server-guide](https://github.com/ikkeiman/secure-mcp-server-guide) | Claude Desktop に入れる MCP サーバーを安全に作るための指針。脅威モデル、よくある問題点、設計案 A〜D の比較、推奨案と、読み取り専用の参照実装（テスト付き） | 公開中 |
| [port_folio](https://github.com/ikkeiman/port_folio) | ポートフォリオサイトのソース。Vue 3 + Vite、UI フレームワーク不使用、GitHub Pages | 公開中 |
| mopo | 個人開発のお出かけアプリ。企画・要件定義・事業計画・プロトタイプの段階 | 非公開（面接時に閲覧できます） |

どのリポジトリも README に「やっていないこと・制約」を書いています。未検証のものを実装済みとは書いていません。

主な技術: Python / FastAPI、Vue 3、C# / .NET、PostgreSQL / PostGIS、kintone、ローカル LLM（Ollama）、MCP
