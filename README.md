# Qt5.12 & QtCreator4.8.0 Binary

## Download

https://drive.google.com/open?id=1uyEYPNcmZPd1ox-wb06nRHEuonPtXhDv

↑ 二つファイルがあるけどどっちも同じで， QtCreator のためのファイルがないので
https://drive.google.com/drive/folders/1wLdFNFmEAUAL09VdvzmBX8mujY5YkC2Y?usp=sharing

ここからダウンロードを TODO: あとで， まとめる

## Install

落とし方は色々あるけど， とりあえず一つの方法として

- 自PC に落とす
- sftp かなんかで ラズパイに送る
- ラズパイ上で解凍
- 中身を ↓ のようにコピる

※ ファイルサイズが大きくなってるので， 時間がかかるし破損する可能性があるので注意を

### Qt

1. copy a directory to `/usr/local/`
2. add to PATH

`PATH=/usr/local/Qt{virsion}/bin:$PATH`

`export PATH`

### QtCreator

copy directories to `/usr/local/`
