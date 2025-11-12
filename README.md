# line-gmail-bot-info
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>My Line Gmail Bot – manaba課題通知Bot</title>
</head>
<body>
  <h1>My Line Gmail Bot – manaba課題通知Bot</h1>
  <h2>Botの概要</h2>
  <p>GmailとLINEを連携し、manaba課題通知が届くBotです。</p>

  <h2>主な機能</h2>
  <ul>
    <li>Gmailからmanaba通知メールを自動取得</li>
    <li>LINEで新着・締切間近の課題を通知</li>
    <li>タグ・コース・優先度で絞り込み表示</li>
    <li>Firestoreに保存された履歴を検索可能</li>
  </ul>

  <h2>使い方</h2>
  <ol>
    <li>LINEでBotを友だち追加</li>
    <li>「/start_fetch」と送信してGmail認証を行う</li>
    <li>認証後、自動で課題通知が届くようになります</li>
  </ol>

  <h2>対応サービス</h2>
  <ul>
    <li>Gmail API</li>
    <li>LINE Messaging API</li>
    <li>Google Cloud Run</li>
    <li>Firebase Firestore</li>
  </ul>

  <h2>対象ユーザー</h2>
  <p>manabaを使っている大学生・教職員、Gmailを使っているLINEユーザー</p>

  <h2>開発者</h2>
  <p>斎藤未咲希（misaki.sa0310@gmail.com）</p>
</body>
</html>
