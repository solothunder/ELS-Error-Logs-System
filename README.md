# ELS-Error-Logs-System

Manual - 説明書

Japanese - 日本語

記述:
Ping機能がVersion 1.0 から追加されました
（linux等では引数の-nを-cに変更し-wから先を削除してください）

まず、ELS(Error Logs System)をダウンロードしていただき、誠にありがとうございます。
このテキストファイルでは、ELSの起動・使用方法をご説明させていただきます。
----------------------------------------------------------------------------------
起動方法
1:まず、PythonがPCに入っていない方はPythonの最新版(2022年9月26日現在 Python3.10.7)をインストールしてください。
-----------------------------------------------------------------------------------------------------
Python Orgからのインストール方法                                                                   
https://www.python.org/downloads/　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　  
にアクセスしてDownload Python 3.10.7を押してダウンロードし、指示に従ってインストールしてください 。
説明サイトはこちらです　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　               
https://www.python.jp/install/windows/install.html                                                 
説明しているのは古いPythonですが、インストールは基本的に変わりません。                             
-----------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------
Microsoft Storeからのインストール方法                                                                        
Microsoft Storeを開いて、検索欄にPythonと入力し一番最新(2022年9月現在 Python3.10)をインストールしてください。
---------------------------------------------------------------------------------------------------------------
インストールが完了または既に完了している方は 2
できない人は 4
2:プログラムの起動
まずいまプログラムが開いてあるパスをコピーします
エクスプローラーでは上の PC > OOOOOO > elspro のようなものの端（文字が書かれていないところ）を押して選択されたら右クリックをしてコピーをしてください
プログラムを起動します            ↓パス 
コマンドプロンプトを起動してcd C:\OOOO\OOOOO\OOOOO\elspro を実行してください（パスは自分のものです）
そしてそのパスに移動出来たら
python3 main.py を実行してください
そして起動したら自動的に検査します
3:自作ソフトなどとの連携
検査する内容は人それぞれで違いますが、
同じPythonだと
import ファイル名 などでよみこんで実行してください詳しくは
https://qiita.com/karadaharu/items/37403e6e82ae4417d1b3 がいいでしょう
4:起動しないとき
基本的には原因は同じ場合が多いです
管理者権限で実行できなくてとかです
インストール画面で Add Python 3.x PATHにチェックを入れなかった場合もダメです
そもそもインストールしてないなどいろいろあります
多すぎるのであとは Google先生に任せてください。
5:注意事項
-----------
1:処理中にプログラム（Python）を停止させない
処理中にプログラムを停止させるとファイル作成中などの場合にはファイルが破損する可能性があります。
2:設定ファイルなど必要なファイルを削除または移動はしない
削除等をした時には設定ファイルなどがリセットされるまたはプログラムが正常に動かなくなる原因になります。
3:必ず最新版のPythonを使ってください
最新版でないとバグ、またはライブラリが正しく動作しないまたは動かない原因になります。(2022年9月現在ではPython3.10が最新版です)
-------------------------------------------------------------------------------------------------------------------------------------------------------------

English

First of all, thank you very much for downloading the ELS (Error Logs System).
This text file will explain how to start and use ELS.
----------------------------------------------------------------------------------
How to start up
1: First, please install the latest version of Python (Python 3.10.7 as of September 26, 2022) if you do not have Python on your PC.
-----------------------------------------------------------------------------------------------------
How to install from Python Org                                                                   
https://www.python.org/downloads/　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　  
and press Download Python 3.10.7, then follow the instructions to install.
The instruction site is here　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　               
https://www.tutorialspoint.com/how-to-install-python-in-windows                                                
The installation is basically the same, although it is older Python that is being described.                             
-----------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------
How to install from Microsoft Store                                                                        
Open the Microsoft Store, type Python in the search field and install the latest version (Python 3.10 as of September 2022).
---------------------------------------------------------------------------------------------------------------
If you have already installed or completed the installation, click 2.
4 if you are unable to do so.
2: Start the program
First, copy the path where the program is now open
In Explorer, press on the edge of something like PC > OOOOOO > elspro above (where there is no text) and when it is selected, right click and copy
Start the program ↓path 
Start a command prompt and do cd C:\OOOOOOO\OOOOO\OOOOO\fww (the path is yours)
And if you can navigate to that path
Run python3 main.py
Then, when it starts up, it will automatically inspect it.
3:Cooperation with your own software
What you check will vary from person to person, but it can be as simple as
If it is the same Python, you can use
import file name, etc. and run it.
https://qiita.com/karadaharu/items/37403e6e82ae4417d1b3 is a good place to start.
4:When it does not start
Basically, the cause is the same in many cases.
For example, you can't run Python 3.x with administrator privileges.
If you did not check the Add Python 3.x PATH checkbox on the installation screen, it is also not working.
You didn't install it in the first place, and so on.
There are too many to list here, so leave the rest to Dr. Google.
5:Notes
-----------
1:Do not stop the program (Python) during processing
Stopping the program during processing may cause file corruption if a file is being created.
2:Do not delete or move necessary files such as configuration files.
Deleting or moving files may reset the configuration files or cause the program to stop working properly.
3:Always use the latest version of Python.
If you do not have the latest version of Python, it may cause bugs or libraries that do not work properly or do not work. (As of September 2022, Python 3.10 is the latest version.)
 -------------------------------------------------------------------------------------------------------------------------------------------------------------
