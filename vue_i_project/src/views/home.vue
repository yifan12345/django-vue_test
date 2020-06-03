<template>
    <div>
        <HelloWorld msg="hello">

        </HelloWorld>
    </div>
</template>

<script>
    import HelloWorld from "../components/HelloWorld";
    export default {
        name: "home",
        props:{
            arg :String,
        },
        components:{
            // eslint-disable-next-line vue/no-unused-components
            HelloWorld
        },
    }
</script>

<style scoped>

</style>