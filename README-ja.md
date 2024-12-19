# CaptionGen_GCE

**CaptionGen_GCE** は、Google Colab の GPU 環境で動作する、InstructBLIP モデルを用いた画像キャプション生成アプリケーションです。ローカル環境や Google Drive から画像フォルダを選択し、詳細なキャプションを生成することができます。


## 特徴

*   **InstructBLIP モデルの採用**: 高性能な視覚言語モデルである InstructBLIP を使用し、詳細な画像キャプションを生成します。
*   **Google Colab Pro の GPU 環境に最適化**: 強力な GPU を活用することで、高速なキャプション生成を実現します。
*   **簡単な操作**: Google Colab ノートブック上で、数ステップでキャプション生成を実行できます。
*   **ローカル/Google Drive からのフォルダ選択**: ローカル環境から画像をアップロードするか、Google Drive 内のフォルダを選択することができます。
*   **バッチ処理**: 複数画像をまとめて処理し、効率的にキャプションを生成します。
*   **キャプションの保存**: 生成されたキャプションは、画像ファイル名と関連付けられたテキストファイルとして保存されます。


## 動作環境

*   **Google Colab Pro**: GPU ランタイム (T4 以上を推奨) が必要です。
*   **ブラウザ**: Google Chrome, Firefox, Safari など、Google Colab をサポートするブラウザ。


## セットアップ方法

1. **Google Colab Pro への登録**: 本アプリケーションは Google Colab Pro の GPU 環境を必要とします。
2. **リポジトリのクローン**: 以下のコマンドで、このリポジトリをクローンします。
    ```bash
    git clone https://github.com/yf591/CaptionGen_GCE.git
    ```
3. **Google Colab でのノートブックの実行**: `caption_gen_app.ipynb` を Google Colab で開き、手順に従って実行します。


## 使用方法

1. **必要なライブラリのインストール**: ノートブックの最初のセルを実行して、必要なライブラリをインストールします。
2. **画像フォルダの選択**:
    *   **ローカルからアップロードする場合**:
        1. 4つ目のセルを実行します。
        2. `1` を入力し、Enter キーを押します。
        3. 表示されるファイルアップロードボタンをクリックし、画像を含むフォルダを zip 化したファイルを選択します。
    *   **Google Drive から選択する場合**:
        1. 4つ目のセルを実行します。
        2. `2` を入力し、Enter キーを押します。
        3. 表示されるプロンプトに、Google Drive 内の画像フォルダのパスを入力します (例: `MyFolder/Images`)。
3. **キャプションの生成**: 5つ目のセルを実行して、キャプションを生成します。生成されたキャプションは、`output_captions` フォルダ内に、画像ファイル名と関連付けられたテキストファイルとして保存されます。


## ライセンス

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

このプロジェクトは [MIT ライセンス](https://opensource.org/licenses/MIT) のもとで公開されています。


## 免責事項

このアプリケーションの使用により生じたいかなる損害についても、作者は責任を負いません。自己責任でご利用ください。