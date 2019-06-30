<template>
    <form action="" method="post">
        <Input type="text"/>
        <Input type="text"/>
        <Button msg="Регистрация"/>
    </form>
</template>

<script>
    import Input from './Input.vue'
    import Button from './Button.vue'
export default {
    name: 'Form',
    components:{
        Input,
        Button
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
