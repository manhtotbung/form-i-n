<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="image_src" href="ckongu.jpg" />
    <link rel="image_src" href="dgawidgawiuydgawd.png" />
    <link rel="icon" href="dgawidgawiuydgawd.png">
    <link rel="stylesheet" href="jquery-ui-1.13.0/jquery-ui.min.css" />
    <link rel="stylesheet" href="style.css" />
    <link rel="stylesheet" href="jquery-ui-1.13.0/jquery-ui.css">
    <script src="jquery-3.6.0.js"></script>
    <script src="jquery-ui-1.13.0/jquery-ui.js"></script>

    <title>contacts with us</title>
    <style>
      
        .thongdiep{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: 14px;
            margin: solid 1px;
            border: 0px;
            border-radius: 15px;
            padding: 20px;
            background-color: rgb(156, 236, 236);

        }
        .md{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: 14px;
            margin: solid 1px;
            border: 1px solid;
            border-radius: 45px;
            padding: 20px;
            margin:1px;
            

        }
        .md01{
            border: 1px solid;
          
        }
    </style>
</head>
<body>
    
    <h1 style="font-size: 40px;text-align: center; color:rgb(74, 180, 184);">Liên hệ với chúng tôi</h1>
   
    <form action="manhdo.com" style="text-align: center;">
   
    <input type="text" name="hoten" class="md" size="70"; placeholder="họ và tên*">
    <br><br>
    <input type="text" name="email" class="md" size="70" placeholder="email*">

    <br><br>
    <input type="text" name="sdt" class="md" size="70" placeholder="số điện thoại*">

    <br><br>
    <input type="text" name="congty" class="md" size="70" placeholder="công ty tổ chức*">

    <br><br>

    
    <textarea name="thongdiep" rows="10" cols="70" placeholder="nội dung thông điệp" class="thongdiep"></textarea>
      <br> <br> 
    <input class="md" type="submit"  value="submit">
    <br><br>
    </form>

    <div id="tabs-6">
        <fieldset style="border-radius: 20;">
        <h2 >
           Máy tính tuổi thông minh
        </h2>
        <div class="center">
           <p>Nhập tuổi của bạn</p>
           <input type="text" onfocus="this.value=''" onChange="mod();" id="age_e">
           <p id="age_a"></p>
           <button id="nut_adawdawdawdawdawd" onclick="age()">Tính tuổi của bạn</button>
        </div>
     </div>
    
     <script>
        var inc = 0, inb = 0; function mod() { inb = inc = 0 } function age() { var n = document.getElementById("age_e").value, e = n + " là tuổi clgt???"; if (0 == document.getElementById("age_e").value.length || isNaN(n)) if (0 == document.getElementById("age_e").value.length) document.getElementById("age_a").innerHTML = "Chưa nhập gì hết."; else { switch (inc) { case 0: document.getElementById("age_a").innerHTML = e; break; case 1: document.getElementById("age_a").innerHTML = "Đây là lần thứ 2 rồi nhưng bạn vẫn nhập sai."; break; case 2: document.getElementById("age_a").innerHTML = "Thật ra bạn chỉ bấm cái nút này cho vui thôi phải không?" }inc++ } else 0 == inb ? (document.getElementById("age_a").innerHTML = "Bạn đã " + n + " tuổi rồi.", inc = 0) : document.getElementById("age_a").innerHTML = "Bạn đã nhấn cái nút này " + inb + " lần, tuổi của bạn vẫn là " + n, inb++; if (3 < inc) for (var t = 0; t <= inc; t++)document.getElementById("age_a").innerHTML = " đừng có nhấn nữa".repeat(t); 6 == inc && (document.getElementById("age_a").innerHTML = "nhấn thêm lần nữa xem?"), 7 == inc && (document.getElementById("age_a").innerHTML = "chắc chưa?", document.getElementById("nut_adawdawdawdawdawd").innerHTML = "chắc."), 7 < inc && (window.location.href = "https://www.youtube.com/watch?v=dQw4w9WgXcQ") }
     </script>
 </fieldset>


</body>
</html>
