# railsBulletinBoard
## サイトURL
[掲示板](http://qanda-1234587.herokuapp.com/)<br>
`http://qanda-1234587.herokuapp.com/`

## 環境構築
### Railsバージョンアップ
`$ gem install rails -v 5.2.5`  
### ImageMagickをインストール
```
username:~/environment $ sudo yum -y install libpng-devel libjpeg-devel libtiff-devel gcc
username:~/environment $ cd
username:~ $ git clone https://github.com/ImageMagick/ImageMagick.git ImageMagick-7.0.11
username:~ $ cd ImageMagick-7.0.11
username:~/ImageMagick-7.0.11 $ ./configure
username:~/ImageMagick-7.0.11 $ make
username:~/ImageMagick-7.0.11 $ sudo make install
```
#### 確認
`username:~/ImageMagick-7.0.10-24 $ convert -version`

### Railsアプリ作成
`username:~/environment $ rails new アプリケーション名`
