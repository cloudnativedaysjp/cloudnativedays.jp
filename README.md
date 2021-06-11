# cloudnativedays.jp

このリポジトリは、 CloudNativeDaysおよび2019年イベントページ（CNDF2019、CNDT2019、CNDK2019）のウェブサイトをホストします。

## Contributing

[CloudNativeDays のウェブサイト](https://cloudnativedays.jp/)は [Hugo](https://gohugo.io/) を用いて作成します。各セクションのコンテンツを変更する場合、 https://github.com/cloudnativedaysjp/cloudnativedays.jp/tree/master/content/sections 内のマークダウンファイルを編集してください。

CI/CDはGitHub Actionsを使っています。PRを作成するとS3にプレビューがデプロイされます。また、PRをマージすると自動的にGitHub Pagesにデプロイされます。

2019年のイベントページはhttps://github.com/cloudnativedaysjp/cloudnativedays.jp/tree/master/docs 内にディレクトリがあります。HTMLファイルを直接修正してPRを作成してください。

2019年のイベントページは `https://cloudnativedays.jp/cndf2019/`のようにイベント毎にパスを用意しました。2020年以降のイベントは`https://cndf2020.cloudnativedays.jp/`のようにサブドメインを用意して提供します。これは、各イベントのウェブサイトを別々のリポジトリで管理することと、GitHubPages以外の方法でもホストできるようにすることが目的です。

新しくイベント用のページを作る場合、リポジトリを作成してGitHubPagesの設定を行ってください。ページ用のサブドメインについて[GitHubPagesへのAレコードを作成](https://help.github.com/ja/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site)し、リポジトリのGitHubPages設定でカスタムドメインにサブドメインを入力すればOKです。DNSの設定はImpressの技術部に依頼する必要があります。cloudnativedaysのSlackで依頼してください。

# Links

- [CNDT2020](https://github.com/cloudnativedaysjp/cndt2020.cloudnativedays.jp)
