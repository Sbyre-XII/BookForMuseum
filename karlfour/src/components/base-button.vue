<template>
    <button class="disable" type="type">Disable button</button>
    <button class="not_disable" type="type">A fonctional button</button>
    <button class="primary" type="type">Primary button</button>
    <button class="warn" type="type">Warn button</button>
    <button class="danger" type="type">Danger button</button>
</template>

<script>
export default {
  name: 'BaseButton',
}

</script>

<style scoped>
.disable{
    cursor: not-allowed;
}
.primary{
    background-color: green;
}
.warn{
    background-color: orange;
}
.danger{
    background-color: red;
}
</style>