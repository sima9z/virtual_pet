■サービス概要  

画面の一部を使用して、バーチャルの犬か猫のお世話をしたり様子を観察できるアプリです。  
作業等の合間に触ることができ、休憩時間と癒しを提供します。

■ このサービスへの思い・作りたい理由  

画面の一部を使用して常時起動させるアイディアについては、先日購入したゲームソフトから貰いました。  
フロントエンドが好きなので、ただ眺めているだけで楽しいアプリを作成したいと考えました。  
フロントエンドが好きが好きな理由は、見た目を整えてユーザビリティの向上させることへが楽しいからです。
犬と猫なのは、自分が好きだからです。

■ ユーザー層について  

動物が好きな方。  
PC作業が多く、作業の合間に癒しが欲しい方。

ペットを飼うことができないが、手軽にペットを飼う感覚を体験を求めている方。  
毎日のお世話のイメージをつかみたい、これからペットを飼う予定がある方。


■サービスの利用イメージ  

作業や学習は目や脳を使用するため疲れますし、集中力も続かないことが多いかと思います。  
かといってPCの前から離れてしまうと別の用事をしてしまい、作業が遅れてしまうこともあります。  
このアプリを使用することによって、作業間の休憩をPC前で手軽に行うことが可能になります。

■ ユーザーの獲得について  

- XでのPR
- RUNTEQのtimesやコミュニティー内でのPR

■ サービスの差別化ポイント・推しポイント  

主にフロントエンド（ペットのアニメーション、画像、UI等）へのこだわりで差別化していきたいです。
フロントエンドについては、アニメーションの細かさ、犬と猫のデザイン、直感的で使いやすくカラフルで見た目が可愛らしいUIをこだわりたいと考えています。

■ 機能候補  

【MVPリリース時に実装予定の機能】  

- ユーザー登録機能
- ログイン機能
- 犬か猫の選択機能
- ペットのお世話をする機能（餌やり、水やり、散歩）
- ペットのアニメーション（放置時）
- ペットのレベルアップ処理
- 新規作成するペットに名前を付けられる機能
- 子供から大人への成長についての処理

【本リリースまでに実装予定の機能】

- 犬と猫の種類を追加
- ペットに空腹値や体力の要素を追加
- 時間経過でペットの状態を変化させる処理（状態によって適切なお世話の種類が変わる）
- ペットのアニメーション（クリック時、お世話をされた時）
- パスワードリセット機能
- Line通知機能
- 育成中のペットの名前や見た目のカスタマイズ機能
- ペットの繫殖についての処理（レベルアップで繫殖する）
- ゲストでログイン機能
- Google認証機能

■ 機能の実装方針予定

- Next.js
- Rails APIモード
- PWA
- sorcery gem
- Typescirpt
- rack-cors gem
- GSAP (GreenSock Animation Platform)
- Sidekiqg

■ 画面遷移図 
https://www.figma.com/design/A0RihBRVCbtBeOo9QCgoW8/virtual_pet-%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?node-id=0-1&t=4S1xDdcr9vnr5qCP-1

■ ER図
https://drive.google.com/file/d/1ndeMAWF9PCiFJEwyL0M76-5SSlCZc3lx/view?usp=sharing