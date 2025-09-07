# devcontainer-for-claude-gemini

Claude CodeとGemini CLIを使用できるdevcontainer環境を作成しました。
[Claude Codeの公式リファレンスリポジトリ](https://github.com/anthropics/claude-code/tree/main)をベースに作成しています。
同じコンテナ内でClaude CodeとGemini CLIを切り替えることが可能です。

## 使用手順

- `git clone`で当プロジェクトを落としてくる
- VSCodeやCursorで当プロジェクトを開き、「Reopen in Container」をクリック
- コンテナ環境内で`claude`コマンドを実行すればClaude Codeが立ち上げる
- 同じく、`gemini`コマンドを実行すると、Gemini CLIが立ち上がる

### 初回のみ

- Claude Code及びGemini CLIの初期設定を聞かれるので、好みのテーマを選択したり、認証を行うこと
- 二度目以降は聞かれない
