pip install -r requirements.txt　を実行
次に、publicフォルダを手動で作成。（これが後にcf pagesのアウトプットディレクトリになる。）
次に、静的サイトを生成するために以下のコマンドを実行
python manage.py distill-local --force public

多分これで完成。
