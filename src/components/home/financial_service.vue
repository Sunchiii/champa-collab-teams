<template>
    <div class="container block m-0 pt-40px pb-40px w-screen h-screen text-center">
        <div>
        <p class="text-cyan-400 font-600">SERVICES</p>
        <h3 class="text-2xl my-4"><b>Fine the financial services you need</b></h3>
        <p> maiores dolorum quos veritatis nisi natus itaque nostrum porro suscipit ex nulla atque iure blanditiis soluta adipisi<br>eligendi accusantium nisi sit inventore asperiores </p>
        </div>
        <div class="box_question flex justify-around px-250px">
            <div class="box">
                <div class="fur bg-pink-500 text-2xl text-white my-12 ">01</div>
                <h3>Answer a few question</h3>
                <p>elit. Praesentium excepturi possimus amet ut, veniam magni laudantium eos sunt adipisicing elit. </p>
            </div>
            <div class="box">
                <div class="fur bg-light-blue-500 text-2xl text-white mt-20 my-12" justify-self-end>02</div>
                <h3>Get matched with top providers</h3>
                <p>adipisicing elit. Praesentium excepturi possimus amet ut, veniam magni laudantium eos sunt </p>
            </div>
            <div class="box">
                <div class="fur bg-purple-500 text-2xl text-white my-12">03</div>
                <h3>Close the deal</h3>
                <p>adipisicing elit. Praesentium excepturi possimus amet ut, veniam magni laudantium eos sunt </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
 .container .box_question .box {
     padding-right: 10%;
     text-align: left;
 }
 .container .box_question .box .fur {
     font-weight: 600;
     width: 100px;
     height: 100px;
     display: flex;
     justify-content: center;
     align-items: center;
     border-radius: 30%;
     font-size: 2.2rem;
 }
 .container .box_question h3 {
     font-weight: bold;
     font-size: 1.2rem;
 }
 .container .box_question p {
     margin-top: 20px;
 }
</style>