# go-node-postgresql-dev-env

## project_nameを修正する。

```
find . -type f -print0 | xargs -0 sed -i -e "s/\[\[project_name\]\]/test_sample/" 
```

## go プロジェクトの初期化

```
mkdir project_dir
cd project_dir
go mod init

```

## frontend プロジェクトの作成


