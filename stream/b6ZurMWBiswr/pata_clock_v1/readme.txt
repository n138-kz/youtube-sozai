////////////////////////////////////////////////////////


【 はじめに  Introduction 】

この度は、OBS用パタパタ時計をダウンロードしていただき、ありがとうございます。
Thank you for downloading the Flip Clock for OBS.

商用、非商用に関わらず、無料でお使いいただけます。
You can use it for free regardless of whether it is commercial or non-commercial.

改変の有無に関わらず、本コードの再配布は禁止させていただきます。
Redistribution of this code is prohibited regardless of whether it has been modified.

verticalフォルダに縦向きレイアウトの時計が同梱されています。
A clock with a vertical layout is included in the 'vertical' folder.


////////////////////////////////////////////////////////

↓かんたんカラーカスタマイズはこちら（ A site where you can easily customize colors ）
https://sawaragismith.github.io/patapataClock/

////////////////////////////////////////////////////////


【 使い方  How to use 】

1.OBSのソースパネルから[+]マークをクリックし、「ブラウザ」を選択
( Click the [+] mark from the OBS source panel and select "Browser". )

2.新規作成で「時計」などのわかりやすい名前をつける
( Give a descriptive name such as "clock" when creating a new one )

3.ローカルファイルにチェックを入れ、ファイルを選択
( Check the local file and select the file )

4.幅500、高さ160 に設定する
( Set the width to 500 and the height to 160 )

5.OKを押して、配置を完了する
( Press OK to complete the placement )


////////////////////////////////////////////////////////


【 カラー変更/サイズ変更について  How to change color and size 】

HTMLソースコードを開くと、#11〜#37行目に、変更箇所が説明してあります。
When you open the HTML source code, the changes are explained on lines # 11 to # 37.

以下のURLのWEBサイトをブラウザで開き、カラーの調整を行います。
Open the website at the following URL in your browser and adjust the color.

URL--> https://sawaragismith.github.io/patapataClock/

出来上がったカスタマイズコードを、#11〜#37行目を上書きする形でコピペします。
Copy and paste the completed customization code by overwriting lines # 11 to # 37.

--> POINT
* 薄めの色に変更したい場合は、「01_white.html」を
  濃いめの色に変更したい場合は、「02_black.html」を ベースにカスタマイズするのがおすすめです。 

* If you want to change to a lighter color, change "01_white.html" to
  If you want to change to a darker color, change "02_black.html" to
  It is recommended to customize it to the base.


サイズを変更したい場合は、#33行目の「--clock-size: 1.0;」の1.0の数値を、
1.25、1.5などの値に変更することでサイズが変わります。
If you want to change the size, enter the value of 1.0 in "--clock-size: 1.0;" on line # 33.
The size changes by changing to a value such as 1.25 or 1.5.

サイズ変更の際は、OBSのブラウザサイズも同じ倍率で幅と高さを変更しましょう。
例: --clock-size: 2.0; としたならば、
　　OBSのブラウザサイズは、幅1000、高さ320。

When resizing, change the width and height of the OBS browser size at the same magnification.
Example: --clock-size: 2.0;
The browser size of OBS is 1000 width and 320 height.


////////////////////////////////////////////////////////


【 製作者について  About the creator 】

vtuber 沢良木スミス（さわらぎすみす）が制作しています。
不具合や、使い方の質問などあれば、Twitter(@SawaragiSmith)のDMで連絡いただければ
可能な限り回答させていただきます。

Produced by Sawaragi Smith(vtuber).
If you have any problems or questions about how to use it, please contact us via Twitter DM(@SawaragiSmith).
We will answer as much as possible.

よろしければ、TwitterのフォローやYoutubeのチャンネル登録、よろしくお願いいたします。
If you like, please follow us on Twitter and subscribe to the Youtube channel.

Twitter: https://twitter.com/SawaragiSmith
Youtube: https://www.youtube.com/channel/UCwFKEIMy_YQspwFm-GNySEg


////////////////////////////////////////////////////////


※このHTMLソースでは、Goolge font 'Oswald' を利用しています。
* This HTML source uses Google font'Oswald'.
----------------
"Oswald" is lisenced under the SIL Open Font License 1.1
https://www.google.com/fonts/attribution
http://scripts.sil.org/OFL


////////////////////////////////////////////////////////