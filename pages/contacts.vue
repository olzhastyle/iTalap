<template>
<div>
      <div class="qwert">
          <h1>Бізбен байланыс:</h1>
            <p>Түркістан қ., Б. Саттарханов даңғылы 64</p>
      </div>

      <Form />
</div>
</template>

<script>


import Form from '../pages/components/Form.vue';

export default {
  
  components:{
    Form

  }
}
</script>

<style>

.qwert {
  position: relative;
  margin-top: auto;
  padding-top: 35px;
  padding-bottom: 20px;
  text-align: center;
  margin: 0 auto;
}

</style>
