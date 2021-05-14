<template>
  <div id="app" class="container-sm">
    <h1>Employees</h1>
    <employee-table />
  </div>
</template>

<script>
  import EmployeeTable from '@/components/EmployeeTable.vue'

  export default {
    name: 'App',
    components: {
      EmployeeTable,
    },
  }
</script>

<style scoped>
  button {
  background: #009435;
    border: 1px solid #009435;
  }
  .container-sm {
    max-width: 680px;
  } 
</style>
