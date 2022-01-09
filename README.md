# go-node-postgresql-dev-env

## __project_name__を修正する。

```
find . -type f -print0 | xargs -0 sed -i -e "s/__project_name__/test_sample/" 
```

## go プロジェクトの初期化

```
mkdir project_dir
cd project_dir
go mod init

```

## frontend プロジェクトの作成


