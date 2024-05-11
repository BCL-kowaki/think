# 20240511 Git&GitHub学習

## GitとGitHubを用いたプロダクトを作り始める

- GitHub 上にプロダクト用のリポジトリを作成

- 作成したリポジトリをクローンする

git clone 自分のリポジトリURL  
→ GitHub上で作成したリポジトリを手元で操作できるようにクローンという作業が必要


## GitHubへプロダクトをpush

- ファイルを add する方法

git add .  
git commit -m "更新内容を記載"
git push origin main  
→上記を打ち込めばGitHubのリポジトリに同期される

## 重要項目

- ディレクトを整理

cd ~/Desktop/  
→ 作業場所のパスを決める

## リポジトリを作成する前にコードを書いていた場合

- 手元のプロダクトのディレクトリでローカルリポジトリを作成しなければならない。  
git init  

- リモートリポジトリとローカルリポジトリを連携させる
git remote add origin リポジトリURL




