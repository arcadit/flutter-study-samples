# qiitaapp

FlutterによるQiitaクライアント

https://www.flutter-study.dev/create-app/qiita-app

## 環境

* fvm
* VSCode
* Xcode14.2
* Android Studio 2022.2.1

iOSシミュレーターで動作確認

## 構築手順

### Ruby

CocoaPodのバージョンに対応したRubyをインストール

1. rbenvをインストール（インストールしていない場合）

```
$ brew install rbenv ruby-build
```

2. .ruby-versionに対応したRubyのバージョンをインストール

```
$ rbenv install 2.7.8
```

### Flutter

1. fvmをインストール

```
$ brew tap leoafarias/fvm
$ brew install fvm
```

2. fvmで指定されたバージョンでflutterをインストール

```
$ fvm install 2.0.1
```

3. fvmで指定したバージョンでpubspecを最新化

```
$ fvm flutter pub get
```

4. CocoaPodをインストール

```
$ cd ios
$ bundle exec pod install
```

5. VSCodeもしくはコマンドラインで起動

iOSシミュレーターを起動

## VSCode

実行とデバッグ - Qiita App

## コマンドライン

```
$ fvm flutter run -t lib/main.dart
```

<img src="https://github.com/arcadit/flutter-study-samples/assets/8144028/0e9367e6-043d-484e-a4e1-db324f6fc266" width="400" />
