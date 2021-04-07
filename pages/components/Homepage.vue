<template>
    <div class="main bg-dark text-center text-white">
        <div class="image445566">
            <img src="../../assets/logo1.png" alt="">
        </div>
        <div class="text">
            <h1>iTalap</h1>
            <p>Talapty elge nur jauar!</p>
           <div class="button">
            <div class="button-start">
                <a href="/about">Курсқа жазылу!</a>
            </div>
            <div class="button-about">
                <a href="/about">Курстар туралы...</a>
            </div>
           </div>
        </div>
    </div>
</template>

<style scoped>

.main {
    height: 400px;
    width: 100%;
    display: flexbox;
    padding-top: 95px;
    padding-bottom: 5px;
    position: relative;
    margin: auto;
}
.image445566 img{
    border: none;
    position: absolute;
    float: left;
    left: 2px;
    top: -50px;
}
.text {
    text-align: center;
    position: relative;
}
.text h1{
    text-align: center;
    position: relative;
    top: 20%;
    font-size: 60px;
}
.text p {
    text-align: center;
    position: relative;
    top: 10%;
    font-size: 24px;
}
.button{
    position: relative;
    top: 50px;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    flex-direction: row;
    flex: 0 1 auto;
    -webkit-box-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    align-items: center;
    flex-wrap: wrap;
}

.button-start {
    text-align: right;
    padding-right: 7px;
    padding-left: 7px;
}
.button-start a{
    display: inline-block;  
    background-color: rgb(97, 218, 251);
    color: rgb(0, 0, 0);
    padding: 10px 25px;
    white-space: nowrap;
    transition: background-color 0.2s ease-out 0s;  
}
.button-start a:-webkit-any-link {
    cursor: pointer;
}
.button-start a::after,::before {
    box-sizing: inherit;
}
.button-about a{
    display: inline-block;
    color: rgb(97, 218, 251);
    transition: color 0.2s ease-out 0s;
    text-decoration: none;
    background-color: transparent;
}
img {
    position: absolute;
    margin: auto;
    border: 20px solid;
}

</style>