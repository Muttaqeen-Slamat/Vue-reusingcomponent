<template>
    <div class="container">
        <h2>Child Component</h2>
        <p>{{ greeting }}</p>
    </div>
</template>

<script>
    export default {
        name: 'ProductComp',
        props: ['greeting']
    }
</script>

<style scoped>
.container{
    background-color: chocolate;
}
</style>