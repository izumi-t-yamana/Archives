### Git クライアントアプリの選定

伊藤さんが使用されていることから着目した。
少しレガシーな雰囲気も感じたり、国内限定かと思ったが、
こちらのページから今でも強力なアプリだと判定して導入することとした。

https://www.slant.co/topics/2089/~best-git-clients-for-windows


## git.exe がついてこなかった。

git.exe がついてくると思って「GitHub Desktop」をインストールした。
こちらに .exe が作成された。
tortoiseGitに設定するパスは下記を設定した。

C:\Users\t.yamana\AppData\Local\GitHubDesktop\app-3.2.0\resources\app\git\cmd


### GitHub との SSH 接続

こちらのサイトに則って進めました。
https://qiita.com/SkyLaptor/items/6347f38c8c010f4d5bd2

公開鍵は TortoiseGitにより生成しました▼
秘密鍵から再表示することもできますが、一応コピペ。

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQC8DmOXl0+h5Q+eTW8mKWnWPXDPCQgcBiVtq2pkHvWqqQB5GISqaJCrTH/xry6I+/zcjVGhOHPLffn5nG8voPN8jn49bSqVSyq+gD2LVjGRBLE/1QEXTd6s6pmzi88TB8RKpEFGqxrge0/WORg6xhfiFQoeS3d8F7nsQuBlyGKWjnp/okt19E3OmhsPPn7wSt+ewmac0dU/PfSptMAWSazPoaGwaV79JMnWah0YjsuXssqy6YImq9bwerjHUz/yR6svuPkUy9rE1WbD26+uyVwqARKuTymJEZn1+PzH5Ws1fPRy8az4CxDWGJbmzHFBR9mVxSgxbY0MiUE/0Lrtu1It rsa-key-20230405

GitHub へ上記を設定しました。

