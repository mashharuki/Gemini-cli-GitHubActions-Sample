<<<<<<< HEAD
# Gemini-cli-GitHubActions-Sample
Gemini CLI + GitHub Actionsのサンプル実装

## 事前セットアップ

- Gemini CLIのインストール
- GitHub リポジトリでGemini APIキーをSecretに登録
  - `GEMINI_API_KEY`
- CLIとGitHub Actionsの連携
  - `gemini /setup-github`
  

## 代表的なユースケース

- 自動 Issue Triage
- PR コードレビュー
- On-demand タスク委譲
  - GitHub Copilotみたいに `@gemini-cli` つけるとテストコードとか書いてくれる

## 無料枠

1,000 リクエスト/日・60 req/分 の無料枠が CLI／Actions と共有されます。


## 参考文献
- [Zenn - 【最新】GitHub ActionsでGemini CLIを活用してみよう](https://zenn.dev/makumaaku/articles/15f56ac617a3af)
- [GitHub - google-gemini/gemini-cli-action](https://github.com/google-gemini/gemini-cli-action)
- [GitHub - google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)
- [GitHub - google-github-actions/run-gemini-cli](https://github.com/google-github-actions/run-gemini-cli)
- [Meet your new AI coding teammate: Gemini CLI GitHub Actions](https://blog.google/technology/developers/introducing-gemini-cli-github-actions/)
- [GitHub Actions run-gemini-cli Marketplace](https://github.com/marketplace/actions/run-gemini-cli)
- [Google Cloud Next Tokyo '25で発表された、Gemini CLI GitHub Actionsを試してみた](https://zenn.dev/iret/articles/run-gemini-cli-test)