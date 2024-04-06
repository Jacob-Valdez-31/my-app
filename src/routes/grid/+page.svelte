<script>
import bennett_jacob from '/src/img/bennett_jacob.jpeg'
import trent_jacob from '/src/img/trent_jacob.jpeg'
import nate_jacob from '/src/img/nate_jacob.jpeg'
import cam_jacob from '/src/img/cam_jacob.jpeg'
import miggy_jacob from '/src/img/miggy_jacob.jpeg'
import kiser_jacob from '/src/img/kiser_jacob.jpeg'
import will_jacob from '/src/img/will_jacob.jpeg'
import brothers from '/src/img/brothers.jpeg'
import family from '/src/img/family.jpeg'
import bride from '/src/img/bride.jpeg'
</script>

<style>
    .parent{
        margin-right: 200px;
        margin-top: 200px;
        position: relative;
    }
    .parent-two{
        margin-left: 320px;
        margin-top:-538px;
        position: relative; 
    }
    .parent-three{
        margin-left: 840px;
        margin-top: -819px;
        position: relative;
        
    }
    .grid-container-colum {
        display: grid;
      grid-template-columns: 258px 200px ;
     grid-area: center;
     justify-content: center;
     position: relative;
    }
    .grid-container-row {
        display: grid;
        grid-template-rows: 258px ;
         grid-area: center;
        justify-content: center;
        transform: translate(-10px, -409px);
        position: relative;
    }
    .img-style{
        transform: rotate(45deg) ;
        width: 180px;
        height: 180px;
        margin-top: 100px;
        position: relative;
    }
    </style>

<div style="margin-right:300px">
    <div class="parent">
        <div class="grid-container-colum">
            <img src={bennett_jacob} class="img-style" alt="" >   
            <img src={trent_jacob} class="img-style" alt="" >
        </div>
        <div class="grid-container-row">
            <img src={nate_jacob} class="img-style" alt="" >   
            <img src={cam_jacob} class="img-style" alt="" >  
         </div>
    </div>
</div>
        
<div class="parent-two">
    <div class="grid-container-row">
        <img src={miggy_jacob} class="img-style" alt="" >   
        <img src={brothers} class="img-style" alt="" >          
    </div>
</div>

<div class="parent-three">
    <div class="grid-container-colum">
        <img src={kiser_jacob} class="img-style" alt="" >   
        <img src={will_jacob} class="img-style" alt="" >  
    </div>
    <div class="grid-container-row">
        <img src={family} class="img-style" alt="" >   
        <img src={bride} class="img-style" alt="">  
     </div>
 </div>


