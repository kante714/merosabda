# merosabda
<!doctype html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Blog</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="author" content="Mipham14">
    <meta name="description" content="Learn to Earn">
    <meta name="keywords" content="programming hero, web playground">
    <link rel="shortcut icon" href="images/favicon.ico" type="image/vnd.microsoft.icon">
    <!--@bootstrapCss-->
    <link rel="stylesheet" href="css/bootstrap.min.css">

    <!--custom css-->
    <link rel="stylesheet" type="text/css" href="swiper.min.css">

    <link rel="stylesheet" href="blog.css">
    <script src="https://kit.fontawesome.com/a076d05399.js">  </script>
  <style>
  @import url('https://fonts.googleapis.com/css?family=Poppins:300,400,600,700');

*{
 padding:0 ;
 margin:0 ;
 font-family:montserrat ;
 box-sizing:border-box;
 
  

}
body { 
   background:tomato;
   background-size: cover;
   
   
}
a { 
   text-decoration:none ;
}

.img-circle {
    border: 3px solid white;
    border-radius: 50%;
}
.section {
    background-color: #fff;
    padding: 15px;
    
    border-radius: 10px;
}
#header {
    background-image: url("https://www.sololearn.com/Uploads/header.jpg");
    background-size: cover;
    height:180px ;
    
}
#header img {
    
    display: block;
    width: 80px;
    height: 80px;
    margin: auto;
}
#header p {
    font-size: 25pt;
    color:lightblack;
    padding-top: 5px;
    margin: 0;
    font-weight: bold;
    text-align: center;
    
}
.conact a{
    display:inline-block ;
    
}
.conact a img { 
      width:70px ;
      height:70px ;
      border:1px solid transparent ;
      margin:5px 5px ;
 }
.conact{
    margin-bottom:7vh ;
    background:#000 ;
    border:1px solid yellow;
    
}
nav{
   float:right ;
   padding-top:10px ;
   margin-right:20px ;
   
}
nav ul{
   margin-right:5px ;
}
nav ul li { 
    
    display:inline-block ;
    
}
nav ul li a{
   color:#fff ;
   text-decoration:none ;
   font-size:20px ;
   font-weight:600 ;
   padding:0 2px ;
   margin:5px ;
   border:1px solid transparent;
   
   
}
a.active, a:hover { 
   color:#000;
   background:#fff ;
   transition: 0.6s ease;
   text-decoration:none ;
}



#m1 h1 { 
   color:#000 ;
   margin-top:5px ;
   text-align:center;
   background:red;
   padding:25px 100px ;
   border:1px solid yellow ;
   
   
}


.container {
    padding-top:5px ;
    width:100%;
    height:845px;
    animation:animate 16s ease-in-out infinite;
    background-size:100% 100%;
   
}
@keyframes animate {
  
  0%,100% {
    background-image:url(images/1.png) ;
    
  }
  25% {
    background-image:url(images/2.jpg) ;
    
  }
  50% {
    background-image:url(images/3.jpg) ;
    
  }
  75% {
    background-image:url(images/4.jpg) ;
    
  }
}

.bg1 {
   margin-top:-10px ;
   background:linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5) ), 
   url(images/bg2.jpeg) no-repeat ;
   background-size:cover ;
   height:895px;
}
#m2 h1 { 
   color:#000 ;
   
   margin-top:1px ;
   text-align:center ;
   background:red;
   padding:25px 100px ;
   border:1px solid yellow ;
 }
#m2 p { 
   color:#fff ;
   margin-left:25px ;
   padding-top:25px ;
}
#m2 pre {
   color:#fff ;
   margin-left:15px ;
}

.bg2 {
   margin-top:-10px ;
   background:linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5) ), #000 ;
   background-size:cover ;
   height:895px;
   display:flex ;
   justify-content:center;
   align-items:center;
   font-family:'poppins', sans-serif;
  
}

#m3 h1 { 
   color:#000;
   margin-top:1px ;
   text-align:center ;
   background:red;
   padding:25px 100px ;
   border:1px solid yellow ;
}
.card{
  position:relative;
  background:#fff;
  width:500px;
  height:600px;
  margin:0 auto;
  
}
.card .content{
   width:500px;
   padding:30px;
   box-sizing:border-box;
 }
 .card .content a{
   display:inline-block;
   margin:10px 0 0;
   padding:10px 20px;
   text-decoration:none;
   border:2px solid #262626;
   color:#262626;
   font-weight:600;
 }
 .card .sliderText{
   position:relative;
   width:100%;
   height:300px;
   display:flex;
   justify-content:center;
   align-items:center;
   background:#000;
 }
 .card .sliderText h3{
    color:#fff;
    font-size:1em;
 }
 .swiper-slide{
    width:500px;
 }
 .swiper-slide:nth-child(1) .sliderText
 {
   background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5) ), url(images/bg.jpg) no-repeat;
   background-position:center ;
   background-size:cover ;
 }
 .swiper-slide:nth-child(2) .sliderText
 {
   background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5) ), url(images/sbg.jpg) no-repeat;
   background-position:center ;
   background-size:cover ;
 }
 .swiper-slide:nth-child(3) .sliderText
 {
   background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5) ), url(images/sbg1.jpg) no-repeat;
   background-position:center ;
   background-size:cover ;
 }
 .swiper-slide:nth-child(4) .sliderText
 {
   background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5) ), url(images/sbg2.jpg) no-repeat;
   background-position:center ;
   background-size:cover ;
 }
 .swiper-slide:nth-child(5) .sliderText
 {
   background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5) ), url(images/sbg3.jpg) no-repeat;
   background-position:center ;
   background-size:cover ;
 }

.bg3 {
   margin-top:-10px ;
   background:linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5) ), 
   url(images/favicon.ico) no-repeat ;
   background-size:cover ;
   height:895px;
}
#m4 h1 { 
   color:#000 ;
   margin-top:1px ;
   text-align:center ;
   background:red;
   padding:25px 100px ;
   border:1px solid yellow ;
}
#m4 pre {
   padding:10px ;
   color:#fff ;
   margin-left:10px ;
   font-size:20px ;
}
#m4 pre a { 
   color:tomato ;
   
}
#m4 pre a:hover { 
   background:#fff ; 
}

  </style>

</head>
<body>

     <div id="header" class="section">
            <img  class="img-circle" src="images/logo.jpeg">
            <p>Mero Sabda</p>
            </div>
            <div class="conact">
            <a href="https://www.facebook.com/anil.themixtureoflove "> <img src="images/fb2.jpg" alt="">   </a>
            <a href=" https://www.instagram.com/anil.chaudhary.official/?hl=en "> <img src="images/ins.jpg" alt=""></a>
            <a href=" https://mobile.twitter.com/Anilchau8956025 "> <img src="images/twi2.jpg" alt=""></a>
            <nav>
            <ul>
              <li><a class="active" href="#m1">Home  </a>  </li>
              <li><a href="#m2">About </a>  </li>
              <li><a href="#m3">My Blog </a>  </li>
              <li><a href="#m4">Contact </a>  </li>
            </ul>
           </nav>
      
            </div>
         
 
  
    <div id="m1">
        <h1>Home </h1>
        <div class="container"> 
         <div class="outer">
         </div>
        </div>
        </div>
     <div id="m2">
         <h1>About Mero Sabda </h1>
        <div class="bg1"> 
         <p>"MERO SABDA" is a Professtional Liturture & Educational channel . 
           The main MOTO of this Channel is to develop Nepaliliturature
           And Education system In the country, So,please Connect with us.</p>
 <pre>
 IN THIS CHANNEL YOU GET -
 📝All knowledge about liturature
 🗣️Motivational / Inspirational videos
 🎇 Quates Vedio | Status Video 
 📽️ Educational videos
 🗨️Biography
 👥 Interview 
 🏆️ Liturature Compitation
 🔎 Tips / Guide & Suggestion </pre>
         
        </div>
        </div>
      <div id="m3">  
        <h1>My Blog  </h1>
        <div class="bg2">  




<div class="swiper-container">
<div class="swiper-wrapper">
<div class="swiper-slide">
 <div class="card">
  <div class="sliderText">
     <h3>  काठमाडौ सहर : बुबासङको यात्रा - उर्गेन छिरिङ  </h3>
     </div>
     <div class="content">
      <p>नदेखेको नसुन्नेको नभोगेको महसुस नगरेको चिज सँगै सबै भन्दा प्यार हुँदो रहेछ! बच्चापान बेला सोचेको थिए आखिर यो चिल किन माथि उडेको होला ? सपना जस्तै ! धुम्मा बादलले ढकेको थियो चिल माथि माथि उड्दै थियो आकास माथि मेरो मन पनि उड्दै थियो चिल सँगै
      </p>
       <a href="   http://esabda.blogspot.com/2020/06/blog-post_9.html " >Read more</a>
     </div>
  </div>
 </div>
 <div class="swiper-slide">
 <div class="card">
 <div class="sliderText">
 <h3>  केही गर्नु छ - अनिल चौधरी </h3>
 </div>
 <div class="content">
 <p> के तपाईंले नदीलाई ध्यानपूर्वक बगिरहेको देख्नुभएको छ?  आफ्नो मूलबाटै आफ्नो गतिमा बगिरहेको हुन्छ । उसको लक्ष्य भनु या गन्तव्य  एउटै हुन्छ र त्यो भनेको समुन्द्रमा पुग्ने र केहि स्थानहरूमा उस्को गति कम हुन्छ र बाटामा अनेक बाधा अडचन पनि आउछ्न जस्तै...
 </p>
 <a href="  http://esabda.blogspot.com/2020/05/blog-post_23.html " >Read more</a>
 </div>
 </div>
 </div>

 <div class="swiper-slide">
 <div class="card">
 <div class="sliderText">
 <h3> श्रदान्जली : अनिल चौधरी | नेपाली कविता - मेरोशब्द  </h3>
 </div>
 <div class="content">
 <p>
 सधैझै आज पनि म बिउँझेछ  </br>
म देख्छु , मेरो नजिक मान्छेले बनाएका भगवानहरु चिच्याइरहेछ्न ।</br>
म सुन्छु , मेरो समीप खुसिका अलङ्कार भन्दा रोद्नका क्रन्दनहरु गिज्याइरहेछ्न ।</br>
लौन के गरु ?...
</p>
 <a href=" http://esabda.blogspot.com/2020/06/blog-post_6.html " >Read more</a>
 </div>
 </div>
 </div>
 
 <div class="swiper-slide">
 <div class="card">
 <div class="sliderText">
 <h3> सेल्फी - अनिल चौधरी | नेपाली उत्कृष्ट कथा | मेरोशब्द  </h3>
 </div>
 <div class="content">
 <p> एकदिन एक बथान साथिहरु उस्लाइ भेट्न आए । कलेजको अन्तिम परिक्षा सकेर बिदा भएकाले केही मिठा पल सङै बिताउने रहर बोकेर उनिहरु उस्को सहमति जताउन आएका थिए । पहिले त उस्ले सिधै इन्कार गरिदिए र आफुलाइ सोही अवस्थामा छाडिदिन पनि आग्रह गरे...
 </p>
 <a href="  http://esabda.blogspot.com/2020/05/blog-post_10.html " >Read more</a>
 </div>
 </div>
 </div>
 
 <div class="swiper-slide">
 <div class="card">
 <div class="sliderText">
    <h3> समय । कविता - उर्गेन छिरिङ ।। मेरोशब्द ||   </h3>
    </div>
     <div class="content">
     <p> समय र घडीको अङ्क त सरिरहन्छ</br>
तर एक दिन म र सङ्ग समय हुने छैन !!</br>
दुनियाँ बाट त एक दिन आफैमा हराउनु छ</br>
तर आफू आफू भित्र हराउनुको आनन्द छुटाइ छ !!</br>
जब म घडी लाई हेर्छु
      </p>
      <a href=" http://esabda.blogspot.com/2020/05/blog-post.html  " >Read more</a>
     </div>
 </div>
 </div>
 </div>
 </div>

 <script src="swiper.min.js">
   
 </script>
 <script>
   var swiper = new Swiper('.swiper-container', {
   effect: 'coverflow',
   grabCursor: true,
   centeredSlides: true,
   slidesPerView: 'auto',
   coverflowEffect: {
   rotate: 30,
   stretch: 0,
   depth: 300,
   modifier: 1,
   slideShadows : true,
   },
   pagination: {
   el: '.swiper-pagination',
   },
   });
 </script>


        </div>
      </div>
      <div id="m4">  
        <h1>Contact  </h1>
        <div class="bg3">  
          <pre>🗣️Admin : Anil Chaudhary 
🔳Instagram : <a href=" https://www.instagram.com/anil.chaudhary.official/">anil.chaudhary.official</a>
💠Fb page : <a href=" https://mbasic.facebook.com/Anilofficial14/">Anilofficial14</a>
 
📛 CONNECT WITH US 📛
Website : <a href="https://www.blogger.com/blogger.g?blo...">OfficialBlog</a>
Instagram : <a href=" https://www.instagram.com/mero.sabda....">MeroSabdaINSTA</a>
Facebook : <a href=" https://m.facebook.com/mero.sabda.7?r...">MeroSabdaFB</a>
Facebook page : <a href="https://m.facebook.com/mero.sabda.off... ">MeroSabdaFBPage</a>
</pre>
   
        </div>
      </div>
    
<!--main js-->
<script src="js/main.js"></script>
</body>
</html>
