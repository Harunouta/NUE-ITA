このデータはITAコーパス(https://github.com/mmorise/ita-corpus)を元に春野詠(@Harunouta)が録音、ラベリングしたものです。

==作成環境=====
録音環境:Thunderbolt3端子のマイク付きイヤホンを用いてipad
ラベリング環境:Julius rev4.6(https://julius.osdn.jp)、segmentation-kit(https://github.com/julius-speech/segmentation-kit)
ただし、一部人手で修正。

==ディレクトリ構成=====
readme.txt(これ)
利用規約.txt(絶対に読んで欲しいもの)

EMOTION100-nue:EMOTION100の文章を読み上げたものを1文ずつwavファイル形式(42000Hz)で録音したもの。(.wav)
EMOTION100-seg:EMOTION100の文章のうち、以下のファイルが1文ごとにディレクトリに格納されたもの。
|-読み上げたものを1文ずつwavファイル形式(16000Hz)に変換したもの(.wav)
|-音素を開始時間、終了時間、音素の種類で母音・子音を区別してラベルづけしたtxtファイル。(.lab)
|-本文そのもの(.txt)
|-Praat用にラベル付したもの(ラベル基準は、ラベル基準.txtに準拠する)(.TextGrid)

RECITATION324-nue:RECITATION324の文章を読み上げたものを1文ずつwavファイル形式(42000Hz)で録音したもの。(.wav)
RECITATION324-seg:RECITATION324の文章のうち、以下のファイルが1文ごとにディレクトリに格納されたもの。
|-読み上げたものを1文ずつwavファイル形式(16000Hz)に変換したもの(.wav)
|-音素を開始時間、終了時間、音素の種類で母音・子音を区別してラベルづけしたtxtファイル。(.lab)
|-本文そのもの(.txt)
|-Praat用にラベル付したもの(ラベル基準は、ラベル基準.txtに準拠する)(.TextGrid)


==注意事項==
読み精度の影響により、本文よりもポーズ挿入箇所が多く入っており、都度ラベル内で表記しています。
このため、連続音素数は本家よりも少ないものになっていると思われます。
ご利用の際は必ず利用規約.txtをご確認ください。商用・非商法に関わらず、「報道目的の利用」および「医療関係情報を扱う利用」は禁止しています。

==連絡先======
春野詠(twitter:@Harunouta,@shounokoto)