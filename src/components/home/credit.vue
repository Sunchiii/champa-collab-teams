<template>

      <div class="md:flex bg-gray-100 p-15 md:p-25 contents">
        <img class="w-100 h-100 md:w-100 md:h-auto md:rounded-none rounded-full mx-auto "
          src="/src/assets/images/credit.png" alt="credit-card" width="384" height="512"/>
        
          <div class="pt-16 md:p-8 text-center ">
  
            <div class="font-sans md:font-serif flex-row-reverse">
              <div class="text-serif-800-xl flex-end">Champa Maker Club</div>
              <p class="text-4xl font-bold  font-sans md:font-serif">
                Find top credit card offers from ours partner.
              </p>
              <p class="text-small font-bold ">
                easily compare credit card offers and apply directly with the issuer
              </p>  
            </div>
                <button class="btn button1">
                  see offers
                </button>
        </div>
      </div>

</template>

<style scoped>
.btn {
 border: none;
  color: white;
  padding: 20px 60px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 100px 400px 0px 0px;
  transition-duration: 0.4s;
  cursor: pointer;
  border-radius: 15px;
  /* margin-top: 100px; */
}
.button1 {
  background-color: #F13596; 
  border-color: #006ebc; 
  box-shadow: 5px 5px;
}

.button1:hover {
  background-color: #4CAF50;
  color: #55f8ff;
  box-shadow: 4px 2px;
}
.font-sans{
  text-align: flex-end;
  margin-top: 20px;
  text-align: justify;
}
.flex-row-reverse {
  -webkit-box-orient: horizontal;
  -webkit-box-direction: reverse;
  -ms-flex-direction: row-reverse;
  -webkit-flex-direction: row-reverse;
  flex-direction: row-reverse;
}
.text-serif-800-xl{
  color:#51c2d5;
}

</style>
