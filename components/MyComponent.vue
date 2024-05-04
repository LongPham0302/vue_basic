<template>
    <div>
        <slot></slot>
    <button>
    <slot name="icon"></slot>
    <slot name="content"></slot>
  </button>
    </div>
</template>

<script>
export default {
    name: 'MyComponent',
}
</script>

<style scoped>
/* Add your component styles here */
</style>