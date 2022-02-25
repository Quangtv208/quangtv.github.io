<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cortic.vn</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="icons" href="anh/pexels-photo-1591447.jpeg">
    
</head>
<body>
    <div class="main">
        <div class="navbar">
            <h2 class="logo"><a href="index.html">CorTic</a></h2>
        </div>
        <div class="menu">
            <ul class="hmenu">
                <li><a href="index.html">Home</a></li>
                <li><a href="webcon/About.html">About</a></li>
                <li><a href="#">Event</a>
                    <ul class="sub-menu">
                        <li><a style="margin-left: -110%;" href="webcon/Free.html">Freefilm</a></li>
                        <li><a style="margin-left: -110%;" href="webcon/byfilm.html">Byfilm</a></li>
                    </ul>
                </li>
                <li><a href="#">Vlogs</a></li>
                <li><a href="#">Contact</a></li>

            </ul>
        </div>
        <div class="search-box">
            <input type="text" class="search-txt" name="" placeholder="Nhập và tìm">
             <a href="#" class="search-btn"><i class="fas-fa-search"><button  type="button" >Search</button></i></a>
        </div>
            <div class="title">

                <h1>FilmSimp</h1> 
                <div class="button">
                    <a href="#" class="btn">Wath Video</a>
                    <a href="#" class="btn">Learn more</a>
                </div>
            </div>
        </div>
        <div>
            <button class="nut-mo-chatbox" onclick="moForm()">Chat</button>
            <div class="chatbox" id="myform">
                <form action="" class="form-container">
                    <h1>ChatBox</h1>
                    <label for="msg"><b>Lời Nhắn</b></label>
                    <textarea placeholder="Bạn hãy nhập lời nhắn..." name="msg" required></textarea>
                    <button type="submit" class="gui">Gửi</button>
                    <button type="button" class="nut-dong-chatbox" onclick="dongform()">Đóng</button>
                    <script>
                        function moForm(){
                             document.getElementById("myform").style.display = "block";
                        }
                        function dongform(){         
                            document.getElementById("myform").style.display = "none";
                        }
                    </script>
                </form>


            </div>
            
        </div>
        <div class="adrr">
            <h2 style="color: tomato;font-family: cursive;">Liên Hệ: </h2>
            <ul class="adress" style="padding: 20px;">
                <li><a href="https://www.facebook.com/caube.tennang" style="border: solid; border-color: aliceblue;color: #385898;">Facebook</a></li>
                <li><a href="https://www.instagram.com/vinwang_t/" style="border: solid; border-color: aliceblue; color: rgba(202, 75, 219, 0.808);">Instagram</a></li>
                <li><a href="https://www.youtube.com/channel/UCmksJ16RZo56_PB09oHBOmg" style="border: solid; border-color: aliceblue; color: red;">Youtube</a></li>
            </ul>
        </div>
        <div class="vitri" >
            <p><a href="#"><marquee behavior="" direction="" style="color: azure;">911/10/7 Quang Trung/ Gò Vấp</marquee></a></p>


        </div>
       
    </div>
    
</body>
</html>
