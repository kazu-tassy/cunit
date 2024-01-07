# CUnit手順
## インストール

2024/1/8

1. ダウンロード

    $wget http://jaist.dl.sourceforge.net/project/cunit/CUnit/2.1-3/CUnit-2.1-3.tar.bz2

1. 解凍

    $tar xvf ./CUnit-2.1-3.tar.bz2
    
    $cd CUnit-2.1-3/

1. インストール

    $sudo apt install libtool -y
    $autoconf
    $automake
    $./configure
    $make
    $sudo install

1. 環境変数の設定(.bashrc)

    export LD_LIBRARY_PATH=/usr/local/lib

1. 環境変数の反映

    $source ~/.bashrc