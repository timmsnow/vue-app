<template>
  <div id="employee-form">
    <form>
      <label>Employee name</label>
      <input type="text" v-model="employee.name" />
      <label>Employee Email</label>
      <input type="text" v-model="employee.email" />
      <button>Add Employee</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "employee-form",
  data() {
    return {
      employee: {
        name: "",
        email: "",
      },
    };
  },
};
</script>

<style scoped>
form {
  margin-bottom: 2rem;
}
</style>
