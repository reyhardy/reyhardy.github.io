<template>
    <div>
        <ul>
            <li v-for="nav in navlink">{{nav}}</li>
        </ul>
    </div>    
</template>

<script>

export default {
    data() {
        return {
            navlink: ['About Me', 'Education', 'Certification']
        }
    }
}
</script>

<style scoped>
    ul {
        list-style-type: none;
    }

</style>
