http://quiz.game.teams.maximum.vc/

# Maximum_Quiz

１，２年生向けにプログラミングに関する問題を出すプログラム。

##　記述言語

主にhtmlとJavaScriptとCSSを使う。フォーマットはQuiz_Templateを参照のこと。

##　ファイル名

問題選択のファイル名は「言語名_問.html」とする。例：JavaScript_.html
問題のファイル名は「言語名_問題の種類.html」とする。例：JavaScript_Multiple_Question.html
JavaScriptの表記はJとSを大文字にして統一する。
CSSは大文字で統一する。

##　共同開発の流れ

以下のサイト参照のこと、Pull Requestを作成したらDiscodeで連絡。
https://blog.maximum.vc/blog/2023/webken/3/

https://blog.maximum.vc/blog/2023/webken/4/

コンフリクトを起こさないようにissueをこなすごとにgit pull origin main でmain　ブランチとコードを合わせること
ブランチ名には日本語及び空白を入れないこと（アンダースコアは大丈夫）

mp3やjpegなどの素材はkeep_outディレクトリに入れること

##　タグについての注意

```
クイズの問題文や解説文の表示にはinnerHTMLというものを使っています。これによりHTMLの記号が使えるようになります(主に改行のため)

つまり、問題文や解説文の中に<br>と書けば改行できます。

ただし、<br>以外のhtmlタグは使えなくしてあります。(解説で使うことの方が多そうだから)

なので解説や、問題で、htmlタグとして<br>以外を(リストとか)使う場合、githubのdiscussionsに書いてください

(HTML4択クイズ初級編では<br>を解説として使っていたので\nで改行できるようにしてあります)

```
# explain.texについて
開発上の注意点についてはREADMEファイルに書きますが、Maximum_Quiz事体の説明はexplain.texに書きます。。


