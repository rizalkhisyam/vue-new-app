<template>
  <li>
    <h2>{{ friend.name }}</h2>
    <button>Show details</button>
    <ul>
      <li><strong>Phone:</strong> {{ friend.phone }}</li>
      <li><strong>Email:</strong> {{ friend.email }}</li>
    </ul>
  </li>
</template>

<script>
export default {
  data: () => {
    isVisible: false;
  },
};
</script>
