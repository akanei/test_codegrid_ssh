﻿# 最初から始める場合
*　githubにリポジトリ作ってそっからgit cloneするだけ

# 途中から始める場合
* git create repository here済みのgitプロジェクトをgithub.com~.gitにpushするだけ

# ssh接続
*　概要githubにマスター公開鍵を登録→個人秘密カギを使いたい人にわたす
## ssh鍵の作成
* D直下に.sshなど適当な名前でディレクトリ設定
> SSHKeyは通常、ホームディレクトリ*の直下の「.ssh」という隠しフォルダの中に格納されるので確認してみてください。
* コマンドで制作　ssh-keygen -t rsa
* できなければ、gitのbinにパス通すhttps://qiita.com/digdagdag/items/9e5c061e7d86e0af9a57
* マスターは.pub(公開鍵/githubに登録) 

# githubに公開鍵を登録

# git clone時に秘密鍵で開ける
# tortoisegitで利用
* 生成した秘密鍵をtortoisegitで扱うppkファイルに変換
* puttygen.exeで読み込んで変換して保存
http://techn-tack.hateblo.jp/entry/2017/02/26/002511
* ppkファイルをclone時にload putty keyで設定!


# その他　gitFAQ
## マージ
* 同じ行を修正したとき以外は自動でマージしてくれる

# 直接編集


