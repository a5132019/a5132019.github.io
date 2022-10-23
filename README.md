# YJ's_website
<link href="https://fonts.googleapis.com/css?family=Noto Sans" rel="stylesheet" type="text/css">
<link href="https://fonts.googleapis.com/css?family=Dancing Script" rel="stylesheet" type="text/css">

<style>

    body { 
        border-radius: 20px;
        width: 70%;
        height: 5000px;
        margin: 50px auto;
        background-image: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
         }
    .color-text{
    color: rgb(117, 16, 232);
         }
        
    .smaller-image {
        padding: 10px;
        border-radius:30px;
        width: 300px;
        height: 350px;
    
       
     }
    .larger-image{
        padding: 10px;
        border-radius:30px;
        width: 250px;
        height: 350px;
       
    }
         h1{
            font-family: "Noto Sans",  serif;
            font-size: 80px;
            text-align: center
         }
         h2{     
            font-size: 20px;
            font-family: "Noto Sans",  serif;
         }
         h3 {
            font-family: "Dancing Script", serif;
            font-size: 30px;
           

         }
         h4 {
            font-family: "Dancing Script", serif;
            font-size: 30px;
            
         }
        h5 {
            font-family: "Dancing Script", serif;
            font-size: 30px;
           
         }
         .bdtext{
          width: 1000px;
         }
        
    
       p {
            color:rgb(16, 2, 2);
            font-family: "Noto Sans", serif;
            font-size:18px;
            text-align: center
         }
         button{
          border-radius:80%;
          height: 50px;
          width: 80px
       
         }
        h7{
            width:60px;
            height:60px;  
            background-color:#ffd28d;
            border-radius:80%;
            font-size: 15px;
}
        rabbit{
            width: 100px;
            height:100px;
            position:relative;
        }
    
        </style>
<!DOCTYPE html>
<html lang="en">
<head>
<link rel="stylesheet" href="main.css">
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.0/jquery.min.js"></script>

<script>
var my_name=prompt("請輸入你的名字");
document.write("歡迎"+my_name+"^^");
$(document).ready(function(){
$("button").click(function(){
    $("main").animate({
        left:'400px',
        height:'500px',
        width:'500px'
    },"slow");
    $("body").animate({
      opacity:'0.01',
     });
    

 
});

});

</script>
 <title>YJ個人網站</title>
 
</head>

<body class="background-image">

    <h1><a id="button1"class="color-text"class="font-family"class="font-size">YJ快樂日記</a></h1>
    <h2 class="font-family"class="font-size">歡迎來到林于靖的個人網站:)這裡記錄各種我的生活點點滴滴，點圖片會有餐聽或地點的IG喔~~</h2>
   <ul>
        <li><a href="#contact"><h3 class="color-text"class="font-family"class="font-size">ABV Restaurant in Banqiao</h3></a></li>
        <li><a href="#宜蘭1.jpg"><h4 class="color-text"class="font-family"class="font-size">Yilan Travel</h4></a></li>
        <li><a href="#九份1.jpg"><h5 class="color-text"class="font-family"class="font-size">Jiufeng</h5></a></li>
    </ul>


    <table>
        <a id="contact"</a>
        <tr>
            <td><center><a href="https://www.instagram.com/abv_penthouse/?igshid=YmMyMTA2M2Y%3D"><img class="smaller-image"src="2.jpg"alt="圖片"</a>
            </center></td>
            <td><center><a href="https://www.instagram.com/621yj/"><img class="larger-image"src="合照.jpg"alt="圖片"在餐廳的合照</a></center></td>
            <td><center>
                <a href="https://www.instagram.com/abv_penthouse/?igshid=YmMyMTA2M2Y%3D"></a><img class="smaller-image" src="1.jpg"alt="圖片" </a></center>
            </td>
        </tr>
    </table>
    <div>
      
       <p>
         ABV位於板橋府中站的閣樓餐酒館，燈光美氣氛佳，當天是去慶生。坐在戶外的位置很有氣氛~~</br>  
         這家餐廳有300款精釀啤酒讓你挑選!很適合朋友情侶癌聚餐、慶生
        </p>
    
        </div>
    
        <table>
            <a id="宜蘭1.jpg"</a>
            <tr>
                <td><center><a href="https://www.facebook.com/B168168168/"><img class="smaller-image"src="宜蘭1.jpg"alt="圖片"</a>
                </center></td>
                <td><center><a href="https://www.instagram.com/ms.wh.tc/"><img class="smaller-image"src="宜蘭2.jpg"alt="圖片"</a></center></td>
                <td><center>
                <a href="https://www.instagram.com/explore/locations/239631070091833/"><img class="larger-image"src="宜蘭3.jpg"alt="圖片"</a></center></td>
            </tr>
            </table>
        <div>
       
         <p>宜蘭頭城車站前的炸彈蔥油餅、超有名的滿山望海、小龜有冰店</p>      
        </div>
            
            <table>
            <a id="九份1.jpg"</a>
            <tr>
                <td><center><a href="https://www.facebook.com/B168168168/"><img class="smaller-image"src="九份1.jpg"alt="圖片"</a>
                </center></td>
                <td><center><a href="https://www.instagram.com/ms.wh.tc/"><img class="larger-image"src="九份2.jpg"alt="圖片"</a></center></td>
                <td><center>
                <a href="https://www.instagram.com/explore/locations/239631070091833/"><img class="smaller-image"src="九份3.jpg"alt="圖片"</a></center></td>  
          </tr>
         </table>
         <div>
         
         <p>沒什麼食物照只好放我跟貓咪、去九份阿柑姨芋園一定要吃^^</p> 
</br>

<button class="button">byebye</button>
<main>
<img class="rabbit"src="bye.png">
</main></br>

</br><div>
<a href="#button1"><h7 class="h7">到頂端</a></h7>
</div>

</body>
</html>
