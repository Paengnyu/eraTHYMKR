YM rev.6,rev.6改,Mk-3 proto4用　STATUS_SPOILERテストパッチ    By  HEROHERO

　これは、eraMegaten0.295の中のSHOW_STATUS_SPOILER.ERBをYMに移植したものですが、
内部は大幅に改造してあります。

　・売却条件　および　恋慕・服従・淫乱・妄信・親愛　についてのみ対応しました。
　・よって、元パッチにあった助手条件表示はオミットしてあります。
　・親愛条件は恋慕取得後に表示されます。
　・妄信条件は、恋慕・服従・淫乱のいずれかを取得後に表示されます。
　・改行や表示に関してはYMのデフォルトをそのまま使った場合を考慮して設定しました。


　適用方法は、それぞれのVer.のYMのERBフォルダの下のどっかにあるABL_MENU.ERBを上書
きして、さらにそのフォルダにSHOW_STATUS_SPOILER.ERBをコピーするといいと思います。
但し、既にABL_MENU.ERBが改造されている場合には差分導入願います。
　まあ、CALLで２関数を呼び出してるだけですけど。

　なお、#LOCALSIZE関連をコメントアウトしてありますが、これはEmuera1755系が添付されている
YM rev.6などに配慮したものです。Emuera1800以降での起動ならばコメントアウトを解除すること
により、よりメモリ節約になるでしょう。


　このパッチを作るにあたって、eraMegaten作者ならびに、このファイルの元作者に深く感謝します。


