# 新規iOSアプリ実装前に決めることリスト

## 前提

### プロジェクトの性質
（規模、期間、運用の有無、注力する点、制約、一般的なプロジェクトとの違いなど）

### プロダクトの性質
（使う技術、Framework、対応OS、対応端末）

### 開発者のモチベーション
（やりたいこと、最近の流行、前のプロジェクトの反省点）


## 決めること

### 開発手法

- GitHubFlow
- コードレビュー
- ペアプログラミング
- スクラム
- テスト駆動開発（TDD）
- ...

### タスク管理ツール

- spreadsheet
- zenhub
- trello
- github issue
- カンバン
- ...

### 開発ツール

#### ライブラリ管理

- CocoaPods
- Carthage
- (Swift Package Manager)

#### リソース管理

- SwiftGen
- R.swift
- L.swift
- ...

#### バージョン管理

- github
- gitlab
- bitbucket
- ...

#### コーディング支援

- swiftlint
- ...

#### UI開発

- Reveal
- PaintCode
- CoreAnimator / QuartzCode
- Tweak
- ...

#### UITest

- appium
- KIF
- ...

#### CI

- CircleCI
- bitrise
- Jenkins
- fastlane
- ...

#### CD

- Fabric
- DeployGate
- TestFlight
- ...


### ライブラリ

#### テスト

- Quick / Nimble
- ...

#### 通信

- Alamofire
- APIKit
- ...

#### 画像読み込み

- Kingfisher
- Nuke
- ...

#### JSONエンコーダー

※ swift4では必要なくなる？

#### DIコンテナ

- swinject
- ...

#### FRP

- ReactiveSwift / ReactiveCocoa
- RxSwift / RxCocoa
- ReSwift
- ...

#### 計測・クラッシュ管理

- Firebase
- Crashlytics
- Google Analytics
- ...

#### PUSH通知

- Firebase
- Amazon SNS
- ...

#### UI実装

- POP
- ...


### アーキテクチャ / デザインパターン

- MVVM
- MVC
- MVP
- VIPER
- Clean Architecture
- Redux
- ...

### フレームワークの分割

- リポジトリから分割
- targetで分割
- 分割しない

### コーディング規約

- Swift API Design Guideline
- Wantedlyコーディング規約
- GitHub
- Ray Wenderlich

###  やりたい書き方

- storyboardの使い方
- 色やフォント等の管理
- TabieView/CollectionViewのDataSourceの実装方法
- テストをどれくらい書くか
- ...

### 参考にするアプリ
