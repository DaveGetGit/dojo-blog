<template>
  <div class="home">
    Home
    <p>My name is {{ name }}</p>
    <button @click="handleClick">Click Me</button>
  </div>
</template>

<script>
export default {
  name: "Home",
  setup() {
    let name = "mario";
    let age = 30;

    const handleClick = () => {
      console.log("CLiked");
    };

    return { name, age, handleClick };
  },
};
</script>
