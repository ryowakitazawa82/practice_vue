【ls コマンド】
カレントディレクトにあるファイルを表示する。（listの略）

ls  #カレントディレクトリにあるファイルやディレクトリを表示する
ls -l  #ファイルやディレクトリの詳細も同時に表示する
ls -a  #隠しファイルも含めファイルやディレクトリを全て表示する
ls −la  #隠しファイルを含む全てのファイルやディレクトリの詳細を表示する


【cd コマンド】
カレントディレクトリにあるファイルに移動する。（change directoryの略）

cd test.html  # testテストというファイルに移動する
cd ~/  #ホームディレクトリに移動する
cd ..  #一つ上の階層のファイルに移動する


【pwd コマンド】
カレントディレクトリのパスを表示する。（print working directoryの略）

pwd  #カレントディレクトリのパスを表示する


【touch コマンド】
中身が空のファイルを作る。

touch test.html  #test.htmlという中身が空のファイルを作る


【mkdir コマンド】
新しい空のディレクトリを作る。（make directoryの略）
mkdir test #testというファイルを作る


【mv コマンド】
ファイルを移動したり、ファイル名を変更したりする。（moveの略）

mv test.html tmp/  #test.htmlというファイルを相対パスでtmp/に移動する
mv test.html test2.html  #test.htmlというファイルをtest2.htmlに名前変更する


【cp コマンド】
ファイルをコピーする。（copyの略）

cp test.html tmp/  #test.htmlを相対パスでtmp/というディレクトリの中にコピーする
cp test.html test2.html  #test.htmlをtest2.htmlという名前でコピーする
cp −r dir /tmp/  #dirというディレクトリとその中身を絶対パスで/tmp/にそっくりコピーする


【rm コマンド】
ファイルを削除する。（removeの略）
※rmコマンドは取り返しのつかないファイルの削除になります。コマンドにあまり慣れていない人は、使わないでください。

rm test.html  #test.htmlを削除する
rm -r test  #testというディレクトリとその中身を削除する
rm -f test  #testというファイルを警告なしで削除する
rm -rf test  #testというディレクトリとその中身を警告なしで削除する


【open コマンド】
ターミナルからFinderでファイルを開く。

open .  #現在のターミナルのディレクトリFinderで開く
open ~/  #ホームディレトリをFinderで開く


【source コマンド】
ファイルの設定を読み込み有効にする。

source ~/.bash_profile  #ホームディレクトリにある.bash_profileに書き込んだ設定を読み込み有効にする
source .bash_profile  #カレントディレクトリにある.bash_profile設定を読み込み有効にする
