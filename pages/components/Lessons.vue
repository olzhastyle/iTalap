<template>
    <div class="main">
        <section>
            <div class="a1">
                <h1>
                    Our courses
                </h1>
                <div class="text">

                     <div class="text3">
                        <a href="/about">
                            Lego Wedo
                            <img class="imageall123" src="../../assets/robotic.jpg" alt="">
                        </a>
                        <a href="/about">
                            Scratch
                            <img class="imageall123" src="../../assets/scratch.jpg" alt="">

                        </a>
                    </div>
                     <div class="text2">
                        <a href="/about">
                            Web development
                            <img class="imageall123" src="../../assets/webdev.png" alt="">

                        </a>
                    </div>
                    <div class="text3">
                        <a href="/about">
                            Lego Mindstorm
                            <img class="imageall123" src="../../assets/mindstorm.jpg" alt="">

                        </a>
                        <a href="/about">
                            Python
                            <img class="imageall123" src="../../assets/coding.jpg" alt="">

                        </a>

                    </div>
                   <div class="text2">
                        <a href="/about">
                            Arduino
                            <img class="imageall123" src="../../assets/arduino.png" alt="">

                        </a>

                    </div>
                   
                    <div class="text3">
                        <a href="/about">
                            Mobile application development
                            <img class="imageall123" src="../../assets/mobappdev.jpg" alt="">

                        </a>
                        <a href="/about">
                            Робототехника
                            <img class="imageall123" src="../../assets/robots.jpg" alt="">

                        </a>

                    </div>
                   
                </div>
            </div>
        </section>
    </div>
</template>

<style scoped>

.main {
    position: relative;
    text-align: center;
    width: 100%;
    max-width: 1220px;
    display: block;
    box-sizing: border-box;
    padding-top: 10px;
    padding-bottom: 10px;
    margin: 0 auto;
}
.a1 {
    text-align: center;
}
.a1 h1 {
    font-size: 50px;
}
.a1 p{
    font-size: 24px;
    
    text-align: center;
}
.text {
    text-align: center;
    width: 100%;
    display: flex;
    margin: 0 auto;
    padding-top: 20px;
}
.text1 {
    width: 20%; 
    margin: auto;
}
.text2 {
    width: 20%;  
    margin: auto; 
    position: relative; 
    text-align: center;
}
.text3 {
    width: 20%;
    margin: auto;
}
.text a{
    font-size: 30px ;
    color: black;
    font-weight: 600;
    cursor: pointer;
}

.text p{
    font-size: 16px;
    margin-top: 20px;
}
.imageall123 {
    width: 400px;
    align-content: center;
}
</style>