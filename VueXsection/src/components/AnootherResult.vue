<template>
<div>
    <p>Counter is: {{ doubleCounter }}</p>
    <p>Number of Clicks: {{ stringCoutner }}</p>
</div>
</template>

<script>
import {mapGetters} from 'vuex'
    export default {
      computed: mapGetters([
          'doubleCounter',
          'stringCounter'
      ])
    }
</script>