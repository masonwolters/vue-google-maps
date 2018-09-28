<template>
  <input type="text" :placeholder="placeholder" ref="input"
    :value="value" @focus="$emit('focus')" @blur="$emit('blur')" @input="$emit('input', $event)"/>
</template>

<script>
export default (function (x) { return x.default || x })(require('./autocompleteImpl.js'))
</script>
