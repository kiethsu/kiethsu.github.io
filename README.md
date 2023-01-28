<html>
<head>
  <style>
    /* Define the size and spacing of the images */
    img {
      width: 150px;
      height: 150px;
      margin: 10px;
      box-shadow:2px 2px 2px rgba(0, 0, 0, 0.5);
      animation: pulse 5s ease-in-out ;
    }
      @keyframes pulse {
      from {
        transform: scale(1.3);
      }
      to {
        transform: scale(1.05);
      }
    }
  
    .row {
      display: flex;
      justify-content: center;
      margin-top: 50px;
      margin-bottom: 0;
        margin-left: 0;
        margin-right: 0;
    }
      .text {
    font-size: 90px;
    color: #fff;
    font-weight: 600;
   
    height: 50vh;
    display: flex;
    align-items: bottom;
    justify-content: center;
    
    position: absolute;
    right: 0;
    left: 0;
    top: 650px;
    bottom: 0;
    margin: auto; 
    transition: 0.5s;
      
    }
    /* Define the hover effect */
    .text:hover {
      color: transparent;
      text-shadow: 0 0 10px ;
      -webkit-text-stroke: 2px #fff;
        
    }
   
      body {
      background: linear-gradient(to right, #000000,#808080); /* Princeton orange */
    }
  </style>
</head>
<body>
  <div class="row">
      <a href="img1.jpg"target="img1.jpg"><img src="1.jpg" alt="Image 1"></a>
      <a href="img2.jpg"target="img2.jpg"><img src="2.jpg" alt="Image 2"></a>
      <a href="img3.jpg"target="img3.jpg"><img src="3.jpg" alt="Image 3"></a>
      <a href="img4.jpg"target="img4.jpg"><img src="4.jpg" alt="Image 4"></a>
      <a href="img5.jpg"target="img5.jpg"><img src="5.jpg" alt="Image 5"></a>
  </div>
  <div class="row">
      <a href="img6.jpg"target="img6.jpg"><img src="6.jpg" alt="Image 6"></a>
      <a href="img7.jpg"target="img7.jpg"><img src="7.jpg" alt="Image 7"></a>
      <a href="img8.jpg"target="img8.jpg"><img src="8.jpg" alt="Image 8"></a>
      <a href="img9.jpg"target="img9.jpg"><img src="9.jpg" alt="Image 9"></a>
      <a href="img10.jpg"target="img10.jpg"><img src="10.jpg" alt="Image 10"></a>
      <div class="text">
        <text>PHOTOGALLERY</text>
      
        </div>
  </div>
</body>
</html>
