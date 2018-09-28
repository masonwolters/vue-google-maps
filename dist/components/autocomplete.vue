<template>
  <input type="text" :placeholder="placeholder" ref="input"
    :value="value" @focus="$emit('focus')" @blur="$emit('blur')"/>
</template>

<script>
export default (function (x) { return x.default || x })(require('./autocompleteImpl.js'))
</script>
