# 問題

![](img/img1.png)

# 解き方

Twitterでこのような検索をすると、下記のようなツイートを見つけた。

![img/img2.png](img/img2.png)

コードと公開というキーワードからgithubに公開したのだろうと推測。

TwitterIDで使われている「MoriSho」をgithubに検索すると。

bioの@MoriSho17795702という文字とTwitterIDが同じアカウントを見つけた。

![](img/img3.png)

これは、同一人物であることが分かる。

一つだけ公開レポジトリがあり、ここに問題のコードがあると推測。

コミットログを見ると「Delete a file」というコミットメッセージを見つけた。

何かを削除した痕跡と推測。

![](img/img4.png)

このコミットから、Javaのコードが復元できる。

![](img/img5.png)

どうやら、これがやらかしてしまったコードらしい。

loadCredentialsという関数に着目し

この関数のドキュメントを検索すると引数1つ目がパスワードなる。

https://docs.web3j.io/transactions/credentials/#use-walletutils-functionality

# trustno1$$letmein

