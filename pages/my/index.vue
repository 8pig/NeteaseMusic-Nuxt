<template>
  <div>
    my
  </div>
</template>

<script>
import axios from 'axios'
export default {
  name: 'my-index',
  async asyncData() {

    const mountains = await axios.get('https://dog.ceo/api/breeds/image/random/3')

    return { mountains: mountains.data.message }
  }
}
</script>

<style scoped>

</style>
