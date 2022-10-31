﻿# Location_Test
<!DOCTYPE html>
<!-- saved from url=(0041)https://kidkender.github.io/duchuu260201/ -->
<html lang="en-US"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width,maximum-scale=2">
    <link rel="stylesheet" type="text/css" media="screen" href="./duchuu260201_files/style.css">

<!-- Begin Jekyll SEO tag v2.7.1 -->
<title>duchuu260201</title>
<meta name="generator" content="Jekyll v3.9.0">
<meta property="og:title" content="duchuu260201">
<meta property="og:locale" content="en_US">
<link rel="canonical" href="https://kidkender.github.io/duchuu260201/">
<meta property="og:url" content="https://kidkender.github.io/duchuu260201/">
<meta property="og:site_name" content="duchuu260201">
<meta name="twitter:card" content="summary">
<meta property="twitter:title" content="duchuu260201">
<script type="application/ld+json">
{"headline":"duchuu260201","url":"https://kidkender.github.io/Location_Test/","@type":"WebSite","name":"duchuu260201","@context":"https://schema.org"}</script>
<!-- End Jekyll SEO tag -->

  </head>

  <body>

    <!-- HEADER -->
    <div id="header_wrap" class="outer">
        <header class="inner">
          <a id="forkme_banner" href="https://github.com/Kidkender/duchuu260201">View on GitHub</a>

          <h1 id="project_title">duchuu260201</h1>
          <h2 id="project_tagline"></h2>

          
        </header>
    </div>

    <!-- MAIN CONTENT -->
    <div id="main_content_wrap" class="outer">
      <section id="main_content" class="inner">
        <h1 id="duchuu260201">duchuu260201</h1>
<h1 id="hello-đức-nè-">Hello Đức nè !!</h1>

    
        <p>Kích vào button để lấy tọa độ của bạn </p>

        <button onclick="getLocation()">Lấy vị trí </button>
        <p id="demo">Vĩ độ :10.766452<br> Kinh độ :106.563482</p>

        <script>
            var x=document.getElementById("demo");

            function getLocation()
            { if(navigator.geolocation)
                { 
                    navigator.geolocation.getCurrentPosition(showPosition,showError);
                }
                else
                { 
                    x.innerHTML="GeoPosition Không được hỗ trợ bởi trình duyệt này !."
                }
            }

            function showPosition(position)
            {
                x.innerHTML="Vĩ độ :" + position.coords.latitude + "<br> Kinh độ :" +position.coords.longitude;
            }

            function showError(error)
            {
                switch(error.code)
                { 
                    case error.PERMISSION_DENIED:
                        x.innerHTML="Người sử dụng từ chối cho xác định vị trí "
                        break;
                    case error.UNAVAILABLE:
                        x.innerHTML="Thông tin vị trí không có sẵn "
                        break;
                    case error.TIMEOUT:
                        x.innerHTML="Yêu cầu vị trí người dùng vượt quá thời gian quy định "
                        break;
                    case error.UNKNOW_ERROR:
                        x.innerHTML="Lỗi không rõ nguyên nhân "
                }
            }
        </script>


    


      </section>
    </div>

    <!-- FOOTER  -->
    <div id="footer_wrap" class="outer">
      <footer class="inner">
        
        <p class="copyright">duchuu260201 maintained by <a href="https://github.com/Kidkender">Kidkender</a></p>
        
        <p>Published with <a href="https://pages.github.com/">GitHub Pages</a></p>
      </footer>
    </div>

    
  

</body></html>
