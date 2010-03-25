# Gyazolife

gyazoっぽい感じではてなフォトライフにスクリーンショットをアップロードします。フォトライフのTwitter連携機能を有効にしておくと、Twitterへの自動ポストも可能です。

## DEPENDENCIES

以下のモジュールをあらかじめCPANからインストールしてください。

- WebService::Hatena::Fotolife
- Config::Pit

## USAGE

Config::PitをCPANらインストールした後、

    $ ppit set hatena.ne.jp

とすると、エディタが起動するので、以下のようなYAMLを記述してください。

    ---
    "username": はてなID
    "password": パスワード
    "gyazolife":
      "folder": アップロード先フォルダ(なければ空でいいです)

あとは、Gyazolife.appを/Application以下にコピーして適当に実行してください。

アップロード先フォルダを変更したい場合は、上記手順と同様ppit用いて、設定ファイルを変更してください。

## SEE ALSO

- Gyazo: http://gyazo.com/ja
- はてなフォトライフ: http://f.hatena.ne.jp/
- Twitter連携: http://f.hatena.ne.jp/guide/twitter

## COPYRIGHT AND LICENSE (The MIT License)

Copyright (c) Kintaro Kuribayashi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
