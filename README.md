# Bootstrap_custom_builder

bootstrap の scss を簡単にカスタムマイズ、ビルドする。


# Features

参考にさせていただきました。
ありがとうございます。
https://oopsoop.com/how-to-customize-bootstrap-5-with-sass/


# Requirement

* node.js
* sass
* bootstap (任意のバージョン)


# Installation


# Usage

1. git からクローンする
2. bootstrap パッケージを入手(任意のバージョン)
3. bootstrap パッケージの中身を /bootstrap ディレクトリにそのままコピー(必要なファイルだけでも大丈夫です)
4. /custom.scss に変更したい設定を記述
5. ターミナルでnpm run コマンドを実行、/_build_css ディレクトリにcssファイルがコンパイルされる
  * npm run sass (css)
  * npm run minify (minify)


# Note

/custom.scss ファイルで bootstrap パッケージ 内の /scss/bootstrap.scss ファイルを読み込んでいます。
パスが異なる場合は適宜変更してください。

@import "./bootstrap/scss/bootstrap";


# Author

* rhdddddddd
* https://github.com/rhdddddddd


==========================================================================


# Bootstrap_custom_builder

Easily customize and build bootstrap's scss.


#Features

I was allowed to reference.
thank you.
https://oopsoop.com/how-to-customize-bootstrap-5-with-sass/


# Requirement

* node.js
* sass
* bootstap (any version)


# Installation


# Usage

1. Clone from git
2. Get the bootstrap package (any version)
3. Copy the contents of the bootstrap package to the /bootstrap directory (it is okay to just use the necessary files)
4. Write the settings you want to change in /custom.scss
5. Execute the npm run command in the terminal, the css file will be compiled in the /_build_css directory.
   * npm run sass (css)
   * npm run minify (minify)


# Note

The /custom.scss file is loading the /scss/bootstrap.scss file in the bootstrap package.
If the path is different, please change it accordingly.

@import "./bootstrap/scss/bootstrap";


# Author

* rhdddddddd
* https://github.com/rhdddddddd

