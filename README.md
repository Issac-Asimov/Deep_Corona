# README.md
# -*- coding: utf-8 -*-
# author: Shin Asakawa <asakawa@ieee.org>
# CreationData: 22 Feb. 2016

このファイルはPDFファイルを作成する方法について記述しています。

動作確認
=======

OS: Mac OSX 11.10, Ubuntu 14.04, 15.10
LaTeX: Texlive2015

で動作確認しました。
texlive2013 では PDF 形式の画像ファイルの取り込みに失敗します。

定義ファイル
==========

独自に定義したファイルを main.tex で読み込んでいます。
terms.sty: 専門用語の定義
listing_settings2.sty: 本文中の実行例を示す lstlisting 環境の定義ファイル


ディレクトリ構成
=============
fig: 画像ファイルが入っています


main.tex 中にある FULLVERSION 変数について
=======================================
執筆途中に作成した変数で，この変数が 真 True なら全体をコンパイルします。
偽 False であれば部分的にしかコンパイルしません。従って貴社では
常に True にしておいてください。

必要なファイル
============
Makefile


Makefile 内での設定
=================
異なる OS で動作することを確認するために，設定を冒頭部分で行っています。


# Deep_Corona
