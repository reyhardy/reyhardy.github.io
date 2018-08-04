<template>
    <header>
        <h1>
            {{welcome}}
        </h1>
        <h2>
            {{myName}}
        </h2>
    </header>
    
</template>

<script>
export default {
    data() {
        return {
            welcome: 'Welcome to my portfolio page' ,
            myName: 'My name is Reza'
        }
    }
}
</script>

<style scoped>
    header {
        text-align: center
    }
</style>
