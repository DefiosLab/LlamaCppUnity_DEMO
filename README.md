# LlamaCppUnity_DEMO
ユニティちゃんと簡単な会話ができるデモアプリです。  
モデルは[`ELYZA-japanese-Llama-2-7b`の2bitモデル](https://huggingface.co/mmnga/ELYZA-japanese-Llama-2-7b-instruct-gguf/tree/main)を使用しています。  
GGUFファイルはアプリ初回起動時に別途ダウンロードされます。  

## 動作要件
WindowsとAndroidに対応しています。  
### Windows
 - OS:Windows10
 - CPU:x86-64
 - MEM:8GB以上
### Android
 - OS:Android10
 - CPU:arm64-v8a
 - MEM:8GB以上

## コマンド
アプリ内のチャット欄でモデルの操作ができます。モデルの読み込みに失敗したときに使用してください。
 - `/download`:モデルをダウンロードします。
 - `/reload`:モデルを再読み込みします。

## 注意事項
アプリを削除してもGGUFファイルは削除されないため、ダウンロード時に表示されるPathからご自身で削除をお願いします。

## アセット及びモデルのライセンス
- © Unity Technologies Japan/UCL
- 空想曲線 https://kopacurve.blog.fc2.com
- Llama 2 is licensed under the LLAMA 2 Community License, Copyright © Meta Platforms, Inc. All Rights Reserved.
