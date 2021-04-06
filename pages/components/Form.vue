<template>
    <div class="main">
        <section>
            <div class="a1">
                <h1>
                    Form
                </h1>

                <div>
                    <form action="#" id="form" class="form__body">
                        <h1 class="form__title">send form to email</h1>
                        <div class="form__item">
                            <label for="formName" class="form__label">Name</label>
                            <input type="text" name="name" id="formName" class="form__input _req">
                        </div>
                        <div class="form__email">
                            <label for="formEmail" class="form__label">Email</label>
                            <input id="formEmail" type="text" name="name" class="form__input _req _email">
                        </div>

                        <button type="submit" class="form__button"> SEND</button>
                    </form>
                </div>
                

            </div>
        </section>
    </div>
</template>

<script src="./script.js"></script>

<style scoped>

.main {
    position: relative;
    text-align: center;
    width: 100%;
    max-width: 1220px;
    display: block;
    box-sizing: border-box;
    padding-top: 100px;
    padding-bottom: 100px;
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

.form__input._error {
    box-shadow: 0 0 15px red;
}
</style>