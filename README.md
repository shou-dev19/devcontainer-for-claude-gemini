# devcontainer-for-gemini-cli

Gemini CLIを使用できるdevcontainer環境
Node.jsをベースにGemini CLIをグローバルインストール済みの環境

## 使用手順

- `git clone`で当プロジェクトを落としてくる
- VSCodeやCursorで当プロジェクトを開き、「Reopen in Container」をクリック
- コンテナ環境内で`gemini`コマンドを実行すると、Gemini CLIが立ち上がる

### 初回のみ

- 好みのGemini CLIのテーマを選択する
- Googleアカウントか、APIキーでの認証を行う

    ※これらの設定はコンテナ内にマウントしている`/home/node/.gemini`内に永続的に保存されるため、二度目以降のコンテナ起動時には聞かれないようになっている
