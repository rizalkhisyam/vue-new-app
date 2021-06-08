<template>
  <section>
    <h2>Hello cuy</h2>
    <ul>
      <li v-for="data in friends">{{ data.name }}</li>
    </ul>
  </section>
</template>

<script>
export default {
  data: () => {
    friends: [
      {
        id: "rizal",
        name: "Rizal",
        phone: "081335886871",
        email: "rkhisyam@gmail.com",
      },
      {
        id: "rizal2",
        name: "Rizal2",
        phone: "081335886871",
        email: "rkhisyam@gmail.com",
      },
    ];
  },
};
</script>
