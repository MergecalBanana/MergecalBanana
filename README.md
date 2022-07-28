# githubマジカルバナナについて  
  
## 概要  
github、勉強はしたけど実際に個人or複数人で使う機会がなくてイマイチ学んだことがピンときていない方  
個人では使っているけど複数人で使った事がないから複数人で運用する体験をしたい方  
失う物のないリポジトリで色々試したい方  
上記のようなユーザーを想定した使って慣れようgithubリポジトリです  
厳かな場にするつもりはないので、ゆる〜くテキトー(いい意味で)に使っていければと思ってます  
  
## 手順  
(1) リモートリポジトリをクローンする  
(2) 参加者は自分用をブランチを切る  
(3) 自分のターンになったら最新の状態をstagingブランチからpull  →  差分をマージ  
(4) 自分のターンを書いてpush  →  stagingブランチに対してプルリクエスト  
(5) main管理者はプルリクエストを確認、stagingで承認したプルリクエストをmainにマージ  
(6) (3)(5)をループ  

## ルール  
プル → マージの手順をちゃんと踏んでいれば順番なんかなくても成立するのでは？と思い、一旦順番関係なくやってみたいと思います！
