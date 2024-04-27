# renpy-live-viewer

Ren'Pyのゲームと通信をして、リアルタイムに画面を表示するツールです。

ゲームには[mttldev/reed](https://github.com/mttldev/reed)が導入されている必要があります。

# 使い方

1. Ren'Pyのゲームを起動するか、`Start game`コマンドでゲームを起動します。
2. `Connect to reed server`コマンドでreedサーバーに接続します。
3. VSCode上でカーソル位置が変更された際に、リアルタイムに画面が更新されます。  
   または、`Jump to label`コマンドで指定したラベルにジャンプします。

# こんとりびゅ～と

VSCodeの拡張機能を作るのが初めてかつ、このプロジェクト自体、自分が使う専用（オレオレ拡張機能）なので、正常に動作しない場合や、不具合がある場合があるかもしれません。  
気づいたらIssueやPRを送っていただければ、対応します。
