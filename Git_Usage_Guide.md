### 導入手順
* アカウント作成＆gitインストールは調べて
    * https://qiita.com/T-H9703EnAc/items/4fbe6593d42f9a844b1c
    * https://qiita.com/mokio/items/f6c67c8f9af050383fc0
* 適当なディレクトリ作成
* 初期化
"""
git init
"""
* リモートリポジトリをローカルリポジトリに追加
"""
git remote add origin https://github.com/YashyHoby/syoten-inventory-management-system.git"
"""
* 編集用ブランチ（develop）を作成、そのブランチへ移動
"""
git checkout -b develop
"""

### 編集後の追加処理
* 編集したファイルをすべて選択
"""
git add .
"""
* ローカルリポジトリにコミット
"""
git commit -m "コメント（変更内容等）"
"""
* リモートリポジトリにプッシュ(プルリクエスト)
"""
git push origin develop
"""