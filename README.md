# 概要

このリポジトリはPythonプロジェクトのテンプレートである。  
Docker + poetryによるPython仮想環境のひな形を提供する。  
初回構築手順を、[環境構築手順](/doc/環境構築手順.md)に示す。

## 導入されるライブラリ

このテンプレートには以下に挙げるライブラリが含まれる。

* フォーマッタ
    * `balack`
    * `isort`
* リンタ
    * `flake8`
    * `mypy`

`flake8`にはいくつかプラグインを導入する。  
詳細は`pyproject.toml`を参照のこと。

## 参考資料

* [poetry](https://python-poetry.org/)
* [Docker docs](https://docs.docker.com/)
* [VS Code Remote Development](https://code.visualstudio.com/docs/remote/remote-overview)
