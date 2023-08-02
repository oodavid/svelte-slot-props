<script lang="ts">
  // If this is exported, the issue goes away
  let prop: 'one' | 'two' | 'three' = 'one';
</script>

<slot {prop} />