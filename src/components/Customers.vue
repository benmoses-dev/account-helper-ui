<script setup lang="ts">
    import GetCustomersButton from './buttons/GetCustomers.vue';
</script>

<template>
    <div class="customers">
        <h1>This is the customers page</h1>
        <GetCustomersButton />
    </div>
</template>
  
<style>
@media (min-width: 1024px) {
    .customers {
        display: flex;
        align-items: center;
    }
}
</style>