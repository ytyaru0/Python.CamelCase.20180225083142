# このソフトウェアについて

* プログラミング言語で使える変数名か判断（[a-zA-Z_]+[a-zA-Z0-9_]*）
* 命名規則で用いられる記法の解析（形態素解析）
* 命名規則で用いられる記法の相互変換
* 翻訳（英語←→日本語）

# 参考

## 単語の分割

* [キャメルケース](https://ja.wikipedia.org/wiki/%E3%82%AD%E3%83%A3%E3%83%A1%E3%83%AB%E3%82%B1%E3%83%BC%E3%82%B9)

記法|説明
----|----
CamelCase|複数ある単語のそれぞれ先頭1字のみ大文字。他は小文字|`MyName`
UpperCamelCase|複数ある単語のそれぞれ先頭1字のみ大文字。他は小文字|`MyName`
LowerCamelCase|複数ある単語のそれぞれ先頭1字のみ大文字。他は小文字。ただし最初の単語は先頭も小文字。|`myName`
SnakeCase|`_`で単語を区切る|`my_name`, `MY_NAME`
ChainCase|`-`で単語を区切る|`my-name`, `MY-NAME`

## 単語の記法

記法|説明|Pythonメソッド
----|----|--------------
lower|すべて小文字|`name`|str.lower()
upper|すべて大文字|`NAME`|str.upper()
？|先頭1字のみ大文字。他は小文字|`Name`|str.title() 

https://note.nkmk.me/python-capitalize-lower-upper-title/

## 対象外

なお、[ハンガリアン記法](https://ja.wikipedia.org/wiki/%E3%83%8F%E3%83%B3%E3%82%AC%E3%83%AA%E3%82%A2%E3%83%B3%E8%A8%98%E6%B3%95)は対象外。

# 開発環境

* [Raspberry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 3 Model B
    * [Raspbian](https://www.raspberrypi.org/downloads/raspbian/) GNU/Linux 8.0 (jessie)
        * [pyenv](http://ytyaru.hatenablog.com/entry/2019/01/06/000000)
            * Python 3.6.4

# ライセンス

このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

