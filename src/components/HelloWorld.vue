<template>
  <h1 class="bg-blue-200">{{ msg }}</h1>
</template>

<script>
export default {
  name: 'HelloWorld',

  props: {
    msg: String
  }
}
</script>
