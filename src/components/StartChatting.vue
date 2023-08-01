<template class="">
    <div class="container">
        <div class="wrapper chatting">
            <div class="header_1 chatting__header">
                <h1>Start chatting
                    with <br> customers, anytime, <br>
                    anywhere with Apex"
                </h1>
                <p class="paragraf">Great software that allows you to chat from any <br> place at any time withgout any
                    interruption </p>
                <button class="chatting__btn--dark">Start Chatting Mow</button>
                <button class="chatting__btn--yellow">Start Chatting Mow</button>

                <div class="para">
                    <img src="../assets/images/1.jpg" alt="">
                    <img class="img_2" src="../assets/images/1.jpg" alt="">
                    <img class="img_3" src="../assets/images/1.jpg" alt="">
                    <div class="header">
                        <h1>2,291</h1>
                        <p>Happy Customers</p>
                    </div>
                    <div class="header">
                        <h1>4.8/5</h1>
                        <p>xxxxx Rating</p>
                    </div>
                </div>
            </div>

            <div class="chatting__img img">
                <a href="#"><img src="../assets/images/start-chatting.svg" alt="logo"></a>
            </div>
        </div>

    </div>
</template>
<style scoped >
.wrapper {

    display: flex;
    justify-content: space-between;


}

img {

    height: 400;
    width: 1600;
}

.wrapper .paragraf {
    font-size: 20px;
    margin-top: 50px;
}

.wrapper h1 {
    font-size: 45px;
}

.header_1 {
    margin-top: 50px;
}

.wrapper button {
    background-color: #FB8E0B;
    border-radius: 8px;
    padding: 10px 30px;
    color: white;
    font-weight: 500;
    line-height: 24px;
    border: 1px solid;
    cursor: pointer;
    transition: all .3s;
    font-size: 20px;
    margin-top: 30px;
}

.btn:hover {
    color: #FB8E0B;
    background: white;

}

.para {
    display: flex;
    gap: 25px;
    margin-top: 45px;
}

.para img {
    border-radius: 500%;
    width: 60px;
    height: 60px;
    border: 5px solid #ffffff;

}

.para .img_2 {
    z-index: -1;
    width: 60px;
    height: 60px;
    margin-left: -100px;
    border: 5px solid #ffffff;
}

.para .img_3 {
    z-index: -2;
    margin-left: -100px;
    width: 60px;
    height: 60px;
    border: 5px solid #ffffff;
}
</style>