<!DOCTYPE html>
<html>
  <head>
    <title>Hello, World!</title>
    <style>
      body{
        background-color: dark magenta;
  padding: 25px;
  text-align: center;
  color: azure;
  font-family: serif;
  font-size: 22px;
}
.title,h2,h3 {
	color:Alice blue;
  background-color: black;
}
.logo{
  height:150px;
  width:150px; 
  float: left;
  padding: 15px;
  top: 15px;
  bottom:15px;
  right: 15px;
}
.container{
  display: flex;
  gap: 15px;
  text-align: center;
}
.item,img{
  height: 300px;
  width: 300px;
}
#box{
  display: grid;
  grid-template-columns: auto;
  gap:10px;
  color: beige; 
  left: 37%;
  position: relative;
  margin-top: 0px;
}
topnav input[type=text] {
  float: right;
  padding: 6px;
  border: none;
  margin-top: 8px;
  margin-right: 16px;
  font-size: 17px;
}
 figcaption{
  background-color:darkslateblue;
  color: antiquewhite;
  font-size:20px;
 }

    </style>
  </head>
  <body>
      <h1 class="title">The Clothery</h1>
      <img class="logo" src="C:\Users\Lenovo\Desktop\wdt\logo.png"></img>
      <p>Welcome to The Clothery, where fashion meets
      comfort and style. We’re dedicated to creating high-quality,
      trendy clothing that fits every lifestyle. Whether you're looking 
      for casual wear, office attire, or something for a night out, 
      we offer versatile pieces that make you feel confident and look your best.</p>

      <div class="topnav">
        <input type="text" placeholder="Search..">
      </div>
      <h2>Our Products</h2>
      <div class="container">
        <div id="item"><img src="C:\Users\Lenovo\Downloads\img-1.jpeg">
         <figcaption>71KB<br>format:JPEG</figcaption>
        </div>
        <div id="item"><img src="C:\Users\Lenovo\Downloads\img 1.png">
          <figcaption>119KB<br>format:PNG</figcaption>
        </div>
        <div id="item"><img src="C:\Users\Lenovo\Downloads\img 1.jpg">
          <figcaption>46KB<br>format:JPG</figcaption>
       </div>
      </div><br>
      <h3>About Discount</h3>
      <b><u>*Listen to the audio for discount*</u></b>
      <div id="box">
     <video id="video"controls src="C:\Users\Lenovo\Downloads\136040-764371296_tiny.mp4" type="video mp4"
              height="300" width="300" >
     </video>
      <audio id="audio"controls src="C:\Users\Lenovo\Downloads\ElevenLabs_Text_to_Speech_audio.mp3" type="mp3">
        listen to the audio for discount!!!
      </audio>
    </div>
     
  </body>
</html>
