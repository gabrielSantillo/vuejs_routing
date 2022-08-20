<template>
    <div>
        <page-header></page-header>
        <h1>This is the menu of 0 items for you to chose</h1>
    </div>
</template>

<script>
import PageHeader from '@/components/PageHeader.vue'

    export default {
  components: { PageHeader },
        
    }
</script>

<style scoped>
h1 {
    color: green;
}
</style>