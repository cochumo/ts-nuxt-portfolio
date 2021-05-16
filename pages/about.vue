<template>
  <div>
    <h1>about</h1>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import axios from 'axios'

export default Vue.extend({
  head: {
    title: 'About',
  },
  async asyncData() {
    const token =
      'b7670128183c8fe31b5fb6b01f6be01339808e2f2076646533407a49467c6fb25d24c9b52071f25e2f031faa5ea3af7f14077c544f92744a6c42c17e8e087a55837761e96daa1e66f0fcc77fac40'
    const pageId = '2bdf4c6d46024216b977639f3fdba940'
    const page = await axios
      .get(`https://notion-api.splitbee.io/v1/page/${pageId}`, {
        headers: { Authorization: `Bearer ${token}` },
      })
      .then((res) => {
        // console.log(res.data)
        return res.data
      })
      .catch((error) => {
        console.error('error')
        return null
      })

    return {
      page,
    }
  },
})
</script>
