# Mobile Engineer 採用面接ガイド

このドキュメントではand factoryのMobile Engineer採用プロセスにおける面接について説明します。

## 目的

この文章は以下の事を目的としています。

- 面接において応募者に高いパフォーマンスを発揮してもらうこと
- 面接がより効率的で有意義なものになること
- 面接の場でお互いをより深く理解できること

## 一次面接

### 出席者

応募者1名に対し、Mobile Engineerと人事担当の2名が面接官として参加いたします。

### 服装・持ち物

リラックスできる服装でお越しください。また、ご持参いただくものはございません。

- 服装は自由です。スーツでも私服でも構いません。
- 履歴書・職務経歴書の持参は不要です。事前に提出いただいたドキュメントは面接官に渡されています。
- PCやノートでメモを取っていただいても構いません。

### 時間割

一次面接は以下の時間割にて進行します。

1. 会社説明（10分）
2. 面接官から応募者への質問（40分）
   1. 一般的な質問
   2. 技術/プロジェクト運用に関する質問
3. 応募者からand factoryへの質問（10分）

### 1. 会社説明

[Company Profile](https://github.com/andfactory/handbook/blob/master/company-profile.md) を用いた会社説明を行います。面接の時間をより有意義にするため事前に目を通していただきますようよろしくお願いいたします。

同ドキュメントの内容に関して質問をご用意いただいていた場合、この時点でご回答します。

応募者の知識レベルによってはこのステップを省略する、またはこのステップの時間すべてを応募者からの質問にあてることがあります。

### 2. 面接官から応募者への質問

#### i. 一般的な質問

皆様にお尋ねしている質問です。

- and factoryを認知した経路、応募した理由について
- 転職する会社の判断軸・ポイント（技術・事業フェーズ・事業領域）
- 今までのキャリア
- 今後のキャリアパス

#### ii. 技術/プロジェクト運用に関する質問

応募者の方に技術やプロジェクト運用に関する経験や知識の質問をします。主に以下の観点があります。

- アーキテクチャ
- データベース
- 通信
- DI
- テスト
- CI
- UI/UX
- アジャイル
- マネジメント

経験のあること、その結果わかったことなどをお話しください。

### 3. 応募者からand factoryへの質問（10分）

応募者からand factoryへの質問に回答します。

どんな質問でも構いませんが、その場で回答できない質問については社内で適切な社員に確認したうえで面接後に回答します。

また、この場で質問しそびれても心配しないでください。採用プロセスのいかなるタイミングでも質問を受け付けています。

## 技術力調査

後日、一次面接後に技術力調査のための課題を出させていただく場合があります。

### 出題例(Android)
#### Overview

課題を通してAndroid開発における技術力を確認させていただければと思います。
以下の要件(Must)を満たすアプリケーションを作成し、github個人アカウントのRepositoryで管理、共有していただきたく段取りとなります。

#### Requirements
| title | importance | notes |
| --- | --- | --- |
| 開発言語:Kotlin | Must | - |
| 任意の`username`に関連するGithubのRepository一覧を表示する | Must | https://developer.github.com/v3/ |
| 項目をタップ時に`README.md`を表示する | Must | 画面遷移あるいはDialogによるWebViewでの表示 |
| MVP, MVVM, Fluxなどのアーキテクチャパターンを導入する | Must | https://github.com/googlesamples/android-architecture |
| dependency injection design patternを使う | Must | dagger2やKodeinなどのDIコンテナを使用する |
| Viewの生成に[epoxy](https://github.com/airbnb/epoxy)を使用する | Could | Android library for building complex screens in a RecyclerView |
| お気に入りにする | Could | `AAC Room` or `Realm` or `ORMA`などを用いてアプリ内DBの構築。 |
| オフライン時に項目をタップでSnackbarでアラートを表示する | Could | - |
| MVP, MVVM, Fluxなどのアーキテクチャパターンを導入する | Could | - |
| 一覧表示時のアニメーション | Could | Slide Upなど |
| 項目をDrag＆Dropして並び替える | Could | - |
| Unit Testing | Could | - |
