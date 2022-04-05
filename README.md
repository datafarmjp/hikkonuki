# hikkonuki

## 課題

- テキストから特定のワード間の文字を抜き出したい
- その際に出現回数もコントロールしたい

## 解決方法

- 専用のカスタム関数を作成しました。

	hikkonuki_word ( 例文 ; 最初の単語 ; 最初の出現回数 ; 最後の単語 ; 最後の出現回数 )
	
	にそれぞれ指定をすることで、その間の文字を抜き出すことができます。

/スクリーンショット 2022-04-05 9.20.22.png
	
## 関数の中身

`Middle ( text ; Position ( text ; start_word ; 0 ; start_word_disp )+Length ( start_word ); Position ( text ; finish_word ; 0 ; finish_word_disp )-Position ( text ; start_word ; 0 ; start_word_disp ) - Length ( start_word ) )`

`/* 最初に指定したワードのn回目から、最後に指定したワードのn回目までを抜き出す */	`

## 作った経緯

- このような計算式をよく書いていたのですが、何度も書くのが面倒だったために作成しました。
- htmlから特定のワードを抜き出すときなどに重宝しています。


## 実際の動画

https://youtu.be/Rtdw8DuGsMY
