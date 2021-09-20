<script lang="tsx">
import { defineComponent } from '@nuxtjs/composition-api'

export default defineComponent({
  setup() {
    const hello = "world"
    return () => (
      <p class="hello">tsx, { hello }</p>
    )
  }
})
</script>

<style scoped>
.hello {
  color:aqua;
}
</style>
