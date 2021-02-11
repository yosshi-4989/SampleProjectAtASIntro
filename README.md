# スパーク学習用ブランチ

# 学習に使用する書籍

- [アプリケーションエンジニアのためのApache Spark入門](https://www.amazon.co.jp/dp/4798053775)
- [入門 PySpark ―PythonとJupyterで活用するSpark 2エコシステム](https://www.amazon.co.jp/dp/4873118182)

# 環境構築

学習環境は、PySparkのJupyter Notebookを利用できるDockerを利用する。<br>
検証したコードはGit管理したいので、作業ディレクトリをマウントしておく。

```bash
$ git clone https://github.com/yosshi-4989/SampleProjectAtASIntro.git
$ docker run --name spark_test -it -p 8888:8888 -v $PWD:/home/jovyan/work jupyter/all-spark-notebook:016833b15ceb
```

# 参考文献

- 環境構築
  - [Docker で始める PySpark 生活](https://qiita.com/tsuchiyaTaro/items/7ae353039b418205246b)
