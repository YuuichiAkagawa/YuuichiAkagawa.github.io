---
layout: page
title: APLINKS for Win32
permalink: /pocketcom/plink/
---
![logo](/assets/images/APLINKSW32logo.gif) [ダウンロード](/assets/softlib/aplinksw32-1.01.exe) / [download(en)](/assets/softlib/aplinksw32-1.02e.exe)
### 概要
近 成人氏により開発された "Pocket Link System" の サーバプログラムである "APLINKS"のWin32 GUI版です。  
Win32 GUI版の特徴
- 完全32bit＆マルチスレッドアプリケーション
- Windows NT3.51以上(Intel)またはWindows9x上で動作
- バックグラウンド動作可能
- ドラッグ＆ドロップでファイルを指定可能
- 通信速度は38400bpsまでサポート
- 512KBモードのサポート(但し、ポケコン側のドライバが対応している必要あり)
- タイムスタンプのサポート 

※重要※
Windows 10ではWindowsヘルプがサポートされなくなりました。ヘルプの表示はできません。 

Windows Vista以降、WinHelpが標準でインストールされなくなってしまったため、別途インストールが必要です。
ヘルプの表示が必要な方は以下のリンクからダウンロード後、インストールしてください(リンク先はMicrosoft)。 

---
### Pocket Link Systemとは
近 成人氏により開発され、ポケコンジャーナル誌'90.6において発表されました。  
パーソナルコンピュータとSHARPのポケットコンピュータ PC-E500シリーズとをシリアルケーブルで接続し、ポケコン側のデバイスドライバとパソコン側のサーバプログラムによりポケットコンピュータの仮想ドライブを提供するものです。
ポケコンから見れば、RAMファイルと同様に扱うことができます。  
パソコン側のリソース保護のため、ファイルを直接読み書きするのではなく、仮想ドライブを作成しそこにファイルを取り込んだ上でポケコン側からアクセスするよ うな仕組みになっています。また、切断時にはポケコン側から変更のあったファイルはパソコン上のディスクに吐き出されます。 

---
### 必要なもの
- i486以上のCPUを搭載し、WindowsNT3.51以上(Intel)またはWindows9xが動作するパーソナルコンピュータ
- PC-E500シリーズのポケコン
- [PLINK.SYS Ver.1.04](http://kenji.ram.ne.jp/e500/soft/index.html#plink) (C) N.Kon または [PLINKC](http://kenji.ram.ne.jp/e500/soft/index.html#plinkc) Ver1.5以上((C)D.Mizobata)
- レベルコンバータ(CE-140T等) 

---
### 履歴
```
Ver.1.01  1997.03.23  タイムスタンプ対応
                      PLINKC Ver.1.60の仮想ドライブ容量変更に対応

Ver.1.00  1996.12.11  正式公開初版
                      アイコンの変更
                      ファイル一覧ボタンの追加

Ver.0.02  1996.09.15  β２リリース
                      MRUリスト対応
                      ウィンドウ位置・サイズの保存
                      ログバッファのフォント選択
                      ディスコネクト時の上書きチェック
                      仮想ドライブ内のファイル一覧出力
                      ファイル取り込み時のファイル名の大文字変換の有無の指定
                      コンパイラのマイナーバージョンアップ
Ver.0.01  1996.05.11  β１リリース
```
---
### 動作確認済み環境

|OS                       |SP  |build     |Lang|
|-------------------------|----|----------|----|
|Windows95                |SP1 |4.00.950a |Ja  |
|Windows98                |SP1 |4.00.1998 |Ja  |
|Windows98SE              |--- |4.00.2222A|Ja  |
|WindowsMe                |--- |4.00.3000 |Ja  |
|WindowsNT3.51 Workstation|SP5 |3.51.1057 |Ja  |
|WindowsNT4.0 Workstation |SP6 |4.00.1381 |Ja  |
|Windows2000 Professional |RC3 |5.00.2183 |En  |
|                         |--- |5.00.2195 |Ja  |
|                         |SP2 |5.00.2195 |Ja  |
|WindowsXP Home Editon	  |RC1 |5.10.2505 |En  |
|WindowsXP Professional	  |RC1 |5.10.2505 |En  |
|WindowsXP Professional	  |SP2 |5.10.2600 |Ja  |
|                         |SP3 |5.10.2600 |Ja  |
|Windows Vista Ultimate   |RC1 |6.00.5600 |Ja  |
|Windows 7 Ultimate	      |Beta|6.10.7000 |Ja  |
|Windows 7 Ultimate(64bit)|--- |6.10.7600 |Ja  |
|Windows 8 (32bit)	      |RP  |6.2.8400  |Ja  |
|Windows 8.1 (32bit)      |--- |6.3.9600  |Ja  |
|Windows 10 (32bit)	      |TP  |6.4.9841  |En  |
|Windows 10 Pro(64bit)    |20H2|19042.746 |Ja  |
|Windows 11 Pro(64bit)    |21H2|22000.194 |Ja  |
|                         |22H2|22621.3737|Ja  |
|                         |23H2|22631.4602|Ja  |

---
### お問い合わせについて
README.TXTに記載の連絡先は存在しないため、Xまでお願いします。
