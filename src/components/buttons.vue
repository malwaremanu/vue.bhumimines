<template>
  <button class="px-3 py-1 bg-green-500 text-green-900 rounded-full font-semibold"> {{ title }} </button>  
</template>

<script>
export default {
  name : 'buttons',
  props : ['title']
}
</script>