# 概要
Android Studio 学習用、および GitHub 学習用に作成したアプリです。

本アプリは、Android Developers の公式Codelab  
[「Compose での ViewModel と状態」](https://developer.android.com/codelabs/basic-android-kotlin-compose-viewmodel-and-state?hl=ja)  
をもとに、Google 公式のサンプルアプリ「[Unscramble app](https://github.com/google-developer-training/basic-android-kotlin-compose-training-unscramble)」をベースとして構築しました。

## 主な改良点

- ViewModel を導入し、UI 状態とロジックの管理を改善
  → ビジネスロジックを UI から分離することで、テストや保守がしやすくなりました。
- アーキテクチャの分離による保守性の向上
  → 状態の変更が ViewModel に集約されており、UI 側はシンプルに保たれています。
- ライフサイクルへの強さ、画面回転などにも対応
  → Compose の State と ViewModel により、状態が自動的に保持されます。

