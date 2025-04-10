<h2>Բարի Գալուստ  իմ կայք</h2>




  <nav>
    <ul>
      <li><a href="#">Գլխավոր</a></li>
      <li><a href="#">Կապ Մեր հետ</a></li>
    </ul>
  </nav>


  <p> Գրեք ձեր Անւնը </p>
    <form>
    <input type="text" placeholder="Անւն">
  </form>
  
  <p> Գրեք Էլ Հասցեն </p>


    <form >
    <input type="email" placeholder="Հասցե">
  </form>

  <p>Հեռախոսահամար</p>
<form>

  
<input type="tel"placeholder="Հեռախոսահամար">


</form>

<h4>Արդյոք ձեզ Հետաքրքրեց</h4>

<label>
  <input type="radio">Հետաքրքրեց 
</label>

<label>
  <input type="radio">Ոչ
</label>

<button id="submitbtn" type="button">Ուղարկել</button>

<div class="parent">

😊😊 Շնորակալություն Օգտվելու համար

<img src="https://media-cdn.tripadvisor.com/media/photo-s/1c/81/4e/5a/smail.jpg">

</div>
<button  class="btn">Փոխել</button>
submitbtn.addEventListener("click", function(event) {
  

    const name = document.querySelector('input[type="text"]').value;
    const email = document.querySelector('input[type="email"]').value;
    const phone = document.querySelector('input[type="tel"]').value;

    console.log(`Անուն;${name} էլ Հասցե; ${email} Հեռախոսահամարը; ${phone}  ` )
});


let btn = document.querySelector(".btn")
let parent = document.querySelector(".parent")


btn.addEventListener("click",function(){

    parent.style.backgroundColor="solid"
    parent.style.transition= "1s"
    parent.style.backgroundColor="green"
    
   

})




h2{
    text-align: center;
}

span{
    position: absolute;
    right: auto;
    left: 36%;
}



ul:nth-of-type(1) li:nth-child(1){
    color: green;
}

ul:nth-of-type(1) li:nth-child(2){
    color: green;
}

ul>li>a:nth-child(1){
    color: black;
}


li:nth-last-of-type(1) a:nth-child(1){
    color:black;
}




form>input{
    border: 2px solid;
}


h2:hover{
    transform: scale(1.2);
    transition: 1s;
}

.parent:hover{
    transition: 4s;
    opacity: 0.8;
    
}

.parent{

    width: 600px;
    height: 600px;
    position:absolute;
    right: 30%;
    top: 10%;
    border-radius: 20px;
    border: 4px solid;
    overflow: hidden;
}


.btn{
    text-align: center;
    position: absolute;

    left: 96%;
    top: 96%;
}
