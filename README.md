# アカウントに紐付けられたGithubページを作成する

リポジトリごとではなく、アカウントに紐付けられたGithubページを作成する方法。

1. リポジトリ作成（「account-id.github.io」という名前にする。「account-id」は自分自身のアカウントのID）
2. ローカルでコマンド実行
    $ git init
    $ git remote add origin https://github.com/account-id/account-id.github.io.git
3. git cloneするなどしてページを作成、pushする
4. アクセスする。＞ [Githubポータル](https://arm-band.github.io/)

## 参考

- [GitHubを使って3分でHPを公開する。 \- Qiita](http://qiita.com/budougumi0617/items/221bb946d1c90d6769e9)
- [GitHub Pages \| Websites for you and your projects, hosted directly from your GitHub repository\. Just edit, push, and your changes are live\.](https://pages.github.com/)