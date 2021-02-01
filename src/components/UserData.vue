<template>
  <section>
    <form>
      <label>Name: </label>
      <input type="text" placeholder="Your name" v-model="enteredName" />
      <label>Age: </label>
      <input type="text" placeholder="Your age" v-model="enteredAge" />
      <button>Set User Data</button>
    </form>
  </section>
</template>
<script>
export default {
  data() {
    return {
      enteredName: "",
      enteredAge: "",
    };
  },
};
</script>
