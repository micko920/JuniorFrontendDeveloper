<template>
  <editor-content class="w-auto bg-white min-h-full" :editor="editor" />
</template>

<script>
import { Editor, EditorContent } from '@tiptap/vue-2'
import StarterKit from '@tiptap/starter-kit'

export default {
  components: {
    EditorContent,
  },

  data() {
    return {
      editor: null,
    }
  },

  mounted() {
    this.editor = new Editor({
      content: '<p>I’m running tiptap with Vue.js. 🎉</p>',
      extensions: [StarterKit],
    })
  },

  beforeDestroy() {
    this.editor.destroy()
  },
}
</script>
