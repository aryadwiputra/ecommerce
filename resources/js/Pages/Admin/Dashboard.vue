<script>
import DashboardLayout from "@/Layouts/DashboardLayout.vue";
import Table from "@/Components/Dashboard/Table.vue";

export default {
    layout: DashboardLayout,

    components: {
        Table,
    },
};
</script>

<template>
    <Table />
</template>
