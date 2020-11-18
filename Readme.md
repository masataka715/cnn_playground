- フォルダ作成した後に、以下のコマンドでfickr APIから画像取得
```
$ python download.py [キーワード]
```

- classesを指定してから、以下のコマンドで画像をnpyファイルに変換
- VGG16モデルの入力サイズ224*224に変換している
```
$ python generate_data_224.py
```

- classesを指定してから、以下のコマンドでモデルをh5ファイルで作成
```
$ python vgg16_transfer.py
```

- classesを指定してから、以下のコマンドで
```
$ python predict.py [画像ファイルのパス]
```