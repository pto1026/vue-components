<template>
  <section>
  <h2>My Friends</h2>
    <ul>
      <li></li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      friends: [
        {
          id: 'manuel',
          name: 'Manuel Lorenz',
          phone: '0123 4567 890',
          email: 'manuel@localhost.com'
        },
        {
          id: 'julie',
          name: 'Julie Jones',
          phone: '0987 6543 211',
          email: 'julie@localhost.com'
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>