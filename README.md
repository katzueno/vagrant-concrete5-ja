# Vagrant + Concrete5 (Japanese / 日本語)

宮内さんが作成した vagrantfile に修正を加えて concrete5 日本語パッケージをインストールできるようにしたものです。

## 使い方

1. VirtualBoxをインストール
 * [https://www.virtualbox.org/](https://www.virtualbox.org/)
2. Vagrantをインストール
 * [http://www.vagrantup.com/](http://www.vagrantup.com/)
3. Chef Development Kit をインストール
 * [http://www.getchef.com/downloads/chef-dk/mac/](http://www.getchef.com/downloads/chef-dk/mac/)
4. 下記コマンドをいれて vagrant pluginsをコマンドラインからインストール
 * `vagrant plugin install vagrant-omnibus`
 * `vagrant plugin install vagrant-berkshelf`
5. このレポジトリをローカルにクローン
 * `git clone https://github.com/katzueno/vagrant-concrete5-ja.git`
6. ディレクトリーに移動
 * `cd vagrant-concrete5`
7. cookbooks をインストール
 * `berks vendor cookbooks`
8. Vagrant 環境を起動.
 * `vagrant up`
9. アクセス先は [http://127.0.0.1:8080/](http://127.0.0.1:8080/)
10. ログイン後[管理画面 (Dashboard)]-[システムと設定(Systsme & Setting)]-[言語(Language)]メニューおり、日本語を設定してください。

## 設定

各属性の説明は下記を参照

[https://github.com/Launch-with-1-Click/concrete5](https://github.com/Launch-with-1-Click/concrete5)

## 作成者

* [@miya0001](https://github.com/miya0001/) * 作者
* [@katzueno](https://github.com/katzueno/) * 日本語版作成
