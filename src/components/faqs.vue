<template>
<main>
<div class="header">
<h1> FAQS </h1>
<h2> Frequently Asked Questions</h2>
<p>With a few basic questions, you can search and compare personalized quotes from top carriers.</p>
</div>

<div class="elements">
   <div class="faqs">
      <details>
         <summary> <p class="letter"> 01.</p>What is Lorem ipsum? </summary>
         <p class="text">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. </p>
      </details>
      <details>
         <summary> <p class="letter"> 02.</p>What is Lorem ipsum?</summary>
         <p class="text">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
      </details>
      <details>
         <summary> <p class="letter"> 03.</p>What is Lorem ipsum?</summary>
         <p class="text">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
      </details>
      
   </div>
</div>
</main>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&family=Readex+Pro:wght@500&display=swap');
main{
   background-color: rgb(243, 243, 243);
   height: 1100px;
   width: auto;
}
.header{
   font-family: 'Open Sans', sans-serif;
   font-family: 'Readex Pro', sans-serif;
   font-size: 25px;
   font-weight: 900;
   padding: 100px 200px;
   text-align: center;
}
.header h1{
   color: #7800CF;
   font-size: 18px;
   letter-spacing: 4px;
   padding-bottom: 10px;
}

.header p{
   opacity: 60%;;
   font-size: 15px;
   font-weight: normal;
   padding-top: 15px;
}

.elements{
   width: 800px;
   height: auto;
   margin: 25px auto;
   border-radius: 7px;
}


::-webkit-details-marker{
   float: right;
   margin-top: 3px;
}

details{
   background: rgb(243, 243, 243);
   padding: 20px 20px;
   border-radius: 7px;
   margin-top: 20px;
   font-family: 'Open Sans', sans-serif;
   font-family: 'Readex Pro', sans-serif;
   font-weight: bold;
   letter-spacing: 1px;
   cursor: pointer;
   border: 0.5px solid rgb(163, 163, 163);
   box-shadow: 1px 2px 4px rgba(192, 192, 192, 0.3);
}

p.letter{
   color: blue;
   display: inline;
}

details summary{
   outline: none;
   font-size: 18px;

}

.text{
   margin-top: 10px;
   padding: 20px 20px;
   background-color: rgb(255, 255, 255);
   border-radius: 10px;
   font-size: 14px;
   font-weight: 100;
}
</style>