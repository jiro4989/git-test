# git-test

別リポジトリからコミットログを残しつつ複製するのを試しただけ。

以下の手順で実施

```bash
mkdir git-test
cd $_
echo test > README.md
git init
hub create

# リポジトリ作成元
cd ../textimg

git remote add testrepo https://github.com/jiro4989/git-test
git push testrepo master
```
