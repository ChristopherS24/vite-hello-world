<script>
import AppTitle from './components/AppTitle.vue';

export default {
  data() {
    return {
        message: ''
    }
  },
  components: {
    AppTitle
  }
}
</script>

<template>
  <AppTitle />
    <div>
        <h1>
            {{  message  }}
        </h1>
    </div>
</template>

<style scoped>

</style>
