<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background-color: pink;
    }

    .smaller-image {
      width: 200px;
      height: 300px;
    }
    .smaller-image1 {
      width: 200px;
      height: 200px;
    }
     .smaller-image2 {
      width: 500px;
      height: 300px;
    }

h1 {
  font-family: "helvetica neue", helvetica, sans-serif;
  color: rgba(255, 94, 77, 0.6);
  position: relative;
  padding-bottom: 10px;
  margin-bottom: 0;
  box-shadow: 1px 1px 10px 1px rgba(0, 0, 0, 0.3); /* 添加 box-shadow */
  border-radius: 10px; /* 添加 border-radius */
  text-align: center; /* 将文本置中 */
   font-family: "Apple Chancery", cursive;
}

h1::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 5px;
  background: linear-gradient(to right, rgba(255, 255, 255, 0), rgba(255, 255, 255, 0.5));
}


    .container {
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    .centered-content {
      text-align: center;
    }

    .content-wrapper {
      display: flex;
      align-items: center;
    }

    .content-wrapper img {
      margin-right: 10px;
      /* 調整圖片和文字之間的間距 */
    }

    .button-container {
      text-align: center;
      margin-top: 20px;
      /* 可以根據需要調整上方的間距 */
    }

    .toggle-button,
    .coral-button,
    .yellow-button,
    .purple-button,
    .brown-button,
    .button {
      font-family: "helvetica neue", helvetica, sans-serif;
      letter-spacing: 1px;
      text-transform: uppercase;
      text-align: center;
      box-shadow: 1px 1px 2px;
      border-radius: 10px;
      padding: 3px 10px;
      display: inline-block;
      cursor: pointer;
      margin-right: 10px;
    }

    .toggle-button {
      border: 2px solid rgba(0, 200, 0, 0.6);
      background: rgba(0, 200, 0, 0.3);
      color: rgba(0, 200, 0, 0.6);
    }

    .coral-button {
      border: 2px solid rgba(255, 94, 77, 0.6);
      background: rgba(255, 94, 77, 0.3);
      color: rgba(255, 94, 77, 0.6);
    }

    .yellow-button {
      border: 2px solid rgba(255, 165, 0, 0.6);
      background: rgba(255, 165, 0, 0.3);
      color: rgb(255, 140, 0);
    }

    .button {
      border: 2px solid rgba(0, 0, 200, 0.6);
      background: rgba(0, 0, 200, 0.3);
      color: rgba(0, 0, 200, 0.6);
    }

    .purple-button {
      border: 2px solid rgba(128, 0, 128, 0.6);
      background: rgba(128, 0, 128, 0.3);
      color: rgba(128, 0, 128, 0.6);
    }
    .brown-button {
      border: 2px solid rgba(255, 145, 71, 0.7);
      background:rgb(165, 42, 42);
      color: rgba(255, 145, 71, 0.7);
    }
    .hidden-content {
      display: none;
    }
  </style>

</head>

<body>
  <h1>FJCU-WHITE BOOK</h1>
  <div class="button-container">
    <span id="toggleButton" class="coral-button" onclick="toggleContent('content1')">輔大美食</span>
    <span class="yellow-button" onclick="toggleContent('content2')">輔大佈景象簿</span>
    <span class="toggle-button" onclick="toggleContent('content3')">某個輔大日記</span>
    <a href="https://tinaaaaa0311.github.io/White-FJCU.test1.github.io/" target="_blank" class="button">點我看測驗</a>
    <a href="https://6566bb915e019a152037b4f6--ubiquitous-madeleine-3306d1.netlify.app/" target="_blank" class="purple-button">關於作者</a>
  </div>

  <div id="hiddenContent1" class="hidden-content container">
    <div class="content-wrapper">
      <a href="#"><img class="smaller-image" src="https://i.imgur.com/n2cjCxR.jpg" alt="meeee"></a>
      <p>
        <ol>
          <li>店名:Share Kitchen 想初。享廚</li>
          <li>地址：242新北市新莊區中正路514巷91號</li>
          <li>總體美味程度：3/5</li>
          <li>介紹：咖喱飯180元有點小貴，不過豬排現炸脆脆的還不錯吃，醬汁也算濃郁，炸物的表現普普通通，但松露醬不是我的菜。</li>
        </ol>
      </p>
    </div>
 <div class="content-wrapper">
      <a href="#"><img class="smaller-image1" src="https://i.imgur.com/FT8rBGT.jpg" alt="meeee"></a>
      <p>
        <ol>
          <li>店名:麵屋三郎</li>
          <li>地址：242新北市新莊區建國一路92號</li>
          <li>總體美味程度：4/5</li>
          <li>介紹：拉麵的價位200-400元不等，湯頭偏向濃郁，喜歡清爽的可以做調整，而肉類的口感都相當不錯，另外可以免費加兩球麵</li>
        </ol>
      </p>
    </div> 
   <div class="content-wrapper">
      <a href="#"><img class="smaller-image" src="https://i.imgur.com/ZfCxOeL.jpg" alt="meeee"></a>
      <p>
        <ol>
          <li>店名:蛋蛋早餐屋</li>
          <li>地址： 242新北市新莊區中正路514巷83號</li>
          <li>總體美味程度：3.5/5</li>
          <li>介紹：出餐速度很快，義大利麵的麵條也算美味，但醬汁比較稀</li>
        </ol>
      </p>
    </div> 
    <div class="content-wrapper">
      <a href="#"><img class="smaller-image1" src="https://i.imgur.com/Ketx6cV.jpg" alt="meeee"></a>
      <p>
        <ol>
          <li>店名:雞加酒 輔大店</li>
          <li>地址：242新北市新莊區中正路514巷35號</li>
          <li>總體美味程度：4.5/5</li>
          <li>介紹：應該不用多作介了，好吃的炸雞店，推薦招牌醬汁比較不會膩(起司吃到後面會膩)</li>
        </ol>
      </p>
    </div> 
<div class="content-wrapper">
<a href="#"><img class="smaller-image" src="https://img.onl/HoBmgM" alt="meeee"></a>
      <p>
        <ol>
          <li>店名:Mr.Omelet歐姆先生</li>
          <li>地址： 242新北市新莊區中正路514巷41號</li>
          <li>總體美味程度：4/5</li>
          <li>介紹：咖哩價位落在150-200元，可免費續飯跟醬汁，炸物的表現不錯，醬汁濃厚，是會想回訪的店家。</li>
        </ol>
      </p>
    </div> 
<h4>我們也歡迎投稿到信箱:fjucise112teamtina@gmail.com(你們有發現csie被打錯嗎嘿嘿)</h4>
  </div>

  
  <div id="hiddenContent2" class="hidden-content">
    <p>佈景的部分就不多加文字說明了，當作相簿的回憶錄~</p>
    <div class="content-wrapper">
    <a href="#"><img class="smaller-image" src="https://i.imgur.com/FtFcwhw.jpg" alt="meeee"></a>
  
      <a href="#"><img class="smaller-image" src="https://i.imgur.com/QJeei7S.jpg" alt="meeee"></a>
      
      <a href="#"><img class="smaller-image" src=" https://i.imgur.com/9Aj12pr.jpg" alt="meeee"></a>
     <a href="#"><img class="smaller-image2" src=" https://i.imgur.com/51uJQeZ.jpg" alt="meeee"></a>
      </div>
<div class="content-wrapper">
    <a href="#"><img class="smaller-image2" src="https://i.imgur.com/n1a8WRd.jpg" alt="meeee"></a>
  
      <a href="#"><img class="smaller-image" src="https://i.imgur.com/keH8tWH.jpg" alt="meeee"></a>
      
      <a href="#"><img class="smaller-image" src=" https://i.imgur.com/iyecRle.jpg" alt="meeee"></a>
     <a href="#"><img class="smaller-image" src=" https://img.onl/71ud2j" alt="meeee"></a>
      </div>    
 <div class="content-wrapper">
    <a href="#"><img class="smaller-image" src="https://img.onl/9qh46R" alt="meeee"></a>
  
      
      
      <a href="#"><img class="smaller-image" src="https://img.onl/85oMkL" alt="meeee"></a>
   <a href="#"><img class="smaller-image2" src="https://img.onl/ak4dsd" alt="meeee"></a>
     <a href="#"><img class="smaller-image" src=" https://img.onl/1OTnun" alt="meeee"></a>
      </div>      
     
    </div>

  <div id="hiddenContent3" class="hidden-content">
    <div class="content-wrapper">
    <a href="#"><img class="smaller-image" src="https://i.imgur.com/2NEGrkl.jpg" alt="meeee"></a>
   
      <ul> 
     <p>2023/9/21-星期四的疲憊早晨</p>
    <li>星期四早上是數位邏輯導論的課</li>
    <li>好多邏輯閘看不懂</li>
    <li>那還是先吃吃早餐吧~~</li>
  </ul>
 
     </div>
     <span class="brown-button" onclick="toggleContent('content4')">下一頁</span>
  </div>

 <div id="hiddenContent4" class="hidden-content">
    <div class="content-wrapper">
    <a href="#"><img class="smaller-image" src="https://i.imgur.com/a99VLVK.jpg" alt="meeee"></a>
       <ul> 
     <p>2023/10/6-星期五的陽光伴隨我回家</p>
    <li>結束了一周的課程</li>
    <li>週五陽光餘暉灑在石頭路上顯得格外耀眼</li>
    <li>好好迎接周末，好好休息吧</li>
  </ul>
     </div>
   <span class="brown-button" onclick="toggleContent('content3')">上一頁</span>
   <span class="brown-button" onclick="toggleContent('content5')">下一頁</span>
  </div> 

<div id="hiddenContent5" class="hidden-content">
    <div class="content-wrapper">
    <a href="#"><img class="smaller-image" src="https://img.onl/jShMTB" alt="meeee"></a>
        
       <ul> 
     <p>2023/10/12-猜猜今天星期幾</p>
    <li>沒錯!今天是讓人聞風喪膽的組合語言</li>
    <li>然後下星期要上機考很緊張餒</li>
    <li>大家考試加油喔(題外話這是常常要搭的聖言樓電梯)</li>
  </ul>
     </div>
   <span class="brown-button" onclick="toggleContent('content4')">上一頁</span>
   <span class="brown-button" onclick="toggleContent('content6')">下一頁</span>
  </div> 

<div id="hiddenContent6" class="hidden-content">
    <div class="content-wrapper">
    <a href="#"><img class="smaller-image2" src="https://img.onl/JU1Svk" alt="meeee"></a>
        
       <ul> 
     <p>2023/11/1-星期三-線性代數日</p>
    <li>黑板上有好多矩陣的線性代數</li>
    <li>早上九點的課真的讓人很想睡覺</li>
    <li>但良華老師很認真，要乖乖上課!</li>
  </ul>
     </div>
   <span class="brown-button" onclick="toggleContent('content5')">上一頁</span>
  </div> 
  <script>
    let activeContentId = null;

    function toggleContent(contentId) {
      var content = document.getElementById("hiddenContent" + contentId.slice(-1));

      // Check if the clicked button is already active
      if (activeContentId === contentId) {
        // Close the active content
        content.style.display = "none";
        activeContentId = null;
      } else {
        // Close the currently active content (if any)
        if (activeContentId) {
          var activeContent = document.getElementById("hiddenContent" + activeContentId.slice(-1));
          activeContent.style.display = "none";
        }

        // Open the clicked content
        content.style.display = "block";
        activeContentId = contentId;
      }
    }
  </script>
</body>

</html>
