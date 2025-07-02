pip install -r requirements.txt　を実行
次に、publicフォルダを手動で作成。（これが後にcf pagesのアウトプットディレクトリになる。）
次に、静的サイトを生成するために以下のコマンドをcf pages実行
python manage.py distill-local --force public

cf pages側の設定で、環境変数でPYTHON_VERSION（必ず大文字）でパイソンのバージョンを指定する

多分これで完成。
