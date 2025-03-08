# media-apple

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
   


</head>
<style>
  
.contenitore1{
   
    width: 100%;
    height:300px;
    display: flex;
    gap: 1px;
   
  
}
.box1{
    
    width: 100%;
    height: 100%;
    flex: 1;
    display: flex;
   
    justify-content: center;
    background-image: url(https://www.apple.com/it/apple-watch-series-10/images/overview/media-card/highlights_health__vrbvtcmuh72y_medium_2x.jpg);
    background-position: center;
       background-repeat: no-repeat;
       background-size: cover;
       font-family: Arial, Helvetica, sans-serif;
       
    

}

.box2{
    
    width: 100%;
    height: 100%;
    flex: 1;
    display: flex;
    background-image: url(https://www.apple.com/v/ipad-pro/ar/images/overview/hero/hero_endframe__sg50vzdd6sqm_large_2x.jpg);
       background-position: center;
       background-repeat: no-repeat;
       background-size: cover;
       justify-content: center;
    

    
}
.contenitore2{
  
    width: 100%;
    height: 300px;
    display: flex;
    margin-top: 1px;
    gap: 1px;

   
}

.box3{
    
    width: 100%;
    height: 100%;
    flex: 1;
    display: flex;
   justify-content: center;
 background-image: url(https://www.apple.com/v/macbook-pro/ao/images/overview/welcome/welcome_hero_endframe__c61x1mv7kgqe_medium_2x.jpg);
 background-position: center;
       background-repeat: no-repeat;
       background-size: cover;
       justify-content: center;
       
       
       
}

.box4{
    
    width: 100%;
    height: 100%;
    flex: 1;
    display: flex;
    justify-content: end;
    background-image: url(https://www.apple.com/v/home/cb/images/promos/airpods-pro-2/promo_airpods_pro_2_avail__vkitqi3okwie_large.jpg);
    background-position: center;
       background-repeat: no-repeat;
       background-size: cover;
       justify-content: center;
       align-items: end;

}

.info1{
     
    margin-top: -10px;
    
    
   
    
}


    
    
    
   
    


.info2{
    color: white;
    margin-top: -15px;
    
    
   
    
}








.watch{
    
    justify-content: center;
    display: flex;
    height: auto;

}

.series{
 
    justify-content: center;
    display: flex;
    height: auto;
    margin-top:-20px;
    



}

.cucu{
  
    justify-content: center;
    display: flex;
    margin-top:-25px;
    


}

.cont3{
   
    width: 160px;
   display: flex;
   justify-content: center;
  justify-content: space-evenly;
   align-items: center;
   margin-top: -10px;

}



.blu{
    width: 74px;
    height: 20px;
    background-color: #007aff ;
    border: none;
    border-radius: 99999px;
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgb(255, 255, 255);
    font-size: 10px;
}


.white{
    width: 40px;
    height: 25px;
    border-color:#007aff  ;
    background-color: rgb(255, 255, 255);
    border-radius: 99999px;
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
    color:#007aff ;
    font-size: 10px;
    

}




@media only screen and (max-width:380px){
    .contenitore1{ flex-direction: column;
                   flex-wrap: wrap;
                   

    }
    .box1 h2, .box2 h2 , .box3 h2, .box4 h2 { 
        font-size: 14px; 
       
    
}

}


@media only screen and (max-width:380px){
    .contenitore2{ flex-direction: column;
                   flex-wrap: wrap;
                   

    }
    .box1 h6, .box2 h6 , .box3 h6, .box4 h6 { 
        font-size: 8px; 
        margin-top: -7px;

}
}


@media only screen and (max-width:380px){
    .contenitore2{ flex-direction: column;
                   flex-wrap: wrap;
                   

    }
    .box1 p, .box2 p , .box3 p, .box4 p { 
        font-size: 10px; 
        margin-top: -17px;

}
}




</style>
<body>
   
    <div class="contenitore1">
        <div class="box1">
            <div class="info1">
                    <h2 class="watch">WATCH</h2>
                    <h6 class="series">SERIES10</h3>
                    <P class="cucu">Thinstant classic</P>
                  <div class="cont3">
                    <button class="blu">learn more</button>
                    <button class="white">Buy</button>
                  </div>
                  
        </div>
        
    </div>
        <div class="box2">
            <div class="info2">
                <h2 class="watch">WATCH</h2>
                <h6 class="series">SERIES10</h3>
                <P class="cucu">Thinstant classic</P>
              <div class="cont3">
                <button class="blu">learn more</button>
                <button class="white">Buy</button>
              </div>
            </div>
        </div>
    </div>

    <div class="contenitore2">
        <div class="box3">
            <div class="info2">
                    <h2 class="watch">WATCH</h2>
                    <h6 class="series">SERIES10</h3>
                    <P class="cucu">Thinstant classic</P>
                  <div class="cont3">
                    <button class="blu">learn more</button>
                    <button class="white">Buy</button>
                  </div>
                  
        </div>
        
    </div>
        <div class="box4">
            <div class="info2">
                <h2 class="watch">WATCH</h2>
                <h6 class="series">SERIES10</h3>
                <P class="cucu">Thinstant classic</P>
              <div class="cont3">
                <button class="blu">learn more</button>
                <button class="white">Buy</button>
              </div>
            </div>
        </div>
    </div>


        
        
   

    



    </div>

    
</body>
</html>
