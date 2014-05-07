fuel_php_for_git_prj
====================

## 作り方

ここ参考
http://dev.classmethod.jp/server-side/framework/fuelphp003/

####

## セットアップ

####僕のgithubリポジトリからcloneする
`
git clone https://github.com/zooloo/fuel_php_for_git_prj.git [my_project]
`

####git submodule化した箇所をcloneする（割りと自動的）
`
cd [my_project]
`

`
git submodule init
`

`
git submodule update
`

※ここでwebで見てcomposer関係のエラーが出るようなら、下記コマンド

`
php composer.phar update
`

submoduleのversionチェック
