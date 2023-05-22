# 基礎プロその2
こっちはQPの基礎プロが大変そうだったので手伝った分です。<br>
ウクライナ(とロシアの戦争)関連の日本語ツイートを分類するために(詳しくは知らない)、東北大の日本語のBERT(`https://huggingface.co/cl-tohoku/bert-base-japanese-whole-word-masking`)を、ウクライナに関するツイートデータを使ってfine-tuningしました。<br>
fine-tuning後のmodelもhugging face hub(`https://huggingface.co/takeshiho0531/bert-japanese-finetuned-Ukraine-tweet`)で共有しています。詳しいfine-tuningのデータはそちらをみてください。