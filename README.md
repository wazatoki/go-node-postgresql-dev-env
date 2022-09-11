# go-node-postgresql-dev-env

## tmp_project_nameを修正する。

```
find . -type f -print0 | xargs -0 sed -i -e "s/tmp_project_name/test_sample/g" 
```

## go プロジェクトの初期化

```
mkdir tmp_project_name
cd tmp_project_name
go mod tidy

```

## frontend プロジェクトの作成

# anglar

```
ng new tmp_project_name
cd tmp_project_name
ng serve

```

# vue

```

npm create vite@latest tmp_project_name -- --template vue
cd tmp_project_name
npm install
npm run dev

```

# svelte

```
npm create vite@latest tmp_project_name -- --template svelte
cd tmp_project_name
npm install
npm run dev
```
