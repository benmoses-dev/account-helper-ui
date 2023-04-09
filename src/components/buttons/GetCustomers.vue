<script setup lang="ts">
    import { ref } from 'vue';
    import Customer from "../Customer.vue";
    const customers = ref([]);
    function getCustomers() {
        customers.value = ["bob", "ben"];
    }
</script>

<template>
    <button v-on:click="getCustomers">View All Customers</button>
    <ul>
        <li v-for="customer in customers">
            <Customer name="test" />
        </li>
    </ul>
</template>

<style>

</style>