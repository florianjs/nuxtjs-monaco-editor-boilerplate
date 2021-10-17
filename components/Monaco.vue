<template>
  <div>
    <MonacoEditor class="editor" v-model="code" language="html" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      code: '<h1>Hello, World</h1>',
    }
  },
}
</script>

<style>
.editor {
  width: 600px;
  height: 800px;
}
</style>
