<template>
    <div class="main">
        <section>
            <div class="a1">
                <h1>
                    Our courses
                </h1>
                <div class="text">

                    <div class="text1">
                        <a href="/about">
                            Robotics
                        </a>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus, assumenda voluptatem autem, atque cum consequatur saepe cumque corporis iusto sit maiores ratione sequi mollitia impedit voluptatum sint adipisci dicta quia.</p>

                    </div>
                    <div class="text2">
                        <a href="/about">
                            Coding
                        </a>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus, assumenda voluptatem autem, atque cum consequatur saepe cumque corporis iusto sit maiores ratione sequi mollitia impedit voluptatum sint adipisci dicta quia.</p>
                        
                    </div>
                    <div class="text3">
                        <a href="/about">
                            Language
                        </a>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus, assumenda voluptatem autem, atque cum consequatur saepe cumque corporis iusto sit maiores ratione sequi mollitia impedit voluptatum sint adipisci dicta quia.</p>
                        
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
</style>