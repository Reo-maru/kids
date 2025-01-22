# kids
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>うちゅうくいず アプリ</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <div id="main-menu" class="menu-container">
    <h1>ようこそ！</h1>
    <button id="start-quiz-btn">くいずをはじめる</button>
  </div>

  
  <div id="quiz-container" class="quiz-container" style="display:none;">
    <h1>うちゅうくいず</h1>
    <div id="quiz">
      <div id="question">しつもんがここにひょうじされます</div>
      <ul>
        <li><button class="answer-btn" data-index="0"></button></li>
        <li><button class="answer-btn" data-index="1"></button></li>
        <li><button class="answer-btn" data-index="2"></button></li>
        <li><button class="answer-btn" data-index="3"></button></li>
      </ul>
      <div id="result"></div>
      <button id="next-btn">つぎへ</button>
    </div>
  </div>

  <div id="ranking-container" class="quiz-container" style="display:none;">
    <h1>ランキング</h1>
    <div id="ranking"></div>
    <button id="restart-btn">もう一度はじめる</button>
  </div>

  <script src="script.js"></script>
</body>
</html>
