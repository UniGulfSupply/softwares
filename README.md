<style>
 
 
 
     body {
    
     background-color: black; 
 
 
     font-family: 'Poppins', sans-serif;
     }
 
     strong {
     font-weight: bold;
     }
 
     .container-outer {
     display: table;
     width: 100%;
     height: 100%;
     }
     .container {
     width: 100%;
     
     display: table-cell;
     vertical-align: middle;
     }
 
     e {
     color: #FF0000;
     }
 
     .main-text {
     position: relative;
     }
 
     .top e, .bottom e {
     line-height: 1;
     
     text-align: center;
     font-weight: bold;
     font-size: 150px;
     letter-spacing: 10px;
     position: absolute;
     width: 100%;
     }
 
     .top, .bottom {
     width: 100%;
     display: block;
     overflow: hidden;
     position: relative;
     animation-duration: 1s;
     animation-fill-mode: forwards;
     animation-delay: 1s;
     }
 
     .bottom e {
     bottom: 0px;
     }
 
     .top {
     height: 70px;
     animation-name: goUp;
     
     }
 
     .bottom {
     height: 78px;
     animation-name: goDown;
     }
 
     .sub-text e {
     text-align: center;
     font-size: 30px;
     line-height: 1;
     font-weight: 300;
     text-transform: uppercase;
     letter-spacing: 10px;
     margin: 0;
     position: absolute;
     width: 100%;
     top: 50%;
     transform: translateY(-70%);
     opacity: 0;
     animation-name: fadeIn;
     animation-duration: 1s;
     animation-fill-mode: forwards;
     animation-delay: 2s;
     }
 
     .date {
     margin-top: 20px;
     opacity: 0;
     animation-name: fadeIn;
     animation-duration: 1s;
     animation-fill-mode: forwards;
     animation-delay: 3s;
     }
 
     .date e {
     position: absolute;
     text-align: center;
     font-size: 14px;
     line-height: 1;
     font-weight: 500;
     letter-spacing: 10px;
     margin: 0;
     width: 100%;
     }
     @keyframes goUp {
     0% {
         transform: translateY(0);
     }
     100% {
         transform: translateY(-22px);
     }
     }
 
     @keyframes goDown {
     0% {
         transform: translateY(0);
     }
     100% {
         transform: translateY(22px);
     }
     }
 
     @keyframes fadeIn {
     0% {
         opacity: 0;
     }
     100% {
         opacity: 1;
     }
     }
 
 </style>
 
<div class="body">
<div class="container-outer">
<div class="container">
<div class="main-text">
<div class="top">
<e>SOFTWARES</e>
</div>
<div class="bottom">  
<e>SOFTWARES</e>
</div>
<div class="sub-text">
<e>UniGulfSupply</e>
</div>
<div class="date">
<e>Build with Content</e>
</div>
</div>
</div>
</div>
</div>
</div>
</html>
 