<template lang="pug">
#about
  b-container
    b-row
      b-col.text-center(cols='12')
        p
          |網頁設計維護
          br
          br
          | 最近更新日期：{{ date }}
</template>
<script>

export default {
  data () {
    return {
      date: new Date().toLocaleString()
    }
  }
}
</script>
