# Githubのメモ
## 初歩的なあれこれ
- フォルダ作る  
  Create new file押す  
  → TIL/ の横にフォルダ名書く  
  → / を後ろにつけるとフォルダになる  

## githubとslackの連携  
例えばjojoさんのhogereposリポジトリをslackに連携して、git_hogereposチャンネルで通知するようにしたい場合  
- リポジトリurl: https://github.com/jojo/hogerepos  
- slackでgit_hogereposのようなチャンネルを作成  
- slackにgithubのapp入れる　　
- チャンネルの中で  
/github subscribe jojo/hogerepos  
とコメント打てばチャンネルに通知入る様になる。  
- あとは試しにgithubでpushしたりプルリクしてみるとよし  
