<template>
    <section>
        <h1>User {{$route.params.id}}</h1>
    </section>
</template>

<script>
export default{
    validate() {
        console.log('validate')
        return True
    }
}
</script>
