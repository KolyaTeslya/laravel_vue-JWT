<template>
    <div>
        <router-link :to="{name: 'fruit.index'}">List</router-link>
        <router-view></router-view>
    </div>
</template>

<script>
export default {
    name: "Index.vue"
}
</script>

<style scoped>

</style>
