# SERU_work
### これはROSを使ったPub&Sub通信です.
### 〇使用方法(Ubunth16.04で操作してください)
#### 1.まずROSをインストールしておいてください(catkinワークスペースの名前は"catkin_ws"としてください)
#### 2.catkin_wsの中にあるディレクトリ"src"の中に本プログラム"SERU_work"をそのまま入れます
#### 3.端末を開いて"cd ~/catkin_ws"と入力します
#### 4."catkin_make"と入力します
#### 5.端末をもう2つ用意します
#### 6.それぞれに"roscore &","rosrun SERU_work SERU_talker","rosrun SERU_work SERU_listener"と入力します
#### 7.rosrun SERU_work SERU_talkerと入力した端末に表示される文字がそのまま
####   rosrun SERU_work SERU_listenerと入力した端末に送られます
