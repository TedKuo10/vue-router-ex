<template>
  <div>
  </div>
</template>

<script>
import axios from 'axios'
export default {
  props: ['id'],
  created () {
    // console.log(this.$route.params.id)
    // const seed = 'a5e154f015418bda'
    const seed = this.id
    axios.get(`https://randomuser.me/api/?seed=${seed}`)
      .then(res => {
        console.log(res)
      })
  }
}
</script>
